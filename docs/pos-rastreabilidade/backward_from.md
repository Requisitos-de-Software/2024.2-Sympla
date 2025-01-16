
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
- **BS**: Brainstorm  
- **O**: Observação  
- **IS**: Introspecção

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Requisitos funcionais elicitados</p></font>
</div>
 Tipo  | Descrição                                                                                                      | <a id="anchor_GERAL" style="color:black;">Rastreabilidade</a> | Implementado |
|-------|--------------------------------------------------------------------------------------------------------------|---------------------------------------|--------------|
| RF01  | O sistema permite filtrar eventos por Estado e Município.                                                     | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS01</a>, <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS01</a>                           | Sim          |
| RF02  | O sistema exibe detalhes importantes do evento, como horário de entrada e local.                              | <a href="../../elicitacao/tecnicas/entrevista2/#anchor_2ENT">2ENT02</a>, <a href="../../elicitacao/tecnicas/entrevista/#anchor_1ENT">1ENT03</a>, <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS16</a>, <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS02</a>           | Sim          |
| RF03  | O sistema envia notificações ou lembretes sobre os eventos comprados.                                         | <a href="../../elicitacao/tecnicas/entrevista2/#anchor_2ENT">2ENT03</a>, <a href="../../elicitacao/tecnicas/entrevista/#anchor_1ENT">1ENT04</a>, <a href="../../elicitacao/tecnicas/questionario/#anchor_QS">QS03</a>, <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS18</a>                | Sim          |
| RF04  | O sistema fornece uma ampla variedade de eventos.                                                             | <a href="../../elicitacao/tecnicas/entrevista2/#anchor_2ENT">2ENT04</a>, <a href="../../elicitacao/tecnicas/questionario/#anchor_QS">QS04</a>                          | Sim          |
| RF05  | O aplicativo permite compartilhar o evento por meio das redes sociais.                                        | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS03</a>                                 | Sim          |
| RF06  | Deve ser possível adicionar vários ingressos ao carrinho antes de finalizar a compra.                         | <a href="../../elicitacao/tecnicas/entrevista/#anchor_1ENT">1ENT01</a>                                | Não          |
| RF07  | Deve ser possível retirar vários ingressos do carrinho adicionados.                                           | <a href="../../elicitacao/tecnicas/entrevista/#anchor_1ENT">1ENT02</a>                                | Não          |
| RF08  | O sistema permite cancelamento e transferências de ingressos diretamente na plataforma.                       | <a href="../../elicitacao/tecnicas/entrevista2/#anchor_2ENT">2ENT07</a>, <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS12</a>, <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS08</a>, <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS10</a>             | Não          |
| RF09  | Deve ser possível visualizar a planta do local para a escolha de assentos (quando aplicável).                 | <a href="../../elicitacao/tecnicas/entrevista2/#anchor_2ENT">2ENT08</a>, <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS08</a>                         | Sim          |
| RF10  | O sistema disponibiliza um histórico completo das compras realizadas pelo usuário.                            | <a href="../../elicitacao/tecnicas/entrevista2/#anchor_2ENT">2ENT09</a>, <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS21</a>                         | Sim          |
| RF11  | O sistema simplifica filas de compra.                                                                         | <a href="../../elicitacao/tecnicas/entrevista2/#anchor_2ENT">2ENT10</a>                                | Não          |
| RF12  | O usuário deve permanecer logado por um tempo determinado para não precisar relogar frequentemente.           | <a href="../../elicitacao/tecnicas/entrevista/#anchor_1ENT">1ENT05</a>                                | Não          |
| RF13  | O aplicativo fornece uma funcionalidade de busca eficiente para facilitar a localização dos produtos.         | <a href="../../elicitacao/tecnicas/questionario/#anchor_QS">QS01</a>, <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS02</a>, <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS09</a>                     | Sim          |
| RF14  | O aplicativo permite a escolha da quantidade de ingressos que o usuário deseja comprar.                       | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS04</a>                                 | Sim          |
| RF15  | O aplicativo permite selecionar poltronas para pessoas idosas, crianças, obesas ou com deficiência, caso existam. | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS05</a>                                | Sim          |
| RF16  | O aplicativo permite selecionar as poltronas especiais.                                                       | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS06</a>                                 | Sim          |
| RF17  | Na seleção de ingresso, o aplicativo permite adicionar um cupom de desconto.                                  | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS07</a>                                 | Sim          |
| RF18  | O aplicativo permite a doação por parte do usuário para fundações.                                            | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS09</a>                                 | Sim          |
| RF19  | O aplicativo permite a realização da compra dos ingressos.                                                    | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS10</a>, <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS04</a>                           | Sim          |
| RF20  | O aplicativo possui uma função para entrar em contato com o suporte.                                          | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS11">OBS11</a>, <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS17</a>                           | Sim          |
| RF21  | O aplicativo permite ao usuário alterar seus dados.                                                           | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS13">OBS13</a>                                 | Sim          |
| RF22  | O aplicativo possui uma função que auxilia na recuperação da conta do usuário.                                | <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS14">OBS14</a>                                 | Sim          |
| RF23  | O aplicativo oferece diversas opções de pagamento para a compra de ingressos.                                | <a href="../../elicitacao/tecnicas/questionario/#anchor_QS">QS02</a>, <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS07</a>                            | Sim          |
| RF24  | As opções de pagamento são seguras, utilizando criptografia para proteger os dados financeiros do usuário.     |  <a href="../../elicitacao/tecnicas/observacao/#anchor_QS">QS05</a>                                | Sim          |
| RF25  | O sistema é acessível por dispositivos móveis, computadores e notebooks, com uma interface responsiva.         | <a href="../../elicitacao/tecnicas/questionario/#anchor_QS"> QS06        </a>                         | Sim          |
| RF26  | O Sympla possibilita filtrar eventos por categorias.        |  <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS03</a>  | Não          |
| RF27  | O Sympla oferece funcionalidades para cadastro e login de usuários. | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS05</a> | Sim          |
| RF28  | O Sympla possibilita a exclusão do cadastro de usuários.    | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS06</a> | Sim          |
| RF29  | O Sympla oferece a opção imprimir ingressos.                | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISNF">IS19</a> | Sim          |
| RF30  | O aplicativo dá sugestões de eventos com base no histórico de buscas do usuário.                  |  <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS11</a>  | Não          |O Sympla oferece a opção imprimir ingressos.
| RF31  | O usuário é capaz de conectar uma carteira digital.                                               | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF"> IS12</a>  | Sim          |
| RF32  | O usuário é capaz de mudar o idioma do app.                                                       |  <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS13 </a> | Não          |
| RF33  | O usuário é capaz de entrar na aba de configurações.                                              |  <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS14 </a> | Não          |
| RF34  | O sistema apresenta uma aba de acessibilidades.                                                   | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF"> IS15 </a> | Não          |
| RF35  | O usuário é capaz de criar preferências de eventos.                                               |  <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS16 </a> | Não          |
| RF36  | Deve ser possível cadastrar diferentes métodos de pagamento.                                               |  <a href="../../elicitacao/tecnicas/entrevista2/#anchor_2ENT">2ENT11</a>  | Não          |
| RF37  | O Sympla permite criar, gerenciar e divulgar eventos de forma intuitiva.                 | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF"> IS19</a> | Não          |
| RF38  | O Sympla fornece relatórios detalhados de vendas e participação em eventos.              | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS20</a> | Não          |
| RF39  | O Sympla possibilita a customização dos ingressos, incluindo preços e lotes.             | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS21</a> | Não          |
| RF40  | O Sympla tem uma área para produtores de eventos.    | <a href="../../elicitacao/elicitacao/tecnicas/introspeccao/#anchor_ISF">IS22</a> | Não          |
<div align="center">
<font size="3"><p style="text-align: center">Fonte: <a href="https://github.com/Gxaite">Gabriel Scheidt</a> e <a href="https://github.com/MilenaFRocha">Milena Rocha</a>, 2025</p></font>
</div>

## Tabelas de requisitos não-funcionais
Este seguimento é destinado para a elaboração da tabela de rastreamento de requisitos não-funcionais, que está sendo demonstrado na tabela 2 a seguir:

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 2</b> - Requisitos não funcionais</p>

| Tipo  | Descrição                                                                                                      | <a id="anchor_GERAL" style="color:black;">Rastreabilidade</a> | Implementado |
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


## Conclusão
A metodologia proposta permite uma rastreabilidade eficiente dos requisitos do Sympla, assegurando que cada funcionalidade seja devidamente associada a seus objetivos iniciais e promovendo uma visão clara e organizada do progresso do projeto. A adaptação do meta-modelo de Toranzo e o foco na categoria de desenvolvimento garantem que as necessidades específicas deste projeto sejam atendidas de forma eficaz.


## Referência Bibliografia

> Requirements Engineering Fundamentals. Disponível em: <https://aprender3.unb.br/pluginfile.php/2972415/mod_resource/content/2/Rastreabilidade.pdf>. Acesso em: 16 jan. 2025.

> Slides da Aula 26 da Professora Milene Serrano. Disponível em: <https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf>. Acesso em: 16 jan. 2025.



## Histórico de Versões

| Versão |              Descrição                |              Autor             |      Data      |          Revisor         |
|:------:|:-------------------------------------:|:------------------------------:|:--------------:|:------------------------:|
|  1.0   | Inserção do requisitos funcionais e não funcionais  | [Gabriel Scheidt](https://github.com/gxaite) | 16/01/2025    | [Milena Rocha](https://github.com/MilenaFRocha) |
|  1.0   | Criação da introdução e referências   | [Gabriel Scheidt](https://github.com/gxaite) | 16/01/2025    | [Milena Rocha](https://github.com/MilenaFRocha) |