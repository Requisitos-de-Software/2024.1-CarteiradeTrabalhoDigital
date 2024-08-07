# História de Usuário

## Sumário
* [Introdução](#Introdução)
* [Definição das Histórias dos Usuários](#Definição-das-Histórias-dos-Usuários)
* [Motivações e Objetivos](#Motivações-e-Objetivos)
* [Metodologia](#Metodologia)
* [Template](#Template)
* [Histórias de Usuários](#Histórias-de-Usuários)
* [Participantes](#Participantes)
* [Validação com Usuário](#Validação-com-Usuário)
* [Observações do Usuário](#Observações-do-Usuário)
* [Conclusão](#Conclusão)
* [Referências Bibliográficas](#Referências-Bibliográficas)
* [Bibliografia](#Bibliografia)
* [Histórico de Versão](#Histórico-de-Versão)

## Introdução

No desenvolvimento de um sistema, compreender as necessidades dos usuários e dos clientes é essencial para o sucesso de um projeto e uma bordagem amplamente adotada para capturar e comunicar essas necessidades são as histórias de usuário. Assim, este artefato apresenta as histórias de usuário trabalhadas pela equipe durante o desenvolvimento desse projeto sobre o aplicativo da Carteira de Trabalho Digital. Isso porque, como foi explicado, as histórias de usuário são essenciais para garantir que a execução do projeto esteja alinhada com as necessidades reais dos usuários. Desse modo, este documento visa detalhar as motivações, os objetivos e a metodologia adotada para a criação dessas histórias, além de apresentar as histórias de usuário padronizadas e validadas por um usuário.

## Definição das Histórias dos Usuários

Segundo o artigo "[Combinando Design Participativo e História de Usuários para Levantamento de Funcionalidades no OpenDesign](https://www.ic.unicamp.br/~reltech/2018/18-12.pdf)"¹, as histórias de usuário são descrições concisas das funcionalidades de um sistema vistas do ponto de vista do usuário final. Assim, elas são utilizadas para expressar as necessidades e os requisitos de software de forma compreensível e centrada no usuário. Segundo Cohn (2004), citado no mesmo artigo "[Combinando Design Participativo e História de Usuários para Levantamento de Funcionalidades no OpenDesign](https://www.ic.unicamp.br/~reltech/2018/18-12.pdf)"¹, uma história de usuário é composta por três aspectos principais:

- **Cartão(card)**: Uma descrição escrita da história, geralmente utilizada para planejamento ou como lembrete.

- **Conversa (Converation)**: Diálogos informais que detalham a história, permitindo esclarecer pontos e responder a dúvidas.

- **Confirmação(confirmation)**: Testes escritos que documentam os detalhes da história e permitem verificar se ela foi implementada corretamente.

Portanto, para facilitar a elaboração de cartões de histórias de usuário, Cohn (2004) propôs um modelo que destaca os diferentes papéis ou tipos de usuários envolvidos e o valor que cada papel agrega à funcionalidade desejada, mais precisamente, ao objetivo a ser alcançado. Dessa forma, o formato sugerido é: "Eu, como um (tipo de usuário), gostaria de (funcionalidade/objetivo), para que (benefício de negócio)". Esse modelo pode ser adotado para descrever as histórias nos cartões.

## Motivações e Objetivos

No contexto do projeto da Carteira de Trabalho Digital, a utilização de histórias de usuário é motivada pela necessidade de desenvolver uma solução centrada nas necessidades reais dos usuários envolvidos, uma vez que a Carteira de Trabalho Digital visa modernizar e simplificar o processo de emissão e gerenciamento da carteira de trabalho com o intuito de facilitar a vida dos cidadãos neste contexto.

Desse modo, a motivação para adotar as histórias de usuário reside na capacidade dessa abordagem em capturar de concisamente as expectativas, os desejos e as necessidades dos usuários finais da carteira de trabalho digital ao expressar as funcionalidades do ponto de vista do usuário, o que a equipe compreenda melhor o contexto e os requisitos do projeto e garanta a solução entregue realmente agregue valor aos usuários.

Assim, os objetivos que buscam ser alcançados são:

- Garantir que a solução desenvolvida atenda às necessidades e expectativas dos usuários finais.

- Priorizar as funcionalidades com base no valor que agregam aos usuários e ao negócio, garantindo que os esforços de desenvolvimento sejam direcionados para as áreas de maior impacto.

## Metodologia

A metodologia da criação das histórias dos usuários será baseada no artigo “[O que são as histórias de usuário e como escrevê-las bem?](https://www2.decom.ufop.br/terralab/o-que-sao-as-historias-de-usuario-e-como-escreve-las-bem/)”². Assim, inicialmente, cada integrante do grupo irá escolher um ou mais dos épicos definidos no [backlog](modelagemAgil/backlog.md). Após essa etapa, cada membro irá elaborar suas próprias histórias de usuário com base nas funcionalidades definidas nos [casos de uso](modelagem/casoDeUso.md), seguindo o formato padronizado sugerido no template. 

## Template

Há um conjunto de questões que precisam ser respondidas e pontuadas nas histórias de usuário, desse modo, a tabela 1 mostra o template que deve ser seguido.

O código da história de usuário é HU + Número.

<center>

**Tabela 1:** Template dos casos de uso.

| Código História de Usuário | - |
|------------------|--------|
| Título           | - |
| Código do requisito funcional | - |
| Rastreabilidade  | -  |
| Quem?           | - |
| O que é?           | - |
| Por que ?         |  - |
| Critérios de Aceitação | - |
| Prioridade       | -    |

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

## Histórias de usuário

</center>

</details>


## EP01 - Login

<details>
  <summary size="20"><b> HI01 - Login com CPF e senha </b></summary> 
 
<center>
<br>
  
**Tabela 2:** Login com CPF e senha

| Código História de Usuário | HI01 |
|------------------|--------|
| Título           | Login com CPF e senha |
| Código do requisito funcional | RF02 |
| Rastreabilidade  | Análise de documentos |
| Quem?           | Usuário com ou sem carteira assinada |
| O que é?        | Permitir ao usuário logar com seu CPF e sua senha. |
| Por que ?         | O usuário deseja logar com CPF e senha para facilitar o acesso a múltiplos serviços governamentais de forma segura e centralizada. |
| Critérios de Aceitação | <li>O usuário deve poder logar com CPF e senha válidos.<br><li>O sistema deve verificar a autenticidade do CPF e senha.<br><li>O usuário deve ter acesso a todos os serviços após o login bem-sucedido. |
| Prioridade       | Alta |


**Fonte:** [Iago Passaglia](https://github.com/Paxxaglia)

</center>

</details>

<details>
  <summary size="20"><b> HI02 - Login com gov.br </b></summary> 
 
<center>
<br>
  
**Tabela 3:** Login com gov.br

| Código História de Usuário | HI02 |
|------------------|--------|
| Título           | Login com gov.br |
| Código do requisito funcional | RF02 |
| Rastreabilidade  | Análise de documentos |
| Quem?           | Usuário com ou sem carteira assinada |
| O que é?        | Permitir ao usuário logar com seu cadastro gov.br. |
| Por que ?         | O usuário gostaria de logar no carteira digital de trabalho através do gov.br para acessar suas informações trabalhistas de maneira rápida e segura. |
| Critérios de Aceitação | <li>O login deve ser seguro, utilizando autenticação de dois fatores (2FA).<br><li>O sistema deve fornecer mensagens claras sobre o status do login (sucesso ou falha).<br><li>O sistema deve estar em conformidade com a LGPD (Lei Geral de Proteção de Dados). |
| Prioridade       | Alta |


**Fonte:** [Iago Passaglia](https://github.com/Paxxaglia)

</center>

</details>


<details>
  <summary size="20"><b> HI03 - Recuperação de senha com email </b></summary> 
 
<center>
<br>
  
**Tabela 4:** Recuperação de senha com email

| Código História de Usuário | HI03 |
|------------------|--------|
| Título           | Recuperação de senha via e-mail |
| Código do requisito funcional | RF02 |
| Rastreabilidade  | Análise de documentos |
| Quem?            | Usuário do sistema com ou sem carteira de trabalho |
| O que é?         | Recuperar a senha da conta |
| Por que ?        | Para voltar a acessar a conta no caso de esquecimento da senha |
| Critérios de Aceitação | <li> Usuário deve ser capaz de solicitar a recuperação de senha através do seu e-mail cadastrado.<br><li> O sistema deve enviar um e-mail com as instruções de recuperação de senha.<br><li> Usuário deve poder definir uma nova senha seguindo as instruções recebidas.<br><li>O sistema deve confirmar a alteração da senha e permitir o acesso com a nova senha. |
| Prioridade       | Alta |

**Fonte:** [Iago Passaglia](https://github.com/Paxxaglia)

</center>

</details>

## EP02 - Perfil

As tabelas a seguir demonstram as histórias de usuário relacionadas ao épico 02 elicitado no backlog do produto.

<details>
  <summary size="20"><b> HI04 - Vizualizar o perfil e dados </b></summary> 
 
<center>
<br>
  
**Tabela 5:**  Vizualizar o perfil e dados

| Código História de Usuário | HI04 |
|------------------|--------|
| Título           | Vizualizar o perfil e dados |
| Código do requisito funcional | RF03 |
| Rastreabilidade  | Análise de documentos |
| Quem?            | Usuário do sistema com ou sem carteira de trabalho |
| O que é?         | Vizualizar os dados do perfil |
| Por que ?        | O usuário deseja consultar seus dados e seu perfil no aplicativo para fins pessoais |
| Critérios de Aceitação | <li> O usuário deve ter uma conta logada no aplicativo <br><li> O usuário deve ter acesso aos seus dados de forma clara e sucinta.<br> |
| Prioridade       | Alta |

**Fonte:** [Caio Mesquita](https://github.com/Caiomesvie)

</center>

</details>

<details>
  <summary size="20"><b> HI05 - Alterar os dados do perfil  </b></summary> 
 
<center>
<br>
  
**Tabela 6:** Alterar os dados do perfil

| Código História de Usuário | HI05 |
|------------------|--------|
| Título           | Alterar os dados do perfil |
| Código do requisito funcional | RF04 |
| Rastreabilidade  | Análise de documentos |
| Quem?            | Usuário do sistema com ou sem carteira de trabalho |
| O que é?         | Alterar os dados do seu perfil |
| Por que ?        | O usuário deseja alterar seus dados e seu perfil no aplicativo a fim de mantê-los atualizados. |
| Critérios de Aceitação | <li> O usuário deve ter uma conta logada no aplicativo <br><li> O usuário deve ter acesso aos seus dados de forma clara e sucinta.<br><li> O usuário deve uma funcionalidade clara a mostra indicando onde irá para alterar os dados<br><li> O usuário deverá receber uma notificação clara o avisando que seus dados foram alterados com sucesso |
| Prioridade       | Alta |

**Fonte:** [Caio Mesquita](https://github.com/Caiomesvie)

</center>

</details>


## EP03 - Contratos

Em relação às histórias de usuários elicitadas no [backlog](modelagemAgil/backlog.md), as tabelas 7, 8, 9, 10 e 11 mostram as histórias de usuário detalhadas referentes ao épico de contratos.

<details>
  <summary size="20"><b> HI06 - Visualizar contratos Antigos </b></summary> 
 
<center>

**Tabela 7:** Visualizar contratos Antigos

| Código História de Usuário | HI06 |
|------------------|--------|
| Título           | Visualização de Contratos Antigos |
| Código do requisito funcional | RF05 |
| Rastreabilidade  | Análise de documentos |
| Quem?           | Usuário Trabalhador de Carteira Assinada |
| O que é?           | Permitir ao usuário visualizar uma lista de seus contratos antigos armazenados no sistema. |
| Por que ?         | O usuário, que já trabalhou em múltiplos empregos de carteira assinada, deseja revisar suas experiências anteriores e os termos dos contratos para referência e reflexão sobre sua carreira profissional. |
| Critérios de Aceitação | <li>O sistema deve exibir uma lista de contratos antigos do usuário, incluindo detalhes como nome da empresa, cargo, data de início e término do contrato.<br><li>O usuário deve poder acessar detalhes completos de cada contrato ao clicar em uma entrada da lista.<br><li>A lista de contratos deve ser ordenada cronologicamente, com os contratos mais recentes no topo. |
| Prioridade       | Alta |


**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

</details>

<details>
  <summary size="20"><b> HI07 - Emitir PDF </b></summary> 
 
<center>
  
**Tabela 8:** Emitir PDF

| Código História de Usuário | HI07 |
|------------------|--------|
| Título           | Emissão de Contratos em PDF |
| Código do requisito funcional | RF07 |
| Rastreabilidade  | Análise de documentos |
| Quem?           | Usuário Trabalhador de Carteira Assinada |
| O que é?           | Permitir ao usuário gerar uma cópia digital em formato PDF de seus contratos armazenados no sistema. |
| Por que ?         | O usuário deseja manter uma cópia digital segura e facilmente acessível de seus contratos para referência futura, compartilhamento com terceiros ou armazenamento pessoal. |
| Critérios de Aceitação | <li>O sistema deve oferecer a opção de gerar um arquivo PDF para cada contrato individualmente.<br><li>O usuário deve poder baixar o PDF do contrato em seu dispositivo após a emissão.<br><li>O PDF gerado deve incluir todos os detalhes do contrato, como nome da empresa, cargo, data de início e término, de forma clara e legível. |
| Prioridade       | Média |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

</details>

<details>
  <summary size="20"><b> HI08 - Visualizar gráficos de contratos </b></summary> 
 
<center>

**Tabela 9:** Visualizar contratos Antigos

| Código História de Usuário | HI08 |
|------------------|--------|
| Título           | Visualização de Gráficos de Histórico Profissional |
| Código do requisito funcional | RF08 |
| Rastreabilidade  | Análise de documentos |
| Quem?           | Usuário Trabalhador de Carteira Assinada |
| O que é?           | Permitir ao usuário visualizar gráficos que representam seu histórico de contratações e remunerações ao longo do tempo. |
| Por que ?         | O usuário deseja entender melhor sua trajetória profissional, identificando tendências, padrões de contratação e variações salariais ao longo do tempo. |
| Critérios de Aceitação | <li>O sistema deve gerar gráficos intuitivos que mostram o número de contratações ao longo dos anos e a remuneração associada a cada contrato.<br><li>O usuário deve poder filtrar os gráficos por período específico, tipo de contrato, ou outras métricas relevantes.<br><li>Os gráficos devem ser atualizados automaticamente conforme novos contratos são adicionados ou alterados. |
| Prioridade       | Baixa |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

</details>

<details>
  <summary size="20"><b> HI09 - Realizar anotações em contratos </b></summary> 
 
<center>

**Tabela 10:** Visualizar contratos Antigos

| Código História de Usuário | HI09 |
|------------------|--------|
| Título           | Adição de Anotações aos Contratos |
| Código do requisito funcional | RF09 |
| Rastreabilidade  | Análise de documentos |
| Quem?           | Usuário Trabalhador de Carteira Assinada |
| O que é?           | Permitir ao usuário adicionar notas e comentários personalizados aos contratos armazenados no sistema. |
| Por que ?         | O usuário deseja ter a capacidade de registrar informações adicionais ou observações relevantes sobre seus contratos para referência futura ou para documentar detalhes específicos de sua experiência de trabalho. |
| Critérios de Aceitação | <li>O sistema deve fornecer uma interface para que o usuário adicione anotações aos contratos existentes.<br><li>As anotações devem ser armazenadas junto com os detalhes do contrato e podem ser visualizadas a qualquer momento.<br><li>O usuário deve poder editar ou excluir suas anotações conforme necessário. |
| Prioridade       | Baixa |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

</details>

<details>
  <summary size="20"><b> HI10 - Reportar denúncias </b></summary> 
 
<center>

**Tabela 11:** Reportar denúncias

| Código História de Usuário | HI10 |
|------------------|--------|
| Título           | Realização de Denúncias Trabalhistas |
| Código do requisito funcional | RF10 |
| Rastreabilidade  | Entrevistas |
| Quem?           | Usuário Trabalhador de Carteira Assinada |
| O que é?           | Permitir ao usuário reportar irregularidades e fazer denúncias trabalhistas contra uma empresa por meio do aplicativo. |
| Por que ?         | O usuário deseja ter um canal oficial e conveniente para relatar problemas trabalhistas, como violações de direitos, más condições de trabalho ou práticas ilegais, garantindo a proteção de seus direitos e o cumprimento da legislação trabalhista. |
| Critérios de Aceitação | <li>O sistema deve fornecer uma seção específica para denúncias trabalhistas, acessível a partir do perfil do usuário.<br><li>O usuário deve poder preencher um formulário de denúncia, incluindo detalhes sobre a empresa, a natureza da irregularidade e qualquer evidência disponível.<br><li>O sistema deve permitir que o usuário anexe documentos, fotos ou outros arquivos relevantes à sua denúncia.<br><li>O usuário deve receber uma confirmação após o envio da denúncia e ser informado sobre o status de sua solicitação.<br><li>O sistema deve garantir a confidencialidade das denúncias, protegendo a identidade do denunciante, se desejado.<br><li>O usuário deve poder acompanhar o progresso de sua denúncia e receber atualizações sobre as ações tomadas pela empresa ou autoridades competentes.<br><li>O sistema deve facilitar a comunicação entre o usuário e as autoridades responsáveis pela investigação da denúncia, se necessário. |
| Prioridade       | Média |


**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

</details>

## EP04 - Benefícios

As Tabelas a seguir detalham os casos de uso do sistema de solicitação de benefícios, incluindo o código e título de cada história de usuário, requisitos funcionais, rastreabilidade, atores envolvidos, objetivos, razões, critérios de aceitação e prioridade. 


<details>
  <summary size="20"><b> HI11 - Visualizar contratos Antigos </b></summary> 
 
<center>
Tabela 12: Visualizar contratos

| Código História de Usuário | HI11 |
|----------------------------|------|
| *Título*                 | Visualizar o histórico detalhado de todos os benefícios solicitados e recebidos |
| *Código do requisito funcional* | RF12 |
| *Rastreabilidade*        |Análise de documentos, Entrevistas e Storytelling  |
| *Quem?*                  | Usuário |
| *O que é?*               | Visualizar o histórico detalhado de todos os benefícios solicitados e recebidos |
| *Por que ?*              | Para ter um controle completo e organizado das minhas solicitações |
| *Critérios de Aceitação* | <ul><li>Usuário deve acessar facilmente o histórico de solicitações.</li><li>Histórico deve incluir todas as solicitações e benefícios recebidos.</li><li>Informações devem ser apresentadas de forma clara e organizada.</li></ul> |
| *Prioridade*             | Alto|

</center>

</details>


<details>
  <summary size="20"><b> HI12 - Solicitar benefícios </b></summary> 
 
<center>

Tabela 13:Solicitar benefícios

| Código História de Usuário | HI12 |
|----------------------------|------|
| *Título*                 | Preencher formulário de solicitação de benefício |
| *Código do requisito funcional* | RF13 |
| *Rastreabilidade*        | Análise de documentos e entrevistas |
| *Quem?*                  | Usuário |
| *O que é?*               | Preencher um formulário de solicitação de benefício de forma simples e guiada |
| *Por que ?*              | Para garantir que todas as informações necessárias sejam fornecidas corretamente |
| *Critérios de Aceitação* | <ul><li>O formulário deve ser fácil de entender e preencher.</li><li>Deve haver orientações claras para cada campo.</li><li>Usuário deve ser capaz de submeter o formulário com sucesso.</li></ul> |
| *Prioridade*             | Obrigatório |

Autor:[Bruno Araújo](https://github.com/brunocva)

</center>

</details>


<details>
  <summary size="20"><b> HI13 -  Consultar dados a respeito de INSS e FGTS  </b></summary> 
 
<center>

Tabela 14:Consultar dados a respeito de INSS e FGTS

| Código História de Usuário | HI13 |
|----------------------------|------|
| *Título*                 | Consultar dados a respeito de INSS e FGTS |
| *Código do requisito funcional* | RF11 |
| *Rastreabilidade*        | Storytelling |
| *Quem?*                  | Usuário |
| *O que é?*               | Permitir ao usuário consultar dados detalhados sobre suas contribuições e saldos do INSS e FGTS. |
| *Por que ?*              | O usuário deseja acompanhar suas contribuições previdenciárias e fundos de garantia, garantindo que estão sendo corretamente depositados e para planejamento financeiro pessoal. |
| *Critérios de Aceitação* | <li> O sistema deve exibir o saldo atualizado das contribuições do INSS. <br><li> O sistema deve exibir o saldo atualizado do FGTS.<br><li> O usuário deve poder visualizar o histórico de contribuições de ambos os benefícios.<br> |
| *Prioridade*             | alto |

Autor:[Bruno Araújo](https://github.com/brunocva)

</center>

</details>


<details>
  <summary size="20"><b> HI14 -  manual a respeito dos benefícios que tenho direito </b></summary> 
 
<center>

Tabela 15: manual a respeito dos benefícios

| Código História de Usuário | HI14 |
|----------------------------|------|
| *Título*                 |  manual a respeito dos benefícios que tenho direito|
| *Código do requisito funcional* | - |
| *Rastreabilidade*        | - |
| *Quem?*                  | Usuário |
| *O que é?*               | Permitir ao usuário acessar um manual detalhado sobre os benefícios a que tem direito.  |
| *Por que ?*              | O usuário deseja conhecer todos os benefícios disponíveis, incluindo como acessá-los e os critérios de elegibilidade, para garantir que está aproveitando todos os direitos trabalhistas e previdenciários oferecidos. |
| *Critérios de Aceitação* | <ul><li>O sistema deve fornecer acesso a um manual digital que descreve todos os benefícios disponíveis ao usuário</li><li>O manual deve incluir informações sobre como acessar cada benefício, os critérios de elegibilidade, e os documentos necessários.</li><li>O manual deve ser facilmente navegável e pesquisável, permitindo ao usuário encontrar rapidamente as informações que procura.</li></ul> |
| *Prioridade*             | Obrigatório |

Autor:[Bruno Araújo](https://github.com/brunocva)

</center>

</details>




## EP05 - Usuário Empregador
Em relação às histórias de usuários elicitadas no backlog, as tabelas 16, 17, 18 e 19 mostram as histórias de usuário detalhadas referentes ao Usuário Empregador.

<details>
  <summary size="20"><b> HI15 - Acessar o histórico de candidatos </b></summary> 
 
<center>

*Tabela 16:* Acessar o histórico de candidatos

| Código História de Usuário | HI15 |
|------------------|--------|
| Título           | Acessar o histórico de candidatos |
| Código do requisito funcional | RF08 |
| Rastreabilidade  | 	Análise de documentos |
| Quem?           | Usuário Empregador |
| O que é?           | Permitir ao empregador acessar o histórico de candidatos para verificar suas experiências anteriores. |
| Por que ?         | O empregador deseja verificar as experiências de trabalho anteriores dos candidatos para tomar decisões informadas durante o processo de contratação. |
| Critérios de Aceitação | <li>O empregador deve poder acessar uma lista de candidatos.<br><li> Para cada candidato, o empregador deve poder visualizar detalhes de suas experiências anteriores, incluindo nome do empregador anterior, datas de início e término do vínculo, cargos ocupados, e responsabilidades principais. <br><li> O sistema deve garantir que as informações exibidas sejam precisas e atualizadas.<br><li> O empregador deve poder filtrar candidatos com base em critérios como período de experiência, setor de atuação, e cargo ocupado. <br><li> O empregador deve poder exportar o histórico de candidatos para um formato de arquivo comum (ex. PDF, CSV) para análise offline. <br><li> O acesso ao histórico de candidatos deve ser protegido por autenticação e respeitar as políticas de privacidade e consentimento dos candidatos.|
| Prioridade       | Média |


*Fonte:* [Luana Medeiros](https://github.com/LuaMedeiros)

</center>

</details>

<details>
  <summary size="20"><b> HI16 - Lançar novos contratos </b></summary> 
 
<center>

*Tabela 17:* Lançar novos contratos

| Código História de Usuário | HI16 |
|------------------|--------|
| Título           | Lançar novos contratos |
| Código do requisito funcional | RF25 |
| Rastreabilidade  | Entrevistas |
| Quem?           | Usuário Empregador |
| O que é?           | Permitir ao empregador lançar novos contratos no sistema para formalizar a contratação. |
| Por que ?         | O empregador deseja formalizar a contratação de novos funcionários de maneira eficiente e conforme as normas trabalhistas, garantindo que todas as informações necessárias sejam registradas e acessíveis. |
| Critérios de Aceitação | <li>O empregador deve poder acessar um formulário para lançar um novo contrato de trabalho.<br><li> O formulário deve permitir a inserção de informações essenciais, como dados pessoais do empregado (nome, CPF, etc.), cargo, data de início, salário, carga horária e demais condições contratuais. <br><li> O sistema deve validar as informações inseridas para garantir que estão completas e corretas. <br><li> Após a inserção dos dados, o empregador deve poder revisar e confirmar o lançamento do contrato. <br><li> O sistema deve gerar um registro oficial do contrato e disponibilizar uma cópia digital para ambos, empregador e empregado. <br><li> O empregador deve poder acessar e gerenciar todos os contratos lançados, incluindo a edição ou cancelamento, se necessário. <br><li> O sistema deve enviar notificações ao empregado sobre o novo contrato e fornecer um meio para que ele possa revisar e aceitar os termos. <br><li> O sistema deve garantir que todas as informações e processos estejam em conformidade com a legislação trabalhista vigente. <br><li> O acesso e lançamento de contratos devem ser protegidos por autenticação para garantir a segurança e privacidade das informações.|
| Prioridade       | Alta |


*Fonte:* [Luana Medeiros](https://github.com/LuaMedeiros)

</center>

</details>

<details>
  <summary size="20"><b> HI17 - Alterar Dados de Contrato </b></summary> 
 
<center>

*Tabela 18:* Alterar Dados de Contrato

| Código História de Usuário | HI17 |
|------------------|--------|
| Título           | Alterar Dados de Contrato |
| Código do requisito funcional | RF25 |
| Rastreabilidade  | Entrevistas |
| Quem?           | Usuário Empregador |
| O que é?           | Permitir ao empregador alterar dados de contrato para manter as informações atualizadas. |
| Por que ?         | O empregador deseja garantir que todas as informações contratuais dos funcionários estejam sempre corretas e atualizadas, refletindo quaisquer mudanças nas condições de trabalho. |
| Critérios de Aceitação | <li>O empregador deve poder acessar uma lista de contratos existentes.<br><li> O empregador deve poder selecionar um contrato específico para edição. <br><li> O sistema deve permitir a alteração de informações contratuais, como cargo, salário, carga horária, e demais condições de trabalho. <br><li> O sistema deve validar as informações alteradas para garantir que estão completas e corretas. <br><li> Após a edição, o empregador deve poder revisar e confirmar as alterações. <br><li> O sistema deve gerar um registro oficial das alterações realizadas e disponibilizar uma cópia digital atualizada para ambos, empregador e empregado. <br><li> O empregado deve ser notificado sobre as alterações no contrato e fornecer um meio para que ele possa revisar e aceitar as mudanças. <br><li> O empregador deve poder acessar o histórico de alterações de cada contrato. <br><li> O sistema deve garantir que todas as alterações estejam em conformidade com a legislação trabalhista vigente. <br><li> O acesso e edição dos contratos devem ser protegidos por autenticação para garantir a segurança e privacidade das informações.|
| Prioridade       | Alta |


*Fonte:* [Luana Medeiros](https://github.com/LuaMedeiros)

</center>

</details>

<details>
  <summary size="20"><b> HI18 - Publicar Vagas Disponíveis no Mural de Vagas </b></summary> 
 
<center>

*Tabela 19:* Publicar Vagas Disponíveis no Mural de Vagas

| Código História de Usuário | HI18 |
|------------------|--------|
| Título           | Publicar Vagas Disponíveis no Mural de Vagas |
| Código do requisito funcional | RF28 |
| Rastreabilidade  | Entrevistas |
| Quem?           | Usuário Empregador |
| O que é?           | Permitir ao empregador publicar vagas disponíveis no mural de vagas para atrair candidatos. |
| Por que ?         | O empregador deseja anunciar oportunidades de emprego para atrair candidatos qualificados de maneira eficiente e centralizada. |
| Critérios de Aceitação | <li>O empregador deve poder acessar um formulário para criar um anúncio de vaga.<br><li> O formulário deve permitir a inserção de informações essenciais da vaga, como título do cargo, descrição das responsabilidades, requisitos, local de trabalho, tipo de contrato, salário oferecido e benefícios. <br><li> O sistema deve validar as informações inseridas para garantir que estão completas e corretas. <br><li> Após a inserção dos dados, o empregador deve poder revisar e confirmar a publicação da vaga. <br><li> O sistema deve publicar a vaga no mural de vagas acessível a todos os usuários registrados como candidatos. <br><li> O empregador deve poder acessar e gerenciar todas as vagas publicadas, incluindo a edição, desativação ou reativação das vagas conforme necessário. <br><li> O sistema deve notificar os candidatos registrados que correspondem ao perfil da vaga publicada. <br><li> O empregador deve poder visualizar estatísticas de visualizações e candidaturas recebidas para cada vaga publicada. <br><li> O acesso e publicação de vagas devem ser protegidos por autenticação para garantir a segurança e privacidade das informações. <br><li> O sistema deve garantir que todas as informações das vagas estejam em conformidade com as normas e regulamentações trabalhistas vigentes.|
| Prioridade       | Alta |


*Fonte:* [Luana Medeiros](https://github.com/LuaMedeiros)

</center>

</details>

## EP06 - Procura de Empregos

Um dos pontos que foi discutido durante as elicitações foi a questão de procura de empregos. Sendo assim, com base também no [backlog](modelagemAgil/backlog.md), as tabelas 20 e 21 mostram as histórias de usuário detalhadas referentes ao contexto de procura por empregos

<details>
  <summary size="20"><b> HI19 - Acesso à informações de vagas de emprego </b></summary> 
 
<center>

**Tabela 20:** Acesso à informações de vagas de emprego

| Código História de Usuário | HI19 |
|------------------|--------|
| Título           | Acesso ao Mural de Vagas Disponíveis |
| Código do requisito funcional | RF16 |
| Rastreabilidade  | Análise de documentos |
| Quem?           | Usuário Trabalhador de Carteira Assinada |
| O que é?           | Permitir ao usuário acessar um mural de vagas disponíveis para encontrar oportunidades de emprego compatíveis com seu perfil e interesses. |
| Por que ?         | O usuário deseja ter acesso a uma lista atualizada de vagas de emprego para facilitar sua busca por oportunidades de trabalho. |
| Critérios de Aceitação | <li>O sistema deve fornecer um mural de vagas disponíveis acessível a partir do perfil do usuário.<br><li>O usuário deve poder visualizar informações detalhadas sobre cada vaga, incluindo título, descrição, requisitos e localização.<br><li>O sistema deve permitir que o usuário filtre as vagas por diferentes critérios, como localização, salário, tipo de contrato, entre outros.<br><li>O usuário deve poder marcar vagas de interesse para revisão posterior.<br><li>O sistema deve atualizar regularmente o mural de vagas para garantir a relevância das informações.<br><li>O usuário deve poder se candidatar a vagas diretamente pelo aplicativo, quando disponível.<br><li>O sistema deve fornecer uma função de pesquisa para facilitar a busca por vagas específicas.<br><li>O usuário deve poder receber notificações sobre novas vagas que correspondam ao seu perfil e interesses.<br><li>O sistema deve garantir a segurança e confidencialidade dos dados do usuário durante a busca por vagas. |
| Prioridade       | Baixa |


**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

</details>

<details>
  <summary size="20"><b> HI20 - Status de contratação </b></summary> 
 
<center>

**Tabela 21:** Status de contratação

| Código História de Usuário | HI20 |
|------------------|--------|
| Título           | Alteração de Status de Contratação |
| Código do requisito funcional | RF15 |
| Rastreabilidade  | Entrevistas |
| Quem?           | Usuário Trabalhador de Carteira Assinada |
| O que é?           | Permitir ao usuário alterar seu status de contratação para informar sua disponibilidade no mercado de trabalho. |
| Por que ?         | O usuário deseja poder indicar se está procurando emprego ou não, para que possa receber ofertas de emprego relevantes e adequadas ao seu perfil. |
| Critérios de Aceitação | <li>O sistema deve fornecer uma opção para o usuário alterar seu status de contratação no perfil.<br><li>O usuário deve poder escolher entre os modos de "Procurando Emprego" e "Não Procurando Emprego".<br><li>Se o usuário escolher o modo "Procurando Emprego", ele deve ter a opção de atualizar seu currículo e indicar a cidade onde está procurando emprego.<br><li>O sistema deve permitir que o usuário altere seu status de contratação a qualquer momento, alternando entre "Procurando Emprego" e "Não Procurando Emprego".<br><li>O sistema deve atualizar automaticamente o perfil do usuário com o novo status de contratação.<br><li>O usuário deve poder receber notificações e ofertas de emprego com base no status de contratação selecionado.<br><li>O sistema deve garantir a segurança e confidencialidade das informações do usuário durante a alteração de status. |
| Prioridade       | Baixa |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

</details>

## EP07 - Segurança

Das histórias de usuários elucidadas no [backlog](modelagemAgil/backlog.md), as tabelas 21 e 22 mostram as histórias de usuário referentes ao épico de segurança.

<details>
  <summary size="20"><b> HI21 - Configurações de privacidade. </b></summary>

<center>

<p align="center"> <b>Tabela 22:</b> Configurações de privacidade. </p>


| Código História de Usuário    | HI21                                               |
| ----------------------------- | -------------------------------------------------- |
| Título                        | Configurações de privacidade                       |
| Código do requisito funcional | RF17                                               |
| Rastreabilidade               | Análise de documentos e storytelling               |
| Quem?                         | Usuário                                            |
| O que é?                      | Configurar quem pode ver as informações do usuário |
| Por que ?                     |  Proteger a privacidade do usuário.                |
| Critérios de Aceitação        |  <ul><li>O usuário deve ser capaz de ocultar suas informações. <li>O aplicativo deve permitir que os usuários escolham quais dados pessoais desejam compartilhar com terceiros. <li>O aplicativo de fornecer opções claras e eficazes para controlar o compartilhamento de dados.</ul> |
| Prioridade                    | Alta                                               |

<b> Autor: </b> <a href="https://github.com/brenoalexandre0"> Breno Alexandre </a>

</center>

</details>

<details>
  <summary size="20"><b> HI22 - Visualizar relatório de atividades da conta. </b></summary>

<center>

<p align="center"> <b>Tabela 23:</b> Visualizar relatório de atividades da conta.  </p>


| Código História de Usuário    | HI22                                                    |
| ----------------------------- | ------------------------------------------------------- |
| Título                        | Visualizar relatório de atividades da conta             |
| Código do requisito funcional | RF05, RF08, RF19                                        |
| Rastreabilidade               | Análise de documentos e storytelling                    |
| Quem?                         | Usuário                                                 |
| O que é?                      | Visualizar um relatório de todas as atividades na conta |
| Por que ?                     | Para monitorar acessos e ações                          |
| Critérios de Aceitação        | <ul><li>O usuário deve ser capaz de acessar o relatório de atividades da conta de forma intuitiva, sem dificuldades. <li>O relatório deve exibir todas as atividades relevantes da conta. <li>Cada atividade listada no relatório deve incluir informações claras. <li>O aplicativo deve permitir que os usuários filtrem e classifiquem as atividades conforme necessário. <li>O relatório não deve exibir informações confidenciais.</ul>
| Prioridade                    | Alta                                                    |

<b> Autor: </b> <a href="https://github.com/brenoalexandre0"> Breno Alexandre </a>

</center>

</details>


## EP08 - Suporte

<details>
  <summary size="20"><b> HI23 - Participar de fóruns de discussão sobre temas trabalhistas </b></summary> 
 
<center>

**Tabela 24:** Participar de fóruns de discussão sobre temas trabalhistas

| Código História de Usuário | HI23 |
|----------------------------|------|
| **Título**                 | Participar de fóruns de discussão sobre temas trabalhistas |
| **Código do requisito funcional** | F20 |
| **Rastreabilidade**        | RF20 |
| **Quem?**                  | Usuário |
| **O que é?**               | Participar de fóruns de discussão sobre temas trabalhistas para trocar experiências e obter informações úteis |
| **Por que ?**              | Para obter suporte e informações relevantes através da troca de experiências com outros usuários |
| **Critérios de Aceitação** | <ul><li>Usuário deve conseguir acessar diferentes fóruns de discussão pelo aplicativo.</li><li>Usuário deve poder postar e responder a tópicos nos fóruns.</li><li>Os fóruns devem ser moderados para manter a relevância e respeito nas discussões.</li></ul> |
| **Prioridade**             | Baixo |


**Fonte:** [Pedro Izarias](https://github.com/Izarias)
</center>

</details>

<details>
  <summary size="20"><b> HI24 - Acessar um canal de suporte direto pelo aplicativo </b></summary> 
 
<center>

**Tabela 25:** Acessar um canal de suporte direto pelo aplicativo

| Código História de Usuário | HI24 |
|----------------------------|------|
| **Título**                 | Acessar um canal de suporte direto pelo aplicativo |
| **Código do requisito funcional** | F20 |
| **Rastreabilidade**        | RF20 |
| **Quem?**                  | Usuário |
| **O que é?**               | Acessar um canal de suporte direto pelo aplicativo para resolver dúvidas e problemas rapidamente |
| **Por que ?**              | Para receber suporte imediato e eficiente em caso de problemas ou dúvidas sobre o uso do aplicativo |
| **Critérios de Aceitação** | <ul><li>Usuário deve conseguir acessar o canal de suporte diretamente pelo aplicativo.</li><li>O suporte deve estar disponível durante o horário comercial.</li><li>As respostas devem ser rápidas e úteis para resolver as dúvidas ou problemas dos usuários.</li></ul> |
| **Prioridade**             | Alto |

**Fonte:** [Pedro Izarias](https://github.com/Izarias)
</center>

</details>

<details>
  <summary size="20"><b> HI25 - Acessar um manual para o uso do aplicativo e possíveis dúvidas </b></summary> 
 
<center>
  
**Tabela 26:** Acessar um manual para o uso do aplicativo e possíveis dúvidas

| Código História de Usuário | HI25 |
|----------------------------|------|
| **Título**                 | Acessar um manual para o uso do aplicativo e possíveis dúvidas |
| **Código do requisito funcional** | F20 |
| **Rastreabilidade**        | RF20 |
| **Quem?**                  | Usuário |
| **O que é?**               | Acessar um manual para o uso do aplicativo e possíveis dúvidas para me orientar no uso da plataforma |
| **Por que ?**              | Para ter um guia de referência que ajude a entender e utilizar todas as funcionalidades do aplicativo |
| **Critérios de Aceitação** | <ul><li>Manual deve estar disponível diretamente no aplicativo.</li><li>Manual deve cobrir todas as principais funcionalidades do aplicativo.</li><li>Usuário deve poder buscar por tópicos específicos no manual.</li></ul> |
| **Prioridade**             | Médio |

**Fonte:** [Pedro Izarias](https://github.com/Izarias)
</center>

</details>


## Referências Bibliográficas

1. Reis, J. C. dos, Maike, V. R. M. L., Duarte, E. F., Gonçalves, F. M., França, B. B. N. de, Bonacin, R., Pereira, R., & Baranauskas, M. C. C. (2018). **Combinando Design Participativo e História de Usuários para Levantamento de Funcionalidades no OpenDesign**. Instituto de Computação, Universidade Estadual de Campinas (UNICAMP), Disponível em <https://www.ic.unicamp.br/~reltech/2018/18-12.pdf>. Acessado em 26 de maio de 2024.

2. Gustavo Guasti, Italo. Carneiro, Tiago. **O que são as histórias de usuário e como escrevê-las bem?**. TerraLab. Disponível em <https://www2.decom.ufop.br/terralab/o-que-sao-as-historias-de-usuario-e-como-escreve-las-bem/>  Acessado em 26 de maio de 2024.


## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Adição da introdução, da definição e dos objetivos, da metodologia e do template   |  Larissa Stéfane   |   Iago Passaglia  | 26/05/2024  |
| 1.1 | Adição História de Usuário e Título  |  Bruno Araújo   |   Iago Passaglia   | 27/05/2024  |
| 1.2 | Adição História de Usuário em relação ao épico 3: Contratos  |  Larissa Stéfane   |   Iago Passaglia   | 27/05/2024  |
| 1.3 | Adição História de Usuário em relação ao épico 6: Busca por empregos  |  Larissa Stéfane   |   Iago Passaglia   | 27/05/2024  |
| 1.4 | Adição História de Usuário em relação ao épico 8: Suporte  |  Pedro Izarias   |   Iago Passaglia   | 27/05/2024  |
| 1.5 | Adição História de Usuário em relação ao épico 5: Usuário Empregador  |  Luana Medeiros  |   -   | 27/05/2024  | 
| 1.6 | Adição História de Usuário em relação ao épico 2  |  Caio Mesquita  |   Luana Medeiros   | 27/05/2024  | 
| 1.7 | Correção de erros na página |  Caio Mesquita  |  Breno Alexandre  | 27/05/2024  | 
| 1.8 | Adição do épico de segurança  |  Breno Alexandre  |  Luana Medeiros   | 27/05/2024  | 
