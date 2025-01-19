
# Backward-From

## Introdução

### Rastreabilidade Backward-From:

Este documento explora o uso do método de rastreabilidade backward-from, uma abordagem essencial no desenvolvimento de sistemas. A rastreabilidade de requisitos desempenha um papel central ao viabilizar a identificação e a conexão entre requisitos durante a etapa de desenvolvimento, além de permitir seu acompanhamento ao longo de todo o ciclo de vida do sistema. Essa prática proporciona uma compreensão mais detalhada das origens e implicações de cada requisito, contribuindo para a garantia da qualidade, uma gestão de mudanças mais eficaz e o alinhamento contínuo com as necessidades do cliente.

### Estabelecendo Conexões com o Método Backward-From

Ao implementar o método de rastreabilidade backward-from, busca-se criar vínculos claros entre os requisitos e suas respectivas origens. Essa abordagem permite rastrear um requisito até sua fonte, seja ela uma solicitação de cliente, um processo de negócio ou outra referência relevante. Materiais como os [slides da aula 26](https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf), ministrada pela professora Milene Serrano, e o livro [Requirements Engineering Fundamentals](https://aprender3.unb.br/pluginfile.php/2972415/mod_resource/content/2/Rastreabilidade.pdf), de Klaus Pohl e Chris Rupp, fornecem insights valiosos que enriquecem essa abordagem, garantindo uma visão mais organizada e completa da rastreabilidade de requisitos.

### Benefícios da Rastreabilidade para Validação e Verificação

A rastreabilidade bem implementada não apenas facilita o entendimento dos requisitos, mas também simplifica os processos de validação e verificação de sistemas. Essa prática permite a identificação precoce de possíveis problemas, resultando em economias significativas de tempo e recursos. Além disso, contribui para a satisfação do cliente ao garantir que o sistema atenda de forma precisa e confiável às suas necessidades ao longo de todo o ciclo de vida.

## Metodologia 

A metodologia utilizada neste projeto baseia-se no meta-modelo de rastreabilidade proposto por Toranzo, adaptado para atender as necessidades específicas do Sympla. Este modelo organiza as informações rastreadas em diferentes categorias e elos de rastreabilidade, permitindo uma visão detalhada e integrada do ciclo de vida dos requisitos. A seguir, detalhamos as adaptações e abordagens adotadas.

#### Classificação das Informações Rastreáveis
As informações rastreadas foram organizadas em quatro categorias principais, conforme o meta-modelo original, mas com adaptações para o escopo do projeto Sympla:

- **Ambiental:** Inclui leis, padrões e estratégias que influenciam o funcionamento do sistema. No caso do Sympla, isso abrange conformidade com LGPD e regulamentações fiscais para eventos.
- **Organizacional:** Relaciona-se às regras de negócio, fluxos de processo e objetivos da organização. Neste projeto, isso inclui políticas de cancelamento e gerenciamento de eventos.
- **Gerencial:** Contém objetivos, tarefas e restrições relacionadas à gestão do projeto, como prazos e restrições orçamentárias.
- **Desenvolvimento:** Abrange requisitos, artefatos de design e código-fonte. Para o Sympla, esta é a categoria central, dado o foco em rastrear implementação e validação de funcionalidades.

#### Adaptação do Meta-Modelo
Foi realizada uma adaptação do meta-modelo de Toranzo para incluir o processo de pós-rastreabilidade. Esta adaptação conecta os artefatos de design e implementação diretamente aos requisitos elicitados e vice-versa, promovendo maior clareza na gestão de dependências.

No entanto, devido à limitação das informações presentes nos artefatos do Sympla, o elo de **responsabilidade** foi incluído com adaptações para rastrear as ações e atribuições associadas aos artefatos e requisitos. Os elos considerados no projeto são:

- **Satisfação:** Relação entre os requisitos elicitados e as funcionalidades que os atendem.
- **Recurso:** Dependência entre os requisitos e os recursos necessários para sua implementação.
- **Responsabilidade:** Conexão entre os artefatos ou requisitos e as pessoas ou equipes responsáveis por sua criação, validação ou implementação.
- **Representação:** Formas alternativas de expressão ou modelagem dos requisitos.
- **Alocado:** Ligação entre os requisitos e subsistemas ou módulos específicos.
- **Agregação:** Composição de elementos interconectados que formam o sistema.


## Tabelas de Requisitos Funcionais

Esta seção é dedicada à construção da tabela de rastreamento dos requisitos funcionais, apresentada na Tabela 1:

**Legenda:**

- **RF**: Requisito Funcional  
- **RNF**: Requisito Não Funcional  
- **ENT**: Entrevista  
- **O**: Observação  
- **IS**: Introspecção
- **X**: Variável representando o número da entrevista

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Requisitos funcionais elicitados</p></font>
</div>
 Tipo e versão  | Descrição                                                                                                      | <a id="anchor_GERAL" style="color:black;">Rastreabilidade</a> | Implementado |
|-------|--------------------------------------------------------------------------------------------------------------|---------------------------------------|--------------|
| RF01 </a> /`1.4`| O sistema permite filtrar eventos por Estado e Município.                                                     | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS01</a>, <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS01</a>                           | Sim          |
| RF02  </a> /`1.4`| O sistema exibe detalhes importantes do evento, como horário de entrada e local.                              | <a href="../../elicitacao/tecnicas/entrevista2/#anchor_2ENT">2ENT02</a>, <a href="../../elicitacao/tecnicas/entrevista/#anchor_1ENT">1ENT03</a>, <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS16</a>, <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS02</a>           | Sim          |
| RF03 </a> /`1.4` | O sistema envia notificações ou lembretes sobre os eventos comprados.                                         | <a href="../../elicitacao/tecnicas/entrevista2/#anchor_2ENT">2ENT03</a>, <a href="../../elicitacao/tecnicas/entrevista/#anchor_1ENT">1ENT04</a>, <a href="../../elicitacao/tecnicas/questionario/#anchor_QS">QS03</a>, <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS18</a>                | Sim          |
| RF04 </a> /`1.4` | O sistema fornece uma ampla variedade de eventos.                                                             | <a href="../../elicitacao/tecnicas/entrevista2/#anchor_2ENT">2ENT04</a>, <a href="../../elicitacao/tecnicas/questionario/#anchor_QS">QS04</a>                          | Sim          |
| RF05  </a> /`1.4`| O aplicativo permite compartilhar o evento por meio das redes sociais.                                        | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS03</a>                                 | Sim          |
| RF06 </a> /`1.4` | Deve ser possível adicionar vários ingressos ao carrinho antes de finalizar a compra.                         | <a href="../../elicitacao/tecnicas/entrevista/#anchor_1ENT">1ENT01</a>                                | Não          |
| RF07 </a> /`1.4` | Deve ser possível retirar vários ingressos do carrinho adicionados.                                           | <a href="../../elicitacao/tecnicas/entrevista/#anchor_1ENT">1ENT02</a>                                | Não          |
| RF08 </a> /`1.4` | O sistema permite cancelamento e transferências de ingressos diretamente na plataforma.                       | <a href="../../elicitacao/tecnicas/entrevista2/#anchor_2ENT">2ENT07</a>, <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS12</a>, <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS08</a>, <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS10</a>             | Não          |
| RF09  </a> /`1.4`| Deve ser possível visualizar a planta do local para a escolha de assentos (quando aplicável).                 | <a href="../../elicitacao/tecnicas/entrevista2/#anchor_2ENT">2ENT08</a>, <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS08</a>                         | Sim          |
| RF10 </a> /`1.4` | O sistema disponibiliza um histórico completo das compras realizadas pelo usuário.                            | <a href="../../elicitacao/tecnicas/entrevista2/#anchor_2ENT">2ENT09</a>, <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS21</a>                         | Sim          |
| RF11 </a> /`1.4` | O sistema simplifica filas de compra.                                                                         | <a href="../../elicitacao/tecnicas/entrevista2/#anchor_2ENT">2ENT10</a>                                | Não          |
| RF12 </a> /`1.4` | O usuário deve permanecer logado por um tempo determinado para não precisar relogar frequentemente.           | <a href="../../elicitacao/tecnicas/entrevista/#anchor_1ENT">1ENT05</a>                                | Não          |
| RF13 </a> /`1.4`  | O aplicativo fornece uma funcionalidade de busca eficiente para facilitar a localização dos produtos.         | <a href="../../elicitacao/tecnicas/questionario/#anchor_QS">QS01</a>, <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS02</a>, <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS09</a>                     | Sim          |
| RF14 </a> /`1.4` | O aplicativo permite a escolha da quantidade de ingressos que o usuário deseja comprar.                       | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS04</a>                                 | Sim          |
| RF15  </a> /`1.4`| O aplicativo permite selecionar poltronas para pessoas idosas, crianças, obesas ou com deficiência, caso existam. | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS05</a>                                | Sim          |
| RF16 </a> /`1.4` | O aplicativo permite selecionar as poltronas especiais.                                                       | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS06</a>                                 | Sim          |
| RF17 </a> /`1.4` | Na seleção de ingresso, o aplicativo permite adicionar um cupom de desconto.                                  | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS07</a>                                 | Sim          |
| RF18 </a> /`1.4` | O aplicativo permite a doação por parte do usuário para fundações.                                            | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS09</a>                                 | Sim          |
| RF19 </a> /`1.4` | O aplicativo permite a realização da compra dos ingressos.                                                    | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS10</a>, <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS04</a>                           | Sim          |
| RF20 </a> /`1.4` | O aplicativo possui uma função para entrar em contato com o suporte.                                          | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS11">OBS11</a>, <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS17</a>                           | Sim          |
| RF21 </a> /`1.4` | O aplicativo permite ao usuário alterar seus dados.                                                           | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS13">OBS13</a>                                 | Sim          |
| RF22 </a> /`1.4`  | O aplicativo possui uma função que auxilia na recuperação da conta do usuário.                                | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS14">OBS14</a>                                 | Sim          |
| RF23 </a> /`1.4` | O aplicativo oferece diversas opções de pagamento para a compra de ingressos.                                | <a href="../../elicitacao/tecnicas/questionario/#anchor_QS">QS02</a>, <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS07</a>                            | Sim          |
| RF24  </a> /`1.4`| As opções de pagamento são seguras, utilizando criptografia para proteger os dados financeiros do usuário.     |  <a href="../../elicitacao/tecnicas/observacao/#anchor_QS">QS05</a>                                | Sim          |
| RF25  </a> /`1.4`| O sistema é acessível por dispositivos móveis, computadores e notebooks, com uma interface responsiva.         | <a href="../../elicitacao/tecnicas/questionario/#anchor_QS"> QS06        </a>                         | Sim          |
| RF26 </a> /`1.4` | O Sympla possibilita filtrar eventos por categorias.        |  <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS03</a>  | Não          |
| RF27 </a> /`1.4` | O Sympla oferece funcionalidades para cadastro e login de usuários. | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS05</a> | Sim          |
| RF28 </a> /`1.4` | O Sympla possibilita a exclusão do cadastro de usuários.    | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS06</a> | Sim          |
| RF29 </a> /`1.4` | O Sympla oferece a opção imprimir ingressos.                | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISNF">IS19</a> | Sim          |
| RF30 </a> /`1.4` | O aplicativo dá sugestões de eventos com base no histórico de buscas do usuário.                  |  <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS11</a>  | Não          |O Sympla oferece a opção imprimir ingressos.
| RF31 </a> /`1.4` | O usuário é capaz de conectar uma carteira digital.                                               | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF"> IS12</a>  | Sim          |
| RF32  </a> /`1.4`| O usuário é capaz de mudar o idioma do app.                                                       |  <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS13 </a> | Não          |
| RF33 </a> /`1.4` | O usuário é capaz de entrar na aba de configurações.                                              |  <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS14 </a> | Não          |
| RF34 </a> /`1.4` | O sistema apresenta uma aba de acessibilidades.                                                   | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF"> IS15 </a> | Não          |
| RF35 </a> /`1.4` | O usuário é capaz de criar preferências de eventos.                                               |  <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS16 </a> | Não          |
| RF36  </a> /`1.4`| Deve ser possível cadastrar diferentes métodos de pagamento.                                               |  <a href="../../elicitacao/tecnicas/entrevista2/#anchor_2ENT">2ENT11</a>  | Não          |
| RF37 </a> /`1.4` | O Sympla permite criar, gerenciar e divulgar eventos de forma intuitiva.                 | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF"> IS19</a> | Não          |
| RF38  </a> /`1.4`| O Sympla fornece relatórios detalhados de vendas e participação em eventos.              | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS20</a> | Não          |
| RF39 </a> /`1.4` | O Sympla possibilita a customização dos ingressos, incluindo preços e lotes.             | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS21</a> | Não          |
| RF40 </a> /`1.4`  | O Sympla tem uma área para produtores de eventos.    | <a href="../../elicitacao/elicitacao/tecnicas/introspeccao/#anchor_ISF">IS22</a> | Não          |
<div align="center">
<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/Gxaite">Gabriel Scheidt</a> e <a href="https://github.com/MilenaFRocha">Milena Rocha</a>, 2025</p></font>
</div>

## Tabelas de requisitos não-funcionais
Este seguimento é destinado para a elaboração da tabela de rastreamento de requisitos não-funcionais, que está sendo demonstrado na tabela 2 a seguir:

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 2</b> - Requisitos não funcionais</p>

| Tipo e versão  | Descrição                                                                                                      | <a id="anchor_GERAL" style="color:black;">Rastreabilidade</a> | Implementado |
|-------|--------------------------------------------------------------------------------------------------------------|---------------------------------------|--------------|
| RNF01 | O envio do ingresso deve ser rápido.                                                                          | <a href="../../elicitacao/tecnicas/entrevista2/#anchor_2ENT">2ENT05   </a>                             | Não          |
| RNF02 | O sistema deve ser seguro para uso comercial.                                                                 | <a href="../../elicitacao/tecnicas/entrevista2/#anchor_2ENT">2ENT06  </a>                              | Sim          |
| RNF03 | O login deve ser estável, evitando falhas frequentes que exijam que o usuário se autentique novamente.        |<a href="../../elicitacao/tecnicas/entrevista/#anchor_1ENT"> 1ENT06  </a>                                | Não          |
| RNF04 | O sistema processa compras de ingressos rapidamente, sem atrasos perceptíveis.                                | <a href="../..elicitacao//tecnicas/entrevista/#anchor_1ENT">1ENT07   </a>                             | Sim          |
| RNF05 | O aplicativo garante um bom desempenho, evitando travamentos ou lentidão durante o uso.                       |  <a href="../../elicitacao/tecnicas/questionario/#anchor_QS">QS07   </a>                              | Sim          |
| RNF06 | O sistema exibe preços competitivos de forma clara e transparente.                                            |  <a href="../../elicitacao/tecnicas/questionario/#anchor_QS">QS08 </a>                              | Não          |
| RNF07 | O sistema aloca os eventos de acordo com a região selecionada para facilitar a busca e a filtragem.           | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS15  </a>                               | Sim          |
| RNF08 | Deve adaptar a tela de seleção de poltronas de acordo com as poltronas já escolhidas.                         |<a href="../../elicitacao/tecnicas/observacao/#anchor_OBS"> OBS17   </a>                              | Sim          |
| RNF09 | Deve apresentar ao usuário o feedback da confirmação de suas ações.                                           |<a href="../../elicitacao/tecnicas/observacao/#anchor_OBS"> OBS18 </a>                                | Sim          |
| RNF10 | Deve apresentar uma página acessível de suporte e de perguntas frequentes com, no máximo, 1 clique.           | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS19</a>                                 | Sim          |
| RNF11 | Deve apresentar uma tela com os dados da conta com ao menos uma etapa de segurança.                           | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS20</a>, IS16                           | Sim          |
| RNF12 | Deve permitir a filtragem dos eventos com apenas 1 clique.                                                    |<a href="../../elicitacao/tecnicas/observacao/#anchor_OBS"> OBS22</a> ,<a href="../../tecnicas/entrevista2/#anchor_2ENT">2ENT01   </a>                            | Sim          |
| RNF13 | O sistema apresenta eventos de forma personalizada, com base na atividade do usuário.                        |  <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF"> IS19   </a>                              | Sim          |
| RNF14 | O usuário deve conseguir acessar informações como data, local e preço do ingresso em, no máximo, 2 cliques durante a busca no Sympla. | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF"> IS20 </a>  | Sim          |
| RNF15 | O Sympla deve permitir que o usuário acesse seus ingressos em, no máximo, 3 cliques.                                                 | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF"> IS21 </a>  | Sim          |
| RNF16 | O Sympla deve oferecer atendimento especial para idosos e pessoas com deficiência durante o processo de compra de ingressos.      | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF"> IS22 </a>  | Não          |
| RNF17 | O aplicativo mostra os eventos de preferência escolhida pelo usuário ao abrir.                    |<a href="../../elicitacao/tecnicas/observacao/#anchor_OBS"> OBS23</a> | Não          |
| RNF18 | O Sympla deve incluir um mecanismo de autenticação seguro, permitindo que os usuários façam login com suas credenciais.           |  <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS23 </a>  | Sim          |
| RNF19 | O Sympla deve contar com uma área para que os usuários reportem erros de funcionamento da plataforma.                             | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF"> IS24</a>   | Sim          |
<div align="center">
<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/Gxaite">Gabriel Scheidt</a> e <a href="https://github.com/MilenaFRocha">Milena Rocha</a>, 2025</p></font>
</div>


## Elos de rastrabilidade
Nesta seção, analisaremos os vínculos associados aos requisitos apresentados nas tabelas 1. Conforme a metodologia adotada, todos os requisitos foram classificados de acordo com o tipo de vínculo correspondente. Vale destacar que todos esses requisitos pertencem exclusivamente à categoria de Desenvolvimento, uma vez que derivam de artefatos produzidos ao longo do processo de elaboração do trabalho, sem conexão direta com aspectos organizacionais ou de gestão do projeto. Com base nesses requisitos, foi elaborada a tabela 3, que consolida e descreve todos os vínculos (elos) identificados.
<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 3:</b> Elos de rastreabilidade</p></font>
</div>

| <a id="anchor_ELOF" style="color:black;">ID</a>      | Requisitos | Tipo de elo       | Descrição do elo                                                                                                                                          |
|---------|------------|-------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| ELOB01  | RF01       | Representação     | O requisito RF01, que especifica que o sistema permite filtrar eventos por Estado e Município, tem como fonte a introspecção (IS01) e observação (OBS01). O tipo de elo é de representação, pois reflete os métodos utilizados para modelar os requisitos. |
| ELOB02  | RF02       | Satisfação        | O requisito RF02, que exige que o sistema exiba detalhes importantes do evento, tem como fontes entrevistas (2ENT02 e 1ENT03), observação (OBS16) e introspecção (IS02). O tipo de elo é de satisfação, pois conecta o requisito às funcionalidades desenvolvidas para atendê-lo. |
| ELOB03  | RF03       | Recurso           | O requisito RF03, que indica que o sistema envia notificações ou lembretes sobre os eventos comprados, está associado às entrevistas (2ENT03 e 1ENT04), questionário (QS03) e introspecção (IS18). O tipo de elo é de recurso, pois representa a dependência dos requisitos em relação aos recursos necessários para sua implementação. |
| ELOB04  | RF04       | Satisfação        | O requisito RF04, que estabelece que o sistema fornece uma ampla variedade de eventos, tem como fontes entrevistas (2ENT04) e questionário (QS04). O tipo de elo é de satisfação, conectando os requisitos às funcionalidades que os atendem. |
| ELOB05  | RF05       | Representação     | O requisito RF05, que determina que o aplicativo permite compartilhar eventos por meio das redes sociais, tem como fonte a observação (OBS03). O elo de representação reflete como o requisito é modelado e apresentado. |
| ELOB06  | RF06       | Recurso           | O requisito RF06, que define que o aplicativo deve permitir adicionar vários ingressos ao carrinho, tem como fonte a entrevista (1ENT01). O tipo de elo é de recurso, pois conecta o requisito aos elementos necessários para sua implementação. |
| ELOB07  | RF07       | Recurso           | O requisito RF07, que determina que o usuário pode remover ingressos do carrinho, tem como fonte a entrevista (1ENT02). O tipo de elo é de recurso, representando a dependência para sua implementação. |
| ELOB08  | RF08       | Representação     | O requisito RF08, que define que o sistema deve permitir cancelamento e transferências de ingressos, está associado à entrevista (2ENT07), observação (OBS12) e introspecção (IS08 e IS10). O tipo de elo é de representação, pois descreve como os requisitos são capturados e expressos. |
| ELOB09  | RF09       | Satisfação        | O requisito RF09, que especifica que o usuário pode visualizar a planta do local para escolha de assentos, está associado à entrevista (2ENT08) e observação (OBS08). O tipo de elo é de satisfação, pois conecta a funcionalidade ao requisito. |
| ELOB10  | RF10       | Satisfação        | O requisito RF10, que permite ao sistema disponibilizar um histórico de compras, está associado à entrevista (2ENT09) e observação (OBS21). O elo de satisfação garante que a funcionalidade atende ao requisito. |
| ELOB11  | RF11       | Recurso           | O requisito RF11, que simplifica filas de compra, está associado à entrevista (2ENT10). O tipo de elo é de recurso, indicando a dependência para sua implementação. |
| ELOB12  | RF12       | Representação     | O requisito RF12, que define que o usuário permanece logado por um período determinado, tem como fonte a entrevista (1ENT05). O tipo de elo é de representação. |
| ELOB13  | RF13       | Satisfação        | O requisito RF13, que fornece uma busca eficiente para localizar produtos, tem como fontes o questionário (QS01), observação (OBS02) e introspecção (IS09). O tipo de elo é de satisfação. |
| ELOB14  | RF14       | Representação     | O requisito RF14, que permite ao usuário escolher a quantidade de ingressos, está associado à observação (OBS04). O elo de representação reflete como o requisito é expresso. |
| ELOB15  | RF15       | Representação     | O requisito RF15, que permite selecionar poltronas especiais para necessidades específicas, está associado à observação (OBS05). O tipo de elo é de representação. |
| ELOB16  | RF16       | Representação     | O requisito RF16, que possibilita selecionar poltronas especiais, está associado à observação (OBS06). O elo de representação reflete como o requisito foi modelado. |
| ELOB17  | RF17       | Recurso           | O requisito RF17, que permite adicionar cupons de desconto ao selecionar ingressos, tem como fonte a observação (OBS07). O tipo de elo é de recurso. |
| ELOB18  | RF18       | Representação     | O requisito RF18, que permite doações para fundações, tem como fonte a observação (OBS09). O elo de representação reflete como o requisito foi capturado. |
| ELOB19  | RF19       | Satisfação        | O requisito RF19, que permite realizar compras de ingressos, tem como fontes a observação (OBS10) e introspecção (IS04). O tipo de elo é de satisfação. |
| ELOB20  | RF20       | Recurso           | O requisito RF20, que permite entrar em contato com o suporte, está associado à observação (OBS11) e introspecção (IS17). O tipo de elo é de recurso. |
| ELOB21  | RF21       | Representação     | O requisito RF21, que permite ao usuário alterar seus dados, tem como fonte a observação (OBS13). O tipo de elo é de representação. |
| ELOB22  | RF22       | Representação     | O requisito RF22, que auxilia na recuperação da conta do usuário, está associado à observação (OBS14). O elo de representação reflete como o requisito é modelado. |
| ELOB23  | RF23       | Satisfação        | O requisito RF23, que oferece diversas opções de pagamento, está associado ao questionário (QS02) e introspecção (IS07). O elo de satisfação conecta a funcionalidade ao requisito. |
| ELOB24  | RF24       | Recurso           | O requisito RF24, que assegura opções de pagamento seguras, tem como fonte o questionário (QS05). O tipo de elo é de recurso. |
| ELOB25  | RF25       | Representação     | O requisito RF25, que assegura uma interface responsiva para diferentes dispositivos, está associado ao questionário (QS06). O elo de representação reflete como o requisito foi expressado. |
| ELOB26  | RF26       | Satisfação        | O requisito RF26, que permite filtrar eventos por categorias, tem como fonte a introspecção (IS03). O elo de satisfação conecta o requisito à funcionalidade desenvolvida. |
| ELOB27  | RF27       | Satisfação        | O requisito RF27, que oferece cadastro e login de usuários, tem como fonte a introspecção (IS05). O tipo de elo é de satisfação. |
| ELOB28  | RF28       | Recurso           | O requisito RF28, que permite exclusão de cadastro de usuários, está associado à introspecção (IS06). O tipo de elo é de recurso. |
| ELOB29  | RF29       | Representação     | O requisito RF29, que oferece a opção de imprimir ingressos, está associado à introspecção (IS19). O tipo de elo é de representação. |
| ELOB30  | RF30       | Recurso           | O requisito RF30, que sugere eventos com base no histórico de buscas, tem como fonte a introspecção (IS11). O tipo de elo é de recurso. |
| ELOB31  | RF31       | Representação     | O requisito RF31, que permite conectar uma carteira digital, está associado à introspecção (IS12). O elo de representação reflete como o requisito foi expresso. |
| ELOB32  | RF32       | Representação     | O requisito RF32, que permite alterar o idioma do aplicativo, tem como fonte a introspecção (IS13). O tipo de elo é de representação. |
| ELOB33  | RF33       | Representação     | O requisito RF33, que permite acessar a aba de configurações, está associado à introspecção (IS14). O elo de representação reflete como o requisito foi modelado. |
| ELOB34  | RF34       | Representação     | O requisito RF34, que apresenta uma aba de acessibilidades, tem como fonte a introspecção (IS15). O elo de representação reflete como o requisito foi capturado. |
| ELOB35  | RF35       | Representação     | O requisito RF35, que permite criar preferências de eventos, está associado à introspecção (IS16). O tipo de elo é de representação. |
| ELOB36  | RF36       | Recurso           | O requisito RF36, que permite cadastrar métodos de pagamento, tem como fonte a entrevista (2ENT11). O tipo de elo é de recurso. |
| ELOB37  | RF37       | Satisfação        | O requisito RF37, que permite criar e divulgar eventos de forma intuitiva, tem como fonte a introspecção (IS19). O elo de satisfação conecta o requisito à funcionalidade. |
| ELOB38  | RF38       | Representação     | O requisito RF38, que fornece relatórios detalhados de vendas, está associado à introspecção (IS20). O tipo de elo é de representação. |
| ELOB39  | RF39       | Representação     | O requisito RF39, que possibilita customização de ingressos, tem como fonte a introspecção (IS21). O tipo de elo é de representação. |
| ELOB40  | RF40       | Representação     | O requisito RF40, que define uma área para produtores de eventos, tem como fonte a introspecção (IS22). O tipo de elo é de representação. |



<div align="center">
<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/Gxaite">Gabriel Scheidt</a> e <a href="https://github.com/MilenaFRocha">Milena Rocha</a>, 2025</p></font>
</div>
### Elos: Análise e Classificação

Neste trecho, exploramos os vínculos associados aos requisitos listados nas tabelas 2. De acordo com a metodologia adotada, cada requisito será classificado com base em seu tipo de vínculo, considerando os elos de rastreabilidade. É importante observar que todos os requisitos identificados pertencem à categoria de **Desenvolvimento**, ou seja, surgem como artefatos gerados durante a criação do projeto. Esses requisitos não têm uma conexão direta com os aspectos **organizacionais** ou **gerenciais** do projeto. 

A análise e classificação dos requisitos resultaram na elaboração da **Tabela 3 e 4**, que detalha os elos relacionados a cada requisito. Os elos são classificados conforme os tipos: **Responsabilidade**, **Satisfação**, **Recurso**, **Representação**, **Alocado** e **Agregação**, de acordo com a contribuição e o papel que desempenham no sistema e na interação com o usuário.




**Legendas:**

> - ID BCx: ID do Backward-From Relacionado Número x

<center>
### Tabela 4: Eixos de Rastreabilidade

| <a id="anchor_ELONF" style="color:black;">ID</a>      | Requisito         | Tipo de Elo             | Descrição do Elo                                                                                                      |
|---------|-------------------|-------------------|-----------------------------------------------------------------------------------------------------------------|
| ELOB01  | RNF01             | Representação     | Este requisito especifica que o envio do ingresso deve ser rápido, representando o objetivo de um sistema ágil. |
| ELOB02  | RNF02             | Satisfação        | Este requisito assegura que o sistema seja seguro, atendendo à necessidade do usuário de proteção de seus dados. |
| ELOB03  | RNF03             | Responsabilidade  | Este requisito atribui ao sistema a responsabilidade de manter estabilidade no login para evitar falhas recorrentes. |
| ELOB04  | RNF04             | Satisfação        | Este requisito garante que o processamento de compras seja rápido, satisfazendo a necessidade de eficiência do usuário. |
| ELOB05  | RNF05             | Representação     | Este requisito representa a necessidade de um sistema com bom desempenho, evitando travamentos e lentidão.        |
| ELOB06  | RNF06             | Agregação         | Este requisito agrega clareza e transparência aos preços apresentados, melhorando a experiência do usuário.       |
| ELOB07  | RNF07             | Alocado           | Este requisito aloca a funcionalidade de organização regional de eventos, facilitando a busca pelo usuário.       |
| ELOB08  | RNF08             | Representação     | Este requisito representa a necessidade de adaptar a seleção de poltronas às escolhas já realizadas.              |
| ELOB09  | RNF09             | Satisfação        | Este requisito busca satisfazer o usuário ao fornecer feedback imediato após confirmações de ações.               |
| ELOB10  | RNF10             | Responsabilidade  | Este requisito define a responsabilidade do sistema em oferecer suporte e perguntas frequentes acessíveis.        |
| ELOB11  | RNF11             | Agregação         | Este requisito agrega segurança adicional aos dados da conta com etapas extras de autenticação.                   |
| ELOB12  | RNF12             | Recurso           | Este requisito especifica que os eventos devem ser filtrados rapidamente, contribuindo para a usabilidade.        |
| ELOB13  | RNF13             | Recurso           | Este requisito conecta a personalização dos eventos ao histórico do usuário, destacando a utilidade dessa função. |
| ELOB14  | RNF14             | Satisfação        | Este requisito satisfaz a necessidade de acesso rápido a informações como data, local e preço de ingressos.       |
| ELOB15  | RNF15             | Satisfação        | Este requisito assegura que o usuário possa acessar seus ingressos com facilidade em até 3 cliques.               |
| ELOB16  | RNF16             | Responsabilidade  | Este requisito define a responsabilidade de atender necessidades especiais de idosos e pessoas com deficiência.    |
| ELOB17  | RNF17             | Representação     | Este requisito representa o objetivo de mostrar eventos de preferência ao abrir o aplicativo.                     |
| ELOB18  | RNF18             | Recurso           | Este requisito conecta a funcionalidade de autenticação segura à proteção dos dados do usuário.                   |
| ELOB19  | RNF19             | Responsabilidade  | Este requisito atribui ao sistema a responsabilidade de permitir que os usuários reportem problemas da plataforma. |

</center>
<div align="center">
<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/Gxaite">Gabriel Scheidt</a> e <a href="https://github.com/MilenaFRocha">Milena Rocha</a>, 2025</p></font>
</div>



## Conclusão
A metodologia proposta permite uma rastreabilidade eficiente dos requisitos do Sympla, assegurando que cada funcionalidade seja devidamente associada a seus objetivos iniciais e promovendo uma visão clara e organizada do progresso do projeto. A adaptação do meta-modelo de Toranzo e o foco na categoria de desenvolvimento garantem que as necessidades específicas deste projeto sejam atendidas de forma eficaz.


## Referência Bibliografia

> Requirements Engineering Fundamentals. Disponível em: <https://aprender3.unb.br/pluginfile.php/2972415/mod_resource/content/2/Rastreabilidade.pdf>. Acesso em: 16 jan. 2025.

> Slides da Aula 26 da Professora Milene Serrano. Disponível em: <https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf>. Acesso em: 16 jan. 2025.



## Histórico de Versões

| Versão |              Descrição                |              Autor             |      Data      |          Revisor         |
|:------:|:-------------------------------------:|:------------------------------:|:--------------:|:------------------------:|
|  1.0   | Inserção do requisitos funcionais e não funcionais  | [Gabriel Scheidt](https://github.com/gxaite) | 16/01/2025    | [Milena Rocha](https://github.com/MilenaFRocha) |
|  1.1   | Criação da introdução e referências   | [Gabriel Scheidt](https://github.com/gxaite) | 16/01/2025    | [Milena Rocha](https://github.com/MilenaFRocha) |
|  1.2   | Criação da metodologia e elos  | [Milena Rocha](https://github.com/MilenaFRocha) | 16/01/2025    |[Gabriel Scheidt](https://github.com/gxaite)  |