# Backlog do Produto

## Sumário

* [Introdução](#Introdução)
* [Metodologia](#Metodologia)
* [Roteiro da Reunião para o Backlog](#Roteiro-da-Reunião-para-o-Backlog)
* []()
* []()
* []()


## Introdução

O Backlog do produto é uma artefato proveniente de metodologias ágeis, onde há uma lista de funcionalidades a serem concebidas no projeto com o objetivo de manter a equipe alinhada com as tarefas que devem ser realizadas e dividir as tarefas de forma intuitiva e de fácil compreensão. Estas funcionalidades estão listadas de forma priorizadas com a participação do Product Owner (dono do produto) no processo de priorização.

## Metodologia

Para a confecção do backlog do produto deste projeto, partimos do uso do artefato [Requisitos Elicitados](Elicitacao/ResquisitosCorrigidos.md) utilizando as técnicas de elicitação e priorização nas etapas anteriores para definir as tarefas a serem realizadas. Para minimizar essas tarefas e faciliar o entendimento delas, elas foram dividias em Tópicos e sub-tópicos, demonstradas na tabela 1, além de conter o seu nível de priorização. 

<center>
Tabela 1: Modelo do Backlog do produto

|Tema|Épico|História de Usuário|Prioridade|
|-|-|-|-|
|Generalizam o escopo das tarefas em grandes blocos mais abstratos |Formam o escopo das histórias de usuário mais bem definido, e menos abstrato que os temas | Neste documento serão citadas as histórias de usuário, as mesmas serão melhor detalhadas neste [link](modelagemAgil/historiaUsuario.md)| Nível de prioridade dividido em 3: Alto, médio e baixo. |

Fonte: [Caio Mesquita]()

</center>

## Entrevista com Product Owner

Foi realizado uma entrevista com um usuário fazendo o papel de Product Owner, que é detalhada abaixo, a fim de obter dados a respeito da divisão de tarefas a partir da ótica de um usuário do aplicativo.
Foram apresentados os requisitos onde a usuária, a partir de sua concepção, se colocando como Product Owner da aplicação nos ajudou a definir o backlog do produto.
A entrevista foi gravada e se encontra abaixo, caso não esteja disponível tente o acesso por este [link](https://youtu.be/vhNR2F1mrjQ)

### Cronograma e gravação

Tabela 2: Cronograma entrevista Product Owner
|||
|:-:|:-:|
|Entrevistador|Caio Mesquita|
|Entrevistado|Natália Beatriz|
|local|Microsoft Teams|
|Horário e data|26/05/2024|

Fonte: [Caio Mesquita]()

<center>

Vídeo 1: Entrevista

<iframe width="680" height="520" src="https://www.youtube.com/embed/vhNR2F1mrjQ" title="Entrevista Natália Beatriz Backlog Requisitos G2 2024.1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


Fonte: [Caio Mesquita]()
</center>

## Backlog do produto

Após a entrevista, foram definidos 5 temas, onde na tabela abaixo será detalhado com seus épicos e histórias de usuário. Cada épico, tema e história possuirá um ID que o indentificará durante o processo de documentação.


<center>

Tabela 3: BackLog do produto

<table>
  <!-- Cabeçalho -->
  <tr>
    <th>Tema</th>
    <th>Épico</th>
    <th>História de Usuário</th>
  </tr>
  
  <!-- Login e Perfil -->
  <tr>
    <td rowspan="5"><b>TM01 - Login e Perfil</b></td>
    <td rowspan="3"><b>EP01 - Login</b></td>
    <td>HI01 - Como usuário, eu quero entrar com meu CPF e senha para acessar minha conta.</td>
  </tr>
  <tr>
    <td>HI02 - Como usuário, eu quero entrar com meu gov.br para acessar minha conta.</td>
  </tr>
  <tr>
    <td>HI03 - Como usuário, eu quero recuperar minha senha usando meu email para voltar a acessar minha conta.</td>
  </tr>
  <tr>
    <td rowspan="2"><b>EP02 - Perfil</b></td>
    <td>HI04 - Como usuário, eu quero visualizar meu perfil para ver minhas informações pessoais e profissionais.</td>
  </tr>
  <tr>
    <td>HI05 - Como usuário, eu quero alterar os dados do meu perfil para mantê-los atualizados.</td>
  </tr>
  
  <!-- Contratos de Trabalho e Benefícios -->
  <tr>
    <td rowspan="9"><b>TM02 - Contratos de Trabalho e Benefícios</b></td>
    <td rowspan="5"><b>EP03 - Contratos</b></td>
    <td>HI06 - Como usuário, eu quero visualizar meus contratos antigos para revisar minhas experiências anteriores.</td>
  </tr>
  <tr>
    <td>HI07 - Como usuário, eu quero emitir contratos em PDF para ter uma cópia digital dos mesmos.</td>
  </tr>
  <tr>
    <td>HI08 - Como usuário, eu quero visualizar gráficos com históricos de contratações e remunerações para entender minha trajetória profissional.</td>
  </tr>
  <tr>
    <td>HI09 - Como usuário, eu quero realizar anotações sobre os contratos para adicionar informações relevantes.</td>
  </tr>
  <tr>
    <td>HI10 - Como usuário, eu quero realizar denúncias trabalhistas para reportar irregularidades.</td>
  </tr>
  <tr>
    <td rowspan="4"><b>EP04 - Benefícios</b></td>
    <td>HI11 - Como usuário, eu quero consultar meus benefícios para saber o que tenho direito.</td>
  </tr>
  <tr>
    <td>HI12 - Como usuário, eu quero solicitar benefícios diretamente pelo aplicativo para facilitar o processo.</td>
  </tr>
  <tr>
    <td>HI13 - Como usuário, eu quero consultar dados a respeito de INSS e FGTS para acompanhar minhas contribuições.</td>
  </tr>
  <tr>
    <td>HI14 - Como usuário, eu quero possuir um manual a respeito dos benefícios que tenho direito para entender melhor cada um deles.</td>
  </tr>
  
  <!-- Integração com Empregadores -->
  <tr>
    <td rowspan="4"><b>TM03 - Integração com Empregadores</b></td>
    <td rowspan="4"><b>EP05 - Usuário Empregador</b></td>
    <td>HI15 - Como empregador, eu quero acessar o histórico de candidatos para verificar suas experiências anteriores.</td>
  </tr>
  <tr>
    <td>HI16 - Como empregador, eu gostaria de lançar novos contratos no sistema para formalizar a contratação.</td>
  </tr>
  <tr>
    <td>HI17 - Como empregador, eu quero alterar dados de contrato para manter as informações atualizadas.</td>
  </tr>
  <tr>
    <td>HI18 - Como empregador, eu quero publicar vagas disponíveis no mural de vagas para atrair candidatos.</td>
  </tr>
  
  <!-- Mural de Vagas -->
  <tr>
    <td rowspan="2"><b>TM04 - Mural de Vagas</b></td>
    <td rowspan="2"><b>EP06 - Procura de Empregos</b></td>
    <td>HI19 - Como usuário, eu gostaria de ter acesso a um mural de vagas disponíveis para encontrar oportunidades de emprego.</td>
  </tr>
  <tr>
    <td>HI20 - Como usuário, eu gostaria de alterar meu status de contratação para informar minha disponibilidade no mercado de trabalho.</td>
  </tr>
  
  <!-- Segurança e Suporte -->
  <tr>
    <td rowspan="6"><b>TM05 - Segurança e Suporte</b></td>
    <td rowspan="3"><b>EP07 - Segurança</b></td>
    <td>HI21 - Como usuário, eu quero configurar quem pode ver minhas informações para proteger minha privacidade.</td>
  </tr>
  <tr>
    <td>HI22 - Como usuário, eu quero visualizar um relatório de todas as atividades na minha conta para monitorar acessos e ações.</td>
  </tr>
  <tr>
    <td>HI23 - Como usuário, eu quero visualizar um relatório de todas as atividades na minha conta para monitorar acessos e ações.</td>
  </tr>
  <tr>
    <td rowspan="3"><b>EP08 - Suporte</b></td>
    <td>HI24 - Como usuário, eu quero participar de fóruns de discussão sobre temas trabalhistas para trocar experiências e obter informações úteis.</td>
  </tr>
  <tr>
    <td>HI25 - Como usuário, eu quero acessar um canal de suporte direto pelo aplicativo para resolver dúvidas e problemas rapidamente.</td>
  </tr>
  <tr>
    <td>HI26 - Como usuário, eu gostaria de um manual para o uso do aplicativo e possíveis dúvidas para me orientar no uso da plataforma.</td>
  </tr>
</table>


</center>

<center>

Fonte: [Caio Mesquita]()

</center>

## Bibliografia

* GOMES, Diego. Product Backlog - Introdução [vídeo]. Agile Coach Diego Gomes. Publicado em 21 Mar. 2020. Disponível em: https://youtu.be/z4ubaBwjCsU. Acesso em: 24/05/2024

* Economia-DF. Backlog. Grupo Economia-DF 2023.2 da Disciplina de Requisitos de Software, Disponível em: https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/agil/backlog/#ep09-ajuda . Acesso em: 24/05/2024.  


## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 |  Adição da introdução e da metodologia   |  Caio Mesquita   |  Larissa Stéfane  |   26/05/2024   |
| 1.1 |  Adição do reoteiro da reunião para o Backlog   |  Larissa Stéfane   |  - |   26/05/2024   |
