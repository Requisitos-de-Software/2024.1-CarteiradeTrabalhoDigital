# Caso de uso 

## Sumário
 
* [Introdução](#Introdução)
* [Metodologia](#Metodologia)
* [Diagrama](#Diagrama-de-Casos-de-Uso)
* [Especificação](#Especificação-dos-Casos-de-uso)
* [Especificação quando o usuário é um trabalhador](#Especificação-quando-o-usuário-é-um-trabalhador)
* [Especificação quando o usuário é uma empresa](#Especificação-quando-o-usuário-é-uma-empresa)
* [Bibliografia](#Bibliografia)
* [Histórico de versão](#Histórico-de-versão)

## Introdução

Um caso de uso se refere a uma descrição detalhada de como o sistema será utilizado em uma determinada situação ou contexto. Ele descreve as interações entre os usuários e o sistema, apresentando os passos necessários para alcançar um objetivo específico. O objetivo dos casos de uso é auxiliar no processo de desenvolvimento de um sistema, fornecendo uma visão clara dos requisitos funcionais do sistema, descrevendo as ações que os usuários podem realizar e as respostas do sistema a essas ações.

## Metodologia

Para a construção dos casos de uso, utilizamos a técnica de Cenários, que é uma das técnicas de elicitação de requisitos. Essa técnica ajuda a identificar requisitos e prever situações que podem ocorrer no uso do sistema. A metodologia foi baseada na técnica de modelagem de casos de uso apresentada em "Requisitos – Aula 13" (SERRANO; SERRANO, 2017)【2】.

O diagrama de caso de uso é uma representação visual que resume as interações entre os usuários e um sistema, destacando suas funcionalidades e comportamentos. Ele é composto por atores, que representam os usuários, e casos de uso, que descrevem as ações realizadas pelos usuários e as respostas do sistema. Abaixo temos uma tabela onde há os elementos contidos no [Diagrama](#Diagrama-de-Casos-de-Uso)


<center>

<b>Tabela 1</b>: Legenda dos elementos do diagrama de caso de uso

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/assets/LegendaCasoUso.jpg" alt="Legenda elementos de caso de uso" width="800">

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

## Diagrama de Casos de Uso

A figura abaixo demonstra o diagrama de casos de uso do aplicativo da Carteira de Trabalho Digital.

<center>
<img src="diagrama_de_casos_de_uso.png" alt="Diagrama de Casos de Uso">
</center>

## Especificação dos Casos de uso

A seguir, são especificados os casos de uso do aplicativo da Carteira de Trabalho Digital.

<b>Tabela 2:</b> Legenda para as tabelas de caso de Uso

| Elemento | Significado            |
| -------- | ---------------------- |
| UC0X     | Caso de Uso Nº X       |
| FB0X     | Fluxo Básico Nº X      |
| FA0X     | Fluxo Alternativo Nº X |
| FE0X     | Fluxo de exceção Nº X  |

Fonte: [Caio Mesquita](https://github.com/caiomesvie)

## Especificação quando o usuário é um trabalhador

### Trabalhador solicita benefício

A tabela 3 mostra quando o usuário(trabalhador) solicita benefícios.

<details>
  <summary size="20"><b> Tabela 3: Trabalhador solicita benefícios </b></summary> 
<center>
Tabela 3: Caso de uso UC01

| UC01                | Solicitar Benefício                                              |
| ------------------- | ---------------------------------------------------------------- |
| Descrição           | Permitir que o trabalhador solicite um benefício, como seguro-desemprego ou auxílio-doença. |
| Atores              | Trabalhador (Usuário Primário); Sistema de Banco de Dados (Usuário Secundário); Órgão Governamental (Usuário Secundário) |
| Frequência          | Sempre que o trabalhador precisar solicitar um benefício.        |
| Pré-condições       | O trabalhador deve estar autenticado no sistema e ter os documentos necessários para a solicitação. |
| Fluxo Básico        | <b> FB01 </b> <ol> <li>O trabalhador faz login no aplicativo da carteira de trabalho digital. <li>O trabalhador acessa a aba "Benefícios". <li>O trabalhador seleciona o benefício desejado. <li>O sistema exibe os requisitos e documentos necessários para a solicitação do benefício. <li>O trabalhador preenche o formulário de solicitação e anexa os documentos necessários. <li>O sistema verifica a consistência das informações e documentos fornecidos. <li>Se todas as informações estiverem corretas, o sistema envia a solicitação para o órgão governamental responsável. <li>O trabalhador recebe uma confirmação de que a solicitação foi enviada com sucesso. </ol> |
| Fluxos Alternativos | <b> FA01 </b> <ol> <li>Se o trabalhador não tiver todos os documentos necessários, ele pode salvar a solicitação como rascunho e completá-la posteriormente. </ol>             |
| Fluxos de exceção   | <b> FE01 </b> <ol> <li>Se ocorrer um erro na validação das informações ou documentos, uma mensagem de erro é exibida e o trabalhador é orientado a corrigir os dados inseridos. <li>Se houver um problema de comunicação com o órgão governamental, uma mensagem de erro é exibida e o trabalhador é instruído a tentar novamente mais tarde. <li>Se a solicitação for rejeitada pelo órgão governamental, o trabalhador recebe uma notificação com o motivo da rejeição. </ol>             |
| Pós-condições       | A solicitação de benefício é registrada e enviada ao órgão governamental responsável para análise. |
| Data de Criação     | 19/05/2024                                                        |
| Rastreabilidade     | [Requisitos Funcionais RF01, RF02]                              |

**Fonte:** [Bruno Araújo](https://github.com/brunocva)

</center>
 </details>

### Trabalhador visualiza aba emprego

A tabela 4 mostra quando o usuário(trabalhador) visualiza aba emprego.

<details>
  <summary size="20"><b> Tabela 4: Trabalhador visualiza aba emprego </b></summary> 
<center>
 
<center>
Tabela 4: Caso de uso UC02

| UC02                | Visualizar aba "Emprego"                                         |
| ------------------- | ---------------------------------------------------------------- |
| Descrição           | Permitir ao trabalhador acessar e completar informações pessoais para visualizar a aba "Emprego". |
| Atores              | Trabalhador (Usuário Primário); Plataforma gov.br (Usuário Secundário) |
| Frequência          | Sempre que o trabalhador precisar visualizar ou atualizar suas informações de emprego. |
| Pré-condições       | O trabalhador deve estar autenticado no sistema.                 |
| Fluxo Básico        | <b> FB02 </b> <ol> <li>O trabalhador faz login no aplicativo da carteira de trabalho digital. <li>O trabalhador acessa a aba "Emprego". <li>O trabalhador seleciona a opção "Quero me cadastrar". <li>O sistema exibe o formulário de "Dados Pessoais". <li>O trabalhador preenche o formulário de "Dados Pessoais". <li>O sistema exibe o formulário de "Endereço". <li>O trabalhador preenche o formulário de "Endereço". <li>O sistema exibe o formulário de "Contato". <li>O trabalhador preenche o formulário de "Contato". <li>O trabalhador envia os formulários e conclui a tarefa. </ol> |
| Fluxos Alternativos | <b> FA02 </b> <ol> <li>Se o trabalhador optar por abandonar a tarefa, ele fecha o aplicativo ou volta à tela inicial sem completar o processo de preenchimento dos formulários. |
| Fluxos de exceção   | <b> FE02 </b> <ol> <li>Se ocorrer um erro na validação das informações, uma mensagem de erro é exibida e o trabalhador é orientado a corrigir os dados inseridos. <li>Se houver um problema de comunicação com o órgão governamental, uma mensagem de erro é exibida e o trabalhador é instruído a tentar novamente mais tarde. <li>Em dispositivos IOS, se o teclado virtual permanecer sobre o botão de "Concluir" na última etapa, inviabilizando a conclusão da tarefa. </ol> |
| Restrição           | 1. O trabalhador deve estar autenticado no sistema para efetuar o cadastro.<br>2. A conexão com a internet deve estar estável durante o processo de solicitação. |
| Pós-condições       | As informações pessoais do trabalhador são registradas e a aba "Emprego" será disponibilizada por completo para o usuário. |
| Data de Criação     | 19/05/2024                                                        |
| Rastreabilidade     | [RF02, RF03]                                                      |


**Fonte:** [Iago Passaglia](https://github.com/Paxxaglia)

</center>

 </details>

### Trabalhador acessa detalhes dos contratos de trabalho

A tabela 5 mostra quando o usuário(trabalhador) deseja acessar detalhes dos contratos de trabalho.

<details>
  <summary size="20"><b> Tabela 5: Trabalhador acessa detalhes dos contratos de trabalho </b></summary> 
  
<center>
Tabela 5: Caso de uso: Acessar Detalhes dos Contratos de Trabalho


| UC03                | Nome do caso                                               |
| ------------------- | ---------------------------------------------------------- |
| Descrição           | Permitir ao usuário(trabalhador) visualizar os detalhes dos seus vínculos trabalhistas, incluindo anotações, observações e gráficos sobre sua vida laboral. |
| Atores              | Usuário(trabalhador) (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário). |
| Frequência          | Conforme necessidade do usuário(trabalhador) para consultar seus contratos de trabalho. |
| Pré-condições       | <ul> <li> O usuário(trabalhador) deve estar autenticado no sistema. <li> O usuário(trabalhador) deve ter o aplicativo da carteira de trabalho digital instalado em seu smartphone. <li> O usuário(trabalhador) deve ter acesso à internet. <li> O sistema deve estar operacional e acessível. <li> O banco de dados de contratos de trabalho deve estar atualizado e acessível. </ul> |
| Fluxo Básico        | **FB03** <ol> <li> O usuário(trabalhador) faz login no aplicativo da carteira de trabalho digital. <li> O usuário(trabalhador) clica no ícone "Contratos de Trabalho" na interface do aplicativo. <li> O sistema recupera e exibe uma lista de todos os contratos de trabalho do usuário(trabalhador). <li> O usuário(trabalhador) seleciona um contrato específico da lista. <li> O sistema exibe os detalhes do contrato selecionado, incluindo: <ul><li> Período trabalhado <li> Endereço do empregador <li> Ocupação inicial <li> Tipo de contrato <li> Salário contratual <li> Remuneração inicial e última remuneração informada <li> Relação de trabalho <li> Tipo de admissão <li> Fonte da informação</ul> <li> O usuário(trabalhador) pode visualizar anotações e observações relacionadas ao contrato. <li> O usuário(trabalhador) pode visualizar gráficos que mostram o histórico de remunerações ao longo do tempo.</ol> |
| Fluxos Alternativos | **FA03** <ol> <li> Se o usuário(trabalhador) deseja exportar os detalhes do contrato: <ul><li> O usuário(trabalhador) clica em "Exportar Contrato" na interface do aplicativo. <li> O sistema gera um arquivo PDF com todos os detalhes do contrato selecionado. <li> O usuário(trabalhador) faz o download do PDF para seu dispositivo.</ul></ol> |
| Fluxos de exceção   | **FE03** <ol> <li> Se ocorrer um erro na recuperação dos dados: <ul><li> O usuário(trabalhador) clica no ícone "Contratos de Trabalho". <li> O sistema tenta recuperar os dados do banco de dados, mas falha. <li> O sistema exibe uma mensagem de erro: "Erro ao recuperar os dados. Por favor, tente novamente mais tarde." <li> O usuário(trabalhador) clica em "OK" para fechar a mensagem de erro. <li> O usuário(trabalhador) pode verificar a conexão com a internet e tentar novamente mais tarde.</ul> <li> Se o usuário(trabalhador) não tiver contratos de trabalho registrados: <ul><li> O usuário(trabalhador) clica no ícone "Contratos de Trabalho". <li> O sistema recupera os dados e verifica que não há contratos registrados. <li> O sistema exibe uma mensagem: "Nenhum contrato de trabalho disponível." <li> O usuário(trabalhador) clica em "OK" para fechar a mensagem.</ul> <li> Se houver um problema de comunicação com o banco de dados: <ul><li> O usuário(trabalhador) clica no ícone "Contratos de Trabalho". <li> O sistema tenta se comunicar com o banco de dados, mas falha. <li> O sistema exibe uma mensagem de erro: "Problema de comunicação com o banco de dados. Tente novamente mais tarde." <li> O usuário(trabalhador) clica em "OK" para fechar a mensagem e pode tentar novamente mais tarde.</ul> <li> Se os dados do contrato forem incompletos ou estiverem corrompidos: <ul><li> O usuário(trabalhador) seleciona um contrato da lista. <li> O sistema tenta carregar os detalhes do contrato, mas os dados estão incompletos ou corrompidos. <li> O sistema exibe uma mensagem de erro: "Dados do contrato incompletos ou corrompidos. Entre em contato com o suporte técnico." <li> O usuário(trabalhador) clica em "OK" para fechar a mensagem e pode contatar o suporte técnico para resolver o problema.</ul> </ol> |
| Pós-condições       | O usuário(trabalhador) visualiza os detalhes do contrato de trabalho selecionado. |
| Data de Criação     | 18/05/2024                                                 |
| Rastreabilidade     | [F05](Elicitacao/ResquisitosCorrigidos.md), [F07](Elicitacao/ResquisitosCorrigidos.md), [NF05](Elicitacao/ResquisitosCorrigidos.md), [nf20](Elicitacao/ResquisitosCorrigidos.md), [NF22](Elicitacao/ResquisitosCorrigidos.md)                                                    |

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>
 </details>

### Trabalhador - Atualização de Contrato  

A tabela 6 mostra quando o usuário(trabalhador) deseja atualizar detalhes dos contratos de trabalho.

<details>
  <summary size="20"><b> Tabela 6: Trabalhador atualiza detalhes dos contratos de trabalho </b></summary> 

<center>
Tabela 6:  Caso de Uso: Atualização dos Contratos de Trabalho

| UC04                | Atualização de Contrato                                  |
| ------------------- | ---------------------------------------------------------- |
| Descrição           | Este caso de uso permite que o usuário (trabalhador) atualize as informações de um contrato de trabalho existente. |
| Atores              | Trabalhador (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário); <br> Empresa (Usuário Secundário) |
| Frequência          | Conforme necessidade do usuário (trabalhador) para consultar seus contratos de trabalho. No entanto, é importante observar que quanto mais atualizações forem feitas, menor será a necessidade de futuras atualizações, o que pode diminuir a frequência. |
| Pré-condições       | 1. O usuário (trabalhador) deve estar autenticado no sistema. <br> 2. O usuário (trabalhador) deve ter acesso à internet. <br> 3. O usuário (trabalhador) deve ter o aplicativo da carteira de trabalho instalado em seu dispositivo móvel. <br> 4. O contrato de trabalho a ser atualizado deve estar registrado no sistema. |
| Fluxo Básico        | <b> FB04 </b> <ol> <li>O usuário (trabalhador) faz login no aplicativo da carteira de trabalho digital.</li> <li>O usuário (trabalhador) acessa a aba "Contratos de Trabalho".</li> <li>O usuário (trabalhador) seleciona o contrato que deseja atualizar.</li> <li>O usuário (trabalhador) verifica que os dados estão desatualizados e clica em "Atualizar" para solicitar a atualização.</li> <li>O sistema apresenta um formulário com os campos do contrato de trabalho para atualização.</li> <li>O usuário (trabalhador) modifica os dados necessários e confirma a atualização.</li> <li>O sistema valida as alterações e verifica a compatibilidade com os dados da empresa.</li> <li>Se os dados forem compatíveis, o sistema atualiza imediatamente o contrato de trabalho no perfil do usuário (trabalhador).</li> <li>Se os dados forem inconsistentes, o sistema notifica a empresa sobre a solicitação de atualização pendente.</li> <li>Após a atualização bem-sucedida, o sistema exibe uma mensagem de confirmação e retorna à visualização dos contratos de trabalho.</li> </ol> |
| Fluxos Alternativos | <b> FA04 </b> <ol> <li>O usuário (trabalhador) seleciona um campo opcional para atualização que não está disponível para alteração. <br> - O sistema exibe uma mensagem informando que o campo selecionado não pode ser alterado.</li> </ol> |
| Fluxos de exceção   | <b> FE04 </b> <ol> <li>Se ocorrer um erro na validação das alterações pelo sistema, uma mensagem de erro é exibida e o usuário (trabalhador) é orientado a corrigir os dados inseridos.</li> <li>Se houver um problema de comunicação com o banco de dados durante a atualização, uma mensagem de erro é exibida e o usuário (trabalhador) é instruído a tentar novamente mais tarde.</li> </ol> |
| Pós-condições       | O contrato de trabalho é atualizado com sucesso no perfil do usuário (trabalhador). |
| Data de Criação     | 18/05/2024                                                 |
| Rastreabilidade     | [F06](Elicitacao/ResquisitosCorrigidos.md), [F22](Elicitacao/ResquisitosCorrigidos.md), [NF18](Elicitacao/ResquisitosCorrigidos.md), [NF16](Elicitacao/ResquisitosCorrigidos.md)               |

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)
</center>

 </details>

### Trabalhador -  Realizar Denúncias Trabalhistas

A tabela 7 mostra quando o usuário(trabalhador) realiza denúnciar trabalhistas.

<details>
  <summary size="20"><b> Tabela 7: realiza denúnciar trabalhistas. </b></summary> 

 Tabela 7: Caso de Uso: Denúncias trabalhistas.

  | UC05                | Realizar Denúncias Trabalhistas                                                                           |
|---------------------|----------------------------------------------------------------------------------------------------------|
| Descrição           | Permitir que o trabalhador faça denúncias anônimas sobre questões trabalhistas através do aplicativo digital.      |
| Atores              | Trabalhador (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário); <br> Departamento/Órgão responsável (Usuário Secundário) |
| Frequência          | Conforme necessidade do usuário (trabalhador) para denunciar violações de direitos trabalhistas.          |
| Pré-condições       | O usuário (trabalhador) deve estar autenticado no sistema; <br> O usuário (trabalhador) deve possuir informações detalhadas sobre a denúncia; <br> O usuário (trabalhador) deve ter acesso à internet e ao aplicativo da carteira de trabalho digital instalado em seu dispositivo. |
| Fluxo Básico        | <b>FB05</b> <ol><li>O usuário (trabalhador) faz login no aplicativo da carteira de trabalho digital.</li> <li>O usuário (trabalhador) acessa a aba "Canal de Denúncias Trabalhistas".</li> <li>O usuário (trabalhador) inicia o processo de denúncia.</li> <li>O usuário (trabalhador) preenche os detalhes da denúncia, incluindo data, descrição do incidente e, opcionalmente, documentos ou mídias de suporte, como fotos ou áudios.</li> <li>O sistema verifica a consistência das informações fornecidas, incluindo a validade da data e a integridade dos documentos ou mídias anexadas.</li> <li>Se todas as informações estiverem corretas, a denúncia é enviada anonimamente para o departamento.</li> <li>O sistema exibe uma mensagem de confirmação para o usuário (trabalhador) informando que a denúncia foi enviada com sucesso.</li></ol> |
| Fluxos Alternativos | <b>FA05</b> <ol><li>O usuário (trabalhador) faz login no aplicativo da carteira de trabalho digital.</li> <li>O usuário (trabalhador) acessa a aba "Canal de Denúncias Trabalhistas".</li> <li>O usuário (trabalhador) inicia o processo de denúncia.</li> <li>O usuário (trabalhador) preenche parcialmente os detalhes da denúncia e decide salvar a denúncia como rascunho.</li> <li>O sistema salva os dados parcialmente preenchidos como rascunho.</li> <li>O usuário (trabalhador) pode acessar o rascunho posteriormente para completar e enviar a denúncia.</li> <li>O sistema exibe uma mensagem de confirmação informando que o rascunho foi salvo com sucesso.</li></ol> |
| Fluxos de exceção   | **FE05** <ol> <li>Se ocorrer um erro na validação das informações fornecidas pelo usuário (trabalhador): <ul><li>O sistema exibe uma mensagem de erro informando sobre a inconsistência dos dados.</li> <li>O usuário (trabalhador) é orientado a corrigir os dados inseridos.</li></ul> <li>Se os documentos ou mídias anexadas estiverem corrompidos ou não puderem ser verificados: <ul><li>O sistema exibe uma mensagem de erro informando que os arquivos anexados estão corrompidos ou não podem ser verificados.</li> <li>O usuário (trabalhador) é instruído a tentar novamente com arquivos válidos.</li></ul> </ol> |
| Pós-condições       | A denúncia é enviada anonimamente para o departamento responsável para investigação e ação adequada.       |
| Data de Criação     | 19/05/2024                                                                                                |
| Rastreabilidade     | [F10](Elicitacao/ResquisitosCorrigidos.md), [F09](Elicitacao/ResquisitosCorrigidos.md), [F25](Elicitacao/ResquisitosCorrigidos.md), [FN09](Elicitacao/ResquisitosCorrigidos.md), [NF22](Elicitacao/ResquisitosCorrigidos.md)                                                                                                   |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

</details>

### Trabalhador - Escolher Modo de Status de Procura de Emprego

A tabela 8 mostra quando o usuário(trabalhador) Escolhe Modo de Status de Procura de Emprego.

<details>
  <summary size="20"><b> Tabela 8: Escolher Modo de Status de Procura de Emprego. </b></summary> 
<center>
 Tabela 8: Caso de uso: Escolher Modo de Status de Procura de Emprego

 | UC06                  | Escolher Modo de Status                       |
|-----------------------|-----------------------------------------------|
| **Descrição**         | Permitir que o Usuário(trabalhador) escolha entre os modos de "Procurando Emprego" e "Não Procurando Emprego" para ajudá-lo na procura por empregos que sejam compatíveis com seu currículo. |
| **Atores**            | Usuário(trabalhador) (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário); <br> Empresas (Usuário Secundário). |
| **Frequência**        | Conforme necessidade do Usuário(trabalhador).         |
| **Pré-condições**     | 1. O Usuário(trabalhador) deve estar autenticado no sistema. <br> 2. O Usuário(trabalhador) deve ter seu currículo, de preferência, atualizado. |
| **Fluxo Básico**      | <b>FB06</b> <ol> <li>O Usuário(trabalhador) faz login no aplicativo da carteira de trabalho digital.</li> <li>O Usuário(trabalhador) acessa as configurações de perfil.</li> <li>O Usuário(trabalhador) seleciona o modo de status desejado: "Procurando Emprego" ou "Não Procurando Emprego".</li> <li>Se o Usuário(trabalhador) escolher o modo "Procurando Emprego", ele tem a opção de atualizar seu currículo e indicar a cidade onde está procurando emprego.</li> <li>O sistema analisa o currículo em relação aos requisitos de ofertas dadas pelas empresas.</li> <li>Se uma empresa tiver uma vaga compatível com os requisitos do currículo do Usuário(trabalhador), o sistema envia uma notificação ou e-mail informando sobre a vaga de emprego.</li> <li>O Usuário(trabalhador), ao conseguir a vaga desativa o modo "procurando emprego", ou seja, fica como "Não procurando emprego". <br> **Observação:** O usuário(trabalhador) pode ajustar o modo de status a qualquer momento, alternando entre "Procurando Emprego" e "Não Procurando Emprego".</li> </ol> |
| **Fluxos Alternativos** | **FA06** <ol> <li>Se o Usuário(trabalhador) não tiver interesse em atualizar seu currículo ou indicar uma cidade de interesse:<ul><li>O sistema exibe uma mensagem informando sobre a conclusão da ação sem alterações.</li></ul></li> </ol> |
| **Fluxos de Exceção** | **FE06** <ol> <li>Se ocorrer um erro na atualização do currículo ou na indicação da cidade de interesse:<ul><li>O sistema exibe uma mensagem de erro informando sobre a inconsistência dos dados.</li><li>O Usuário(trabalhador) é orientado a corrigir as informações inseridas.</li></ul></li><li>Se houver um problema de comunicação com o sistema de envio de currículos ou com a base de dados de vagas de emprego:<ul><li>O sistema exibe uma mensagem de erro informando sobre o problema de comunicação.</li><li>O Usuário(trabalhador) é instruído a tentar novamente mais tarde.</li></ul></li><li>Se o Usuário(trabalhador) escolher o modo "Procurando Emprego" mas não atualizar seu currículo ou indicar uma cidade de interesse:<ul><li>Uma mensagem de alerta é exibida recomendando a conclusão dessas ações para melhorar suas chances de encontrar emprego.</li></ul></li></ol> |
| **Pós-condições**     | O modo de status é atualizado no perfil do Usuário(trabalhador). |
| **Data de Criação**   | 19/05/2024                                     |
| **Rastreabilidade**   | [F15](Elicitacao/ResquisitosCorrigidos.md), [F14](Elicitacao/ResquisitosCorrigidos.md), [FN16](Elicitacao/ResquisitosCorrigidos.md), [NF20](Elicitacao/ResquisitosCorrigidos.md) , [NF22](Elicitacao/ResquisitosCorrigidos.md) |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

</details>

### Trabalhador exporta relatório de vínculos empregatícios

A tabela 9 mostra quando o usuário(trabalhador) exporta relatório de vínculos empregatícios.

<details>
  <summary size="20"><b> Tabela 9: Trabalhador exporta relatório de vínculos empregatícios </b></summary> 
<center>
 
<center>
Tabela 9: Caso de uso UC07

| UC07                | Exportar Relatório de Vínculos Empregatícios                                         |
| ------------------- | ---------------------------------------------------------------- |
| Descrição           | Permitir ao trabalhador gerar e exportar um relatório contendo todos os seus vínculos empregatícios registrados. |
| Atores              | Trabalhador (Usuário Primário); Sistema de Banco de Dados (Usuário Secundário); Órgão Governamental (Usuário Secundário) |
| Frequência          | Sempre que o trabalhador precisar de um relatório completo dos seus vínculos empregatícios. |
| Pré-condições       | O trabalhador deve estar autenticado no sistema e ter vínculos empregatícios registrados. |
| Fluxo Básico        | <b> FB07 </b> <ol> <li>O trabalhador faz login no aplicativo da carteira de trabalho digital. <li>O trabalhador acessa a aba "Relatórios". <li>O trabalhador seleciona a opção "Exportar Relatório de Vínculos". <li>O sistema exibe as opções de formato de exportação (por exemplo, PDF, Excel). <li>O trabalhador escolhe o formato desejado e confirma a exportação. <li>O sistema gera o relatório e disponibiliza para download. <li>O trabalhador baixa o relatório e conclui a tarefa. </ol> |
| Fluxos Alternativos | <b> FA07 </b> <ol> <li>Se o trabalhador optar por abandonar a tarefa, ele fecha o aplicativo ou volta à tela inicial sem completar o processo de exportação. </ol> |
| Fluxos de exceção   | <b> FE07 </b> <ol> <li>Se ocorrer um erro durante a geração do relatório, uma mensagem de erro é exibida e o trabalhador é orientado a tentar novamente mais tarde. <li>Se houver um problema de comunicação com o órgão governamental, uma mensagem de erro é exibida e o trabalhador é instruído a tentar novamente mais tarde. <li>Em dispositivos iOS, se o teclado virtual permanecer sobre o botão de "Concluir" na última etapa, inviabilizando a conclusão da tarefa. </ol> |
| Restrição           | <ol> <li>O trabalhador deve estar autenticado no sistema para exportar o relatório. <li>A conexão com a internet deve estar estável durante o processo de exportação do relatório. </ol> |
| Pós-condições       | O relatório de vínculos empregatícios do trabalhador é gerado e disponibilizado para download no formato escolhido. |
| Data de Criação     | 19/05/2024  |
| Rastreabilidade     | [RF01, RF02, RF07] |


**Fonte:** [Luana Medeiros](https://github.com/LuaMedeiros)

</center>

 </details>

### Consultar Seguro Desemprego

A tabela x mostra quando o usuário(trabalhador) consulta requerimentos de Seguro Desemprego.

<details>
  <summary size="20"><b> Tabela x: Consultar seguro desemprego. </b></summary> 
<center>
Tabela x: Caso de uso UC00

| UC01                | Solicitar Benefício                                              |
| ------------------- | ---------------------------------------------------------------- |
| Descrição           | Permitir que o trabalhador consulte requerimentos de seguro desemprego. |
| Atores              | Trabalhador (Usuário Primário); Sistema de Banco de Dados (Usuário Secundário); Órgão Governamental (Usuário Secundário) |
| Frequência          | Quando o trabalhador quiser verificar se atende aos requisitos de elegibilidade para o seguro-desemprego ou acompanhar seu requerimento.    |
| Pré-condições       | O trabalhador deve estar autenticado no sistema escolher a opção Benefícios. |
| Fluxo Básico        | <b> FB01 </b> <ol> <li>O trabalhador faz login no aplicativo da carteira de trabalho digital. <li>O trabalhador acessa a aba "Benefícios". <li>O trabalhador seleciona a opção Seguro Desemprego. <li>O trabalhador seleciona a opção consultar. <li>O trabalhador seleciona Seguro Desemprego ou Seguro Desemprego do empregado doméstico. <li>O sistema verifica a existência de requisições de seguro desemprego. <li>Se houverem requisições feitas, irão aparecer na tela.</ol> |
| Fluxos Alternativos | <b> FA01 </b> <ol> <li>Se o trabalhador acessar a opção Menu, Benefícios e Seguro Desemprego, ainda pode fazer a consulta da mesma maneira.</ol>             |
| Fluxos de exceção   | <b> FE01 </b> <ol> <li>Se não houverem requisições feitas pelo trabalhador para Seguro Desemprego, o aplicativo apresentará a mensagem "Não foram encontradas requerimentos de Seguro-Desemprego. </ol>             |
| Pós-condições       | Os requerimentos de Seguro Desemprego são mostrados na tela. |
| Data de Criação     | 19/05/2024                                                        |
| Rastreabilidade     | [Requisitos Funcionais F12]                              |

**Fonte:** [Pedro Izarias](https://github.com/Izarias)

</center>

 
## Bibliografia

<b>MINISTÉRIO DO TRABALHO E EMPREGO</b>. Passo a Passo Carteira de Trabalho Digital APP e WEB. 2023.

<b>SERRANO</b>, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: <https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf>. Acesso em: 14/05/2023.

<b>SERRANO</b>, Milene; SERRANO, Maurício. Requisitos – Aula 13. 2017. Apresentação de slides. Disponível em: <https://example.com/Requisitos-Aula-013a.pdf>. Acesso em: 19 mai. 2024.

## Histórico de Versão
| Versão | Alteração                | Responsável     | Revisor         | Data       |
| ------ | ------------------------ | --------------- | --------------- | ---------- |
| 1.0    | Criação da documentação  | Bruno Araújo    | Iago Passaglia  | 19/05/2024 |
| 1.1    | Caso de uso UC02         | Iago Passaglia  | Bruno Araújo    | 19/05/2024 |
| 1.2    | Correção da bibliografia | Breno Alexandre | Larissa Stéfane               | 19/05/2024 |
| 1.3    | Adição do caso de uso: Acessar Detalhes dos Contratos de Trabalho | Larissa Stéfane | - | 19/05/2024 |
| 1.4    | Adição do caso de uso: Atualização dos Contratos de Trabalho | Larissa Stéfane | - | 19/05/2024 |
| 1.5    | Adição do caso de uso: Denúncias trabalhistas. | Larissa Stéfane | - | 19/05/2024 |
| 1.6    | Adição do caso de uso: Escolher Modo de Status de Procura de Emprego | Larissa Stéfane | - | 19/05/2024 |
| 1.7    | Adição do caso de uso: Empresa anucia vagas/ofertas de emprego | Larissa Stéfane | - | 19/05/2024 |
| 1.8    | Adição do caso de uso: Empresa adiciona novos contratos de emprego | Larissa Stéfane | - | 19/05/2024 |
| 1.9    | Adição do caso de uso: Empresa atualiza contratos de emprego | Larissa Stéfane | - | 19/05/2024 |
| 2.0    | Adição do caso de uso: Empresa encerra contratos de emprego | Larissa Stéfane | - | 19/05/2024 |
| 2.1    | Compactar tabelas do caso 01 e 02 | Larissa Stéfane | - | 19/05/2024 |
| 2.2    | Atualiação do sumário | Larissa Stéfane | - | 19/05/2024 |
| 2.3    | Adição do caso de uso:Consultar Seguro Desemprego | Pedro Izarias | - | 19/05/2024 |
| 2.3    | Retirada de alguns caso de uso | Larissa Stéfane | - | 19/05/2024 | 
| 2.4    | Adição do caso de uso: Trabalhador exporta relatório de vínculos empregatícios| Luana Medeiros | - | 19/05/2024 | 
