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
| USA01 | O sistema deve apresentar cores compatíveis com a opção de alto contraste, e os botões das ações principais ou críticas devem ser de cor vermelha.                          |
| USA02 | O sistema deve possuir recursos de acessibilidade como teclado virtual, [mudar idioma](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l06-mudar-idioma), opção de alto contraste, aumento de fonte e audiodescrição.      |
| USA03 | O sistema deve dar feedback ao [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario), com pop ups e mensagens, por exemplo, ao [notificar eventos](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l04-notificar-eventos) e ao [sugerir eventos](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l02-sugestoes-de-eventos).                                                                         |
| USA04 | O sistema deve possuir caminhos curtos, com tarefas complexas sendo finalizadas em no máximo 7 cliques.                                   |
| USA05 | O sistema deve fornecer no mínimo as quatro principais formas de pagamentos: Boleto Bancário, Pix, Cartão de crédito e Cartão de débito. |
| USA06 | O sistema deve evitar que o [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) realize passos repetitivos.                                                                          |

</center>

<font size="3"><p style="text-align: center">Fonte: [Matheus Henrique](https://github.com/mathonaut).</p></font>

## Confiabilidade

Envolvem garantir que o sistema funcione de maneira previsível e sem falhas críticas. Eles incluem alta disponibilidade para minimizar interrupções, precisão nos resultados das operações, previsibilidade no comportamento das funcionalidades, baixa frequência de falhas e mecanismos eficientes de recuperação em caso de paradas completas ou falhas inesperadas.

Para essa categoria os requisitos identificados estão representados na tabela 2 a seguir.

<font><p style="text-align: center">**Tabela 2** - Requisitos de Confiabilidade.</p></font>

<center>

| ID    | Descrição                                                                                                                         |
| ----- | --------------------------------------------------------------------------------------------------------------------------------- |
| CON01 | O sistema deve ser acessível 24 horas por dia, 7 dias por semana.                                                                 |
| CON02 | O sistema deve possuir as informações atualizadas e condizentes com a realidade.                                                  |
| CON03 | O sistema deve manter íntegra as informações sobre o [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) e seus meios de pagamentos.                                          |
| CON04 | O sistema deve seguir a Lei Geral de Proteção de Dados (LGPD).                                                                    |
| CON05 | O sistema deve permitir que o [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) se recupere de problemas e erros com no máximo 3 cliques.                                   |
| CON06 | O sistema deve deixar claro e de fácil acesso toda e qualquer informação sobre taxas aplicada aos [usuários](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario).                       |
| CON07 | O sistema deve possuir backups dos dados dos [usuários](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) e eventos.                                                                  |
| CON08 | O sistema deve impedir que o [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) realize atividades que possa colocar a integridade do sistema e de outros usuários em risco. |
| CON09 | O sistema deve ser distribuído em diversos servidores.                                                                            |

</center>

<font size="3"><p style="text-align: center">Fonte: [Matheus Henrique](https://github.com/mathonaut).</p></font>

## Desempenho

Abrangem aspectos relacionados à eficiência do sistema em condições de operação. Eles incluem alta taxa de transferência de informações, tempos de resposta rápidos e consistentes, e uso otimizado de recursos computacionais como memória, processamento e rede, mesmo em situações de alta demanda.

Para essa categoria os requisitos identificados estão representados na tabela 3 a seguir.

<font><p style="text-align: center">**Tabela 3** - Requisitos de Desempenho.</p></font>

| ID    | Descrição                                                                                          |
| ----- | -------------------------------------------------------------------------------------------------- |
| DES01 | O sistema deve, mostrar como padrão no máximo 20 eventos por página, por exemplo, ao fazer uma busca com [filtragem de eventos](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos).                               |
| DES02 | O sistema não deve ter um tempo de resposta superior a 200ms.                                      |
| DES03 | O sistema deve permitir mais de 1 milhão requisições por segundo.                                  |
| DES04 | O sistema deve possuir uma navegação fluida, sem engasgo e caminhos seguindo uma sequência lógica. |
| DES05 | O sistema deve possuir uma interface leve, com no máximo 30 elementos na tela de uma vez.          |

<font size="3"><p style="text-align: center">Fonte: [Matheus Henrique](https://github.com/mathonaut).</p></font>

## Suportabilidade

dizem respeito à capacidade do sistema de se adaptar e ser mantido ao longo do tempo. Eles incluem compatibilidade com diferentes ambientes de hardware e software, facilidade de teste e depuração, capacidade de adaptação às mudanças, simplicidade na manutenção e configuração, processos claros de instalação e escalabilidade para suportar o crescimento em volume de usuários ou dados, além de ferramentas para localização e solução de problemas.

Para essa categoria os requisitos identificados estão representados na tabela 4 a seguir.

<font><p style="text-align: center">**Tabela 4** - Requisitos de Suportabilidade.</p></font>

| ID    | Descrição                                                                                                                                                                                                                                                                  |
| ----- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| SUP01 | O sistema deve possuir uma documentação separada em tópicos (ao menos 10 tópicos principais) e que apresente grande parte das dúvidas mais frequentes.                                                                                                                                                                        |
| SUP02 | O sistema deve possuir uma facilidade de manutenção através de uma estrutura modular e código bem organizado.                                                                                                                                                              |
| SUP03 | O sistema deve possuir uma capacidade de extensão para adicionar novas funcionalidades e acompanhar as mudanças.                                                                                                                                                           |
| SUP04 | O sistema deve possuir uma facilidade de atualização com processos eficientes (de até 200ms) e sem interrupções significativas, que ultrapassem o tempo limite de resposta.                                                                                                                                                           |
| SUP05 | O sistema deve possuir um suporte ao [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) com canais adequados de suporte e equipe disponível.                                                                                                                                                                          |
| SUP06 | O sistema deve possuir uma testabilidade, com facilidade de realização de testes durante o desenvolvimento e a manutenção.                                                                                                                                                 |
| SUP07 | O sistema deve possuir uma rastreabilidade com mecanismos para registrar e rastrear mudanças e correções ao longo do tempo, incluindo controle de versão e registros de alterações.                                                                                        |
| SUP08 | O sistema deve possuir uma tolerância a falhas para garantir que o sistema possa lidar com falhas adequadamente, por meio de mecanismos de recuperação, detecção de falhas, manutenção da integridade dos dados, backups regulares e restauração rápida em caso de falhas. |

<font size="3"><p style="text-align: center">Fonte: [Rafael Ferreira](https://github.com/RafaelCLG0).</p></font>
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



</center>
