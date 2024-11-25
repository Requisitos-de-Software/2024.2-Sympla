## Introdução 

Após a coleta dos requisitos por meio de técnicas como Questionário, Observação, Introspeccção e Entrevistas, é fundamental aplicar critérios para classificá-los, permitindo determinar a relevância de cada um deles. Assim, neste documento, utilizaremos a técnica "In or Out" para realizar essa classificação.

## Metodologia

Esse método organiza os requisitos em duas categorias: "In" e "Out" do escopo do projeto. A proposta é distinguir as funcionalidades indispensáveis das secundárias. Os requisitos classificados como "In" representam elementos essenciais, sem os quais o projeto não pode ser finalizado. Já os requisitos "Out" são considerados desejáveis, mas não cruciais para o sucesso do projeto.

 Para priorizar os requisitos, o integrante do grupo Renan Araújo reuniu-se junto com a usuária do Sympla Fernanda, explicou como funciona o processo de prorização e pediu a realização da técnica. 

Além disso, temos um [termo de consentimento](../assets/Termo%20de%20Consetimento%20-%20Fernanda.pdf), devidamente assinado pelos usuários entrevistados, garantindo a ética e o respeito à privacidade dos participantes durante a coleta de dados.

<div align="center">
<font size="3"><p style="text-align: center">Tabela 1: Reunião</p></font>
</div>

<center>

| Mediador                                        | Participante | Data       | Hora   | Local |
|------------------------------------------------|--------------|------------|--------|-------|
| [Renan Araújo](https://github.com/renantfm4) | Fernanda Souza       | 24/11/2024 | 19:00  | Presencial |

</center>

<font size="3"><p style="text-align: center">Fonte: [Renan Araújo](https://github.com/renantfm4)<p><font>


## Requisitos

A Tabela 2 a seguir contém priorização dos requisitos elicitados que foi realizada. 

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 2</b> - Requisitos funcionais e não funcionais</p>
 

| Tipo  | Descrição                                                                                                      | ID                                   | Prioridade   |
|-------|--------------------------------------------------------------------------------------------------------------|---------------------------------------|--------------|
| RF01  | O sistema permite filtrar eventos por Estado e Município.                                                     | OBS01, IS01                           |         In     |
| RF02  | O sistema exibe detalhes importantes do evento, como horário de entrada e local.                              | 2ENT02, 1ENT03, OBS16, IS02           |     In         |
| RF03  | O sistema envia notificações ou lembretes sobre os eventos comprados.                                         | 2ENT03, 1ENT04, QS03                  |       In       |
| RF04  | O sistema fornece uma ampla variedade de eventos.                                                             | 2ENT04, QS04                          |       In       |
| RF05  | O aplicativo permite compartilhar o evento por meio das redes sociais.                                        | OBS03                                 |       In       |
| RF06  | Deve ser possível adicionar vários ingressos ao carrinho antes de finalizar a compra.                         | 1ENT01                                |        In      |
| RF07  | Deve ser possível retirar vários ingressos do carrinho adicionados.                                           | 1ENT02                                |      In        |
| RF08  | O sistema permite cancelamento e transferências de ingressos diretamente na plataforma.                       | 2ENT07, OBS12, IS08, IS10             |     In         |
| RF09  | Deve ser possível visualizar a planta do local para a escolha de assentos (quando aplicável).                 | 2ENT08, OBS08                         |      In        |
| RF10  | O sistema disponibiliza um histórico completo das compras realizadas pelo usuário.                            | 2ENT09, OBS21                         |       In       |
| RF11  | O sistema simplifica filas de compra.                                                                         | 2ENT10                                |       In        |
| RF12  | O usuário deve permanecer logado por um tempo determinado para não precisar relogar frequentemente.           | 1ENT05                                |      In        |
| RF13  | O aplicativo fornece uma funcionalidade de busca eficiente para facilitar a localização dos produtos.         | QS01, OBS02, IS09                     |      In        |
| RF14  | O aplicativo permite a escolha da quantidade de ingressos que o usuário deseja comprar.                       | OBS04                                 |       In       |
| RF15  | O aplicativo permite selecionar poltronas para pessoas idosas, crianças, obesas ou com deficiência, caso existam. | OBS05                                |      In        |
| RF16  | O aplicativo permite selecionar as poltronas especiais.                                                       | OBS06                                 |       In       |
| RF17  | Na seleção de ingresso, o aplicativo permite adicionar um cupom de desconto.                                  | OBS07                                 |       Out       |
| RF18  | O aplicativo permite a doação por parte do usuário para fundações.                                            | OBS09                                 |       In       |
| RF19  | O aplicativo permite a realização da compra dos ingressos.                                                    | OBS10, IS04                           |       In       |
| RF20  | O aplicativo possui uma função para entrar em contato com o suporte.                                          | OBS11, IS17                           |      In        |
| RF21  | O aplicativo permite ao usuário alterar seus dados.                                                           | OBS13                                 |     In         |
| RF22  | O aplicativo possui uma função que auxilia na recuperação da conta do usuário.                                | OBS14                                 |       In       |
| RF23  | O aplicativo oferece diversas opções de pagamento para a compra de ingressos.                                | QS02, IS07                            |        In      |
| RF24  | As opções de pagamento são seguras, utilizando criptografia para proteger os dados financeiros do usuário.     | QS05                                  |      In        |
| RF25  | O sistema é acessível por dispositivos móveis, computadores e notebooks, com uma interface responsiva.         | QS06                                  |        In      |
| RF26  | O Sympla possibilita filtrar eventos por categorias.                                                          | IS03                                  |      In        |
| RF27  | O Sympla oferece funcionalidades para cadastro e login de usuários.                                           | IS05                                  |       In       |
| RF28  | O Sympla possibilita a exclusão do cadastro de usuários.                                                      | IS06                                  |      In        |
| RF29  | O Sympla oferece a opção imprimir ingressos.                                                                  | IS11                                  |       Out       |
| RF30  | O aplicativo dá sugestões de eventos com base no histórico de buscas do usuário.                              | IS11                                  |       Out       |
| RF31  | O usuário é capaz de conectar uma carteira digital.                                                           | IS12                                  |      In        |
| RF32  | O usuário é capaz de mudar o idioma do app.                                                                   | IS13                                  |      In        |
| RF33  | O usuário é capaz de entrar na aba de configurações.                                                          | IS14                                  |      In        |
| RF34  | O sistema apresenta uma aba de acessibilidades.                                                               | IS55                                  |        In      |
| RF35  | O usuário é capaz de criar preferências de eventos.                                                           | IS16                                  |       In       |
| RF36  | O app faz sugestões e envia notificações com base na preferência escolhida do usuário.                        | IS17                                  |      In        |
| RNF01 | O envio do ingresso deve ser rápido.                                                                          | 2ENT05                                |       In       |
| RNF02 | O sistema deve ser seguro para uso comercial.                                                                 | 2ENT06                                |      In        |
| RNF03 | O login deve ser estável, evitando falhas frequentes que exijam que o usuário se autentique novamente.         | 1ENT06                                |       In       |
| RNF04 | O sistema processa compras de ingressos rapidamente, sem atrasos perceptíveis.                                | 1ENT07                                |        In      |
| RNF05 | O aplicativo garante um bom desempenho, evitando travamentos ou lentidão durante o uso.                       | QS07                                  |       In       |
| RNF06 | O sistema exibe preços competitivos de forma clara e transparente.                                            | QS08                                  |       In       |
| RNF07 | O sistema aloca os eventos de acordo com a região selecionada para facilitar a busca e a filtragem.           | OBS15                                 |        In      |
| RNF08 | Deve adaptar a tela de seleção de poltronas de acordo com as poltronas já escolhidas.                         | OBS17                                 |         In     |
| RNF09 | Deve apresentar ao usuário o feedback da confirmação de suas ações.                                           | OBS18                                 |      In        |
| RNF10 | Deve apresentar uma página acessível de suporte e de perguntas frequentes com, no máximo, 1 clique.           | OBS19                                 |       In       |
| RNF11 | Deve apresentar uma tela com os dados da conta com ao menos uma etapa de segurança.                           | OBS20, IS16                           |       In       |
| RNF12 | Deve permitir a filtragem dos eventos com apenas 1 clique.                                                    | OBS22, 2ENT01                         |        In      |
| RNF13 | O sistema apresenta eventos de forma personalizada, com base na atividade do usuário.                         | IS12                                  |       In       |
| RNF14 | O usuário deve conseguir acessar informações como data, local e preço do ingresso em, no máximo, 2 cliques durante a busca no Sympla. | IS13  |        In      |
| RNF15 | O Sympla deve permitir que o usuário acesse seus ingressos em, no máximo, 3 cliques.                          | IS14                                  |       In       |
| RNF16 | O Sympla deve oferecer atendimento especial para idosos e pessoas com deficiência durante o processo de compra de ingressos. | IS15 |       In       |
| RNF17 | O aplicativo mostra os eventos de preferência escolhida pelo usuário ao abrir.                                | OBS23                                 |       In       |

<font size="3"><p style="text-align: center">Fonte: [Renan Araújo](https://github.com/renantfm4)<p><font>

## Gravação

Abaixo, no Vídeo 1, apresentamos a priorização in or out


<div style="text-align: center">

<font size="3"><p style="text-align: center">Vídeo 1: Priorização</p></font>

<iframe width="560" height="315" src="https://www.youtube.com/embed/R6-2r4NAC-U?feature=youtu.be" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<font size="3"><p style="text-align: center"><b>Fonte:</b> Os Autores. Grupo 08 - Sympla - Priorização In Or Out. Disponível em: <a href="https://www.youtube.com/watch?v=R6-2r4NAC-U&feature=youtu.be">https://www.youtube.com/watch?v=R6-2r4NAC-U&feature=youtu.be</a>. Acesso em: 24 nov. 2024.</p></font>
</div>


## **Referências bibliográficas**

><a id="REF1">1.</a> FIRST things first: Setting requirement priorities. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 313-329. ISBN 0735679665.

><a id="REF2">2.</a> IN OR OUT. In: Requisitos de Software - VLC 2023.1. Disponível em: https://requisitos-de-software.github.io/2023.1-VLC/#/elicitacao/in_or_out. Acesso em: 24 nov. 2024.


## Histórico de Versões


| Versão |          Descrição              |     Autor      |      Data      |   Revisor     | 
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|
|  1.0   | Criação do documento |  [Renan Araújo](https://github.com/renantfm4) | 24/11/2024 |  |
|  1.1   | Adição da tabela de requisitos e vídeo |  [Renan Araújo](https://github.com/renantfm4) | 24/11/2024 |  |
