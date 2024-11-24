## Introdução 

Após a coleta dos requisitos por meio de técnicas como Questionário, Observação, Introspeccção e Entrevistas, é fundamental aplicar critérios para classificá-los, permitindo determinar a relevância de cada um deles. Assim, neste documento, utilizaremos a técnica "In or Out" para realizar essa classificação.

## Metodologia

Esse método organiza os requisitos em duas categorias: "In" e "Out" do escopo do projeto. A proposta é distinguir as funcionalidades indispensáveis das secundárias. Os requisitos classificados como "In" representam elementos essenciais, sem os quais o projeto não pode ser finalizado. Já os requisitos "Out" são considerados desejáveis, mas não cruciais para o sucesso do projeto.

 Para priorizar os requisitos, o integrante do grupo Renan Araújo reuniu-se junto com a usuária do Sympla Fernanda, explicou como funciona o processo de prorização e pediu a realização da técnica. 

<div align="center">
<font size="3"><p style="text-align: center">Tabela 1: Reunião</p></font>
</div>

<center>

| Mediador                                        | Participante | Data       | Hora   | Local |
|------------------------------------------------|--------------|------------|--------|-------|
| [Renan Araújo](https://github.com/renantfm4) | Fernanda        | 24/11/2024 | 16:00  | Presencial |

</center>

<font size="3"><p style="text-align: center">Fonte: [Renan Araújo](https://github.com/renantfm4)<p><font>


## Requisitos

A Tabela 2 a seguir contém priorização dos requisitos elicitados que foi realizada. 

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 2</b> - Requisitos funcionais e não funcionais</p>
 

| Tipo  | Descrição                                                                                                      | ID                                   | Prioridade |
|-------|--------------------------------------------------------------------------------------------------------------|---------------------------------------|------------|
| RF01  | O sistema permite filtrar eventos por Estado e Município.                                                     | OBS01, IS01                           |            |
| RF02  | O sistema exibe detalhes importantes do evento, como horário de entrada e local.                              | 2ENT02, 1ENT03, OBS16, IS02           |            |
| RF03  | O sistema envia notificações ou lembretes sobre os eventos comprados.                                         | 2ENT03, 1ENT04, QS03                  |            |
| RF04  | O sistema fornece uma ampla variedade de eventos.                                                             | 2ENT04, QS04                          |            |
| RF05  | O aplicativo permite compartilhar o evento por meio das redes sociais.                                        | OBS03                                 |            |
| RF06  | Deve ser possível adicionar vários ingressos ao carrinho antes de finalizar a compra.                         | 1ENT01                                |            |
| RF07  | Deve ser possível retirar vários ingressos do carrinho adicionados.                                           | 1ENT02                                |            |
| RF08  | O sistema permite cancelamento e transferências de ingressos diretamente na plataforma.                       | 2ENT07, OBS12, IS08, IS10             |            |
| RF09  | Deve ser possível visualizar a planta do local para a escolha de assentos (quando aplicável).                 | 2ENT08, OBS08                         |            |
| RF10  | O sistema disponibiliza um histórico completo das compras realizadas pelo usuário.                            | 2ENT09, OBS21                         |            |
| RF11  | O sistema simplifica filas de compra.                                                                         | 2ENT10                                |            |
| RF12  | O usuário deve permanecer logado por um tempo determinado para não precisar relogar frequentemente.           | 1ENT05                                |            |
| RF13  | O aplicativo fornece uma funcionalidade de busca eficiente para facilitar a localização dos produtos.         | QS01, OBS02, IS09                     |            |
| RF14  | O aplicativo permite a escolha da quantidade de ingressos que o usuário deseja comprar.                       | OBS04                                 |            |
| RF15  | O aplicativo permite selecionar poltronas para pessoas idosas, crianças, obesas ou com deficiência, caso existam. | OBS05                                |            |
| RF16  | O aplicativo permite selecionar as poltronas especiais.                                                       | OBS06                                 |            |
| RF17  | Na seleção de ingresso, o aplicativo permite adicionar um cupom de desconto.                                  | OBS07                                 |            |
| RF18  | O aplicativo permite a doação por parte do usuário para fundações.                                            | OBS09                                 |            |
| RF19  | O aplicativo permite a realização da compra dos ingressos.                                                    | OBS10, IS04                           |            |
| RF20  | O aplicativo possui uma função para entrar em contato com o suporte.                                          | OBS11, IS17                           |            |
| RF21  | O aplicativo permite ao usuário alterar seus dados.                                                           | OBS13                                 |            |
| RF22  | O aplicativo possui uma função que auxilia na recuperação da conta do usuário.                                | OBS14                                 |            |
| RF23  | O aplicativo oferece diversas opções de pagamento para a compra de ingressos.                                | QS02, IS07                            |            |
| RF24  | As opções de pagamento são seguras, utilizando criptografia para proteger os dados financeiros do usuário.     | QS05                                 |            |
| RF25  | O sistema é acessível por dispositivos móveis, computadores e notebooks, com uma interface responsiva.         | QS06                                 |            |
| RF26  | O Sympla possibilita filtrar eventos por categorias.        | IS03 |            |
| RF27  | O Sympla oferece funcionalidades para cadastro e login de usuários. | IS05 |            |
| RF28  | O Sympla possibilita a exclusão do cadastro de usuários.    | IS06 |            |
| RF29  | O Sympla oferece a opção imprimir ingressos.                | IS11 |            |
| RNF01 | O envio do ingresso deve ser rápido.                                                                          | 2ENT05                                |            |
| RNF02 | O sistema deve ser seguro para uso comercial.                                                                 | 2ENT06                                |            |
| RNF03 | O login deve ser estável, evitando falhas frequentes que exijam que o usuário se autentique novamente.        | 1ENT06                                |            |
| RNF04 | O sistema processa compras de ingressos rapidamente, sem atrasos perceptíveis.                                | 1ENT07                                |            |
| RNF05 | O aplicativo garante um bom desempenho, evitando travamentos ou lentidão durante o uso.                       | QS07                                 |            |
| RNF06 | O sistema exibe preços competitivos de forma clara e transparente.                                            | QS08                                 |            |
| RNF07 | O sistema aloca os eventos de acordo com a região selecionada para facilitar a busca e a filtragem.           | OBS15                                 |            |
| RNF08 | Deve adaptar a tela de seleção de poltronas de acordo com as poltronas já escolhidas.                         | OBS17                                 |            |
| RNF09 | Deve apresentar ao usuário o feedback da confirmação de suas ações.                                           | OBS18                                 |            |
| RNF10 | Deve apresentar uma página acessível de suporte e de perguntas frequentes com, no máximo, 1 clique.           | OBS19                                 |            |
| RNF11 | Deve apresentar uma tela com os dados da conta com ao menos uma etapa de segurança.                           | OBS20, IS16                           |            |
| RNF12 | Deve permitir a filtragem dos eventos com apenas 1 clique.                                                    | OBS22 ,2ENT01                         |            |
| RNF13 | O sistema apresenta eventos de forma personalizada, com base na atividade do usuário.                        | IS12                                 |            |
| RNF14 | O usuário deve conseguir acessar informações como data, local e preço do ingresso em, no máximo, 2 cliques durante a busca no Sympla. | IS13  |            |
| RNF15 | O Sympla deve permitir que o usuário acesse seus ingressos em, no máximo, 3 cliques.                          | IS14  |            |
| RNF16 | O Sympla deve oferecer atendimento especial para idosos e pessoas com deficiência durante o processo de compra de ingressos.      | IS15  |            |


<font size="3"><p style="text-align: center">Fonte: [Renan Araújo](https://github.com/renantfm4)<p><font>


## **Referências bibliográficas**

><a id="REF1">1.</a> FIRST things first: Setting requirement priorities. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 313-329. ISBN 0735679665.

## Histórico de Versões


| Versão |          Descrição              |     Autor      |      Data      |   Revisor     | 
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|
|  1.0   | Criação do documento |  [Renan Araújo](https://github.com/renantfm4) | 24/11/2024 |  |
