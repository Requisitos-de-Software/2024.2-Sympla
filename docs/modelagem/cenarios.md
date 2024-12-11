## Introdução 

Os cenários, para a modelagem de requisitos, são descrições detalhadas, que retratam situações ou eventos envolvendo atores. Eles são importantes para compreender como os ambientes, sistemas e atores interagem entre si, oferecendo uma visão de como o sistema deve se comportar em diferentes situações, seus fluxos e reações.

## Metodologia

A metodologia utilizada para a criação dos cenários foi baseada nos requisitos previamente elicitados e priorizados. A partir desses requisitos, selecionamos 9 requisitos de alta prioridade, onde foram priorizados pelo método [Three Level Scale](https://requisitos-de-software.github.io/2024.2-Sympla/elicitacao/priorizacao/three_level_scale/) e trabalhamos nossos cenários neles, estruturando-os para refletir os processos e fluxos de interação dos usuários com o sistema, assegurando que todas as situações relevantes fossem contempladas. Os nossos cenários criados em cima do aplicativo [Sympla](https://requisitos-de-software.github.io/2024.2-Sympla/planejamento/aplicativo_selecionado/) estão organizados abaixo, nas tabelas de 1 a 9.
## Cenários

### Cenário 1 - Criação da conta no Sympla

Na tabela 1 abaixo, nosso primeiro cenário aborda a história onde o usuário irá criar uma conta no Sympla para começar a utilizar a plataforma.

<font size="3"><p style="text-align: center">Tabela 1: Criação da conta no Sympla</p></font>

| **Cenário 1** |
|---------------|
| **Título**    |
| Usuário vai criar uma conta no Sympla. |
| **Objetivo**  |
| Permitir que o usuário crie uma conta para acessar o Sympla e realizar suas atividades. |
| **Contexto**  |
| <p>**Local:** Aplicativo Sympla em um smartphone ou versão web do Sympla.</p> <p>**Tempo:** Durante o processo de criação de conta, o tempo estimado é de 5 a 10 minutos.</p> <p>**Pré-condições:** O usuário deve ter acesso à internet e um e-mail válido.</p> |
| **Atores**    |
| Usuário |
| **Recursos**  |
| <p>Internet.</p><p>Informações do usuário (nome, e-mail, senha).</p> |
| **Episódios** |
| <p>O usuário abre o aplicativo Sympla ou acessa a versão web do Sympla.</p> <p>O usuário seleciona a opção de "Criar conta" ou "Cadastrar-se".</p> <p>O aplicativo ou a versão web solicita o preenchimento dos campos necessários, como nome, e-mail e senha.</p> <p>O usuário preenche as informações e clica em "Criar conta".</p> <p>O sistema valida as informações fornecidas e envia um e-mail de confirmação.</p> <p>O usuário acessa seu e-mail e confirma a criação da conta.</p> <p>O sistema finaliza o processo de criação da conta e redireciona o usuário para a tela inicial do aplicativo ou página de boas-vindas.</p> |
| **Restrições**|
| <p>O e-mail fornecido deve ser válido e não pode estar cadastrado em outra conta.</p><p>A senha deve atender aos requisitos de segurança (mínimo de 8 caracteres, incluindo letras e números).</p> |
| **Exceção**   |
| <p>Se o e-mail já estiver cadastrado, o sistema deve exibir uma mensagem informando que o e-mail não pode ser utilizado.</p><p>Se a senha não atender aos requisitos de segurança, o sistema deve informar ao usuário para criar uma senha mais forte.</p><p>Se o usuário não receber o e-mail de confirmação, o sistema deve 

<font size="3"><p style="text-align: center"><b>Fonte:</b> Elaborado por <a href="https://github.com/VHbernardes">Victor Hugo</a>, 2024</p></font>

### Cenário 2 - Edição de perfil do usuário

Na tabela 2 abaixo, nosso segundo cenário aborda uma história onde o usuário irá editar seu perfil no Sympla.

<font size="3"><p style="text-align: center">Tabela 2: Edição de perfil do usuário</p></font>

| **Cenário 2** |
|---------------|
| **Título**    |
| Usuário vai editar seu perfil. |
| **Objetivo**  |
| Permitir que o usuário atualize suas informações pessoais no perfil do Sympla. |
| **Contexto**  |
| <p>**Local:** Aplicativo Sympla em um smartphone ou versão web do Sympla.</p> <p>**Tempo:** Durante o uso do aplicativo ou da versão web, enquanto o usuário deseja atualizar suas informações pessoais.</p> <p>**Pré-condições:** O usuário deve estar logado no Sympla e ter uma conta ativa.</p> |
| **Atores**    |
| Usuário |
| **Recursos**  |
| <p>Internet.</p><p>Informações de perfil (nome, e-mail, foto, etc.).</p> |
| **Episódios** |
| <p>O usuário abre o aplicativo Sympla ou acessa a versão web do Sympla.</p> <p>O usuário localiza a opção "Meu Perfil" ou "Configurações" no menu.</p> <p>O usuário seleciona a opção de editar seu perfil.</p> <p>O sistema exibe um formulário com os campos de informações do perfil, como nome, e-mail, telefone, foto, etc.</p> <p>O usuário edita as informações desejadas (como nome, foto, ou e-mail).</p> <p>O usuário confirma as alterações clicando em "Salvar" ou "Atualizar".</p> <p>O sistema valida as informações inseridas (ex: formato correto de e-mail, senha forte, etc.).</p> <p>Se as informações forem válidas, o sistema salva as alterações e exibe uma mensagem de confirmação.</p> <p>O usuário pode visualizar seu perfil atualizado com as novas informações.</p> |
| **Restrições**|
| <p>O usuário só pode editar informações que não sejam essenciais para a autenticidade da conta (ex: e-mail ou senha).</p><p>As alterações no e-mail ou senha podem exigir uma confirmação adicional via e-mail ou SMS para garantir a segurança da conta.</p> |
| **Exceção**   |
| <p>Se o usuário inserir dados inválidos, o sistema deve exibir uma mensagem de erro e solicitar que os dados sejam corrigidos.</p><p>Se houver problemas de conexão com a internet, o sistema deve exibir uma mensagem de erro e pedir para o usuário tentar novamente.</p> |

<font size="3"><p style="text-align: center"><b>Fonte:</b> Elaborado por <a href="https://github.com/VHbernardes">Victor Hugo</a>, 2024</p></font>

### Cenário 3 - Contato com o suporte

Na tabela 3 abaixo, nosso terceiro cenário aborda uma história onde o usuário irá entrar em contato com o suporte do Sympla.

<font size="3"><p style="text-align: center">Tabela 3: Contato com o suporte</p></font>

| **Cenário 3** |
|---------------|
| **Título**    |
| Usuário vai entrar em contato com o suporte. |
| **Objetivo**  |
| Permitir que o usuário entre em contato com o suporte do Sympla para resolver problemas ou esclarecer dúvidas. |
| **Contexto**  |
| <p>**Local:** Aplicativo Sympla em um smartphone ou versão web do Sympla.</p> <p>**Tempo:** Durante o uso do aplicativo ou da versão web, quando o usuário precisar de ajuda ou tiver dúvidas relacionadas ao Sympla.</p> <p>**Pré-condições:** O usuário deve estar logado no Sympla e ter acesso à funcionalidade de suporte.</p> |
| **Atores**    |
| Usuário |
| **Recursos**  |
| <p>Internet.</p><p>Funcionalidade de contato com o suporte (chat, formulário de contato, e-mail, etc.).</p> |
| **Episódios** |
| <p>O usuário abre o aplicativo Sympla ou acessa a versão web do Sympla.</p> <p>O usuário localiza a opção de "Suporte" ou "Fale Conosco" no menu de configurações ou na tela inicial.</p> <p>O usuário seleciona a opção de contato com o suporte.</p> <p>O sistema exibe as opções de contato disponíveis (chat ao vivo, formulário de e-mail, telefone, etc.).</p> <p>O usuário escolhe a forma de contato preferida (por exemplo, chat ao vivo ou enviar um e-mail).</p> <p>Se o usuário escolher o chat, o sistema conecta o usuário a um atendente ou bot de suporte.</p> <p>Se o usuário optar pelo envio de e-mail, o sistema exibe um formulário para o usuário descrever o problema ou dúvida.</p> <p>O usuário descreve sua dúvida ou problema e envia a mensagem ao suporte.</p> <p>O sistema confirma o envio e exibe uma mensagem de agradecimento, informando o prazo de resposta ou o acompanhamento do atendimento.</p> |
| **Restrições**|
| <p>O usuário deve estar logado no Sympla para acessar a funcionalidade de suporte.</p><p>O suporte pode ter horários de funcionamento específicos, dependendo da disponibilidade da equipe.</p> |
| **Exceção**   |
| <p>Se houver problemas de conexão com a internet, o sistema deve exibir uma mensagem de erro e sugerir que o usuário tente novamente mais tarde.</p><p>Se não houver atendentes disponíveis no momento, o sistema pode oferecer alternativas, como enviar um e-mail ou esperar um retorno posterior.</p> |

<font size="3"><p style="text-align: center"><b>Fonte:</b> Elaborado por <a href="https://github.com/VHbernardes">Victor Hugo</a>, 2024</p></font>


### Cenário 4 - Pesquisa de evento filtrando por município ou estado

Na tabela 4 abaixo, nosso quarto cenário aborda uma história onde o usuário irá realizar uma pesquisa de evento filtrando por município ou estado.

<font size="3"><p style="text-align: center">Tabela 4: Pesquisa de evento filtrando por município ou estado</p></font>

| **Cenário 4** |
|---------------|
| **Título**    |
| Usuário vai fazer uma pesquisa de evento filtrando por município ou estado. |
| **Objetivo**  |
| Permitir que o usuário encontre eventos específicos filtrando por município ou estado. |
| **Contexto**  |
| <p>**Local:** Aplicativo Sympla em um smartphone ou versão web do Sympla.</p> <p>**Tempo:** Durante o uso do aplicativo ou da versão web, enquanto o usuário deseja procurar por eventos em uma localidade específica.</p> <p>**Pré-condições:** O usuário deve ter o aplicativo Sympla instalado ou estar acessando a versão web, uma conexão à internet estável e os eventos devem estar devidamente cadastrados com a informação de município ou estado.</p> |
| **Atores**    |
| Usuário |
| **Recursos**  |
| <p>Internet.</p><p>Funcionalidade de pesquisa com filtro por município ou estado no aplicativo Sympla ou versão web.</p> |
| **Episódios** |
| <p>O usuário abre o aplicativo Sympla ou acessa a versão web do Sympla.</p> <p>O usuário localiza a barra de pesquisa na tela inicial do aplicativo ou na versão web.</p> <p>O usuário seleciona a opção para filtrar eventos por município ou estado.</p> <p>O aplicativo ou a versão web exibe uma lista de estados, municípios e regiões disponíveis para seleção.</p> <p>O usuário escolhe o município ou estado desejado.</p> <p>O aplicativo ou a versão web exibe uma lista de eventos disponíveis para a localidade selecionada.</p> <p>O usuário seleciona o evento desejado da lista de resultados.</p> <p>O aplicativo ou a versão web exibe a página de detalhes do evento selecionado.</p> |
| **Restrições**|
| <p>O usuário só pode filtrar eventos por municípios, estados ou regiões onde há eventos cadastrados.</p><p>Os resultados da pesquisa dependem dos dados atualizados dos eventos no sistema, incluindo a localidade.</p> |
| **Exceção**   |
| <p>Se não houver eventos para o município ou estado selecionado.</p><p>Se houver problemas de conexão com a internet.</p><p>O sistema apresenta falhas ou está fora do ar.</p> |

<font size="3"><p style="text-align: center"><b>Fonte:</b> Elaborado por <a href="https://github.com/VHbernardes">Victor Hugo</a>, 2024</p></font>


### Cenário 5 - Pesquisa de evento filtrando por data

Na tabela 5 abaixo, nosso quinto cenário aborda uma história onde o usuário irá realizar uma pesquisa de evento filtrando por data.

<font size="3"><p style="text-align: center">Tabela 5: Pesquisa de evento filtrando por data</p></font>

| **Cenário 5** |
|---------------|
| **Título**    |
| Usuário vai fazer uma pesquisa de evento filtrando por data. |
| **Objetivo**  |
| Permitir que o usuário encontre eventos específicos filtrando por data. |
| **Contexto**  |
| <p>**Local:** Aplicativo Sympla em um smartphone ou versão web do Sympla.</p> <p>**Tempo:** Durante o uso do aplicativo ou da versão web, enquanto o usuário deseja procurar por eventos em uma data específica.</p> <p>**Pré-condições:** O usuário deve ter o aplicativo Sympla instalado ou estar acessando a versão web, uma conexão à internet estável e os eventos devem estar devidamente cadastrados com a informação de data.</p> |
| **Atores**    |
| Usuário |
| **Recursos**  |
| <p>Internet.</p><p>Funcionalidade de pesquisa com filtro por data no aplicativo Sympla ou versão web.</p> |
| **Episódios** |
| <p>O usuário abre o aplicativo Sympla ou acessa a versão web do Sympla.</p> <p>O usuário localiza a barra de pesquisa na tela inicial do aplicativo ou na versão web.</p> <p>O usuário seleciona a opção para filtrar eventos por data.</p> <p>O aplicativo ou a versão web exibe um calendário ou uma lista de intervalos de datas disponíveis para seleção.</p> <p>O usuário escolhe a data ou o intervalo de datas desejado.</p> <p>O aplicativo ou a versão web exibe uma lista de eventos disponíveis para a data selecionada.</p> <p>O usuário seleciona o evento desejado da lista de resultados.</p> <p>O aplicativo ou a versão web exibe a página de detalhes do evento selecionado.</p> |
| **Restrições**|
| <p>O usuário só pode filtrar eventos por datas onde há eventos cadastrados.</p><p>Os resultados da pesquisa dependem dos dados atualizados dos eventos no sistema, incluindo a data.</p> |
| **Exceção**   |
| <p>Se não houver eventos para a data selecionada.</p><p>Se houver problemas de conexão com a internet.</p><p></p> O sistema apresenta falhas ou está fora do ar. |

<font size="3"><p style="text-align: center"><b>Fonte:</b> Elaborado por <a href="https://github.com/VHbernardes">Victor Hugo</a>, 2024</p></font>


### Cenário 6 - Favoritar um evento

Na tabela 6 abaixo, nosso sexto cenário aborda uma história onde o usuário irá favoritar um evento.

<font size="3"><p style="text-align: center">Tabela 6: Favoritar um evento</p></font>

| **Cenário 6** |
|---------------|
| **Título**    |
| Usuário vai favoritar um evento. |
| **Objetivo**  |
| Permitir que o usuário adicione um evento à sua lista de favoritos. |
| **Contexto**  |
| <p>**Local:** Aplicativo Sympla em um smartphone ou versão web do Sympla.</p> <p>**Tempo:** Durante o uso do aplicativo ou da versão web, enquanto o usuário deseja adicionar um evento aos favoritos.</p> <p>**Pré-condições:** O usuário deve ter o aplicativo Sympla instalado ou estar acessando a versão web, uma conexão à internet estável, e o usuário deve estar logado na sua conta.</p> |
| **Atores**    |
| Usuário |
| **Recursos**  |
| <p>Internet.</p><p>Funcionalidade de favoritar no aplicativo Sympla ou versão web.</p> |
| **Episódios** |
| <p>O usuário abre o aplicativo Sympla ou acessa a versão web do Sympla.</p> <p>O usuário localiza o evento que deseja favoritar.</p> <p>O usuário clica no ícone de favoritar (estrela, coração, etc.) ao lado do evento.</p> <p>O aplicativo ou a versão web adiciona o evento à lista de favoritos do usuário.</p> <p>O usuário pode acessar a lista de eventos favoritos na seção de favoritos do aplicativo ou versão web.</p> |
| **Restrições**|
| <p>O usuário precisa estar logado na sua conta para poder favoritar eventos.</p><p>O evento deve estar disponível e visível para o usuário.</p> |
| **Exceção**   |
| <p>Se houver problemas de conexão com a internet.</p></p><p></p> O sistema apresenta falhas ou está fora do ar. |

<font size="3"><p style="text-align: center"><b>Fonte:</b> Elaborado por <a href="https://github.com/VHbernardes">Victor Hugo</a>, 2024</p></font>

### Cenário 7 - Adicionar um método de pagamento à sua conta

Na tabela 7 abaixo, nosso sétimo cenário aborda uma história onde o usuário irá adicionar um método de pagamento à sua conta.

<font size="3"><p style="text-align: center">Tabela 7: Adicionar um método de pagamento à sua conta</p></font>

| **Cenário 7** |
|---------------|
| **Título**    |
| Usuário vai adicionar um método de pagamento à sua conta. |
| **Objetivo**  |
| Permitir que o usuário adicione um método de pagamento válido à sua conta no Sympla para facilitar futuras compras. |
| **Contexto**  |
| <p>**Local:** Aplicativo Sympla em um smartphone ou versão web do Sympla.</p> <p>**Tempo:** Durante o uso do aplicativo ou da versão web, enquanto o usuário deseja adicionar um método de pagamento à sua conta.</p> <p>**Pré-condições:** O usuário deve ter o aplicativo Sympla instalado ou estar acessando a versão web, estar logado na sua conta e ter uma conexão à internet estável.</p> |
| **Atores**    |
| Usuário |
| **Recursos**  |
| <p>Internet.</p><p>Funcionalidade de adicionar método de pagamento no aplicativo Sympla ou versão web.</p> |
| **Episódios** |
| <p>O usuário abre o aplicativo Sympla ou acessa a versão web do Sympla.</p> <p>O usuário vai até a seção de configurações ou perfil.</p> <p>O usuário seleciona a opção "Adicionar método de pagamento".</p> <p>O aplicativo ou a versão web solicita os dados do método de pagamento (cartão de crédito, débito, boleto, etc.).</p> <p>O usuário insere as informações do cartão ou outro método de pagamento (nome, número do cartão, data de validade, código de segurança, etc.).</p> <p>O usuário confirma a adição do método de pagamento.</p> <p>O sistema valida as informações do método de pagamento e adiciona esse método à conta do usuário.</p> <p>O usuário pode ver o método de pagamento adicionado na seção de pagamentos ou perfil.</p> |
| **Restrições**|
| <p>O usuário precisa estar logado para adicionar um método de pagamento.</p><p>O método de pagamento deve ser válido e aceito pelo sistema.</p> |
| **Exceção**   |
| <p>Se as informações do método de pagamento estiverem incorretas (cartão inválido, dados errados).</p><p>Se houver problemas de conexão com a internet.</p> |

<font size="3"><p style="text-align: center"><b>Fonte:</b> Elaborado por <a href="https://github.com/VHbernardes">Victor Hugo</a>, 2024</p></font>



### Cenário 8 - Efetuar uma compra do ingresso

Na tabela 8 abaixo, nosso oitavo cenário aborda uma história onde o usuário irá efetuar uma compra do ingresso.

<font size="3"><p style="text-align: center">Tabela 8: Efetuar uma compra do ingresso</p></font>

| **Cenário 8** |
|---------------|
| **Título**    |
| Usuário vai comprar ingresso. |
| **Objetivo**  |
| Adquirir um ingresso para um evento no Sympla. |
| **Contexto**  |
| <p>**Local:** Aplicativo Sympla em um smartphone.</p> <p>**Tempo:** Durante o período de venda do evento.</p> <p>**Pré-condições:** O usuário deve estar logado no Sympla, o evento precisa estar disponível e o usuário deve ter um método de pagamento válido.</p> |
| **Atores**    |
| Usuário |
| **Recursos**  |
| <p>Internet.</p><p>Informações do evento (tipos de ingressos, valores, descrições).</p><p>Método de pagamento.</p> |
| **Episódios** |
| <p>O usuário abre o aplicativo Sympla e localiza o evento desejado.</p> <p>O usuário acessa a página do evento e visualiza os tipos de ingressos disponíveis.</p> <p>O usuário seleciona a quantidade e o tipo de ingresso desejado.</p> <p>O usuário clica em "Comprar" e é redirecionado para a página de pagamento.</p> <p>O usuário insere as informações de pagamento e confirma a compra.</p> <p>O sistema valida o pagamento e exibe uma mensagem de confirmação.</p> <p>O ingresso é enviado para o e-mail do usuário e adicionado ao seu perfil no Sympla.</p> |
| **Restrições**|
| <p>O pagamento deve ser aprovado.</p><p>O evento deve ter ingressos disponíveis.</p><p>O sistema precisa estar online para processar a compra.</p> |
| **Exceção**   |
| <p>O pagamento é recusado (cartão inválido, saldo insuficiente).</p><p>Os ingressos se esgotam antes da confirmação da compra.</p><p>O sistema apresenta falhas ou está fora do ar.</p> |


<font size="3"><p style="text-align: center"><b>Fonte:</b> Elaborado por <a href="https://github.com/VHbernardes">Victor Hugo</a>, 2024</p></font>

### Cenário 9 - Cancelamento ou transferência de ingresso

Na tabela 9 abaixo, nosso nono cenário aborda uma história onde o usuário irá efetuar o cancelamento ou a transferência de um ingresso no Sympla.

<font size="3"><p style="text-align: center">Tabela 9: Cancelamento ou transferência de ingresso</p></font>

| **Cenário 9** |
|---------------|
| **Título**    |
| Usuário vai efetuar o cancelamento ou transferência de ingresso. |
| **Objetivo**  |
| Permitir que o usuário cancele ou transfira o ingresso adquirido para outro participante. |
| **Contexto**  |
| <p>**Local:** Aplicativo Sympla em um smartphone ou versão web do Sympla.</p> <p>**Tempo:** Durante o uso do aplicativo ou da versão web, enquanto o usuário deseja gerenciar os ingressos adquiridos.</p> <p>**Pré-condições:** O usuário deve estar logado no Sympla, ter ingressos válidos adquiridos, e o evento deve permitir o cancelamento ou transferência de ingressos.</p> |
| **Atores**    |
| Usuário |
| **Recursos**  |
| <p>Internet.</p><p>Informações do evento e ingressos adquiridos.</p> |
| **Episódios** |
| <p>O usuário abre o aplicativo Sympla ou acessa a versão web do Sympla.</p> <p>O usuário localiza a seção "Meus ingressos" ou "Ingressos adquiridos".</p> <p>O usuário seleciona o ingresso que deseja cancelar ou transferir.</p> <p>O aplicativo ou a versão web exibe as opções de cancelamento ou transferência de ingresso.</p> <p>O usuário escolhe a opção desejada: "Cancelar ingresso" ou "Transferir ingresso".</p> <p>Se o usuário escolher transferir, o sistema solicita as informações do novo participante (nome, e-mail, etc.).</p> <p>O usuário insere as informações solicitadas e confirma a ação.</p> <p>O sistema processa a ação (cancelamento ou transferência), exibe uma mensagem de confirmação e, se necessário, envia um e-mail de notificação.</p> <p>O ingresso é removido ou transferido para o novo participante conforme a opção escolhida.</p> |
| **Restrições**|
| <p>O cancelamento ou transferência de ingresso só pode ser realizado se o evento permitir essa ação.</p><p>O sistema pode estabelecer prazos ou condições para o cancelamento ou a transferência (ex: até X dias antes do evento).</p> |
| **Exceção**   |
| <p>Se o ingresso não puder ser cancelado ou transferido devido a restrições do evento ou do prazo.</p><p>Se houver problemas de conexão com a internet.</p> |

<font size="3"><p style="text-align: center"><b>Fonte:</b> Elaborado por <a href="https://github.com/VHbernardes">Victor Hugo</a>, 2024</p></font>

## **Bibliografia**

> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1. Disponível em: [https://aprender3.unb.br/pluginfile.php/2972471/mod_resource/content/2/ihc-ux-%20Personas.pdf](https://aprender3.unb.br/pluginfile.php/2972471/mod_resource/content/2/ihc-ux-%20Personas.pdf). Acesso em: 05 de Dez. de 2024.

> SERRANO, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: [https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/2972470/mod_resource/content/1/Aula%2010.pdf). Acesso em: 05 de Dez. de 2024.

> Cenários. Repositório da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: [https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/). Acesso em: 06 de Dez. 2024.


## Histórico de Versões

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     | 
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|
|  1.0   | Criação desse documento |  [Victor Hugo](https://github.com/VHbernardes) | 05/12/2024 | [Milena Rocha](https://github.com/MilenaFRocha)  |
|  1.1   | Correção pós apresentação (melhoria nos índices) |  [Victor Hugo](https://github.com/VHbernardes) | 11/12/2024 | [Milena Rocha](https://github.com/MilenaFRocha)  |





