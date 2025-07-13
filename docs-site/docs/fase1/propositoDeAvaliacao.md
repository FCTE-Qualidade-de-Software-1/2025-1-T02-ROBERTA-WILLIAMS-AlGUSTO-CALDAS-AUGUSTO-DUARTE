# Estabelecer Requisitos de Avaliação

## Planejamento de Qualidade para o sistema AgroMart

## Aplicação Escolhida
#### Por que o AgroMart?

O **AgroMart** foi escolhido como objeto de avaliação por ser uma aplicação voltada ao fortalecimento da agricultura familiar e da conexão direta entre pequenos produtores e consumidores. A proposta do sistema está alinhada com diversos Objetivos de Desenvolvimento Sustentável (ODS), especialmente os relacionados à **agricultura sustentável**, **inclusão econômica** e **inovação tecnológica acessível**.

O AgroMart tem como foco:

- Incentivar a comercialização de produtos locais e agroecológicos.
- Reduzir intermediários, promovendo maior margem de lucro ao agricultor.
- Proporcionar uma experiência digital acessível e funcional para produtores e consumidores.


### Repositórios do Projeto

| Repositório                                                  | Descrição                                                                                                                  |
|--------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|
| [mobile-client](https://github.com/AgroMart/mobile-client)   | Front-end do sistema, desenvolvido em **React Native**, responsável pela interface mobile utilizada pelos usuários.        |
| [api](https://github.com/AgroMart/api)                       | Back-end principal da aplicação, implementado com **Strapi**, onde estão as funcionalidades de autenticação, produtos etc. |
| [api-dicionario](https://github.com/AgroMart/api-dicionario) | Serviço responsável por armazenar as **URLs dos back-ends das CSAs** integradas.                                           |          
| [docs](https://github.com/AgroMart/docs)                     | Documentação geral do projeto, incluindo requisitos, arquitetura e diretrizes de desenvolvimento.                          |



### Estabelecer o Propósito da Avaliação

- Avaliar o sistema **AgroMart** com o objetivo de verificar se o software atende de forma eficiente, segura e confiável às necessidades de pequenos agricultores e consumidores.
- Identificar oportunidades de melhoria com foco em **usabilidade**.
- Garantir conformidade com os critérios da **norma ISO/IEC 25010**, com ênfase em:

| Critério               | Ênfase                |
|------------------------|-----------------------|
| Usabilidade            | 5 — Essencial         |
| Adequação Funcional    | 4 — Alta importância  |
| Segurança              | 3 — Importância média |
| Manutenibilidade       | 2 — Pouca importância |
| Confiabilidade         | 2 — Pouca importância |
| Desempenho             | 2 — Pouca importância |
| Portabilidade          | 2 — Pouca importância |
| Compatibilidade        | 1 — Sem importância   |




### Identificar Tipos de Produtos a Serem Avaliados

| Componente               | Descrição                                                                                                    |
|--------------------------|--------------------------------------------------------------------------------------------------------------|
| Aplicativo Mobile        | Páginas principais do aplicativo, como login, cadastro, navegação etc.                                       |
| Imagens e Elementos UI   | Disposição visual dos elementos de interface e aspectos de acessibilidade visual (ex: suporte a daltonismo). |

### Especificar Modelo de Qualidade

| Critério               | Subcaracterísticas Avaliadas                                                            |
|------------------------|-----------------------------------------------------------------------------------------|
| Usabilidade            | Facilidade de uso e aprendizado, com foco em:                                           |
|                        | - **Acessibilidade**: suporte a usuários com deficiência (ex: daltonismo, baixa visão). |

### Conexão com os Objetivos de Desenvolvimento Sustentável (ODS)

| ODS     | Objetivo                                      | Contribuição do AgroMart                                                                |
|---------|-----------------------------------------------|-----------------------------------------------------------------------------------------|
| ODS 2   | Fome Zero e Agricultura Sustentável           | Conecta consumidores a produtores locais, incentivando produção agroecológica.          |
| ODS 8   | Trabalho Decente e Crescimento Econômico      | Gera oportunidades digitais e renda para pequenos agricultores.                         |
| ODS 9   | Inovação e Infraestrutura                     | Implementa tecnologia segura e acessível para o setor agro.                             |
| ODS 12  | Consumo e Produção Responsáveis               | Promove alimentação local, saudável e consciente.                                       |

---

## Histórico de Versões

| Versão | Data       | Descrição                                   | Autor                     | Revisor                |
|--------|------------|---------------------------------------------|---------------------------|------------------------|
| 1.0    | 11/07/2025 | Elaboração do propósito de avaliação        | Augusto Duarte            | Algusto Rodrigues      |
| 1.1    | 11/07/2025 | Ajuste nos critérios da norma ISO/IEC 25010 | Algusto Rodrigues         | Augusto Duarte         |
