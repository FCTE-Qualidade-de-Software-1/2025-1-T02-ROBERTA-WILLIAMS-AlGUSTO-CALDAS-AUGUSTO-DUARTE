# Abstraction Sheet – Objetivo de Medição: Usabilidade com Foco em Acessibilidade

## Definições de Medição

| Elemento              | Descrição                                                                                                                                   |
|-----------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| **Objeto**            | Aplicativo móvel AgroMart                                                                                                                  |
| **Propósito**         | Avaliar a capacidade do sistema de oferecer uma experiência acessível e intuitiva para todos os perfis de usuário, com foco em limitações visuais. |
| **Foco de Qualidade** | Usabilidade com ênfase em acessibilidade. |
| **Ponto de Vista**    | Equipe de desenvolvimento.                                                    |

---


| **Foco da Qualidade**                         | **Fatores de Variação**                                                                                          |
|----------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| Legibilidade e contraste                      | Uso de cores e tamanhos de fonte que garantam boa visibilidade e distinção, mesmo para pessoas com daltonismo ou baixa visão. |
| Facilidade de interação                        | Elementos com tamanho e espaçamento apropriados para toque, além de indicações claras de foco, facilitando o uso em dispositivos móveis e por pessoas com limitações motoras. |
| Presença de descrições acessíveis             | Inclusão consistente de textos alternativos e labels em elementos visuais como botões, ícones e imagens para garantir acesso via leitores de tela. |
| Feedbacks acessíveis e redundantes             | Informações importantes transmitidas através de múltiplos canais sensoriais, como texto, som e cor, para reforçar a compreensão e garantir que o feedback seja percebido por todos os usuários. |

----

## Hipóteses Básicas e Impacto dos Fatores de Variação

| **Hipóteses Básicas (estimativa)**                                                                             | **Impacto dos Fatores de Variação**                                                                        |
|----------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| H1: A interface possui elementos com tamanho adequado ao toque em pelo menos 90% das telas, facilitando uso por pessoas com limitações motoras. | A usabilidade em dispositivos móveis pode ser comprometida se elementos forem pequenos ou muito próximos, dificultando a interação. |
| H2: Todas as telas críticas (100%) são compatíveis com leitores de tela, com rótulos e foco adequados.           | A navegação para usuários com deficiência visual pode ser prejudicada sem compatibilidade total com leitores de tela. |
| H3: Mais de 95% dos elementos interativos (botões, ícones e imagens) possuem descrições textuais (alt text) apropriadas. | A ausência de descrições textuais claras pode aumentar o tempo para aprendizado e causar confusão na navegação assistida. |
| H4: 100% dos feedbacks visuais importantes (cores, ícones) são reforçados por textos ou sinais sonoros descritivos. | Usuários com deficiência visual ou daltonismo podem não perceber informações importantes, impactando a experiência. |

---

## Histórico de Versões

| Versão | Data       | Descrição                                   | Autor                     | Revisor                |
|--------|------------|---------------------------------------------|---------------------------|------------------------|
| 1.0    | 11/07/2025 | Desenvolvimento Abstraction Sheet           | Augusto Duarte            | Algusto Rodrigues      |