# Requisitos Elicitados

## Introdução

Esta página reúne todos os requisitos funcionais e não funcionais elicitados por meio das técnicas de [introspecção](../tecnicas/introspeccao.md), [questionário](../tecnicas/questionario.md), [entrevista](../tecnicas/entrevista.md) e [observação](../tecnicas/observacao.md).

## Metodologia

A Tabela 1 apresenta os requisitos funcionais e não funcionais, organizados por ID, com suas respectivas descrições,que ao clicar são direcionados à página das técnicas utilizadas para sua elicitação e uma indicação do status de implementação.

As siglas representam:

- RFx: Requisito Funcional nºx
- RNFx: Requisito Não-Funcional nºx
- ISx: Requisito nºx elicitado pela Introspecção
- Qx: Requisito nºx elicitado pelo Questionário
- BSx: Requisito nºx elicitado pelo Brainstorming
- OBSx: Requisito nºx elicitado pela Observação

## Requisitos funcionais

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 1</b> - Requisitos funcionais</p>



| Tipo  | Descrição                                                                                                                         | ID                             | Implementado |
|-------|-----------------------------------------------------------------------------------------------------------------------------------|--------------------------------|--------------|
| RNF01 | O Sympla deve apresentar eventos de forma personalizada, com base na atividade do usuário.                                        | IS12, IS07                    | Sim          |
| RNF02 | O usuário deve conseguir acessar informações como data, local e preço do ingresso em, no máximo, 2 cliques durante a busca no Sympla. | IS13, IS08                    | Sim          |
| RNF03 | O Sympla deve permitir que o usuário acesse seus ingressos em, no máximo, 3 cliques.                                                 | IS14                           | Sim          |
| RNF04 | O Sympla deve oferecer atendimento especial para idosos e pessoas com deficiência durante o processo de compra de ingressos.      | IS15                           | Não          |
| RNF05 | O Sympla deve incluir um mecanismo de autenticação seguro, permitindo que os usuários façam login com suas credenciais.           | IS16, IS09                    | Sim          |
| RNF06 | O Sympla deve contar com uma área para que os usuários reportem erros de funcionamento da plataforma.                             | IS17, IS10                    | Sim          |
| RF01  | O Sympla permite filtrar eventos por Estado e Município.    | IS01                           | Sim          |
| RF02  | O Sympla oferece filtros por data e horário dos eventos.    | IS02                           | Sim          |
| RF03  | O Sympla possibilita filtrar eventos por categorias.        | IS03                           | Não          |
| RF04  | O Sympla permite a realização da compra de ingressos.       | IS04, OBS10                    | Sim          |
| RF05  | O Sympla oferece funcionalidades para cadastro e login de usuários. | IS05                           | Sim          |
| RF06  | O Sympla possibilita a exclusão do cadastro de usuários.    | IS06                           | Sim          |
| RF07  | O Sympla permite o cadastro de métodos de pagamento.        | IS07                           | Sim          |
| RF08  | O Sympla oferece a opção de cancelar compras realizadas.    | IS08                           | Não          |
| RF09  | O Sympla dispõe de um mecanismo de busca integrado.         | IS09                           | Sim          |
| RF10  | O Sympla oferece a opção de transferir ingressos.           | IS10                           | Sim          |
| RF11  | O Sympla oferece a opção de imprimir ingressos.                | IS11                           | Sim          |
| RF01  | O aplicativo filtra os eventos por Estado.                    | OBS01                          | Sim          |
| RF02  | O aplicativo permite a busca por eventos.                     | OBS02                          | Sim          |
| RF03  | O aplicativo permite compartilhar o evento por meio das redes sociais.                                                | OBS03                          | Sim          |
| RF04  | O aplicativo permite escolher a quantidade de ingressos que o usuário deseja comprar.                                 | OBS04                          | Sim          |
| RF05  | O aplicativo permite selecionar as poltronas para pessoas idosas, crianças, obesas ou com deficiência, caso as tenha. | OBS05                          | Sim          |
| RF06  | O aplicativo permite selecionar as poltronas especiais.                                                               | OBS06                          | Sim          |
| RF07  | Na seleção de ingresso, o aplicativo permite adicionar um cupom de desconto.                                          | OBS07                          | Sim          |
| RF08  | Caso o local do evento disponibilize, o aplicativo disponibiliza uma visão prévia da poltrona.                        | OBS08                          | Sim          |
| RF09  | O aplicativo permite a doação por parte do usuário para fundações.                                                    | OBS09                          | Sim          |
| RF10  | O aplicativo permite a realização da compra dos ingressos.                                                            | OBS10                          | Sim          |
| RF11  | O aplicativo possui uma função para entrar em contato com o suporte.                                                  | OBS11                          | Sim          |
| RF12  | O aplicativo permite ao usuário cancelar o pedido.                                                                    | OBS12                          | Sim          |
| RF13  | O aplicativo permite ao usuário alterar seus dados.                                                                   | OBS13                          | Sim          |
| RF14  | O aplicativo possui uma função que auxilia na recuperação da conta do usuário.                                        | OBS14                          | Sim          |
| RNF01 | O sistema deve alocar os eventos de acordo com a região selecionada a fim de facilitar a busca e a filtragem.                                                                   | OBS15                          | Sim          |
| RNF02 | Deve possuir, na página do evento, uma descrição sobre o local, a qual possui data, horário, valor e informações sobre o evento que pode ser acessada em, no máximo, 3 cliques. | OBS16                          | Sim          |
| RNF03 | Deve adaptar a tela de seleção de poltronas de acordo com as poltronas já escolhidas.                                                                                           | OBS17                          | Sim          |
| RNF04 | Deve apresentar ao usuário o feedback da confirmação de suas ações.                                                                                                             | OBS18                          | Sim          |
| RNF05 | Deve apresentar uma página acessível de suporte e de perguntas frequentes com, no máximo, 1 clique.                                                                             | OBS19                          | Sim          |
| RNF06 | Deve apresentar uma tela com os dados da conta com ao menos uma etapa de segurança.                                                                                             | OBS20                          | Sim          |
| RNF07 | Deve apresentar uma página com o histórico de pedidos do usuário em dois cliques.                                                                                               | OBS21                          | Sim          |
| RNF08 | Deve permitir a filtragem dos eventos com apenas 1 clique.                                                                                                                      | OBS22                          | Sim          |


<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/MilenaFRocha">Milena Rocha</a></p></font>

## Histórico de Versões

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     | 
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|
|  1.0   | Criação desse documento | [Milena Rocha](https://github.com/MilenaFRocha) | 18/11/2024 | [Rafael Pereira](https://github.com/rafgpereira)  |
