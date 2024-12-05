## Introdução

O Léxico tem como objetivo descrever os símbolos de uma linguagem.  Na modelagem de requisitos, os léxicos são responsáveis por explicar, seguindo uma estrutura pré definida, termos da aplicação(símbolos) que podem ser estranhos para o público. Cada símbolo possui noção, impacto e sinônimos. Noção é uma breve descrição do que significa aquele símbolo, impacto é a conotação de um símbolo, o que ele faz/causa quando utilizado, e sinônimos são símbolos semelhantes.

## Metodologia

Para a elaboração dos léxicos, utilizamos a notação do Léxico Ampliado da Linguagem (LAL)<a id="anchor_1" href="#REF1">^1^</a>, com os conceitos explicitados na Tabela 1, e o template utilizado para cada símbolo pode ser visualizado na Tabela 2:

<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Léxicos LAL</p></font>

| Tipo do símbolo | Noção | Impacto |
|-----------------|-------|-------|
| Verbo | Quem realiza, quando acontece e quais os procedimentos | Quais os reflexos das ações no ambiente e novos estados decorrentes |
| Objeto | Definir o objeto e identificar outros objetos com os quais ele se relaciona | Ações que podem ser aplicadas ao objeto  |
| Estado | O que indica e ações que levaram a esse estado | Identificar outros estados que podem ocorrer a partir do estado que se descreve  |

<font size="3"><p style="text-align: center">Fonte: SAYÃO e CARVALHO<a id="anchor_1" href="#REF1">^1^</a>.</p></font>

</figure>


<font size="3"><p style="text-align: center"><b>Tabela 2:</b> Template de Símbolos</p></font>

| ID | Descrição |
|-----------------|-------|
| Classificação | Estado/Objeto/Verbo |
| Noção | Símbolo - significado |
| Impacto | Descrição  | 
| Sinônimos | Palavras semelhantes |

<font size="3"><p style="text-align: center">Fonte: [Rafael Pereira](https://github.com/rafgpereira), 2024.</p></font>
</figure>

## Léxicos

### <a id="L01" href="#anchor_L01" style="color:red;"> L01: Pesquisar Eventos</a>

O primeiro Léxico, na Tabela 3, faz o uso dos seguintes requisitos não implementados: filtrar por Estado e por Município (<a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS01</a>, <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS08</a> e <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS01</a>), filtrar por data e por horário (<a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS02</a> e <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q03</a>), filtrar por idade mínima de entrada (<a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS03</a> e <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q02</a>) e filtrar por categorias (<a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q04</a>).

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 3</b> - Léxico 01: Filtrar Eventos (L01)</p></font>

| L01 | Descrição |
|-----------------|-------|
| Classificação | Verbo |
| Impacto | Os eventos são listados de acordo com o filtro requisitado | 
| Noção | O <a id="#anchor_L05" href="#L05">usuário</a> está interessado na compra de um ingresso ou na visualização de um evento <br> O usuário escolhe os filtros desejados <br> O usuário realiza a busca com os filtros  |
| Dicionário | Aprimorar busca, Restringir busca e Limitar resultados |

<font size="3"><p style="text-align: center">Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).</p></font>
</figure>

### <a id="L02" href="#anchor_L02" style="color:red;"> L02: Sugestões de Eventos</a>

O segundo Léxico, presente na Tabela 4, faz o uso do seguinte requisito não implementado: o aplicativo da sugestões de eventos com base no histórico de buscas do usuário (<a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q05</a> e <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS11</a>).

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 4</b> - Léxico 02: Sugestões de Eventos (L02)</p></font>

| L02 | Descrição |
|-----------------|-------|
| Classificação | Estado |
| Impacto | A aba de sugestões mostra os eventos sugeridos àquele <a id="#anchor_L05" href="#L05">usuário</a> | 
| Noção | A aba de sugestões se adapta ao que o <a id="#anchor_L05" href="#L05">usuário</a> vê ou consome no site |
| Dicionário | Eventos Sugeridos, Palpites e Recomendações |

<font size="3"><p style="text-align: center">Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).</p></font>
</figure>

### <a id="L03" href="#anchor_L03" style="color:red;"> L03: Evento com Tags</a>

O terceiro Léxico, presente na Tabela 5, faz o uso do seguinte requisito não implementado: o aplicativo tem palavras-chave ou tags associadas aos eventos para facilitar a busca (<a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q06</a>).

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 5</b> - Léxico 03: Evento com Tags (L03)</p></font>


| L03 | Descrição |
|-----------------|-------|
| Classificação | Estado |
| Impacto | Na busca, serão listados todos os eventos vinculados àquela determinada palavra-chave | 
| Noção | O tipo de evento é relacionado a uma categoria pelo anunciante <br> O aplicativo está relacionado a um rótulo ou palavra-chave |
| Dicionário | Eventos com Palavras-chave e Eventos com Rótulo |

<font size="3"><p style="text-align: center">Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).</p></font>
</figure>

### <a id="L04" href="#anchor_L04" style="color:red;"> L04: Notificar Eventos</a>

O quarto Léxico, presente na Tabela 6, faz o uso dos seguintes requisitos não implementados: o aplicativo notifica usuário sobre eventos, quando permitido (<a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q07</a> e <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS06</a>), o aplicativo tem palavras-chave ou tags associadas aos eventos para facilitar a busca (<a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q06</a>), o aplicativo da sugestões de eventos com base no histórico de buscas do usuário (<a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q05</a> e <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS11</a>), .

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 6</b> - Léxico 04: Notificar Eventos (L04)</p></font>


| L04 | Descrição |
|-----------------|-------|
| Classificação | Verbo |
| Impacto | Os eventos são notificados aos <a id="#anchor_L05" href="#L05">usuários</a> que permitiram | 
| Noção | O <a id="#anchor_L05" href="#L05">usuário</a> permitiu e, portanto, deseja ser notificado pelo sistema sobre determinados eventos |
| Dicionário | Aviso de eventos, Comunicar eventos e Informar eventos |

<font size="3"><p style="text-align: center">Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).</p></font>
</figure>

### <a id="L05" href="#anchor_L05" style="color:red;"> L05: Usuário</a>

O quinto Léxico, presente na Tabela 7, faz o uso dos seguintes requisitos não implementados: o aplicativo notifica usuário sobre eventos, quando permitido (<a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q07</a> e <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS06</a>), filtrar por Estado e por Município (<a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS01</a>, <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS08</a> e <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS01</a>), filtrar por data e por horário (<a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS02</a> e <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q03</a>), filtrar por idade mínima de entrada (<a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS03</a> e <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q02</a>), filtrar por categorias (<a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q04</a>), o usuário deve ser capaz de conectar uma carteira digital (<a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS18</a>), o usuário deve ser capaz de mudar o idioma do app (<a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS19</a>) e o usuário deve ser capaz de acessar à assistente virtual (<a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS22</a>).

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 6</b> - Léxico 05: Usuário (L05)</p></font>

| L05 | Descrição |
|-----------------|-------|
| Classificação | Objeto |
| Impacto | O usuário pode escolher se quer ou não receber notificações (<a id="#anchor_L04" href="#L04">L04</a>) </br> O usuário pode filtrar a busca por idade, Estado, Município, data, horário e categoria (<a id="#anchor_L01" href="#L01">L01</a>) </br> O usuário é capaz de conectar uma carteira digital </br> O usuário pode acessar à assistente virtual </br> O usuário pode mudar o idioma do app (<a id="#anchor_L06" href="#L06">L06</a>) </br> | 
| Noção | O usuário pode se enquadrar no [perfil de usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/perfil_de_usuario/)</br> O usuário pode ser alguém que queira visualizar eventos </br> O usuário pode ser alguém que queira comprar ingressos </br> O sistema pode enviar notificações ao usuário, caso permitido (<a id="#anchor_L04" href="#L04">L04</a>) </br> O sistema coleta dados das atividades do usuário dentro do app e os sugere (<a id="#anchor_L04" href="#L02">L02</a>) </br> |
| Dicionário | Cliente, Comprador, Consumidor e Freguês |

<font size="3"><p style="text-align: center">Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).</p></font>
</figure>

### <a id="L06" href="#anchor_L06" style="color:red;"> L06: Mudar Idioma</a>

O sexto Léxico, presente na Tabela 8, faz o uso do seguinte requisito não implementado: o usuário deve ser capaz de mudar o idioma do app (<a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS19</a>).

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 6</b> - Léxico 06: Usuário (L06)</p></font>

| L06 | Descrição |
|-----------------|-------|
| Classificação | Verbo |
| Impacto | O aplicativo muda do idioma atual para o idioma selecionado | 
| Noção | O <a id="#anchor_L05" href="#L05">usuário</a> clicou no botão de alterar o idioma selecionado e selecionou o desejado |
| Dicionário | Alterar Idioma, Selecionar Idioma e Trocar Idioma/Língua |

<font size="3"><p style="text-align: center">Fonte: [Arthur de Melo](https://github.com/arthurmlv).</p></font>
</figure>

## **Bibliografia**

>SERRANO, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: [https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf). Acesso em: 14/05/2023.

## **Referências Bibliográficas**

> <a id="REF1" href="#anchor_1">1.</a> SAYÃO, Miriam, CARVALHO, Gustavo. Construção do léxico de aplicações. Information and Human Language Technology, 4th Workshop, Ribeirão Preto, 2006. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf/>. Acesso em: 14/05/2023.


## Histórico de Versões

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     | 
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|
|  1.0   | Criação desse documento | [Rafael Pereira](https://github.com/rafgpereira) | 05/12/2024 | [Milena Rocha](https://github.com/MilenaFRocha)  |
