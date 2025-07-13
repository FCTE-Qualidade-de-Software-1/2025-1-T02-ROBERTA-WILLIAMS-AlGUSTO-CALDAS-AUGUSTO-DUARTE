# Soluções de Acessibilidade no AgroMart
# Protótipo de Alta Fidelidade

## Introdução

Durante a **Fase 4** do projeto AgroMart, focada na **avaliação da qualidade do sistema**, foram identificados diversos problemas críticos de **usabilidade com ênfase em acessibilidade**. Essas questões, detalhadas nas análises das métricas M1, M2, M3 e M4, comprometem significativamente a experiência de usuários, especialmente aqueles com limitações visuais ou motoras, impactando os fluxos essenciais da aplicação.

Diante desses achados, a equipe optou pela construção de um **protótipo de alta fidelidade**. O objetivo é redesenhar e propor soluções concretas e acessíveis para os pontos de atrito, visando não apenas corrigir as falhas identificadas, mas também estabelecer um padrão de interface mais inclusivo e centrado no usuário.

O protótipo foi desenvolvido utilizando a ferramenta **Figma**, que permite a criação de telas navegáveis com simulação de interações, e inclui anotações para facilitar a transição entre as etapas de design e desenvolvimento.

## Fundamentação: Métricas GQM Abordadas

Este protótipo propõe soluções diretas para os problemas identificados nas seguintes métricas da metodologia GQM, avaliadas na Fase 3:

* **M1: Acessibilidade Visual** – Endereçando problemas de contraste adequado, legibilidade e suporte a daltonismo.
* **M2: Navegabilidade Acessível** – Focando na adequação do tamanho dos elementos ao toque, foco visível e ordem de leitura correta para leitores de tela.
* **M3: Cobertura de Textos Alternativos** – Visando a presença de textos alternativos ou descrições acessíveis (`labels`) em ícones, imagens e botões.
* **M4: Redundância Multissensorial de Feedbacks** – Abordando a necessidade de mensagens visuais importantes (como erros/sucesso) serem acompanhadas por texto ou som acessível.

## Objetivos do Protótipo

Os principais objetivos deste protótipo de alta fidelidade são:

* **Corrigir os principais atritos de acessibilidade** nos fluxos de `login`, `cadastro`, `seleção de CSA`, `busca`, `planos`, `histórico`, `carrinho` e `pagamento`.
* **Melhorar a Acessibilidade Visual (M1)**: garantindo contraste e tamanhos de área de toque adequados para todos os elementos interativos.
* **Aprimorar a Navegabilidade Acessível (M2)**: resolvendo problemas de incompatibilidade de menus com TalkBack, conflitos de foco e loops de navegação.
* **Ampliar a Cobertura de Textos Alternativos (M3)**: assegurando que todas as imagens e elementos interativos possuam descrições textuais apropriadas para leitores de tela.
* **Reforçar a Redundância Multissensorial de Feedbacks (M4)**: garantindo que todas as informações críticas sejam comunicadas por múltiplos canais (visual, textual, sonoro), incluindo mensagens de erro e status.
* **Elevar a satisfação geral do usuário** com a interface, tornando-a mais inclusiva e intuitiva.

## Ferramenta Utilizada

A ferramenta utilizada para o desenvolvimento do protótipo foi o **Figma**, escolhido por oferecer:

* **Prototipação navegável**: permitindo simular a interação real com a interface.
* **Componentes reutilizáveis**: otimizando o processo de design e mantendo a consistência.
* **Simulação realista de navegação**: facilitando a validação das melhorias propostas.
* **Facilidade de colaboração**: permitindo que a equipe trabalhe em conjunto e receba feedback.

## Resultados Esperados

Com a implementação das soluções propostas no protótipo, espera-se:

* **Redução drástica de falhas de navegação** para usuários que dependem de tecnologias assistivas.
* **Melhora significativa na clareza e no feedback** das ações do usuário, em conformidade com as métricas de acessibilidade.
* **Aumento da taxa de sucesso** na conclusão de tarefas por novos usuários e usuários com deficiência.
* **Elevação da acessibilidade geral da interface** para atingir os critérios de "Aceitável" na avaliação de Usabilidade, conforme o Plano de Medição.
* Resultar em uma **interface mais amigável e intuitiva** para todos.
* **Fortalecer a confiança e a estabilidade** percebida pelos usuários.

## Acesso ao Protótipo

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://embed.figma.com/design/wVIBxt5Qsh9Ir4gMP1jTwD/AgroMart_Acessibilidade?node-id=0-1&embed-host=share" allowfullscreen></iframe>

O protótipo desenvolvido está disponível publicamente no Figma, permitindo a navegação pelas telas, simulação de interações e visualização dos comentários técnicos realizados para guiar a implementação.

> [Clique aqui para acessar o protótipo navegável no Figma](https://www.figma.com/design/wVIBxt5Qsh9Ir4gMP1jTwD/AgroMart_Acessibilidade?node-id=0-1&p=f&t=uJndjm28puqn1VJN-0)

> [Clique aqui para acessar o fluxo completo do protótipo no Figma](https://www.figma.com/proto/wVIBxt5Qsh9Ir4gMP1jTwD/AgroMart_Acessibilidade?node-id=1-6&p=f&t=9FvMF0VRyDEZt60d-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=1%3A6)

Esses links podem ser utilizados por professores, avaliadores e desenvolvedores para validar a proposta, testar os fluxos e verificar as melhorias implementadas em acessibilidade e usabilidade.

## Conclusão

O desenvolvimento deste protótipo de alta fidelidade constitui uma **ação estratégica de melhoria contínua**, fundamentada em dados concretos de **usabilidade e acessibilidade**. Com base nas métricas avaliadas (M1, M2, M3, M4) e nas boas práticas de engenharia de software e design inclusivo, o novo design oferece uma interface:

* Mais clara, funcional e **acessível**;
* Mais **previsível e segura** para todos os perfis de usuário;
* Mais alinhada às expectativas e limitações do público-alvo, incluindo usuários com baixa familiaridade digital, agricultores familiares e **pessoas com deficiência**.

A implementação dessas melhorias torna o AgroMart um sistema mais preparado para escalar com qualidade, mantendo-se centrado no usuário e sustentado por fundamentos sólidos de design e desenvolvimento inclusivo.

## Histórico de Versões

| Versão | Data       | Descrição                          | Autor             | Revisor        |
|--------|------------|------------------------------------|-------------------|----------------|
| `1.0`  | 13/07/2025 | Elaboração da Proposta de Melhoria | Algusto Rodrigues | Augusto Duarte |