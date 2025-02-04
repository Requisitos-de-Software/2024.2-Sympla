# Validação do Protótipo

## Introdução

Os protótipos são essenciais para externalizar as ideias acerca de um produto antes de sua concepção em si. Dessa forma, neste documento são apresentados os protótipos das funcionalidades que não foram implementadas no Sympla. Cada integrante escolheu um dos requisitos elicitados não implementados para desenvolver, a relação pode ser visualizada na Tabela 1, e em seguida validaram por meio de entrevistas cada um dos protótipos desenvolvidos.

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 1</b> - Requisitos funcionais e não funcionais</p>

| Tipo  | Descrição                                                                                                      | <a id="anchor_GERAL" style="color:black;">ID</a> | Implementado |
|-------|--------------------------------------------------------------------------------------------------------------|---------------------------------------|--------------|
| <a id="RF32"></a>RF32  | O usuário é capaz de mudar o idioma do app.                                                       |  <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS13 </a> | Não          |
| RF33  | O usuário é capaz de entrar na aba de configurações.                                              |  <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS14 </a> | Não          |
| RF34  | O sistema apresenta uma aba de acessibilidades.                                                   | <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF"> IS15 </a> | Não          |
| <a id="RF35"></a>RF35   | O usuário é capaz de criar preferências de eventos.                                               |  <a href="../../elicitacao/tecnicas/introspeccao/#anchor_ISF">IS16 </a> | Não          |
| RF36  | Deve ser possível cadastrar diferentes métodos de pagamento.                                               |  <a href="../../elicitacao/tecnicas/entrevista2/#anchor_2ENT">2ENT11</a>  | Não          |


<font size="2"><p style="text-align: center">Fonte: <a href="https://github.com/rafgpereira">Rafael Pereira, 2025</a></p></font>


## Metodologia 

Neste trabalho, elaboramos seis protótipos de altas fidelidade, cada uma baseada nos requisitos não implementados. A criação dos protótipos ocorreu por meio da plataforma Figma, permitindo desenvolver interfaces dinâmicas e testar interações de navegação. 


Depois de desenvolver os protótipos, conduzimos seis entrevistas com usuários reais. Essas conversas proporcionaram insights valiosos sobre a usabilidade das novas funcionalidades, a clareza de seu funcionamento e a eficiência do design sugerido, auxiliando na validação dos requisitos estabelecidos.

### Protótipos

#### Menu de Acessibilidades


<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://embed.figma.com/proto/ts3p3lrlslUWDIlsDnGfmk/PrototipoSympla?node-id=45-84&p=f&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=45%3A84&embed-host=share" allowfullscreen></iframe>

<font size="3"><p style="text-align: center">Fonte: [Renan Araújo](https://github.com/renantfm4).</p></font>

### Idiomas

O objetivo desse protótipo é implementar o [requisito funcional 32](../elicitacao/requisitos/requisitos_elicitados.md#RF32), dessa forma o usuário será capaz de alterar o idioma do app Sympla facilmente.


#### Protótipo RF32

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://embed.figma.com/proto/1UiLbBh3SgAvJt5ZaENqPb/Untitled?node-id=8-3&p=f&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=8%3A3&embed-host=share" allowfullscreen></iframe>
<font size="3"><p style="text-align: center">Fonte: [Milena Rocha](https://github.com/MilenaFRocha).</p></font>

### Preferências de eventos 

O objetivo desse protótipo é implementar o [requisito funcional 35](../elicitacao/requisitos/requisitos_elicitados.md#RF35), dessa forma o usuário será capaz de ter um conteúdo personalizado, mostrando eventos de preferência sem que haja eventos não coesos poluindo a tela



#### Protótipo RF35

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://embed.figma.com/proto/7yZrYZDpvNC6dO9PNN6giT/Figma---Sympla?node-id=3-4&starting-point-node-id=3%3A4&embed-host=share" allowfullscreen></iframe>
<font size="3"><p style="text-align: center">Fonte: [Gabriel Scheidt](https://github.com/Gxaite).</p></font>



### Entrevistas

#### Entrevista 1

Essa entrevista tem como objetivo validar o protótipo referente ao [Requisito Funcional 34](../elicitacao/requisitos/requisitos_elicitados.md#RF34) pelo usuário Gustavo que concordou em disponibilizar sua voz e imagem para fins acadêmicos por meio do [termo de consentimento](../assets/Termo_Gustavo.pdf) 

<div align="center">
<font size="3"><p style="text-align: center">Tabela 1: Cronograma de entrevista</p></font>
</div>

| **Data**  | **Hora** | **Entrevistador** | **Entrevistado** | **Duração** | **Local**                  |
|------------|-------|--------------------|------------------|-------------|---------------------------|
| 03/02/2025 | 11:00 | [Renan Araújo](https://github.com/renantfm4)        | Renan Araújo   | 07:38       | Presencial - FGA|

<font size="3"><p style="text-align: center">Fonte: [Renan Araújo](https://github.com/renantfm4), 2025.<p><font>

<p style="text-align: center"><a href="https://www.youtube.com/embed/Np9O2gWoQ4U" target="blanket">Vídeo 1 - Entrevista Gustavo</a></p>

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/Np9O2gWoQ4U"></iframe></p>

#### FeedBack

O Gustavo de maneira geral gostou do protótipo, citou que nunca tinha visto algumas das funcionalidades de acessibilidades em aplicativos que ele usou, citou que as telas estão bem intuitivas e fácil pro usuário, mas chamou a atenção na funcionalidade de dessaturação que poderia mudar as cores das letras para ficar mais visível em relação ao fundo da tela.

<font size="3"><p style="text-align: center">Fonte: [Renan Araújo](https://github.com/renantfm4), 2025.</p></font>

#### Entrevista 2

Essa entrevista tem como objetivo validar o protótipo referente ao [Requisito Funcional 32](../elicitacao/requisitos/requisitos_elicitados.md#RF32) pelo usuário Vinicíus que concordou em disponibilizar sua voz e imagem para fins acadêmicos por meio do [termo de consentimento](../assets/termo_vinicius.pdf) 

<div align="center">
<font size="3"><p style="text-align: center">Tabela 1: Cronograma de entrevista</p></font>
</div>

| **Data**  | **Hora** | **Entrevistador** | **Entrevistado** | **Duração** | **Local**                  |
|------------|-------|--------------------|------------------|-------------|---------------------------|
| 02/02/2025 | 14:00 | [Milena Rocha](https://github.com/MilenaFRocha)        | Vinicius Fernandes   | 12:00       | Presencial - Vicente Pires |

<font size="3"><p style="text-align: center">Fonte: [Milena Rocha](https://github.com/MilenaFRocha), 2025.<p><font>


#### Entrevista 3

Essa entrevista tem como objetivo validar o protótipo referente ao [Requisito Funcional 35](../elicitacao/requisitos/requisitos_elicitados.md#RF35) pelo usuário Vinicíus que concordou em disponibilizar sua voz e imagem para fins acadêmicos por meio do [termo de consentimento](../assets/termo_vinicius.pdf) 

<div align="center">
<font size="3"><p style="text-align: center">Tabela 2: Cronograma de entrevista</p></font>
</div>

| **Data**  | **Hora** | **Entrevistador** | **Entrevistado** | **Duração** | **Local**                  |
|------------|-------|--------------------|------------------|-------------|---------------------------|
| 02/02/2025 | 14:00 | [Milena Rocha](https://github.com/MilenaFRocha)        | Vinicius Fernandes   | 12:10       | Presencial - Vicente Pires |

<font size="3"><p style="text-align: center">Fonte: [Milena Rocha](https://github.com/MilenaFRocha), 2025.<p><font>

<iframe width="560" height="315" src="https://www.youtube.com/embed/RZmXiJdhQRM?si=tBF61PraN-MYpPdL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></

#### FeedBack

O Vinicius falou que gostou bastante da implementação do requisito de preferência de eventos, porque deixou a tela mais limpa e também agilizou na hora da busca. Ele achou que isso melhorou bastante a experiência.

<font size="3"><p style="text-align: center">Fonte: [Milena Rocha](https://github.com/MilenaFRocha), 2025.</p></font>

## Histórico de Versões

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     | 
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|
|  1.0   | Criação desse documento | [Milena Rocha](https://github.com/MilenaFRocha)  | 30/01/2025 | [Victor Hugo](https://github.com/VHbernardes) |
|  1.1   | Entrevista | [Renan Araújo](https://github.com/renantfm4)  | 03/02/2025 | |
|  1.2   | Protótipo e entrevista |[Milena Rocha](https://github.com/MilenaFRocha)   | 03/02/2025 | [Victor Hugo]|