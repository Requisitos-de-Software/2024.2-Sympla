
# Backward-From

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



#### Conclusão
A metodologia proposta permite uma rastreabilidade eficiente dos requisitos do Sympla, assegurando que cada funcionalidade seja devidamente associada a seus objetivos iniciais e promovendo uma visão clara e organizada do progresso do projeto. A adaptação do meta-modelo de Toranzo e o foco na categoria de desenvolvimento garantem que as necessidades específicas deste projeto sejam atendidas de forma eficaz.


## Introdução

### Rastreabilidade Backward-From:

Este documento explora o uso do método de rastreabilidade backward-from, uma abordagem essencial no desenvolvimento de sistemas. A rastreabilidade de requisitos desempenha um papel central ao viabilizar a identificação e a conexão entre requisitos durante a etapa de desenvolvimento, além de permitir seu acompanhamento ao longo de todo o ciclo de vida do sistema. Essa prática proporciona uma compreensão mais detalhada das origens e implicações de cada requisito, contribuindo para a garantia da qualidade, uma gestão de mudanças mais eficaz e o alinhamento contínuo com as necessidades do cliente.

### Estabelecendo Conexões com o Método Backward-From

Ao implementar o método de rastreabilidade backward-from, busca-se criar vínculos claros entre os requisitos e suas respectivas origens. Essa abordagem permite rastrear um requisito até sua fonte, seja ela uma solicitação de cliente, um processo de negócio ou outra referência relevante. Materiais como os [slides da aula 26](https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf), ministrada pela professora Milene Serrano, e o livro [Requirements Engineering Fundamentals](https://aprender3.unb.br/pluginfile.php/2972415/mod_resource/content/2/Rastreabilidade.pdf), de Klaus Pohl e Chris Rupp, fornecem insights valiosos que enriquecem essa abordagem, garantindo uma visão mais organizada e completa da rastreabilidade de requisitos.

### Benefícios da Rastreabilidade para Validação e Verificação

A rastreabilidade bem implementada não apenas facilita o entendimento dos requisitos, mas também simplifica os processos de validação e verificação de sistemas. Essa prática permite a identificação precoce de possíveis problemas, resultando em economias significativas de tempo e recursos. Além disso, contribui para a satisfação do cliente ao garantir que o sistema atenda de forma precisa e confiável às suas necessidades ao longo de todo o ciclo de vida.

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


## Referência Bibliografia

> Requirements Engineering Fundamentals. Disponível em: <https://aprender3.unb.br/pluginfile.php/2972415/mod_resource/content/2/Rastreabilidade.pdf>. Acesso em: 16 jan. 2025.

> Slides da Aula 26 da Professora Milene Serrano. Disponível em: <https://aprender3.unb.br/pluginfile.php/2972560/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf>. Acesso em: 16 jan. 2025.



## Histórico de Versões

| Versão |              Descrição                |              Autor             |      Data      |          Revisor         |
|:------:|:-------------------------------------:|:------------------------------:|:--------------:|:------------------------:|
|  1.0   | Criação da introdução e referências   | [Gabriel Scheidt](https://github.com/gxaite) | 16/01/2025    | [Milena Rocha](https://github.com/MilenaFRocha) |
|  1.1   | Criação da metodologia   | [Milena Rocha](https://github.com/MilenaFRocha) | 16/01/2025    | [Gabriel Scheidt](https://github.com/gxaite) |



