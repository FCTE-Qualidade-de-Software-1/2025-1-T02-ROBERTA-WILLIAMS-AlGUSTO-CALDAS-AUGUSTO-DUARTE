# Q-Rapids

O Q-Rapids (Quality-Aware Rapid Software Development) é um framework voltado para o apoio à tomada de decisão sobre qualidade em desenvolvimento ágil, baseado em evidências técnicas reais. A tabela abaixo mostra os dados brutos que esse framework utiliza para obter suas análises de dados.

### Tabela 1 – Categorização das métricas utilizadas para a análise de dados

| Categoria             | Tipo             | Métrica ou informação                                                                 |
|-----------------------|------------------|----------------------------------------------------------------------------------------|
| **Código-fonte**      | Histórico de código | Commits — número, data, descrição detalhada<br>Desenvolvedores — número, nomes e envolvimento<br>Branches — nomes, commits, histórico de mudanças |
|                       | Qualidade de código | Complexidade de classes, funções e arquivos<br>Número de linhas duplicadas e sua densidade<br>Densidade de comentários e seu número |
| **Processo de desenvolvimento** | Testes            | Tempo de teste — máximo, mínimo e média<br>Testes aprovados/reprovados indicados para funcionalidades, melhorias ou correções específicas |
|                       | Backlog           | Funcionalidades e tarefas planejadas para o backlog de sprint<br>Tempo necessário para implementar funcionalidades específicas |
|                       | Issues (Problemas) | Número de issues abertas e fechadas recentemente<br>Issues abertas — bugs, tarefas e funcionalidades ainda não resolvidas<br>Issues reabertas — aquelas reabertas devido a modificações |
|                       | Bugs              | Número de bugs relatados para funcionalidades específicas<br>Criticidade dos bugs<br>Tempo para corrigir um bug específico |
| **Aplicação em execução** | Uso              | Tempo gasto utilizando funcionalidades específicas (média, máx., mín.)<br>Funcionalidades utilizadas — lista das mais frequentemente usadas |
|                       | Segurança         | Vulnerabilidades indicadas no código<br>Explorações (exploits) que foram relatadas<br>Criticidade das falhas de segurança |
|                       | Feedback do usuário | Avaliações fornecidas pelos usuários sobre a utilidade da aplicação |


## Plano para Obter as Métricas do Objetivo de Acessibilidade usando Q-Rapids

A usabilidade se refere à facilidade com que usuários podem utilizar um sistema ou aplicativo de software. Isso engloba a eficiência, eficácia e satisfação na interação com a ferramenta. Já a acessibilidade se refere à capacidade de um sistema ou aplicativo ser utilizado por todas as pessoas, independentemente de suas habilidades ou deficiências. A acessibilidade é o principal foco de medição deste trabalho.

Portanto, após o estudo sobre Q-Rapids e a discussão interna, a dupla decidiu não alterar as questões e as métricas definidas ma fase 2. Isso se deve ao fato de que utilizaremos uma **aplicação em execução** — um dos tipos de fontes de dados usadas pelo **Q-Rapids** — para realizar a validação das questões de usabilidade.

---

## Histórico de Versões

| Versão | Data       | Descrição                                   | Autor                     | Revisor                |
|--------|------------|---------------------------------------------|---------------------------|------------------------|
| 1.0    | 11/07/2025 | Implementação do framework Q-Rapids         | Algusto Rodrigues         | Augusto Duarte         |