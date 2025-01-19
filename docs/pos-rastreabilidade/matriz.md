## Introdução

A matriz de rastreabilidade de requisitos de software é um artefato essencial no processo de desenvolvimento de software, que permite o acompanhamento e a verificação da implementação dos requisitos ao longo do ciclo de vida do projeto. Este documento facilita a identificação de dependências e relações entre os requisitos, garantindo que todos os requisitos definidos sejam atendidos e que qualquer mudança seja devidamente gerenciada. A rastreabilidade assegura que o produto final esteja alinhado com as necessidades e expectativas dos stakeholders, contribuindo para a qualidade e sucesso do projeto.


## Metodologia

A Matriz de Rastreabilidade consiste na apresentação dos [requisitos elicitados](../elicitacao/requisitos/requisitos_elicitados.md) e todas as suas respectivas conexões em todos os documentos produzidos. A matriz é estruturada da seguinte forma:

- **Código**: Identifica o requisito analisado e o rastreia.
- **Tipo**: Classifica o requisito como funcional (RF) ou não funcional (RNF).
- **Descrição**: Define o requisito.
- **Pré-Rastreabilidade**: Identifica a origem da elicitação e a rastreia.
- **Implementado?**: Identifica se o requisito já está implementado (Sim ou Não).
- **Artefatos**: Identifica os artefatos que fazem referência ao requisito e os rastreiam.
- **Elos**: Conecta requisitos e artefatos nos documentos Backward-From e Forward-From.


# **Matriz de Rastreabilidade**

Na Tabela 1, visualiza-se a Matriz de Rastreabilidade, conforme foi definida anteriormente, dos requisitos do Sympla.


<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 1</b> - Matriz de Rastreabilidade Sympla</p>


| Código | Tipo | Descrição | Pré-Rastreabilidade | Implementado | Artefatos | Elos |
|--------|------|-----------|---------------------|--------------|-----------|------|
| <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF01<a/> | RF | O sistema permite filtrar eventos por Estado e Município. | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS01</a>, <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS01</a> | Sim | sd | sd |
| <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF02<a/> | RF | O sistema exibe detalhes importantes do evento, como horário de entrada e local. | <a href="../../elicitacao/tecnicas/entrevista2/#anchor_2ENT">2ENT02</a>, <a href="../../elicitacao/tecnicas/entrevista/#anchor_1ENT">1ENT03</a>, <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS16</a>, <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS02</a> | Sim | sd | sd |
| <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF03<a/> | RF | O sistema envia notificações ou lembretes sobre os eventos comprados. | REF | Sim | ART | ELO |
| <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF04<a/> | RF | O sistema fornece uma ampla variedade de eventos. | REF | Sim | ART | ELO |
| <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF05<a/> | RF | O aplicativo permite compartilhar o evento por meio das redes sociais. | REF | Sim | ART | ELO |
| <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF06<a/> | RF | Deve ser possível adicionar vários ingressos ao carrinho antes de finalizar a compra. | REF | Não | ART | ELO |
| <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF07<a/> | RF | Deve ser possível retirar vários ingressos do carrinho adicionados.	 | REF | Não | ART | ELO |
| <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF08<a/> | RF | O sistema permite cancelamento e transferências de ingressos diretamente na plataforma.	 | REF | Não | ART | ELO |
| <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF09<a/> | RF | Deve ser possível visualizar a planta do local para a escolha de assentos (quando aplicável). | REF | Sim | ART | ELO |
| <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF10<a/> | RF | O sistema disponibiliza um histórico completo das compras realizadas pelo usuário. | REF | Sim | ART | ELO |
| <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF11<a/> | RF | O sistema simplifica filas de compra. | REF | Não | ART | ELO |
| <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF12<a/> | RF | O usuário deve permanecer logado por um tempo determinado para não precisar relogar frequentemente. | REF | Não | ART | ELO |
| <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF13<a/> | RF | O aplicativo fornece uma funcionalidade de busca eficiente para facilitar a localização dos produtos. | REF | Sim | ART | ELO |
| <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF14<a/> | RF | O aplicativo permite a escolha da quantidade de ingressos que o usuário deseja comprar. | REF | Sim | ART | ELO |
| <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF15<a/> | RF | O aplicativo permite selecionar poltronas para pessoas idosas, crianças, obesas ou com deficiência, caso existam. | REF | Sim | ART | ELO |
| <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF16<a/> | RF | O aplicativo permite selecionar as poltronas especiais. | REF | Sim | ART | ELO |
| <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF17<a/> | RF | Na seleção de ingresso, o aplicativo permite adicionar um cupom de desconto. | REF | Sim | ART | ELO |
| <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF18<a/> | RF | O aplicativo permite a doação por parte do usuário para fundações. | REF | Sim | ART | ELO |
| <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF19<a/> | RF | O aplicativo permite a realização da compra dos ingressos.	 | REF | Sim | ART | ELO |
| <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF20<a/> | RF | O aplicativo possui uma função para entrar em contato com o suporte. | REF | Sim | ART | ELO |
| <a href="../../elicitacao/requisitos/requisitos_elicitados/#anchor_GERAL">RF21<a/> | RF | O aplicativo permite ao usuário alterar seus dados. | REF | Sim | ART | ELO |


