## Introdução

Esta fase tem como objetivo descrever o plano detalhado de avaliação de qualidade do sistema **AgroMart**, com foco específico em **acessibilidade**. O plano define os métodos, ferramentas, recursos e critérios de sucesso que guiarão a execução da avaliação, a fim de garantir um processo sistemático, reprodutível e alinhado à **norma ISO/IEC 25010**.

A abordagem escolhida visa observar, medir e interpretar a experiência de uso por pessoas com deficiência visual ou motora, utilizando ferramentas especializadas em testes de acessibilidade.

## Método de Avaliação

A avaliação será realizada com base nas métricas e hipóteses estabelecidas na Fase 2, focando na característica de **usabilidade com ênfase em acessibilidade**. Para isso, duas ferramentas serão empregadas:

### 1. Scanner de Acessibilidade (Accessibility Scanner)

Ferramenta desenvolvida para identificar oportunidades de melhoria na acessibilidade da interface do usuário. Entre os principais aspectos avaliados estão:

* Rótulos de elementos ausentes;
* Descrições duplicadas ou ambíguas;
* Links com texto genérico (ex: "clique aqui");
* Baixo contraste entre texto/imagem e plano de fundo;
* Elementos clicáveis com área menor que 48x48dp;
* Problemas na ordem de navegação por leitura de tela;
* Tamanhos de texto que dificultam leitura em dispositivos móveis.

A análise será conduzida em uma versão funcional do aplicativo AgroMart, instalada em um dispositivo Android, com inspeção de cada tela principal da navegação (login, cadastro, navegação de produtos e carrinho).

### 2. TalkBack

Ferramenta nativa do Android voltada à leitura de tela para pessoas com deficiência visual. O TalkBack permite:

* Testar a leitura correta de descrições de elementos interativos;
* Verificar a ordem de navegação entre os componentes da interface;
* Avaliar se feedbacks visuais são acompanhados de descrições faladas;
* Garantir que todos os campos importantes sejam focáveis e acessíveis.

Durante os testes com o TalkBack, os avaliadores simularão a navegação usando os gestos do recurso, avaliando o comportamento da interface em cada etapa do fluxo do usuário.

## Instruções de Aplicação

* O aplicativo será executado em um **dispositivo Android com suporte ao TalkBack e ao Scanner de Acessibilidade**.
* Cada membro da equipe realizará os testes individualmente, registrando os **problemas encontrados** e **evidências visuais (prints e anotações)**.
* Os resultados serão tabulados e classificados segundo a **Escala de Desempenho** definida na Fase 2 (Excelente, Bom, Regular, Insatisfatório).
* As não conformidades encontradas serão documentadas com base nas métricas **M1 a M4**.

## Recursos Necessários

| Tipo de Recurso           | Descrição                                                                     |
| ------------------------- | ----------------------------------------------------------------------------- |
| Aplicativo AgroMart       | Versão funcional instalada localmente em dispositivo Android                  |
| Scanner de Acessibilidade | Aplicativo auxiliar para avaliação automatizada de elementos da interface     |
| TalkBack                  | Ferramenta nativa do Android para navegação por leitura de tela               |
| Planilha de Registro      | Documento para registro manual das ocorrências, prints e notas observacionais |
| Cronômetro (opcional)     | Para medir tempo de navegação em trechos específicos                          |

## Critérios de Sucesso

A avaliação será considerada satisfatória se:

* Pelo menos **70% das métricas** (M1 a M4) obtiverem pontuação **"Bom" ou "Excelente"**;
* Não houver ocorrências críticas de inacessibilidade em telas essenciais;
* As recomendações do Scanner forem plenamente compreendidas e documentadas para posterior correção.

## Conclusão

Este plano de avaliação estrutura a execução de testes focados em acessibilidade, utilizando duas ferramentas complementares para verificação automática e manual da interface. Ao aplicar o Scanner de Acessibilidade e o TalkBack, a equipe garante uma abordagem dupla — técnica e empática — para validar o compromisso do AgroMart com a inclusão digital.

Os dados coletados nortearão recomendações de melhorias futuras e contribuirão para um sistema mais utilizável por todos os perfis de usuários.


## Histórico de Versões

| Versão | Data       | Descrição                         | Autor             | Revisor        |
|--------|------------|-----------------------------------|-------------------|----------------|
| 1.0    | 12/07/2025 | Elaboração do Plano de Avaliação  | Algusto Rodrigues | Augusto Duarte |
