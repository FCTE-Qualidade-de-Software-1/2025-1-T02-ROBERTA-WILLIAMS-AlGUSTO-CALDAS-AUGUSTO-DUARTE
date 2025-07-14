# Resultados da Avaliação de Qualidade

## Introdução

Este documento apresenta **dashboards visuais** que permitem acompanhar o progresso e o fluxo de trabalho relacionados às atividades de avaliação de qualidade do sistema **AgroMart**, com foco nas métricas de **usabilidade, com ênfase em acessibilidade**.

* * *

## Cumulative Flow – Fluxo Cumulativo

O **Fluxo Cumulativo** (Cumulative Flow Diagram – CFD) é uma ferramenta visual que permite observar o andamento do trabalho ao longo do tempo, revelando:

* A quantidade total de tarefas em cada etapa do fluxo;
* Possíveis **gargalos** e **atrasos** no processo;
* O **tempo de ciclo** e a taxa de entrega;
* O **equilíbrio entre início e conclusão** das atividades.

Essa ferramenta é fundamental em métodos ágeis, como o **Kanban**, pois evidencia se o trabalho está fluindo de maneira previsível.

### Parâmetros Utilizados

| Etapa | Descrição |
| --- | --- |
| **Para Fazer** | Atividades ainda não iniciadas. |
| **Em Progresso** | Atividades em andamento, em fase de execução. |
| **Completo** | Atividades finalizadas, aguardando validação interna. |
| **Implantado** | Atividades finalizadas e aplicadas ao sistema ou à documentação. |

* * *

### Gráfico de Fluxo Cumulativo – Acessibilidade AgroMart

<canvas id="myChart" width="400" height="200"></canvas>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

<script>const labels = ['10/07/2025', '11/07/2025', '12/07/2025', '13/07/2025'];const ctx = document.getElementById('myChart').getContext('2d');new Chart(ctx, {  type: 'line',  data: {    labels: labels,    datasets: [      {        label: 'Implantado',        data: [0, 0, 4, 9],        borderColor: 'rgb(20, 8, 128)',        backgroundColor: 'rgba(20, 8, 128, 0.74)',        fill: true      },      {        label: 'Completo',        data: [0, 2, 3, 0],        borderColor: 'rgb(158, 3, 3)',        backgroundColor: 'rgba(158, 3, 3, 0.74)',        fill: true      },      {        label: 'Em Progresso',        data: [0, 3, 2, 0],        borderColor: 'rgb(182, 194, 75)',        backgroundColor: 'rgba(182, 194, 75, 0.74)',        fill: true      },      {        label: 'Para Fazer',        data: [9, 4, 0, 0],        borderColor: 'rgb(36, 93, 155)',        backgroundColor: 'rgba(36, 94, 155, 0.74)',        fill: true      }    ]  },  options: {    responsive: true,    stacked: true,    plugins: {      title: {        display: true,        text: 'Fluxo Cumulativo - Avaliação de Acessibilidade AgroMart'      }    },    scales: {      x: { stacked: true },      y: { stacked: true, beginAtZero: true }    }  }});</script>

## Burndown Chart – Gráfico de Queima

O **Burndown Chart** permite acompanhar a redução do número de tarefas ao longo de um ciclo de trabalho. Ele mostra:

* A quantidade de tarefas planejadas;
* A **linha ideal** de execução (progresso constante);
* A **linha real** com base nas tarefas efetivamente concluídas;
* **Atrasos**, **bloqueios** ou **adiantamentos** no andamento das atividades.

### Parâmetros

| **Elemento** | **Descrição** |
| --- | --- |
| **Total de Tarefas** | Quantidade total de tarefas planejadas para o ciclo. |
| **Linha Ideal** | Redução linear esperada das tarefas ao longo do tempo. |
| **Linha Real** | Progresso real diário, com base nas tarefas concluídas. |
| **Datas da Sprint** | Período planejado para execução do ciclo. |

* * *

### Burndown Chart – Tarefas Restantes por Dia

<canvas id="burndownChart" width="400" height="200"></canvas>

<script>const burndownCtx = document.getElementById('burndownChart').getContext('2d');const datasSprint = ['10/07/2025','11/07/2025','12/07/2025','13/07/2025'];const tarefasRestantes = [9, 4, 2, 0];const linhaIdeal = tarefasRestantes.map((_, i, arr) => {  const total = 9;  return Math.max(0, total - (total / (arr.length - 1)) * i);});new Chart(burndownCtx, {  type: 'line',  data: {    labels: datasSprint,    datasets: [      {        label: 'Ideal',        data: linhaIdeal,        borderColor: 'rgba(0, 200, 0, 0.8)',        backgroundColor: 'rgba(0, 200, 0, 0.2)',        fill: false,        borderDash: [5, 5],      },      {        label: 'Real',        data: tarefasRestantes,        borderColor: 'rgba(200, 0, 0, 0.8)',        backgroundColor: 'rgba(200, 0, 0, 0.2)',        fill: false      }    ]  },  options: {    responsive: true,    plugins: {      title: {        display: true,        text: 'Burndown Chart - Avaliação de Qualidade AgroMart'      }    },    scales: {      y: {        beginAtZero: true,        title: { display: true, text: 'Tarefas Restantes' }      },      x: {        title: { display: true, text: 'Dias do Ciclo' }      }    }  }});</script>

## Histórico de Versões

| Versão | Data       | Descrição                          | Autor             | Revisor        |
|--------|------------|------------------------------------|-------------------|----------------|
| `1.0`  | 13/07/2025 | Explicação do Progresso do Porjeto | Algusto Rodrigues | Augusto Duarte |
