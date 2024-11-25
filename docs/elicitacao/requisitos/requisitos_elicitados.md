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

## Requisitos

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 1</b> - Requisitos funcionais e não funcionais</p>
 

| Tipo  | Descrição                                                                                                      | ID                                   | Implementado |
|-------|--------------------------------------------------------------------------------------------------------------|---------------------------------------|--------------|
| RF01  | O sistema permite filtrar eventos por Estado e Município.                                                     | OBS01, IS01                           | Sim          |
| RF02  | O sistema exibe detalhes importantes do evento, como horário de entrada e local.                              | 2ENT02, 1ENT03, OBS16, IS02           | Sim          |
| RF03  | O sistema envia notificações ou lembretes sobre os eventos comprados.                                         | 2ENT03, 1ENT04, QS03  ,IS18                | Sim          |
| RF04  | O sistema fornece uma ampla variedade de eventos.                                                             | 2ENT04, QS04                          | Sim          |
| RF05  | O aplicativo permite compartilhar o evento por meio das redes sociais.                                        | OBS03                                 | Sim          |
| RF06  | Deve ser possível adicionar vários ingressos ao carrinho antes de finalizar a compra.                         | 1ENT01                                | Não          |
| RF07  | Deve ser possível retirar vários ingressos do carrinho adicionados.                                           | 1ENT02                                | Não          |
| RF08  | O sistema permite cancelamento e transferências de ingressos diretamente na plataforma.                       | 2ENT07, OBS12, IS08, IS10             | Não          |
| RF09  | Deve ser possível visualizar a planta do local para a escolha de assentos (quando aplicável).                 | 2ENT08, OBS08                         | Sim          |
| RF10  | O sistema disponibiliza um histórico completo das compras realizadas pelo usuário.                            | 2ENT09, OBS21                         | Sim          |
| RF11  | O sistema simplifica filas de compra.                                                                         | 2ENT10                                | Não          |
| RF12  | O usuário deve permanecer logado por um tempo determinado para não precisar relogar frequentemente.           | 1ENT05                                | Não          |
| RF13  | O aplicativo fornece uma funcionalidade de busca eficiente para facilitar a localização dos produtos.         | QS01, OBS02, IS09                     | Sim          |
| RF14  | O aplicativo permite a escolha da quantidade de ingressos que o usuário deseja comprar.                       | OBS04                                 | Sim          |
| RF15  | O aplicativo permite selecionar poltronas para pessoas idosas, crianças, obesas ou com deficiência, caso existam. | OBS05                                | Sim          |
| RF16  | O aplicativo permite selecionar as poltronas especiais.                                                       | OBS06                                 | Sim          |
| RF17  | Na seleção de ingresso, o aplicativo permite adicionar um cupom de desconto.                                  | OBS07                                 | Sim          |
| RF18  | O aplicativo permite a doação por parte do usuário para fundações.                                            | OBS09                                 | Sim          |
| RF19  | O aplicativo permite a realização da compra dos ingressos.                                                    | OBS10, IS04                           | Sim          |
| RF20  | O aplicativo possui uma função para entrar em contato com o suporte.                                          | OBS11, IS17                           | Sim          |
| RF21  | O aplicativo permite ao usuário alterar seus dados.                                                           | OBS13                                 | Sim          |
| RF22  | O aplicativo possui uma função que auxilia na recuperação da conta do usuário.                                | OBS14                                 | Sim          |
| RF23  | O aplicativo oferece diversas opções de pagamento para a compra de ingressos.                                | QS02, IS07                            | Sim          |
| RF24  | As opções de pagamento são seguras, utilizando criptografia para proteger os dados financeiros do usuário.     | QS05                                 | Sim          |
| RF25  | O sistema é acessível por dispositivos móveis, computadores e notebooks, com uma interface responsiva.         | QS06                                 | Sim          |
| RF26  | O Sympla possibilita filtrar eventos por categorias.        | IS03 | Não          |
| RF27  | O Sympla oferece funcionalidades para cadastro e login de usuários. | IS05 | Sim          |
| RF28  | O Sympla possibilita a exclusão do cadastro de usuários.    | IS06 | Sim          |
| RF29  | O Sympla oferece a opção imprimir ingressos.                | IS19 | Sim          |
| RF30  | O aplicativo dá sugestões de eventos com base no histórico de buscas do usuário.                  | IS11 | Não          |O Sympla oferece a opção imprimir ingressos.
| RF31  | O usuário é capaz de conectar uma carteira digital.                                               | IS12 | Não          |
| RF32  | O usuário é capaz de mudar o idioma do app.                                                       | IS13 | Não          |
| RF33  | O usuário é capaz de entrar na aba de configurações.                                              | IS14 | Não          |
| RF34  | O sistema apresenta uma aba de acessibilidades.                                                   | IS15 | Não          |
| RF35  | O usuário é capaz de criar preferências de eventos.                                               | IS16 | Não          |
| RNF01 | O envio do ingresso deve ser rápido.                                                                          | 2ENT05                                | Não          |
| RNF02 | O sistema deve ser seguro para uso comercial.                                                                 | 2ENT06                                | Sim          |
| RNF03 | O login deve ser estável, evitando falhas frequentes que exijam que o usuário se autentique novamente.        | 1ENT06                                | Não          |
| RNF04 | O sistema processa compras de ingressos rapidamente, sem atrasos perceptíveis.                                | 1ENT07                                | Sim          |
| RNF05 | O aplicativo garante um bom desempenho, evitando travamentos ou lentidão durante o uso.                       | QS07                                 | Sim          |
| RNF06 | O sistema exibe preços competitivos de forma clara e transparente.                                            | QS08                                 | Não          |
| RNF07 | O sistema aloca os eventos de acordo com a região selecionada para facilitar a busca e a filtragem.           | OBS15                                 | Sim          |
| RNF08 | Deve adaptar a tela de seleção de poltronas de acordo com as poltronas já escolhidas.                         | OBS17                                 | Sim          |
| RNF09 | Deve apresentar ao usuário o feedback da confirmação de suas ações.                                           | OBS18                                 | Sim          |
| RNF10 | Deve apresentar uma página acessível de suporte e de perguntas frequentes com, no máximo, 1 clique.           | OBS19                                 | Sim          |
| RNF11 | Deve apresentar uma tela com os dados da conta com ao menos uma etapa de segurança.                           | OBS20, IS16                           | Sim          |
| RNF12 | Deve permitir a filtragem dos eventos com apenas 1 clique.                                                    | OBS22 ,2ENT01                               | Sim          |
| RNF13 | O sistema apresenta eventos de forma personalizada, com base na atividade do usuário.                        | IS19                                 | Sim          |
| RNF14 | O usuário deve conseguir acessar informações como data, local e preço do ingresso em, no máximo, 2 cliques durante a busca no Sympla. | IS20  | Sim          |
| RNF15 | O Sympla deve permitir que o usuário acesse seus ingressos em, no máximo, 3 cliques.                                                 | IS21  | Sim          |
| RNF16 | O Sympla deve oferecer atendimento especial para idosos e pessoas com deficiência durante o processo de compra de ingressos.      | IS22  | Não          |
| RNF17 | O aplicativo mostra os eventos de preferência escolhida pelo usuário ao abrir.                    | OBS23 | Não          |
| RNF18 | O Sympla deve incluir um mecanismo de autenticação seguro, permitindo que os usuários façam login com suas credenciais.           | IS23  | Sim          |
| RNF19 | O Sympla deve contar com uma área para que os usuários reportem erros de funcionamento da plataforma.                             | IS24  | Sim          |





<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/MilenaFRocha">Milena Rocha</a></p></font>

## Histórico de Versões

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     | 
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|
|  1.0   | Criação desse documento | [Milena Rocha](https://github.com/MilenaFRocha) | 18/11/2024 | [Rafael Pereira](https://github.com/rafgpereira)  |
|  1.1   | Atualização da tabela| [Milena Rocha](https://github.com/MilenaFRocha) | 18/11/2024 | [Rafael Pereira](https://github.com/rafgpereira)  |
|  1.2   | Atualização da tabela| [Gabriel Scheidt](https://github.com/gxaite) | 24/11/2024 | [Milena Rocha](https://github.com/MilenaFRocha)  |
|  1.3   | Ajustes de escrita|  [Milena Rocha](https://github.com/MilenaFRocha) | 24/11/2024 | [Gabriel Scheidt](https://github.com/gxaite) |

