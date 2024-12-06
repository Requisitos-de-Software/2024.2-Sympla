## Introdução
A Especificação Suplementar é um documento redigido em linguagem natural que detalha os requisitos de um sistema, funcionando como um complemento aos casos de uso<a id="anchor_1" href="#REF1"> 1</a>, ao capturar aspectos que não foram considerados anteriormente. Esse documento aborda uma ampla variedade de requisitos, incluindo questões legais e regulamentares, padrões de aplicativos, atributos de qualidade como utilidade, confiabilidade, desempenho e suportabilidade, além de requisitos técnicos relacionados a sistemas e ambientes operacionais, compatibilidade e restrições de design. O modelo FURPS+ é amplamente utilizado como metodologia para estruturar esse tipo de especificação.

## Finalidade

A finalidade é de documentar aspectos do sistema que não estão diretamente relacionados às funcionalidades, mas que são igualmente importantes para o seu desenvolvimento e operação. Ela complementa os requisitos funcionais, que descrevem o que o Sympla deve fazer.

## Escopo

O objetivo do Sympla Internet Soluções S.A  facilitar a criação, gestão e venda de ingressos para eventos.

## Metodologia

Para a produção desse artefato, será utilizado o [modelo](https://www.gov.br/agricultura/pt-br/acesso-a-informacao/licitacoes-e-contratos/edital/2019/pregao-eletronico-no-05-2018/templates-artefatos/estoria-de-usuario.doc/view) de especificação disponibilizado por André Barros, baseado em uma versão modificada do FURPS+. Essa metodologia organiza os requisitos em categorias específicas: **F** de Functionality (Funcionalidade), **U** de Usability (Usabilidade), **R** de Reliability (Confiabilidade), **P** de Performance (Desempenho), **S** de Supportability (Suportabilidade), e **+**, que inclui outros requisitos não-funcionais, como Requisitos de Design, Requisitos de Implementação, Requisitos de Interface e Requisitos Físicos.  

No entanto, nesta versão adaptada, os requisitos de interface e a seção de componentes adquiridos serão omitidos, já que essas informações estão detalhadas em outros artefatos. Além disso, os requisitos não-funcionais foram elicitados utilizando técnicas como [Observação](../elicitacao/elicitacao/tecnicas/observacao.md), [Introspecção](../elicitacao/tecnicas/introspeccao.md), [Questionário](../elicitacao/tecnicas/questionario.md) e [Entrevista](../elicitacao/tecnicas/entrevista.md/).

## Funcionalidade

Os requisitos funcionais foram elicitados na seção de elicitação e a [tabela 1](../elicitacao/requisitos/requisitos_elicitados.md) da página de [requisitos elicitados](../elicitacao/requisitos/requisitos_elicitados.md) demonstra todos os requisitos priorizados.


## Usabilidade

Referem-se à facilidade do [usuário](https://requisitos-de-software.github.io/2024.2-Sympla/modelagem/lexico/#l05-usuario) no uso e interação do sistema, considerando fatores humanos e questões de interface. Eles incluem acessibilidade para diferentes públicos, design estético que seja intuitivo e agradável, consistência visual e funcional dentro da interface e entre funcionalidades, e o suporte para reduzir a curva de aprendizado dos usuários.

Para essa categoria os requisitos identificados estão representados na tabela 1 a seguir.

<font><p style="text-align: center">**Tabela 1** - Requisitos de Usabilidade.</p></font>

<center>

| ID    | Descrição                                                                                                                                |
| ----- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| USA01 | O aplicativo deve oferecer suporte a temas com alto contraste, garantindo que as ações principais ou críticas sejam destacadas em vermelho. |
| USA02 | O aplicativo deve incluir recursos de acessibilidade, como teclado virtual, [troca de idioma](https://requisitos-de-software.github.io/2024.2-Sympla/modelagem/lexico/#l06-mudar-idioma), modo de alto contraste, ajuste de tamanho da fonte e suporte a audiodescrição. |
| USA03 | O aplicativo deve fornecer retorno imediato ao [usuário](https://requisitos-de-software.github.io/2024.2-Sympla/modelagem/lexico/#l05-usuario) por meio de pop-ups e mensagens, como ao [notificar eventos](https://requisitos-de-software.github.io/2024.2-Sympla/modelagem/lexico/#l04-notificar-eventos) ou [sugerir eventos](https://requisitos-de-software.github.io/2024.2-Sympla/modelagem/lexico/#l02-sugestoes-de-eventos). |
| USA04 | O aplicativo deve garantir jornadas simplificadas, permitindo a conclusão de tarefas complexas com no máximo sete toques na tela.         |
| USA05 | O aplicativo deve oferecer pelo menos quatro opções principais de pagamento: boleto bancário, Pix, cartão de crédito e cartão de débito.  |
| USA06 | O aplicativo deve minimizar a repetição de passos pelo [usuário](https://requisitos-de-software.github.io/2024.2-Sympla/modelagem/lexico/#l05-usuario), otimizando os fluxos e reduzindo redundâncias nas interações. |                                                                      |


</center>

<font size="3"><p style="text-align: center">Fonte: [Milena Rocha](https://github.com/MilenaFRocha).</p></font>

## Confiabilidade

Envolvem garantir que o sistema funcione de maneira previsível e sem falhas críticas. Eles incluem alta disponibilidade para minimizar interrupções, precisão nos resultados das operações, previsibilidade no comportamento das funcionalidades, baixa frequência de falhas e mecanismos eficientes de recuperação em caso de paradas completas ou falhas inesperadas.

Para essa categoria os requisitos identificados estão representados na tabela 2 a seguir.

<font><p style="text-align: center">**Tabela 2** - Requisitos de Confiabilidade.</p></font>

<center>

| ID    | Descrição                                                                                                                         |
| ----- | --------------------------------------------------------------------------------------------------------------------------------- |
| CON01 | O aplicativo deve estar disponível para acesso 24 horas por dia, 7 dias por semana.                                               |
| CON02 | O aplicativo deve garantir que as informações exibidas estejam sempre atualizadas e em conformidade com a realidade.              |
| CON03 | O aplicativo deve assegurar a integridade das informações do [usuário](https://requisitos-de-software.github.io/2024.2-Sympla/modelagem/lexico/#l05-usuario) e dos meios de pagamento associados.                            |
| CON04 | O aplicativo deve atender aos requisitos da Lei Geral de Proteção de Dados (LGPD).                                                |
| CON05 | O aplicativo deve permitir que o [usuário](https://requisitos-de-software.github.io/2024.2-Sympla/modelagem/lexico/#l05-usuario) resolva problemas ou recupere de erros em no máximo três toques na interface.                |
| CON06 | O aplicativo deve apresentar de forma clara e facilmente acessível todas as informações sobre taxas aplicadas aos [usuários](https://requisitos-de-software.github.io/2024.2-Sympla/modelagem/lexico/#l05-usuario).           |
| CON07 | O aplicativo deve realizar backups regulares dos dados dos [usuários](https://requisitos-de-software.github.io/2024.2-Sympla/modelagem/lexico/#l05-usuario) e eventos cadastrados.                                             |
| CON08 | O aplicativo deve evitar que o [usuário](https://requisitos-de-software.github.io/2024.2-Sympla/modelagem/lexico/#l05-usuario) realize ações que comprometam a integridade do sistema ou de outros usuários.                  |
| CON09 | O aplicativo deve ser implementado em uma infraestrutura distribuída utilizando vários servidores para garantir maior robustez.    |                                                                      |

</center>

<font size="3"><p style="text-align: center">Fonte: [Milena Rocha](https://github.com/MilenaFRocha).</p></font>

## Desempenho

Abrangem aspectos relacionados à eficiência do sistema em condições de operação. Eles incluem alta taxa de transferência de informações, tempos de resposta rápidos e consistentes, e uso otimizado de recursos computacionais como memória, processamento e rede, mesmo em situações de alta demanda.

Para essa categoria os requisitos identificados estão representados na tabela 3 a seguir.

<font><p style="text-align: center">**Tabela 3** - Requisitos de Desempenho.</p></font>

| ID   | Descrição                                                                                                                |
| ---- | ------------------------------------------------------------------------------------------------------------------------ |
| PE01 | O aplicativo deve carregar rapidamente, com tempo ideal de menos de 3 segundos para páginas principais, como a busca de eventos. |
| PE02 | O sistema não deve ter um tempo de resposta superior a 300ms para operações críticas, como busca e compra de ingressos.   |
| PE03 | O sistema deve exibir no máximo 25 eventos por página como padrão ao realizar buscas ou filtragens de eventos.            |
| PE04 | O sistema deve autenticar o usuário e carregar o painel principal em até 2 segundos após o envio das credenciais válidas. |
| PE05 | O sistema deve suportar mais de 2 milhões de requisições por segundo em momentos de pico de tráfego.                      |


<font size="3"><p style="text-align: center">Fonte: [Renan Araújo](https://github.com/renantfm4).</p></font>

## Suportabilidade

Dizem respeito à capacidade do sistema de se adaptar e ser mantido ao longo do tempo. Eles incluem compatibilidade com diferentes ambientes de hardware e software, facilidade de teste e depuração, capacidade de adaptação às mudanças, simplicidade na manutenção e configuração, processos claros de instalação e escalabilidade para suportar o crescimento em volume de usuários ou dados, além de ferramentas para localização e solução de problemas.

Para essa categoria os requisitos identificados estão representados na tabela 4 a seguir.

<font><p style="text-align: center">**Tabela 4** - Requisitos de Suportabilidade.</p></font>

| ID    | Descrição                                                                                                                |
| ----- | ------------------------------------------------------------------------------------------------------------------------ |
| SUP01 | O aplicativo deve suportar diferentes sistemas operacionais (iOS e Android) e dispositivos (smartphones e tablets), garantindo uma experiência consistente. |
| SUP02 | O aplicativo deve ter um chatbot para ajudar usuários com dúvidas sobre ingressos e reembolsos.                          |
| SUP03 | O aplicativo deve oferecer disponibilização de opções em português, inglês e espanhol.                                   |
| SUP04 | O sistema deve permitir personalização de notificações para os usuários, como ativar/desativar lembretes de eventos e atualizações sobre ingressos. |
| SUP05 | O sistema deve permitir compartilhamento de ingressos entre usuários diretamente pelo aplicativo, com rastreamento de transferências realizadas. |
| SUP06 | O sistema deve oferecer integração com ferramentas de acessibilidade, como leitores de tela e suporte a navegação por teclado, para atender a usuários com deficiências. |
| SUP07 | O sistema deve implementar um mecanismo de feedback dentro do aplicativo, permitindo que usuários enviem sugestões ou relatem problemas diretamente à equipe de desenvolvimento. |
| SUP08 | O sistema deve possuir alta testabilidade, permitindo realização de testes automatizados e manuais durante o desenvolvimento e manutenção para garantir estabilidade. |
| SUP09 | O sistema deve apresentar tolerância a falhas, com mecanismos de recuperação, detecção de erros, manutenção da integridade dos dados, backups regulares e processos de restauração rápidos em caso de falhas. |
| SUP10 | O sistema deve adotar uma arquitetura com código bem estruturado e organizado, permitindo fácil manutenção e implementação de melhorias. |


<font size="3"><p style="text-align: center">Fonte: [Renan Araújo](https://github.com/renantfm4).</p></font>

## Restrições de Design

Restrições de design são condições e limitações específicas que precisam ser consideradas no processo de criação e desenvolvimento de um produto, como um aplicativo, site, ou qualquer outro projeto digital. No caso do Sympla, essas restrições podem abranger aspectos técnicos, visuais, funcionais, orçamentários, prazos de entrega, entre outros. Elas servem como diretrizes que influenciam e orientam as decisões de design, garantindo que o produto final atenda aos requisitos estabelecidos e proporcione uma experiência alinhada às expectativas dos usuários.

Na Tabela 5, estão listados os Requisitos Não Funcionais relacionados às Restrições de Design identificados para o aplicativo Sympla.

Para essa categoria os requisitos identificados estão representados na tabela 5 a seguir.

<font><p style="text-align: center">**Tabela 5** - Requisitos não funcionais sobre Restrições de Design.</p></font>

| ID    | Descrição                                                                                     |
|-------|-----------------------------------------------------------------------------------------------|
| RD01  | O design deve ser modular e reutilizável, permitindo fácil manutenção e expansão do sistema.  |
| RD02  | O layout deve ser responsivo e adaptável a diferentes dispositivos (desktop, tablet, celular).|
| RD03  | A interface de usuário (UI) deve ser intuitiva, com navegação clara e fácil de entender para o usuário. |
| RD04  | As cores e tipografia devem seguir as diretrizes da marca, garantindo consistência visual no sistema. |
| RD05  | O design deve incluir elementos de feedback visual, como mensagens de erro ou sucesso, para proporcionar uma boa experiência ao usuário. |


<font size="3"><p style="text-align: center">Fonte: [Renan Araújo](https://github.com/renantfm4).</p></font>

## Requisitos de Implementação

Os requisitos de implementação são diretrizes e boas práticas que orientam o desenvolvimento do código, garantindo que o sistema seja eficiente, escalável e alinhado com os padrões da indústria. No caso do Sympla, esses requisitos abrangem aspectos como modularidade, escalabilidade, compatibilidade e documentação, assegurando que o código seja sustentável e facilite futuras atualizações.

Na Tabela 6, estão listados os Requisitos Não Funcionais relacionados à implementação identificados para o aplicativo Sympla.

Para essa categoria, os requisitos identificados estão representados na tabela 6 a seguir.

<font><p style="text-align: center">**Tabela 6** - Requisitos não funcionais sobre Implementação.</p></font>

| ID    | Descrição                                                                                     |
|-------|-----------------------------------------------------------------------------------------------|
| IM01  | O código deve ser modularizado, com funções e classes bem definidas, para facilitar a manutenção e reutilização. |
| IM02  | A implementação deve ser escalável, permitindo que novas funcionalidades sejam facilmente integradas sem afetar a performance do sistema. |
| IM03  | O sistema deve ser compatível com as bibliotecas e frameworks mais recentes, garantindo que o código esteja alinhado com as melhores práticas da indústria. |
| IM04  | O código deve ser bem documentado, com comentários claros explicando a lógica de funções e métodos críticos. |
| IM05  | O código deve ser eficiente em termos de uso de recursos, evitando operações desnecessárias e garantindo um bom desempenho. |

<font size="3"><p style="text-align: center">Fonte: [Renan Araújo](https://github.com/renantfm4).</p></font>

## Requisitos de Interface

Os requisitos de interface definem os elementos e funcionalidades que garantem uma experiência do usuário eficiente e intuitiva. Para o Sympla, esses requisitos incluem a organização clara das informações, navegabilidade intuitiva e um design responsivo, proporcionando uma interface que atenda às necessidades dos usuários e ofereça interações fluidas e agradáveis.

Na Tabela 7, estão listados os Requisitos Não Funcionais relacionados à interface identificados para o aplicativo Sympla.

Para essa categoria, os requisitos identificados estão representados na tabela 7 a seguir.

<font><p style="text-align: center">**Tabela 7** - Requisitos não funcionais sobre Interface.</p></font>

| ID    | Descrição                                                                                     |
|-------|-----------------------------------------------------------------------------------------------|
| IN01  | A interface deve ser intuitiva e fácil de usar, com navegação simples entre as seções de criação, gerenciamento e visualização de eventos. |
| IN02  | A página inicial deve exibir eventos em destaque de forma clara, com filtros para categorias e datas, proporcionando uma experiência personalizada ao usuário. |
| IN03  | O design deve ser responsivo, garantindo uma experiência de uso fluida tanto em dispositivos móveis quanto em desktops, com ajuste automático de layouts. |
| IN04  | Cada evento deve ter uma página dedicada, contendo informações detalhadas como descrição, data, local, preço e opções para inscrição ou compra de ingressos, com botões de ação visíveis e acessíveis. |
| IN05  | A interface de usuário deve incluir feedback visual claro, como animações ou mensagens de confirmação, quando o usuário realiza ações como comprar ingressos ou se inscrever em um evento. |

<font size="3"><p style="text-align: center">Fonte: [Renan Araújo](https://github.com/renantfm4).</p></font>


## Requisitos de Licenciamento  

O sistema deve limitar seu uso por meio de termos de uso específicos, estabelecendo diretrizes claras para os usuários.  

## Considerações Legais, de Copyright e Proteção de Dados  

O sistema deve respeitar a legislação de direitos autorais vigente, exigindo autorização prévia para o uso de marcas de terceiros. Além disso, deve estar em conformidade com a Lei Geral de Proteção de Dados (LGPD) e regulamentos relacionados a serviços financeiros.  

## Padrões e Normas Aplicáveis  

O sistema deve aderir aos seguintes padrões e normas:  
- WCAG (Diretrizes de Acessibilidade para Conteúdo Web);  
- ISO 9241-11 (Ergonomia da interação humano-computador);  
- ISO/TC-211 (Geoinformação/Geomática);  
- ISO 9000 e ISO 9001-3 (Gestão da qualidade);  
- ISO 12207 e ISO 12202 (Engenharia de software).  

Além disso, deve seguir os guias de estilo e boas práticas para plataformas Android e iOS.  

## Requisitos de Compatibilidade com Dispositivos  

O sistema deve ser acessível em computadores de mesa, laptops, tablets e smartphones, funcionando adequadamente em navegadores de internet compatíveis.

## Referências Bibliográficas

> <a id="REF2" href="#anchor_2">2.</a>Concept: Requisitos Suplementare. **Centro de Informática - UFPE**. Disponível em: <<https://www.cin.ufpe.br/~rls2/processo_tg/Metodologia%20S&B/guidances/concepts/supporting_requirements_C0220FE1.html>>. Acesso em: 02 de dezembro de 2024.
> 
## Bibliografia

> HENRIQUE, Matheus. Especificação Suplementar. Repositório do Grupo Bilheteria Digital da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: <<https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/>>. Acesso em: 02 dezembro 2024.

## Histórico de Versões

<center>


| Versão |          Descrição              |     Autor      |      Data      |   Revisor     |
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|
|  1.0   | Criação do documento |  [MilenaFRocha](https://github.com/MilenaFRocha) | 02/12/2024   | [Gabriel Scheidt](https://github.com/Gxaite) |
|  1.1   | Adição de tabelas |  [MilenaFRocha](https://github.com/MilenaFRocha) | 02/12/2024   | [Gabriel Scheidt](https://github.com/Gxaite) |



</center>
