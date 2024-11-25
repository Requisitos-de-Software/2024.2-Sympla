# Introspecção

## Introdução

A introspecção é um método de obtenção de requisitos que envolve, através de uma análise pessoal e detalhada, identificar o que é essencial para o desenvolvimento de um software desse tipo. Nesse contexto, o responsável por aplicar essa abordagem deve imaginar uma situação hipotética em que uma tarefa específica seria executada. Assim, os requisitos levantados estão apresentados nas Tabelas 2 e 3.

## Metodologia

O processo de introspecção foi conduzido individualmente pelos alunos [Milena Rocha](https://github.com/MilenaFRocha) e  [Gabriel Scheidt](https://github.com/Gxaite). Após essa etapa, os requisitos identificados foram consolidados em duas tabelas: a Tabela 2 reúne os Requisitos Funcionais, enquanto a Tabela 3 apresenta os Requisitos Não-Funcionais. Ao término do processo, revisitamos o aplicativo escolhido pelo grupo para verificar se os requisitos levantados estavam presentes. Abaixo estão descritos os participantes e o cronograma de aplicação da técnica

### Cronograma

<font size="3"><p style="text-align: center">Tabela 1: Participantes.</p></font>

<center>

| Nome                                             | Data                   |  Hora |
| ------------------------------------------------ | ------------------------ | -------------- |
| [Milena Rocha](https://github.com/MilenaFRocha)   |  18/11/2024| 14:00|
|  [Gabriel Scheidt](https://github.com/Gxaite) |  18/11/2024|   14:00 |

</center>

<font size="3"><p style="text-align: center">Fonte: [Milena Rocha](https://github.com/MilenaFRocha) e  [Gabriel Scheidt](https://github.com/Gxaite).</p></font>

### [Gabriel Scheidt](https://github.com/Gxaite)

Para a aplicação deste método, imaginei-me em uma situação cotidiana de João (persona escolhida) na qual eu desejasse participar de um evento utilizando o Sympla. Assim, como usuário e sem visualizar o aplicativo, refleti sobre as funcionalidades que seriam indispensáveis para realizar essa tarefa. Além disso, considerei as possíveis dificuldades que poderiam surgir e o que o aplicativo deveria oferecer como solução para essas situações.

<iframe width="560" height="315" src="https://www.youtube.com/embed/EXQK9Ttb9YQ?si=2h67PuAjvNV9gueW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<font size="3"><p style="text-align: center"><b>Fonte:</b> Gabriel Scheidt.Técnica de Introspecção, 2024/2, UnB. 2024. Disponível em: <a href="https://youtu.be/EXQK9Ttb9YQ">https://youtu.be/EXQK9Ttb9YQ</a>. Acesso em: 24 nov. 2024.</p></font>

### [Milena Rocha](https://github.com/MilenaFRocha)

Para a aplicação deste método, imaginei-me em uma situação cotidiana de Beatriz (persona escolhida). Sou Beatriz, analista de marketing e mãe. Minha rotina é corrida, e, quando tenho tempo livre, gosto de encontrar eventos culturais ou de entretenimento para aproveitar com minha família. Uso o Sympla porque preciso de uma forma rápida e prática de achar eventos interessantes. Quero filtros simples por categoria e localização, sugestões que combinem com meus gostos e uma integração fácil com meu calendário para organizar tudo. Também preciso que a compra de ingressos seja descomplicada, com pagamento rápido e seguro. Não posso perder tempo, então, se algo der errado, espero suporte imediato e soluções rápidas, para que eu possa curtir meu tempo livre sem preocupações. [Vídeo da execução da técnica](https://youtu.be/mq34x8JQDG8)

<iframe width="560" height="315" src="https://www.youtube.com/embed/mq34x8JQDG8?si=ygLm9ctYI98R9imB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<font size="3"><p style="text-align: center"><b>Fonte:</b> Milena Rocha.Técnica de Introspecção, 2024/2, UnB. 2024. Disponível em: <a href="https://youtu.be/mq34x8JQDG8">https://youtu.be/mq34x8JQDG8</a>. Acesso em: 24 nov. 2024.</p></font>



## Requisitos elicitados

### Funcionais

Legenda das Tabelas 2 e 3:

- RFx: Requisito Funcional nºx
- RNFx: Requisito Não-Funcional nºx
- ISx: Requisito nºx elicitado pela introspecção.

<font size="3"><p style="text-align: center">Tabela 2: Requisitos Funcionais.</p></font>

<center>

| Tipo  | Descrição                                                   | ID   | Implementado |
|-------|-------------------------------------------------------------|------|--------------|
| RF01  | O Sympla permite filtrar eventos por Estado e Município.    | IS01 | Sim          |
| RF02  | O Sympla oferece filtros por data e horário dos eventos.    | IS02 | Sim          |
| RF03  | O Sympla possibilita filtrar eventos por categorias.        | IS03 | Não          |
| RF04  | O Sympla permite a realização da compra de ingressos.       | IS04 | Sim          |
| RF05  | O Sympla oferece funcionalidades para cadastro e login de usuários. | IS05 | Sim          |
| RF06  | O Sympla possibilita a exclusão do cadastro de usuários.    | IS06 | Sim          |
| RF07  | O Sympla permite o cadastro de métodos de pagamento.        | IS07 | Sim          |
| RF08  | O Sympla oferece a opção de cancelar compras realizadas.    | IS08 | Não          |
| RF09  | O Sympla dispõe de um mecanismo de busca integrado.         | IS09 | Sim          |
| RF10  | O Sympla oferece a opção de transferir ingressos.           | IS10 | Sim          |
| RF11  | O aplicativo dá sugestões de eventos com base no histórico de buscas do usuário. | IS11 | Sim          |
| RF12  | O usuário é capaz de conectar uma carteira digital.         | IS12 | Sim          |
| RF13  | O usuário é capaz de mudar o idioma do app.               | IS13 | Sim          |
| RF14  | O usuário é capaz de entrar na aba de configurações.                 | IS14 | Sim          |
| RF15  | O sistema apresenta uma aba de acessibilidades.                 | IS15 | Sim          |
| RF16  | O usuário é capaz de criar preferências de eventos.              | IS16 | Sim          |
| RF17  | O app faz sugestões e envia notificações com base na preferência escolhida do usuário.                   | IS18 | Sim          |
| RF18  | O Sympla oferece a opção imprimir ingressos.                | IS19 | Sim          |

</center>

<font size="3"><p style="text-align: center">Fonte: [Milena Rocha](https://github.com/MilenaFRocha) e  [Gabriel Scheidt](https://github.com/Gxaite).</p></font>

Vale ressaltar que os requisitos RF11 só é possível por meio do email e não direto no aplicativo. O RF08 não há no app, mas pode ser que isso dependa do produtor.

### Não funcionais

<font size="3"><p style="text-align: center">Tabela 3: Requisitos Não-Funcionais.</p></font>

<center>

| Tipo  | Descrição                                                                                                                         | ID   | Implementado |
|-------|-----------------------------------------------------------------------------------------------------------------------------------|-------|--------------|
| RNF01 | O Sympla deve apresentar eventos de forma personalizada, com base na atividade do usuário.                                        | IS12  | Sim          |
| RNF02 | O usuário deve conseguir acessar informações como data, local e preço do ingresso em, no máximo, 2 cliques durante a busca no Sympla. | IS13  | Sim          |
| RNF03 | O Sympla deve permitir que o usuário acesse seus ingressos em, no máximo, 3 cliques.                                                 | IS14  | Sim          |
| RNF04 | O Sympla deve oferecer atendimento especial para idosos e pessoas com deficiência durante o processo de compra de ingressos.      | IS15  | Não          |
| RNF05 | O Sympla deve incluir um mecanismo de autenticação seguro, permitindo que os usuários façam login com suas credenciais.           | IS16  | Sim          |
| RNF06 | O Sympla deve contar com uma área para que os usuários reportem erros de funcionamento da plataforma.                             | IS17  | Sim          |

</center>

<font size="3"><p style="text-align: center">Fonte: [Milena Rocha](https://github.com/MilenaFRocha) e  [Gabriel Scheidt](https://github.com/Gxaite).</p></font>


## Bibliografia

> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. **UnB Gama**, Brasília, 2023. Disponível em: <<https://aprender3.unb.br/pluginfile.php/2580553/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>>. Acesso em: 26/04/2023.

## Histórico de Versões

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     | 
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|
|  1.0   | Criação desse documento | [Milena Rocha](https://github.com/MilenaFRocha) | 18/11/2024 | [Rafael Pereira](https://github.com/rafgpereira)  |
|  1.1   | Vídeo postado | [Milena Rocha](https://github.com/MilenaFRocha) | 23/11/2024 | [Rafael Pereira](https://github.com/rafgpereira)  |
|  1.2   | Vídeo postado | [Gabriel Scheidt](https://github.com/MilenaFRocha) | 24/11/2024 | [Victor Hugo](https://github.com/VHbernardes)  |

