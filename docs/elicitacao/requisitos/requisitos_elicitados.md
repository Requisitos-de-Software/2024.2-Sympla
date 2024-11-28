# Requisitos Elicitados

## Introdução

Esta página reúne todos os requisitos funcionais e não funcionais elicitados por meio das técnicas de [introspecção](../tecnicas/introspeccao.md), [questionário](../tecnicas/questionario.md), [entrevista 1](../tecnicas/entrevista.md), [entrevista 2](../tecnicas/entrevista2.md) e [observação](../tecnicas/observacao.md).

## Metodologia

A Tabela 1 apresenta os requisitos funcionais e não funcionais, organizados por ID, com suas respectivas descrições e se estão implementados.

As siglas representam:

- RFx: Requisito Funcional nºx
- RNFx: Requisito Não-Funcional nºx
- ISx: Requisito nºx elicitado pela Introspecção
- QSx: Requisito nºx elicitado pelo Questionário
- 1ENTx: Requisito nºx elicitado pelo Entrevista 1
- 2ENTx: Requisito nºx elicitado pelo Entrevista 2
- OBSx: Requisito nºx elicitado pela Observação
- x: Variável ou nº do requisito

## Requisitos

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 1</b> - Requisitos funcionais e não funcionais</p>

| Tipo  | Descrição                                                                                                      | ID                                   | Implementado |
|-------|--------------------------------------------------------------------------------------------------------------|---------------------------------------|--------------|
| RF01  | O sistema permite filtrar eventos por Estado e Município.                                                     | <a href="../../tecnicas/introspeccao/#anchor_ISF">IS01</a>, <a href="../../tecnicas/observacao/#anchor_OBS">OBS01</a>                           | Sim          |
| RF02  | O sistema exibe detalhes importantes do evento, como horário de entrada e local.                              | <a href="../../tecnicas/entrevista/#anchor_2ENT">2ENT02</a>, <a href="../../tecnicas/entrevista/#anchor_1ENT">1ENT03</a>, <a href="../../tecnicas/observacao/#anchor_OBS">OBS16</a>, <a href="../../tecnicas/introspeccao/#anchor_ISF">IS02</a>           | Sim          |
| RF03  | O sistema envia notificações ou lembretes sobre os eventos comprados.                                         | <a href="../../tecnicas/entrevista/#anchor_2ENT">2ENT03</a>, <a href="../../tecnicas/entrevista/#anchor_1ENT">1ENT04</a>, <a href="../../tecnicas/questionario/#anchor_QS">QS03</a>, <a href="../../tecnicas/introspeccao/#anchor_ISF">IS18</a>                | Sim          |
| RF04  | O sistema fornece uma ampla variedade de eventos.                                                             | <a href="../../tecnicas/entrevista/#anchor_2ENT">2ENT04</a>, <a href="../../tecnicas/questionario/#anchor_QS">QS04</a>                          | Sim          |
| RF05  | O aplicativo permite compartilhar o evento por meio das redes sociais.                                        | <a href="../../tecnicas/observacao/#anchor_OBS">OBS03</a>                                 | Sim          |
| RF06  | Deve ser possível adicionar vários ingressos ao carrinho antes de finalizar a compra.                         | <a href="../../tecnicas/entrevista/#anchor_1ENT">1ENT01</a>                                | Não          |
| RF07  | Deve ser possível retirar vários ingressos do carrinho adicionados.                                           | <a href="../../tecnicas/entrevista/#anchor_1ENT">1ENT02</a>                                | Não          |
| RF08  | O sistema permite cancelamento e transferências de ingressos diretamente na plataforma.                       | <a href="../../tecnicas/entrevista/#anchor_2ENT">2ENT07</a>, <a href="../../tecnicas/observacao/#anchor_OBS">OBS12</a>, <a href="../../tecnicas/introspeccao/#anchor_ISF">IS08</a>, <a href="../../tecnicas/introspeccao/#anchor_ISF">IS10</a>             | Não          |
| RF09  | Deve ser possível visualizar a planta do local para a escolha de assentos (quando aplicável).                 | <a href="../../tecnicas/entrevista/#anchor_2ENT">2ENT08</a>, <a href="../../tecnicas/observacao/#anchor_OBS">OBS08</a>                         | Sim          |
| RF10  | O sistema disponibiliza um histórico completo das compras realizadas pelo usuário.                            | <a href="../../tecnicas/entrevista/#anchor_2ENT">2ENT09</a>, <a href="../../tecnicas/observacao/#anchor_OBS">OBS21</a>                         | Sim          |
| RF11  | O sistema simplifica filas de compra.                                                                         | <a href="../../tecnicas/entrevista/#anchor_2ENT">2ENT10</a>                                | Não          |
| RF12  | O usuário deve permanecer logado por um tempo determinado para não precisar relogar frequentemente.           | <a href="../../tecnicas/entrevista/#anchor_1ENT">1ENT05</a>                                | Não          |
| RF13  | O aplicativo fornece uma funcionalidade de busca eficiente para facilitar a localização dos produtos.         | <a href="../../tecnicas/questionario/#anchor_QS">QS01</a>, <a href="../../tecnicas/observacao/#anchor_OBS">OBS02</a>, <a href="../../tecnicas/introspeccao/#anchor_ISF">IS09</a>                     | Sim          |
| RF14  | O aplicativo permite a escolha da quantidade de ingressos que o usuário deseja comprar.                       | <a href="../../tecnicas/observacao/#anchor_OBS">OBS04</a>                                 | Sim          |
| RF15  | O aplicativo permite selecionar poltronas para pessoas idosas, crianças, obesas ou com deficiência, caso existam. | <a href="../../tecnicas/observacao/#anchor_OBS">OBS05</a>                                | Sim          |
| RF16  | O aplicativo permite selecionar as poltronas especiais.                                                       | <a href="../../tecnicas/observacao/#anchor_OBS">OBS06</a>                                 | Sim          |
| RF17  | Na seleção de ingresso, o aplicativo permite adicionar um cupom de desconto.                                  | <a href="../../tecnicas/observacao/#anchor_OBS">OBS07</a>                                 | Sim          |
| RF18  | O aplicativo permite a doação por parte do usuário para fundações.                                            | <a href="../../tecnicas/observacao/#anchor_OBS">OBS09</a>                                 | Sim          |
| RF19  | O aplicativo permite a realização da compra dos ingressos.                                                    | <a href="../../tecnicas/observacao/#anchor_OBS">OBS10</a>, <a href="../../tecnicas/introspeccao/#anchor_ISF">IS04</a>                           | Sim          |
| RF20  | O aplicativo possui uma função para entrar em contato com o suporte.                                          | <a href="../../tecnicas/observacao/#anchor_OBS11">OBS11</a>, <a href="../../tecnicas/introspeccao/#anchor_ISF">IS17</a>                           | Sim          |
| RF21  | O aplicativo permite ao usuário alterar seus dados.                                                           | <a href="../../tecnicas/observacao/#anchor_OBS13">OBS13</a>                                 | Sim          |
| RF22  | O aplicativo possui uma função que auxilia na recuperação da conta do usuário.                                | <a href="../../tecnicas/observacao/#anchor_OBS14">OBS14</a>                                 | Sim          |
| RF23  | O aplicativo oferece diversas opções de pagamento para a compra de ingressos.                                | <a href="../../tecnicas/questionario/#anchor_QS">QS02</a>, <a href="../../tecnicas/introspeccao/#anchor_ISF">IS07</a>                            | Sim          |
| RF24  | As opções de pagamento são seguras, utilizando criptografia para proteger os dados financeiros do usuário.     |  <a href="../../tecnicas/observacao/#anchor_QS">QS05</a>                                | Sim          |
| RF25  | O sistema é acessível por dispositivos móveis, computadores e notebooks, com uma interface responsiva.         | <a href="../../tecnicas/questionario/#anchor_QS"> QS06        </a>                         | Sim          |
| RF26  | O Sympla possibilita filtrar eventos por categorias.        |  <a href="../../tecnicas/introspeccao/#anchor_ISF">IS03</a>  | Não          |
| RF27  | O Sympla oferece funcionalidades para cadastro e login de usuários. | <a href="../../tecnicas/introspeccao/#anchor_ISF">IS05</a> | Sim          |
| RF28  | O Sympla possibilita a exclusão do cadastro de usuários.    | <a href="../../tecnicas/introspeccao/#anchor_ISF">IS06</a> | Sim          |
| RF29  | O Sympla oferece a opção imprimir ingressos.                | <a href="../../tecnicas/introspeccao/#anchor_ISNF">IS19</a> | Sim          |
| RF30  | O aplicativo dá sugestões de eventos com base no histórico de buscas do usuário.                  |  <a href="../../tecnicas/introspeccao/#anchor_ISF">IS11</a>  | Não          |O Sympla oferece a opção imprimir ingressos.
| RF31  | O usuário é capaz de conectar uma carteira digital.                                               | <a href="../../tecnicas/introspeccao/#anchor_ISF"> IS12</a>  | Não          |
| RF32  | O usuário é capaz de mudar o idioma do app.                                                       |  <a href="../../tecnicas/introspeccao/#anchor_ISF">IS13 </a> | Não          |
| RF33  | O usuário é capaz de entrar na aba de configurações.                                              |  <a href="../../tecnicas/introspeccao/#anchor_ISF">IS14 </a> | Não          |
| RF34  | O sistema apresenta uma aba de acessibilidades.                                                   | <a href="../../tecnicas/introspeccao/#anchor_ISF"> IS15 </a> | Não          |
| RF35  | O usuário é capaz de criar preferências de eventos.                                               |  <a href="../../tecnicas/introspeccao/#anchor_ISF">IS16 </a> | Não          |
| RNF01 | O envio do ingresso deve ser rápido.                                                                          | <a href="../../tecnicas/entrevista/#anchor_2ENT">2ENT05   </a>                             | Não          |
| RNF02 | O sistema deve ser seguro para uso comercial.                                                                 | <a href="../../tecnicas/entrevista/#anchor_2ENT">2ENT06  </a>                              | Sim          |
| RNF03 | O login deve ser estável, evitando falhas frequentes que exijam que o usuário se autentique novamente.        |<a href="../../tecnicas/entrevista/#anchor_1ENT"> 1ENT06  </a>                                | Não          |
| RNF04 | O sistema processa compras de ingressos rapidamente, sem atrasos perceptíveis.                                | <a href="../../tecnicas/entrevista/#anchor_1ENT">1ENT07   </a>                             | Sim          |
| RNF05 | O aplicativo garante um bom desempenho, evitando travamentos ou lentidão durante o uso.                       |  <a href="../../tecnicas/questionario/#anchor_QS">QS07   </a>                              | Sim          |
| RNF06 | O sistema exibe preços competitivos de forma clara e transparente.                                            |  <a href="../../tecnicas/questionario/#anchor_QS">QS08 </a>                              | Não          |
| RNF07 | O sistema aloca os eventos de acordo com a região selecionada para facilitar a busca e a filtragem.           | <a href="../../tecnicas/observacao/#anchor_OBS">OBS15  </a>                               | Sim          |
| RNF08 | Deve adaptar a tela de seleção de poltronas de acordo com as poltronas já escolhidas.                         |<a href="../../tecnicas/observacao/#anchor_OBS"> OBS17   </a>                              | Sim          |
| RNF09 | Deve apresentar ao usuário o feedback da confirmação de suas ações.                                           |<a href="../../tecnicas/observacao/#anchor_OBS"> OBS18 </a>                                | Sim          |
| RNF10 | Deve apresentar uma página acessível de suporte e de perguntas frequentes com, no máximo, 1 clique.           | <a href="../../tecnicas/observacao/#anchor_OBS">OBS19</a>                                 | Sim          |
| RNF11 | Deve apresentar uma tela com os dados da conta com ao menos uma etapa de segurança.                           | <a href="../../tecnicas/observacao/#anchor_OBS">OBS20</a>, IS16                           | Sim          |
| RNF12 | Deve permitir a filtragem dos eventos com apenas 1 clique.                                                    |<a href="../../tecnicas/observacao/#anchor_OBS"> OBS22</a> ,<a href="../../tecnicas/entrevista/#anchor_2ENT">2ENT01   </a>                            | Sim          |
| RNF13 | O sistema apresenta eventos de forma personalizada, com base na atividade do usuário.                        |  <a href="../../tecnicas/introspeccao/#anchor_ISF"> IS19   </a>                              | Sim          |
| RNF14 | O usuário deve conseguir acessar informações como data, local e preço do ingresso em, no máximo, 2 cliques durante a busca no Sympla. | <a href="../../tecnicas/introspeccao/#anchor_ISF"> IS20 </a>  | Sim          |
| RNF15 | O Sympla deve permitir que o usuário acesse seus ingressos em, no máximo, 3 cliques.                                                 | <a href="../../tecnicas/introspeccao/#anchor_ISF"> IS21 </a>  | Sim          |
| RNF16 | O Sympla deve oferecer atendimento especial para idosos e pessoas com deficiência durante o processo de compra de ingressos.      | <a href="../../tecnicas/introspeccao/#anchor_ISF"> IS22 </a>  | Não          |
| RNF17 | O aplicativo mostra os eventos de preferência escolhida pelo usuário ao abrir.                    |<a href="../../tecnicas/observacao/#anchor_OBS"> OBS23</a> | Não          |
| RNF18 | O Sympla deve incluir um mecanismo de autenticação seguro, permitindo que os usuários façam login com suas credenciais.           |  <a href="../../tecnicas/introspeccao/#anchor_ISF">IS23 </a>  | Sim          |
| RNF19 | O Sympla deve contar com uma área para que os usuários reportem erros de funcionamento da plataforma.                             | <a href="../../tecnicas/introspeccao/#anchor_ISF"> IS24</a>   | Sim          |





<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/MilenaFRocha">Milena Rocha</a></p></font>

## Histórico de Versões

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     | 
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|
|  1.0   | Criação desse documento | [Milena Rocha](https://github.com/MilenaFRocha) | 18/11/2024 | [Rafael Pereira](https://github.com/rafgpereira)  |
|  1.1   | Atualização da tabela| [Milena Rocha](https://github.com/MilenaFRocha) | 18/11/2024 | [Rafael Pereira](https://github.com/rafgpereira)  |
|  1.2   | Atualização da tabela| [Gabriel Scheidt](https://github.com/gxaite) | 24/11/2024 | [Milena Rocha](https://github.com/MilenaFRocha)  |
|  1.3   | Ajustes de escrita|  [Milena Rocha](https://github.com/MilenaFRocha) | 24/11/2024 | [Gabriel Scheidt](https://github.com/gxaite) |

