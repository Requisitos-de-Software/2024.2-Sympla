## Introdução

O Léxico tem como objetivo descrever os símbolos de uma linguagem.  Na modelagem de requisitos, os léxicos são responsáveis por explicar, seguindo uma estrutura pré definida, termos da aplicação(símbolos) que podem ser estranhos para o público. Cada símbolo possui noção, impacto e sinônimos. Noção é uma breve descrição do que significa aquele símbolo, impacto é a conotação de um símbolo, o que ele faz/causa quando utilizado, e sinônimos são símbolos semelhantes.

## Metodologia

Para a elaboração dos léxicos, utilizamos a notação do Léxico Ampliado da Linguagem (LAL)<a id="anchor_1" href="#REF1"><sup>1</sup></a>, com os conceitos explicitados na Tabela 1, e o template utilizado para cada símbolo pode ser visualizado na Tabela 2:

<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Léxicos LAL</p></font>
<center>

| Tipo do símbolo | Noção | Impacto |
|-----------------|-------|-------|
| Verbo | Quem realiza, quando acontece e quais os procedimentos | Quais os reflexos das ações no ambiente e novos estados decorrentes |
| Objeto | Definir o objeto e identificar outros objetos com os quais ele se relaciona | Ações que podem ser aplicadas ao objeto  |
| Estado | O que indica e ações que levaram a esse estado | Identificar outros estados que podem ocorrer a partir do estado que se descreve  |

</center>
<font size="3"><p style="text-align: center">Fonte: SAYÃO e CARVALHO<a id="anchor_1" href="#REF1"><sup>1</sup></a>.</p></font>

---

<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Template de Símbolos</p></font>

<center>

| ID | Descrição |
|-----------------|-------|
| Classificação | Estado/Objeto/Verbo |
| Noção | Símbolo - significado |
| Impacto | Descrição  | 
| Sinônimos | Palavras semelhantes |

</center>

<font size="3"><p style="text-align: center">Fonte: [Rafael Pereira](https://github.com/rafgpereira), 2024.</p></font>

---

## Léxicos

### <a id="L01" href="#anchor_L01" style="color:blue;"> L01: Filtrar Eventos</a>

O primeiro Léxico, na Tabela 3, faz o uso dos seguintes requisitos: filtrar por Estado e por Município (<a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF01</a>) e filtrar por categorias (<a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF26</a>).

<font size="3"><p style="text-align: center"><b>Tabela 3</b> - Léxico 01: Filtrar Eventos (L01)</p></font>

<center>

| L01 | Descrição |
|-----------------|-------|
| Classificação | Verbo |
| Noção | Tarefa realizada pelo <a id="#anchor_L05" href="#L05">usuário</a>. Acontece quando o <a id="#anchor_L05" href="#L05">usuário</a> quer visualizar eventos específicos. <br> O <a id="#anchor_L05" href="#L05">usuário</a> seleciona os filtros desejados. <br> O <a id="#anchor_L05" href="#L05">usuário</a> visualiza eventos filtrados.  |
| Impacto | Apenas eventos correspondentes aos filtros são listados. <br> O <a id="#anchor_L05" href="#L05">usuário</a> pode filtrar os eventos novamente para visualizar diferentes resultados.|
| Sinônimos | Aprimorar busca, Especificar resultados, Restringir busca |

</center>
<font size="3"><p style="text-align: center">Fonte: [Rafael Pereira](https://github.com/rafgpereira), 2024.</p></font>

### <a id="L02" href="#anchor_L02" style="color:blue;"> L02: Sugestões de Eventos</a>

O segundo Léxico, presente na Tabela 4, se relaciona com os seguintes requisitos: apresenta eventos personalizados com base na atividade do usuário (<a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RNF13</a>) e mostrar eventos de preferência do usuário ao abrir (<a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RNF17</a>).

<font size="3"><p style="text-align: center"><b>Tabela 4</b> - Léxico 02: Sugestões de Eventos (L02)</p></font>

| L02 | Descrição |
|-----------------|-------|
| Classificação | Estado |
| Noção | Em uma seção do aplicativo são exibidos eventos recomendados para o <a id="#anchor_L05" href="#L05">usuário</a>. <br> Indica os eventos que o <a id="#anchor_L05" href="#L05">usuário</a> tem mais chance de participar. <br> Quando o <a id="#anchor_L05" href="#L05">usuário</a> compra ou busca ingressos de um evento, eventos semelhantes são sugeridos.  |
| Impacto | O <a id="#anchor_L05" href="#L05">usuário</a> visualiza os eventos sugeridos. <br> O <a id="#anchor_L05" href="#L05">usuário</a> compra um evento sugerido.|
| Sinônimos | Eventos recomendados, Recomendação de eventos, Eventos para você |

<font size="3"><p style="text-align: center">Fonte: [Milena Rocha](https://github.com/MilenaFRocha), 2024.</p></font>

### <a id="L03" href="#anchor_L03" style="color:blue;"> L03: Carrinho de compras</a>

O terceiro Léxico, presente na Tabela 5, faz o uso de dois requisitos não implementados: adicionar vários ingressos ao carrinho antes de finalizar a compra (<a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF06</a>) e retirar vários ingressos do carrinho (<a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF07</a>).

<font size="3"><p style="text-align: center"><b>Tabela 5</b> - Léxico 03: Carrinho de compras (L03)</p></font>


| L03 | Descrição |
|-----------------|-------|
| Classificação | Objeto |
| Noção | O carrinho de compras é uma seção do aplicativo que permite que o <a id="#anchor_L05" href="#L05">usuário</a> selecione, armazene e gerencie ingressos antes de finalizar a compra. <br> Ele organiza os itens escolhidos e calcula o valor total. |
| Impacto | Facilita a orgaização e visualização dos itens selecionados pelo <a id="#anchor_L05" href="#L05">usuário</a>. <br> Permite ajustes, como alteração e remoção de itens. <br> Simplifica e otimiza o processo de compra. |
| Sinônimos | Carrinho, Cesta de compras, Carrinho virtual, Sacola de compras |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Scheidt](https://github.com/gxaite), 2024.</p></font>


### <a id="L04" href="#anchor_L04" style="color:blue;"> L04: Notificar Sobre Eventos</a>

O quarto Léxico, presente na Tabela 6, se relaciona com o seguinte requisito: o sistema envia notificações ou lembretes sobre os eventos comprados (<a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF03</a>).

<font size="3"><p style="text-align: center"><b>Tabela 6</b> - Léxico 04: Notificar Sobre Eventos (L04)</p></font>


| L04 | Descrição |
|-----------------|-------|
| Classificação | Verbo |
| Noção | O sistema envia notificações ao <a id="#anchor_L05" href="#L05">usuário</a> que permitiu o envio de notificações <br> Quando existe um evento recomendado para o <a id="#anchor_L05" href="#L05">usuário</a>, uma notificação é enviada. <br> Quando o <a id="#anchor_L05" href="#L05">usuário</a> compra um ingresso, ele é notificado sobre data, hora, local, ou atualizações relevantes. |
| Impacto | O <a id="#anchor_L05" href="#L05">usuário</a> recebe lembretes sobre os eventos adquiridos e recomendados. <br> Reduz o risco de esquecimento por parte do usuário. <br> Aumenta o engajamento ao garantir que o <a id="#anchor_L05" href="#L05">usuário</a> esteja sempre atualizado. |
| Sinônimos | Enviar lembrete, Avisar sobre eventos, Lembrar sobre eventos |

<font size="3"><p style="text-align: center">Fonte: [Victor Hugo](https://github.com/VHbernardes), 2024.</p></font>


### <a id="L05" href="#anchor_L05" style="color:blue;"> L05: Usuário</a>

O quinto Léxico, presente na Tabela 7, se relaciona com diversos <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">requisitos elicitados</a> que estão voltados para as necessidades do usuário.

<font size="3"><p style="text-align: center"><b>Tabela 7</b> - Léxico 05: Usuário (L05)</p></font>

| L05 | Descrição |
|-----------------|-------|
| Classificação | Objeto |
| Noção | O usuário pode se enquadrar no [perfil de usuário](../elicitacao/perfil_usuario.md). </br> O usuário é a pessoa que quer visualizar/pesquisar eventos. </br> O usuário é a pessoa que quer comprar ingressos de eventos. </br> O sistema pode enviar notificações ao usuário, caso permitido. </br> O sistema coleta dados das atividades do usuário dentro do app e cria sugestões personalizadas. </br> |
| Impacto | O sistema atende às necessidades e expectativas do usuário. <br> O usuário permite o envio de notificações (<a id="#anchor_L05" href="#L04">L04</a>) e a personalização dos conteúdos. <br> O sistema melhora a experiência do usuário ao adaptar-se para atender o seu perfil e comportamento (<a id="#anchor_L05" href="#L02">L02</a>). |
| Sinônimos | Cliente, Comprador, Consumidor, Freguês, Visitante, Participante. |

<font size="3"><p style="text-align: center">Fonte: [Renan Araújo](https://github.com/renantfm4), 2024.</p></font>

### <a id="L06" href="#anchor_L06" style="color:blue;"> L06: Trocar Titularidade</a>

O sexto Léxico, presente na Tabela 8, faz o uso do seguinte requisito: o sistema permite transferências de ingressos diretamente na plataforma (<a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF08</a>).

<font size="3"><p style="text-align: center"><b>Tabela 8</b> - Léxico 06: Trocar Titularidade (L06)</p></font>

| L06 | Descrição |
|-----------------|-------|
| Classificação | Verbo |
| Noção | O sistema permite que o usuário troque a titularidade do ingresso adquirido. <br> Ação de alterar a titularidade de um ingresso comprado no aplicativo, transferindo todos os dados e direitos para outra pessoa. <br> O processo pode incluir o envio de informações do novo titular, dependendo de cada produtor de eventos.  |
| Impacto | Permite que o ingresso seja utilizado por outra pessoa. <br> Facilita a gestão de ingressos em caso de imprevistos. <br> Garante que o novo titular tenha acesso ao evento de forma segura e regularizada. | 
| Sinônimos | Transferir ingressos, Mudar titular do ingresso, Alterar dono do ingresso. |

<font size="3"><p style="text-align: center">Fonte: [Rafael Pereira](https://github.com/rafgpereira), 2024.</p></font>


### <a id="L07" href="#anchor_L07" style="color:blue;"> L07: Cancelar Compra de Ingresso </a>

O sétimo Léxico, presente na Tabela 9, faz o uso do seguinte requisito: o sistema permite o cancelamento de ingressos diretamente na plataforma (<a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF08</a>).

<font size="3"><p style="text-align: center"><b>Tabela 9</b> - Léxico 07: Cancelar Compra de Ingresso (L07)</p></font>

| L07 | Descrição |
|-----------------|-------|
| Classificação | Verbo |
| Noção | O sistema permite que o usuário cancele a compra do ingresso adquirido. <br> Ação de desfazer a compra de um ingresso comprado no aplicativo, estornando todos os valores ao usuário e retirando seu direito de acesso ao evento. <br> O processo pode incluir o pagamento de taxas extras ou ser limitado de acordo com o produtor de eventos.  |
| Impacto | Permite que a compra seja desfeita pelo usuário. <br> Facilita a gestão de ingressos em caso de imprevistos. <br> Garante que o valor pago seja devolvido parcialmente ou integralmente ao usuário. |
| Sinônimos | Anular compra de ingresso, Desfazer compra de ingresso, Cancelar compra de ingresso. |

<font size="3"><p style="text-align: center">Fonte: [Rafael Pereira](https://github.com/rafgpereira), 2024.</p></font>


### <a id="L08" href="#anchor_L08" style="color:blue;"> L08: Produtor de Eventos </a>

O oitavo Léxico, presente na Tabela 10, faz o uso do seguinte requisito: o sistema permite o cancelamento de ingressos diretamente na plataforma (<a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF08</a>).

<font size="3"><p style="text-align: center"><b>Tabela 10</b> - Léxico 08: Produtor de Eventos (L08)</p></font>

| L08 | Descrição |
|-----------------|-------|
| Classificação | Objeto |
| Noção | O produtor de eventos é a pessoa física ou jurídica responsável por criar, organizar e gerenciar eventos no aplicativo. <br> Ele utiliza o sistema para cadastrar eventos, configurar ingressos, acompanhar vendas e interagir com usuários interessados/compradores do evento. |
| Impacto | Permite a criação e gestão de eventos na plataforma. <br> Facilita o acompanhamento de métricas de venda. <br> Garante comunicação eficiente entre os usuários interessados/compradores com a produção do evento. |
| Sinônimos | Organizador de eventos, Criador de eventos, Administrador de eventos. |

<font size="3"><p style="text-align: center">Fonte: [Rafael Pereira](https://github.com/rafgpereira), 2024.</p></font>

## **Bibliografia**

>SERRANO, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: [https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf). Acesso em: 05 dez. 2024.

## **Referências Bibliográficas**

> <a id="REF1" href="#anchor_1">1.</a> SAYÃO, Miriam, CARVALHO, Gustavo. Construção do léxico de aplicações. Information and Human Language Technology, 4th Workshop, Ribeirão Preto, 2006. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf/>. Acesso em: 05 dez. 2024.


## Histórico de Versões

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     | 
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|
|  1.0   | Criação desse documento | [Rafael Pereira](https://github.com/rafgpereira) | 05/12/2024 | [Milena Rocha](https://github.com/MilenaFRocha)  |
|  1.1   | Adição dos léxicos criados | [Rafael Pereira](https://github.com/rafgpereira) | 06/12/2024 | [Renan Araújo](https://github.com/renantfm4)  |
|  1.2   | Adiciona hyperlinks | [Rafael Pereira](https://github.com/rafgpereira) | 08/12/2024 | [Gabriel Scheidt](https://github.com/Gxaite)  |
