# Observação

## Introdução
A técnica de observação de requisitos é uma abordagem essencial para coletar informações sobre as necessidades de um software. Ela consiste em observar usuários, processos e sistemas em funcionamento para compreender as demandas e preferências dos usuários finais, além de identificar limitações e restrições no ambiente de uso do aplicativo. Agradecemos, desde já, a participação de Gabriel Pessoa, usuário que foi observado durante a utilização do app Sympla


No dia 18/11/2024, das 14:00 às 15:00, os integrantes se reuniram, conforme detalhado na Tabela 1, por meio do Microsoft Teams, com o propósito de realizar uma Observação Participativa, na qual o Engenheiro de Software exerce influência sobre o processo. Durante essa atividade, os observadores [Milena Rocha](https://github.com/MilenaFRocha) e [Gabriel Scheidt](https://github.com/Gxaite) orientaram o usuário Gabriel Pessoa sobre as ações a serem executadas no aplicativo da Sympla. O usuário compartilhou a tela de seu celular, enquanto os observadores guiavam os passos a serem seguidos. Os requisitos identificados estão registrados nas Tabelas 2 e 3.
### Participantes

<font size="3"><p style="text-align: center">Tabela 1: Participantes.</p></font>

<center>

| Nome                                             | Função                   |
| ------------------------------------------------ | ------------------------ |
| [Milena Rocha](https://github.com/MilenaFRocha)  | Observador               |
| [Gabriel Scheidt](https://github.com/Gxaite)   | Observador |
| Gabriel Pessoa  | Observado |

</center>

<font size="3"><p style="text-align: center">Fonte: [Milena Rocha](https://github.com/MilenaFRocha) e [Gabriel Scheidt](https://github.com/Gxaite).</p></font>

### [Link para a gravação da observação.](https://www.youtube.com/watch?v=YAJ2Utv1DEg)
<iframe width="560" height="315" src="https://www.youtube.com/embed/YAJ2Utv1DEg?si=hrKmBmviNJFMxqnc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Requisitos elicitados

Legenda das Tabelas 2 e 3:

- RFx: Requisito Funcional nºx
- RNFx: Requisito Não-Funcional nºx
- OBSx: Requisito nºx elicitado pela observação.

### Funcionais

<font size="3"><p style="text-align: center">Tabela 2: Requisitos Funcionais.</p></font>

<center>

| Tipo | Descrição                                                                                                             | <a id="anchor_OBS" style="visibility: hidden;"></a> ID | Implementado |
| ---- | --------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ | ------------ |
| RF01 | O aplicativo filtra os eventos por Estado.                                                                            | OBS01                                                  | Sim          |
| RF02 | O aplicativo permite a busca por eventos.                                                                             | OBS02                                                  | Sim          |
| RF03 | O aplicativo permite compartilhar o evento por meio das redes sociais.                                                | OBS03                                                  | Sim          |
| RF04 | O aplicativo permite escolher a quantidade de ingressos que o usuário deseja comprar.                                 | OBS04                                                  | Sim          |
| RF05 | O aplicativo permite selecionar as poltronas para pessoas idosas, crianças, obesas ou com deficiência, caso as tenha. | OBS05                                                  | Sim          |
| RF06 | O aplicativo permite selecionar as poltronas especiais.                                                               | OBS06                                                  | Sim          |
| RF07 | Na seleção de ingresso, o aplicativo permite adicionar um cupom de desconto.                                          | OBS07                                                  | Sim          |
| RF08 | Caso o local do evento disponibilize, o aplicativo disponibiliza uma visão prévia da poltrona.                        | OBS08                                                  | Sim          |
| RF09 | O aplicativo permite a doação por parte do usuário para fundações.                                                    | OBS09                                                  | Sim          |
| RF10 | O aplicativo permite a realização da compra dos ingressos.                                                            | OBS10                                                  | Sim          |
| RF11 | O aplicativo possui uma função para entrar em contato com o suporte.                                                  | OBS11                                                  | Sim          |
| RF12 | O aplicativo permite ao usuário cancelar o pedido.                                                                    | OBS12                                                  | Sim          |
| RF13 | O aplicativo permite ao usuário alterar seus dados.                                                                   | OBS13                                                  | Sim          |
| RF14 | O aplicativo possui uma função que auxilia na recuperação da conta do usuário.                                        | OBS14                                                  | Sim          |

</center>

<font size="3"><p style="text-align: center">Fonte: [Milena Rocha](https://github.com/MilenaFRocha) e [Gabriel Scheidt](https://github.com/Gxaite).</p></font>

### Não funcionais

<font size="3"><p style="text-align: center">Tabela 3: Requisitos Não-Funcionais.</p></font>

<center>

| Tipo  | Descrição                                                                                                                                                                       | <a id="anchor_OBSNF" style="visibility: hidden;"></a>ID | Implementado |
| ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- | ------------ |
| RNF01 | O sistema deve alocar os eventos de acordo com a região selecionada a fim de facilitar a busca e a filtragem.                                                                   | OBS15                                                   | Sim          |
| RNF02 | Deve possuir, na página do evento, uma descrição sobre o local, a qual possui data, horário, valor e informações sobre o evento que pode ser acessada em, no máximo, 3 cliques. | OBS16                                                   | Sim          |
| RNF03 | Deve adaptar a tela de seleção de poltronas de acordo com as poltronas já escolhidas.                                                                                           | OBS17                                                   | Sim          |
| RNF04 | Deve apresentar ao usuário o feedback da confirmação de suas ações.                                                                                                             | OBS18                                                   | Sim          |
| RNF05 | Deve apresentar uma página acessível de suporte e de perguntas frequentes com, no máximo, 1 clique.                                                                             | OBS19                                                   | Sim          |
| RNF06 | Deve apresentar uma tela com os dados da conta com ao menos uma etapa de segurança.                                                                                             | OBS20                                                   | Sim          |
| RNF07 | Deve apresentar uma página com o histórico de pedidos do usuário em dois cliques.                                                                                               | OBS21                                                   | Sim          |
| RNF08 | Deve permitir a filtragem dos eventos com apenas 1 clique.                                                                                                                      | OBS22                                                   | Sim          |

</center>

<font size="3"><p style="text-align: center">Fonte: [Milena Rocha](https://github.com/MilenaFRocha) e [Gabriel Scheidt](https://github.com/Gxaite).</p></font>

## Bibliografia

> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. **UnB Gama**, Brasília, 2023. Disponível em: <<https://aprender3.unb.br/pluginfile.php/2580553/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>>. Acesso em: 29/04/2023.

## Histórico de Versões

| Versão | Data       | Descrição                      | Autor(es)                                                                                         | Revisor(es)                                    |
| ------ | ---------- | ------------------------------ | ------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| `1.0`  | 18/11/2024 | Criação do arquivo     |[Milena Rocha](https://github.com/MilenaFRocha)  [Gabriel Scheidt](https://github.com/Gxaite) | [Rafael Pereira](https://github.com/rafgpereira) |
