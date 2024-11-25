## Introdução

A técnica de priorização _Three Level Scale_<a id="anchor_1" href="#REF1"><sup>1</sup></a> é uma abordagem comum para priorizar requisitos, que agrupa-os em três categorias. Essas categorias geralmente são: **alta**, **média** e **baixa** prioridade. Entretanto, como aplicar essa escala pode ser uma tarefa subjetiva, que gera diferentes interpretações, as partes devem conversar e decidir uma forma de avaliação padrão.

## Metodologia

Para padronizar a abordagem e deixá-la útil, o integrante [Rafael Pereira](https://github.com/rafgpereira) estudou uma análise em duas dimensões: **importância** e **urgência**. Dessa forma, os requisitos avaliados como urgentes e importantes tem alta prioridade, os menos urgentes mas ainda importantes tem média prioridade, e os menos importantes e menos urgentes são de baixa prioridade. Destaca-se que, nesse método, os que são avaliados como urgentes mas não tão importantes são considerados inúteis ou de baixa prioridade, já que muito provavelmente houve algum interesse pessoal de quem está priorizando, e, portanto, não são importantes. Veja na Figura 1 a distribuição das prioridades no quadro de duas dimensões.


<div style="text-align: center;">
    Figura 1: Three Level Scale bidimensional.
</div>

![Imagem](../assets/Importante.png)
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/rafgpereira">Rafael Pereira</a>, 2024</p></font>



Para priorizar os requisitos utilizando essa metodologia, o desenvolvedor [Rafael Pereira](https://github.com/rafgpereira) convidou a usuária do Sympla Denise Cristina, explicou-a como funciona esse processo de priorização, como mostra a Tabela 1, e então mediou uma sessão de priorização com a usuária listando todos os requisitos elicitados, e obetiveram-se os resultados exibidos abaixo. Além disso, um [termo de consentimento]() para uso de imagem e voz foi assinado, permitindo a realização e publicação da priorização.


<div align="center">
<font size="3"><p style="text-align: center">Tabela 1: Reunião de Priorização</p></font>
</div>

<center>

| Mediador                                        | Participante | Data       | Hora   | Local |
|------------------------------------------------|--------------|------------|--------|-------|
| [Rafael Pereira](https://github.com/rafgpereira) | Denise Cristina       | 24/11/2024 | 20:30  | Presencial |

</center>

<font size="3"><p style="text-align: center">Fonte: [Rafael Pereira](https://github.com/rafgpereira), 2024.<p><font>


## Resultados

A Tabela 2 exibida a seguir exibe o resultado da sessão de priorização realizada com a usuária Denise, que classificou os requisitos em Alta, Média e Baixa prioridade conforme a metodologia descrita acima. Para visualizar na íntegra todo o processo, acesse o vídeo disponibilizado no fim da página.

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 2</b> - Requisitos funcionais e não funcionais priorizados</p>
 

| Tipo  | Descrição                                                                                                      | ID                                   | Prioridade   |
|-------|--------------------------------------------------------------------------------------------------------------|---------------------------------------|--------------|
| RF01  | O sistema permite filtrar eventos por Estado e Município.                                                     | OBS01, IS01                           |        Alta      |
| RF02  | O sistema exibe detalhes importantes do evento, como horário de entrada e local.                              | 2ENT02, 1ENT03, OBS16, IS02           |        Alta      |
| RF03  | O sistema envia notificações ou lembretes sobre os eventos comprados.                                         | 2ENT03, 1ENT04, QS03                  |       Baixa       |
| RF04  | O sistema fornece uma ampla variedade de eventos.                                                             | 2ENT04, QS04                          |        Média      |
| RF05  | O aplicativo permite compartilhar o evento por meio das redes sociais.                                        | OBS03                                 |         Baixa     |
| RF06  | Deve ser possível adicionar vários ingressos ao carrinho antes de finalizar a compra.                         | 1ENT01                                |         Média     |
| RF07  | Deve ser possível retirar vários ingressos do carrinho adicionados.                                           | 1ENT02                                |          Média    |
| RF08  | O sistema permite cancelamento e transferências de ingressos diretamente na plataforma.                       | 2ENT07, OBS12, IS08, IS10             |       Alta       |
| RF09  | Deve ser possível visualizar a planta do local para a escolha de assentos (quando aplicável).                 | 2ENT08, OBS08                         |           Alta   |
| RF10  | O sistema disponibiliza um histórico completo das compras realizadas pelo usuário.                            | 2ENT09, OBS21                         |         Baixa     |
| RF11  | O sistema simplifica filas de compra.                                                                         | 2ENT10                                |              Alta |
| RF12  | O usuário deve permanecer logado por um tempo determinado para não precisar relogar frequentemente.           | 1ENT05                                |           Média   |
| RF13  | O aplicativo fornece uma funcionalidade de busca eficiente para facilitar a localização dos produtos.         | QS01, OBS02, IS09                     |            Alta  |
| RF14  | O aplicativo permite a escolha da quantidade de ingressos que o usuário deseja comprar.                       | OBS04                                 |           Alta   |
| RF15  | O aplicativo permite selecionar poltronas para pessoas idosas, crianças, obesas ou com deficiência, caso existam. | OBS05                                |         Alta     |
| RF16  | O aplicativo permite selecionar as poltronas especiais.                                                       | OBS06                                 |           Alta   |
| RF17  | Na seleção de ingresso, o aplicativo permite adicionar um cupom de desconto.                                  | OBS07                                 |       Baixa       |
| RF18  | O aplicativo permite a doação por parte do usuário para fundações.                                            | OBS09                                 |           Baixa   |
| RF19  | O aplicativo permite a realização da compra dos ingressos.                                                    | OBS10, IS04                           |           Alta   |
| RF20  | O aplicativo possui uma função para entrar em contato com o suporte.                                          | OBS11, IS17                           |           Alta   |
| RF21  | O aplicativo permite ao usuário alterar seus dados.                                                           | OBS13                                 |          Alta   |
| RF22  | O aplicativo possui uma função que auxilia na recuperação da conta do usuário.                                | OBS14                                 |          Média    |
| RF23  | O aplicativo oferece diversas opções de pagamento para a compra de ingressos.                                | QS02, IS07                            |          Alta    |
| RF24  | As opções de pagamento são seguras, utilizando criptografia para proteger os dados financeiros do usuário.     | QS05                                  |        Alta      |
| RF25  | O sistema é acessível por dispositivos móveis, computadores e notebooks, com uma interface responsiva.         | QS06                                  |        Alta      |
| RF26  | O Sympla possibilita filtrar eventos por categorias.                                                          | IS03                                  |         Média     |
| RF27  | O Sympla oferece funcionalidades para cadastro e login de usuários.                                           | IS05                                  |        Alta      |
| RF28  | O Sympla possibilita a exclusão do cadastro de usuários.                                                      | IS06                                  |          Média    |
| RF29  | O Sympla oferece a opção imprimir ingressos.                                                                  | IS11                                  |       Alta      |
| RF30  | O aplicativo dá sugestões de eventos com base no histórico de buscas do usuário.                              | IS11                                  |       Baixa       |
| RF31  | O usuário é capaz de conectar uma carteira digital.                                                           | IS12                                  |          Média    |
| RF32  | O usuário é capaz de mudar o idioma do app.                                                                   | IS13                                  |          Média    |
| RF33  | O usuário é capaz de entrar na aba de configurações.                                                          | IS14                                  |           Alta   |
| RF34  | O sistema apresenta uma aba de acessibilidades.                                                               | IS55                                  |          Alta    |
| RF35  | O usuário é capaz de criar preferências de eventos.                                                           | IS16                                  |            Baixa  |
| RF36  | O app faz sugestões e envia notificações com base na preferência escolhida do usuário.                        | IS17                                  |          Baixa    |
| RNF01 | O envio do ingresso deve ser rápido.                                                                          | 2ENT05                                |          Alta    |
| RNF02 | O sistema deve ser seguro para uso comercial.                                                                 | 2ENT06                                |           Alta   |
| RNF03 | O login deve ser estável, evitando falhas frequentes que exijam que o usuário se autentique novamente.         | 1ENT06                                |           Alta   |
| RNF04 | O sistema processa compras de ingressos rapidamente, sem atrasos perceptíveis.                                | 1ENT07                                |            Alta  |
| RNF05 | O aplicativo garante um bom desempenho, evitando travamentos ou lentidão durante o uso.                       | QS07                                  |          Alta    |
| RNF06 | O sistema exibe preços competitivos de forma clara e transparente.                                            | QS08                                  |          Alta    |
| RNF07 | O sistema aloca os eventos de acordo com a região selecionada para facilitar a busca e a filtragem.           | OBS15                                 |           Média   |
| RNF08 | Deve adaptar a tela de seleção de poltronas de acordo com as poltronas já escolhidas.                         | OBS17                                 |           Alta   |
| RNF09 | Deve apresentar ao usuário o feedback da confirmação de suas ações.                                           | OBS18                                 |           Alta   |
| RNF10 | Deve apresentar uma página acessível de suporte e de perguntas frequentes com, no máximo, 1 clique.           | OBS19                                 |          Média    |
| RNF11 | Deve apresentar uma tela com os dados da conta com ao menos uma etapa de segurança.                           | OBS20, IS16                           |          Alta    |
| RNF12 | Deve permitir a filtragem dos eventos com apenas 1 clique.                                                    | OBS22, 2ENT01                         |          Baixa    |
| RNF13 | O sistema apresenta eventos de forma personalizada, com base na atividade do usuário.                         | IS12                                  |     Baixa         |
| RNF14 | O usuário deve conseguir acessar informações como data, local e preço do ingresso em, no máximo, 2 cliques durante a busca no Sympla. | IS13  |        Baixa      |
| RNF15 | O Sympla deve permitir que o usuário acesse seus ingressos em, no máximo, 3 cliques.                          | IS14                                  |          Média    |
| RNF16 | O Sympla deve oferecer atendimento especial para idosos e pessoas com deficiência durante o processo de compra de ingressos. | IS15 |          Alta    |
| RNF17 | O aplicativo mostra os eventos de preferência escolhida pelo usuário ao abrir.                                | OBS23                                 |     Baixa         |

<font size="3"><p style="text-align: center">Fonte: [Rafael Pereira](https://github.com/rafgpereira), 2024.<p><font>

## Gravação

Abaixo, no Vídeo 1, está disponível a gravação da priorização com a Denise.


<div style="text-align: center">

<font size="3"><p style="text-align: center">Vídeo 1: Grupo 08 - Sympla - Priorização de Requisitos - Three Level Scale</p></font>

<iframe width="560" height="315" src="https://www.youtube.com/embed/Q8SttPMThjI?si=eSMyQe6bzWGkioww" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<font size="3"><p style="text-align: center"><b>Fonte:</b> Os Autores. Grupo 08 - Sympla - Priorização de Requisitos - Three Level Scale. Disponível em: <a href="https://youtu.be/Q8SttPMThjI">https://youtu.be/Q8SttPMThjI</a>. Acesso em: 24 nov. 2024.</p></font>
</div>


## **Referências bibliográficas**

><a id="REF1">1.</a> FIRST things first: Setting requirement priorities. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 313-329. ISBN 0735679665.

## Histórico de Versões


| Versão |          Descrição              |     Autor      |      Data      |   Revisor     | 
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|
|  1.0   | Criação do documento |  [Rafael Pereira](https://github.com/rafgpereira) | 23/11/2024 |[Victor Hugo](https://github.com/VHbernardes)  |
|  1.1   | Adição dos resultados e gravação |  [Rafael Pereira](https://github.com/rafgpereira) | 24/11/2024 |[Milena Rocha](https://github.com/MilenaFRocha)  |
