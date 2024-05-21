# Cenários

## Sumário
* [Introdução](#Introdução)
* [Metodologia](#Metodologia)
* [Cenários](#Cenários)
* [Histórico de versão](#Histórico-de-versão)
* 
## Introdução

Um cenário é uma descrição detalhada de uma situação específica na qual o aplicação do Carteira de Trabalho Digital será utilizado. Esses cenários ajudam a capturar as necessidades e expectativas dos usuários, fornecendo contexto sobre como o software deve funcionar em condições reais. Eles são fundamentais para orientar o desenvolvimento e garantir que todas as funcionalidades relevantes sejam contempladas. Além disso, servem como uma base para testes, validação e refinamento dos requisitos ao longo do ciclo de vida do projeto.

## Metodologia

Para a elaboração dos cenários, cada um dos integrantes construiiu o cenário de acordo com uma funcionalidade específica. o layout base utilizado para a construção desse cenários está definido na tabela 0

**Tabela 0**: Modelo dos cenários.

| | |
| - | - |
|Denominação | Descrição breve da tarefa realizada |
|Objetivo/meta | Definição clara do que os atores desejam alcançar ao interagir com o sistema |
|Contexto | Descrição do ambiente ou situação em que o cenário ocorre, incluindo informações relevantes sobre o sistema e os usuários |
|Atores | Identificação dos principais usuários ou sistemas que interagem no cenário |
|Recursos | Referem-se aos elementos necessários para a execução e realização do cenário descrito |
|Episódios | Referem-se a sequências específicas de interações ou eventos que ocorrem dentro do cenário |
|Exceção | Situações anômalas ou de erro que podem ocorrer durante o fluxo de eventos que faça com que a tarefa não possa ser concluída |

Fonte: [Iago Passaglia](https://github.com/Paxxaglia)

## Cenários

## O Trabalhador (Funcionário com Carteira Assinada) como Protagonista do Cenário (Usuário primário)

### Visualizar aba "Emprego"

<details>
  <summary size="20"><b> Tabela 1: Trabalhador deseja visualizar aba "Emprego" </b></summary> 

<center>

| Denominação | Visualizar aba "Emprego" |
| - | - |
| Objetivo/meta | Permitir a visualização completa da aba "Emprego" por meio do cadastro de informações pessoais. |
| Contexto | **Contexto:** O usuário já possui um login ativo na plataforma Carteira de Trabalho Digital através do gov.br. O usuário deseja acessar todas as funcionalidades disponíveis na aba "Emprego" do aplicativo. <br> **Pré-condição:** O trabalhador deve estar autenticado no sistema. |
| Atores | Trabalhador (Usuário Primário);<br> Plataforma gov.br (Usuário Secundário) |
| Recursos | Smartphone;<br> Conexão à internet; <br> Aplicativo Carteira de Trabalho Digital instalado e atualizado;<br> Conta ativa no gov.br para login. |
| Episódios | 1. O trabalhador faz login no aplicativo da carteira de trabalho digital. <br> 2. O trabalhador acessa a aba "Emprego".<br> 3. O trabalhador seleciona a opção "Quero me cadastrar".<br> 4. O sistema exibe o formulário de "Dados Pessoais" <br> 5. O trabalhador preenche o formulário de "Dados Pessoais". <br> 6. O sistema exibe o formulário de "Endereço". <br> 7. O trabalhador preenche o formulário de "Dados Pessoais". <br> 8. O sistema exibe o formulário de "Contato".<br> 9. O trabalhador preenche o formulário de "Contato".<br> 10. O trabalhador envia os formulários e conclui a tarefa|
| Exceção | 1. Se ocorrer um erro na validação das informações, uma mensagem de erro é exibida e o trabalhador é orientado a corrigir os dados inseridos. <br> 2. Se houver um problema de comunicação com o órgão governamental, uma mensagem de erro é exibida e o trabalhador é instruído a tentar novamente mais tarde.<br> 3. Em dispositivos IOS, o teclado virtual permanece em cima do botão de "Concluir" na ultima etapa, o que inviabiliza a conclusão da tarefa. |
| Restrição | 1. O trabalhador deve estar autenticado no sistema para efetuar o cadastro. <br> 2. A conexão com a internet deve estar estável durante o processo de solicitação.|

**Fonte:** [Iago Passaglia](https://github.com/Paxxaglia)
</center>
</details>



### Consultar Seguro Desemprego 

<details>
  <summary size="20"><b> Tabela 2: Trabalhador deseja consultar Seguro Desemprego </b></summary> 

<center>

| Denominação | Consultar Seguro Desemprego |
| - | - |
| Objetivo/meta | Consultar requerimentos de Seguro Desemprego do usuário. |
| Contexto | **Contexto:** O usuário já possui um login ativo na plataforma Carteira de Trabalho Digital através do gov.br. O usuário deseja visualizar o requerimento feito para seu Seguro Desemprego. <br> **Pré-condição:** O trabalhador deve estar autenticado no sistema. |
| Atores | Trabalhador (Usuário Primário);<br> Plataforma gov.br (Usuário Secundário) |
| Recursos | Smartphone ou tablet;<br> Conexão à internet; <br> Aplicativo Carteira de Trabalho Digital instalado e atualizado;<br> Conta ativa no gov.br para login. |
| Episódios | 1. O trabalhador faz login no aplicativo da carteira de trabalho digital. <br> 2. O trabalhador acessa a aba "Menu".<br> 3. O trabalhador seleciona a opção "Benefícios".<br> 4. O trabalhador seleciona a opção "Seguro-Desemprego" <br> 5. O trabalhador seleciona a opção consultar. <br> 6. O sistema exibe os requerimentos feitos pelo usuário para Seguro Desemprego. |
| Exceção | 1. Se não houverem requerimentos de Seguro Desemprego realizados, a seguinte mensagem é exibida: "Não foram encontrados requerimentos de Seguro Desemprego". |
| Restrição | 1. O trabalhador deve estar autenticado no sistema para efetuar o cadastro. <br> 2. A conexão com a internet deve estar estável durante o processo de consulta.|

**Fonte:** [Pedro Izarias](https://github.com/Izarias)
</center>
</details>

### Solicitar um benefício

<details>
  <summary size="20"><b> Tabela 3: Trabalhador deseja solicitar um benefício </b></summary> 

<center>

## Solicitar benefício

**Tabela 3**: Solicitar Benefício

| Denominação | Solicitar Benefício | 
| - | - |
| Objetivo/meta | Permite que o trabalhador solicite um benefício, como seguro-desemprego ou auxílio-doença. |
| Contexto | **Contexto:** O trabalhador precisa solicitar um benefício disponível através do aplicativo da carteira de trabalho digital. <br> **Local:** Na aba "Benefícios". <br> **Tempo:** O processo de solicitação pode levar de 10 a 20 minutos, dependendo da complexidade do benefício solicitado. <br> **Pré-condição:** O trabalhador deve estar autenticado no sistema e ter os documentos necessários para a solicitação. |
| Atores | Trabalhador (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário); <br> Órgão Governamental (Usuário Secundário) |
| Recursos | Aplicativo da carteira de trabalho digital; <br> Conexão à internet; <br> Banco de dados de benefícios. |
| Episódios | 1. O trabalhador faz login no aplicativo da carteira de trabalho digital. <br> 2. O trabalhador acessa a aba "Benefícios". <br> 3. O trabalhador seleciona o benefício desejado. <br> 4. O sistema exibe os requisitos e documentos necessários para a solicitação do benefício. <br> 5. O trabalhador preenche o formulário de solicitação e anexa os documentos necessários. <br> 6. O sistema verifica a consistência das informações e documentos fornecidos. <br> 7. Se todas as informações estiverem corretas, o sistema envia a solicitação para o órgão governamental responsável. <br> 8. O trabalhador recebe uma confirmação de que a solicitação foi enviada com sucesso. |
| Exceção | 1. Se ocorrer um erro na validação das informações ou documentos, uma mensagem de erro é exibida e o trabalhador é orientado a corrigir os dados inseridos. <br> 2. Se houver um problema de comunicação com o órgão governamental, uma mensagem de erro é exibida e o trabalhador é instruído a tentar novamente mais tarde. <br> 3. Se a solicitação for rejeitada pelo órgão governamental, o trabalhador recebe uma notificação com o motivo da rejeição. |
| Restrição | 1. O trabalhador deve estar autenticado no sistema para solicitar um benefício. <br> 2. Os documentos anexados devem estar em conformidade com os requisitos especificados pelo órgão governamental. <br> 3. A conexão com a internet deve estar estável durante o processo de solicitação. |

**Fonte:** [Bruno Araújo](https://github.com/brunocva)
</center>
</details>



### Atualização dos Contratos de Trabalho

A tabela 4 mostra o cenário para quando um trabalhador deseja atualizar seus contratos de trabalho

<details>
  <summary size="20"><b> Tabela 4: Trabalhador deseja atualizar dados de Contratos de Trabalho </b></summary> 

<center>

**Tabela 4**: Atualização dos Contratos de Trabalho

| Denominação | Atualização de Contrato |
| - | - |
| Objetivo/meta | Permitir que o trabalhador atualize as informações de um contrato de trabalho existente. |
| Contexto | **Contexto:** O trabalhador precisa fazer uma alteração em um contrato devido a uma mudança nas condições de emprego ou desafagem dos dados. <br> **Local:** Na aba "Contratos de Trabalho"  <br> **Tempo:** A atualização de dados pode levar de 5 a 10 minutos, dependendo da quantidade de informações a serem alteradas. <br> **Pré-condição:**  O trabalhador deve estar autenticado no sistema e ter as informações necessárias para a atualização. |
| Atores | Trabalhador (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário); <br> Empresa (Usuário Secundário) |
| Recursos | Aplicativo da carteira de trabalho digital; <br> Conexão à internet; <br> Banco de dados de contratos de trabalho. |
| Episódios | 1. O trabalhador faz login no aplicativo da carteira de trabalho digital. <br> 2. O trabalhador acessa a aba "Contratos de Trabalho". <br> 3. O trabalhador seleciona o contrato que deseja verificar. <br> 4. O trabalhador verifica que os dados estão desatualizados e clica em "Atualizar" para solicitar a atualização. <br> 5. O trabalhador indica quais dados deseja atualizar (Já os modificando). <br> 6. O sistema verifica se os dados indicados pelo trabalhador são compatíveis com os dados declarados pela empresa. <br> 7. Se os dados forem compatíveis, o sistema atualiza imediatamente o contrato de trabalho no perfil do trabalhador. <br> 8. Se os dados forem inconsistentes, o sistema envia uma notificação para a empresa informando sobre a solicitação de atualização pendente. <br> 9. Se a empresa atualizar os dados, o sistema atualiza o contrato no perfil do trabalhador. |
| Exceção | 1. Se ocorrer um erro na validação das alterações pelo sistema, uma mensagem de erro é exibida e o trabalhador é orientado a corrigir os dados inseridos. <br> 2. Se houver um problema de comunicação com o banco de dados durante a atualização, uma mensagem de erro é exibida e o trabalhador é instruído a tentar novamente mais tarde. |
| Restrição | 1. O trabalhador só pode atualizar contratos dos quais ele seja o titular. <br> 2. As alterações devem estar de acordo com as políticas e regulamentos da empresa. <br> 3. A conexão com a internet deve estar estável durante o processo de atualização. <br> 4. Após um ano sem atualização por parte da empresa, o sistema envia uma nova notificação lembrando sobre a pendência. |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

 </center> 
 </details>

### Canal de Denúncias

A tabela 5 mostra o cenário para quando um trabalhador deseja relacionar uma denúncia sobre a empresa onde trabalha.

<details>
  <summary size="20"><b> Tabela 5: Trabalhador no Canal de Denúncias </b></summary> 

<center>
  
**Tabela 5**:  Trabalhador no Canal de Denúncias


| Denominação | Realizar Denúncias Trabalhistas |
| - | - |
| Objetivo/meta | Permitir que o trabalhador faça denúncias sobre questões trabalhistas. |
| Contexto |  **Contexto:** O trabalhador identifica uma situação de violação dos direitos trabalhistas e deseja denunciar anonimamente para o orgão apropriado. <br> **Local:** Na aba "Canal de Denúncias Trabalhistas".  <br> **Tempo:** O preenchimento e envio da denúncia pode levar de 15 a 20 minutos, dependendo do nível de detalhe fornecido.  <br> **Pré-condição:** O trabalhador deve estar autenticado no sistema e possuir informações detalhadas sobre a denúncia.|
| Atores | Trabalhador (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário); <br> Departamento/ Orgão responsável (Usuário Secundário) |
| Recursos | Aplicativo da carteira de trabalho digital; <br> Conexão à internet; <br> Banco de dados de denúncias trabalhistas <br> Comunicação com orgão que recebe denúncias|
| Episódios | 1. O trabalhador faz login no aplicativo da carteira de trabalho digital. <br> 2. O trabalhador acessa a aba "Canal de Denúncias Trabalhistas". <br> 3. O trabalhador inicia o processo de denúncia. <br> 4. O trabalhador preenche os detalhes da denúncia, incluindo data, descrição do incidente e, opcionalmente, documentos ou mídias de suporte, como fotos ou áudios. <br> 5. O sistema verifica a consistência das informações fornecidas, incluindo a validade da data e a integridade dos documentos ou mídias anexadas. <br> 6. Se todas as informações estiverem corretas, a denúncia é enviada anonimamente para o departamento. <br> 7. O sistema exibe uma mensagem de confirmação para o trabalhador informando que a denúncia foi enviada com sucesso. |
| Exceção | 1. Se ocorrer um erro na validação das informações fornecidas pelo trabalhador, uma mensagem de erro é exibida e o trabalhador é orientado a corrigir os dados inseridos. <br> 2. Se os documentos ou mídias anexadas estiverem corrompidos ou não puderem ser verificados, uma mensagem de erro é exibida e o trabalhador é instruído a tentar novamente com arquivos válidos. |
| Restrição | 1. O trabalhador deve garantir que as informações fornecidas sejam precisas e completas. <br> 2. A denúncia será tratada anonimamente e encaminhada para o departamento para investigação e ação adequada. |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

 </center> 
 </details>

### Escolher Modo de Status de Procura de Emprego


A tabela 6 mostra o cenário para quando um trabalhador deseja escolher o seu modo de status em relação a procura de emprego

<details>
  <summary size="20"><b> Tabela 6: Trabalhador deseja escolher Modo de Status de Procura de Emprego </b></summary> 

<center>

**Tabela 6**:  Escolher Modo de Status de Procura de Emprego

| Denominação | Escolher Modo de Status |
| - | - |
| Objetivo/meta | Permitir que o trabalhador escolha entre os modos de "Procurando Emprego" e "Não Procurando Emprego" para ajudá-lo na procura por empregos que sejam compatíveis com seu currículo. |
| Contexto |  **Contexto:** O trabalhador está ativamente procurando emprego e deseja indicar sua disponibilidade para receber notificações sobre vagas/ofertas compatíveis com seu perfil. <br> **Local:**  Nas configurações de perfil.  <br> **Tempo:** A seleção e atualização do modo de status pode levar de 3 a 45 minutos (se tiver que atualizar o currículo). <br> **Pré-condição:** O trabalhador deve estar autenticado no sistema e ter seu currículo, de preferência, atualizado. |
| Atores | Trabalhador (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário); <br> Empresas (Usuário Secundário) |
| Recursos | Aplicativo da carteira de trabalho digital; <br> Conexão à internet <br> Banco de dados de currículos e vagas de emprego. |
| Episódios | 1. O trabalhador faz login no aplicativo da carteira de trabalho digital. <br> 2. O trabalhador acessa as configurações de perfil e seleciona o modo de status desejado: "Procurando Emprego" ou "Não Procurando Emprego". <br> 3. Se o trabalhador escolher o modo "Procurando Emprego", ele tem a opção de atualizar seu currículo e indicar a cidade onde está procurando emprego. <br> 4. Após atualizar, o sistema analisa o currículo em relação aos requisitos de ofertas dadas pelas empresas. <br> 5. Se uma empresa tiver uma vaga compatível com os requisitos do currículo do trabalhador, o sistema envia uma notificação ou e-mail informando sobre a vaga de emprego. <br> 6. O trabalhador pode ajustar o modo de status a qualquer momento, alternando entre "Procurando Emprego" e "Não Procurando Emprego". |
| Exceção | 1. Se ocorrer um erro na atualização do currículo ou na indicação da cidade de interesse, uma mensagem de erro é exibida e o trabalhador é orientado a corrigir as informações inseridas. <br> 2. Se houver um problema de comunicação com o sistema de envio de currículos ou com a base de dados de vagas de emprego, uma mensagem de erro é exibida e o trabalhador é instruído a tentar novamente mais tarde. <br> 3. Se o trabalhador escolher o modo "Procurando Emprego" mas não atualizar seu currículo ou indicar uma cidade de interesse, uma mensagem de alerta é exibida recomendando a conclusão dessas ações para melhorar suas chances de encontrar emprego. |
| Restrição | 1. O trabalhador deve manter seu currículo atualizado para receber notificações sobre vagas de emprego compatíveis. <br>  2. A cidade de interesse indicada pelo trabalhador deve ser válida e reconhecida pelo sistema. |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center> 
 </details>

### Exportar Relatório de Vínculos Empregatícios


A tabela 7 mostra o cenário para quando um trabalhador deseja Exportar Relatório de Vínculos Empregatícios

<details>
  <summary size="20"><b> Tabela 7: Trabalhador deseja Exportar Relatório de Vínculos Empregatícios </b></summary> 

<center>

**Tabela 7**: Exportar Relatório de Vínculos Empregatícios

| Denominação | Exportar Relatório de Vínculos Empregatícios |
| - | - |
| Objetivo/meta | Permitir que o trabalhador gere e exporte um relatório completo dos seus vínculos empregatícios. |
| Contexto      | *Contexto:* O usuário já possui um login ativo na plataforma Carteira de Trabalho Digital através do gov.br. O usuário deseja obter um relatório detalhado de todos os seus vínculos empregatícios registrados. <br> *Pré-condição:* O trabalhador deve estar autenticado no sistema e ter vínculos empregatícios registrados.|
| Atores        | Trabalhador (Usuário Primário); Sistema de Banco de Dados (Usuário Secundário); Órgão Governamental (Usuário Secundário) |
| Recursos      | Smartphone <br> Conexão à internet <br> Aplicativo Carteira de Trabalho Digital instalado e atualizado <br> Conta ativa no gov.br para login |
| Episódios     | <ol> <li>O trabalhador faz login no aplicativo da carteira de trabalho digital. <li>O trabalhador acessa a aba "Relatórios". <li>O trabalhador seleciona a opção "Exportar Relatório de Vínculos". <li>O sistema exibe as opções de formato de exportação (por exemplo, PDF, Excel). <li>O trabalhador escolhe o formato desejado e confirma a exportação. <li>O sistema gera o relatório no formato escolhido. <li>O sistema disponibiliza o relatório para download. <li>O trabalhador baixa o relatório e conclui a tarefa. </ol> |
| Exceção       | <ol> <li>Se ocorrer um erro durante a geração do relatório, uma mensagem de erro é exibida e o trabalhador é orientado a tentar novamente mais tarde. <li>Se houver um problema de comunicação com o órgão governamental, uma mensagem de erro é exibida e o trabalhador é instruído a tentar novamente mais tarde. <li>Em dispositivos iOS, se o teclado virtual permanecer sobre o botão de "Concluir" na última etapa, o que inviabiliza a conclusão da tarefa. </ol> |
| Restrição     |  <ol> <li>O trabalhador deve estar autenticado no sistema para exportar o relatório. <li>A conexão com a internet deve estar estável durante o processo de exportação do relatório. </ol> |


**Fonte:** [Luana Medeiros](https://github.com/LuaMedeiros)
</center>
</details>

### Atualização das Informações pessoais

A tabela 8 mostra o cenário para quando um trabalhador deseja atualizar suas informações pessoais.

<details>
  <summary size="20"><b> Tabela 8: Trabalhador deseja atualizar suas informações pessoais. </b></summary> 

<center>

**Tabela 8**: Atualização das informações pessoais.

| Denominação | Atualização de informações |
| - | - |
| Objetivo/meta | Permitir que o trabalhador atualize suas informações pessoais no sistema, como endereço, telefone e email. |
| Contexto | **Contexto:** O trabalhador mudou de endereço ou alterou seu número de telefone/email e deseja atualizar essas informações no sistema.  <br> **Local:** Na aba "Configurações de Conta" no aplicativo.  <br> **Tempo:**  A atualização de informações pessoais pode levar de 5 a 10 minutos. <br> **Pré-condição:** O trabalhador deve estar autenticado no sistema.  |
| Atores | Trabalhador (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário).  |
| Recursos | Aplicativo da carteira de trabalho digital; <br> Conexão à internet. <br> Dados atualizados em mãos.|
| Episódios |1. O trabalhador faz login no aplicativo da carteira de trabalho digital. <br> 2. O trabalhador acessa a aba "Configurações de Conta" e seleciona "Atualizar Informações Pessoais". <br> 3. O sistema exibe um formulário com as informações pessoais atuais do trabalhador. <br> 4. O trabalhador altera as informações desejadas (endereço, telefone, email, etc.). <br> 5. O trabalhador confirma as alterações e envia o formulário. <br> 6. O sistema verifica as informações e atualiza os dados no banco de dados. <br> 7. O sistema exibe uma mensagem de confirmação informando que as informações foram atualizadas com sucesso.  |
| Exceção | 1. Se ocorrer um erro na validação das informações, o sistema exibe uma mensagem de erro e solicita que o trabalhador corrija os dados inseridos. <br> 2. Se a conexão com a internet for interrompida, o sistema solicita que o trabalhador tente novamente mais tarde. |
| Restrição |  1. O trabalhador deve estar autenticado no sistema. <br> 2. As informações fornecidas devem ser válidas e completas. <br> 3. A conexão com a internet deve estar estável. |

**Fonte:** [Caio Mesquita](https://github.com/Caiomesvie)

 </center> 
 </details>

 ### Verificar direitos trabalhistas do contrato atual

 A tabela 9 mostra o cenário para quando um trabalhador deseja verificar os direitos caso seja demitido sem justa causa.

<details>
  <summary size="20"><b> Tabela 9: Trabalhador deseja verificar os direitos caso seja demitido sem justa causa. </b></summary>

<center>
<p align="center"> Tabela 9: Trabalhador deseja verificar os direitos caso seja demitido sem justa causa. </p>

| Denominação | Verificar direitos trabalhistas do contrato atual |
| ----------- | ------------------------------------------------- |
| Objetivo/meta | Permitir a visualização completa da opção "Direitos" na aba "Benefícios" do aplicativo.
| Contexto | <b>Contexto:</b> O usuário já possui um login ativo na plataforma Carteira de Trabalho Digital através do gov.br. O usuário deseja acessar todas as funcionalidades disponíveis da opção “Direitos” na aba "Benefícios" do aplicativo. <b>Pré-condição:</b> O trabalhador deve estar autenticado no sistema.
| Atores | Trabalhador (Usuário Primário).
| Recursos | Smartphone; Conexão à internet; Aplicativo Carteira de Trabalho Digital instalado e atualizado; Conta ativa no gov.br para login.
| Episódios | 1. O trabalhador faz login no aplicativo da carteira de trabalho digital. 2. O trabalhador acessa a aba "Benefícios". 3. O trabalhador seleciona a opção “Direitos”. 4. O sistema exibe os direitos em forma de tópicos, além de cálculos nos valores que dependem de outros valores e porcentagens. 
| Exceção | 1. Se o usuário (trabalhador) acessar a página de direitos e lá estiver vazia ou não é exibida corretamente, o aplicativo exibe uma mensagem de erro informando que não foi possível carregar e recomenda tentar novamente mais tarde. 2. Se o usuário (trabalhador) acessar a página de direitos e o aplicativo exibe uma mensagem de erro informando que não foi possível carregar, aparecerá uma mensagem falando que recomenda tentar novamente mais tarde.
| Restrição | 1. O trabalhador deve estar autenticado no sistema para efetuar o cadastro. 2. A conexão com a internet deve estar estável durante o processo de solicitação.

<b>Fonte:</b> <a href="https://github.com/brenoalexandre0"> Breno Alexandre </a>.

</center>
</details>

### Consultar dados de INSS e FGTS

A tabela 10 mostra o cenário para quando um trabalhador deseja verificar dados relacionados ao FGTS e INSS.


<details>
  <summary size="20"><b> Tabela 10: Trabalhador deseja verificar dados relacionados ao FGTS e INSS </b></summary> 

<center>

**Tabela 10**: Trabalhador na Verificação de Dados do FGTS e INSS

| Denominação | Verificação de Dados do FGTS e INSS |
| - | - |
| Objetivo/meta | Permitir que o trabalhador visualize e verifique os dados do FGTS e INSS, e seja informado sobre quaisquer inconsistências nas informações. |
| Contexto | **Contexto:** O trabalhador deseja acompanhar suas contribuições ao FGTS e INSS, verificando se estão corretas e atualizadas. <br> **Local:** Na aba "Dados do FGTS/INSS" do aplicativo. <br> **Tempo:** A consulta dos dados pode levar de 2 a 5 minutos. <br> **Pré-condição:** O trabalhador deve estar autenticado no sistema e ter o aplicativo da carteira de trabalho digital instalado. |
| Atores | Trabalhador (Usuário Primário); <br>  Aplicativo do governo também relacionado ao meio trabalhista(Usuário Secundário); <br> Empresa (Usuário Secundário, em caso de inconsistência). |
| Recursos | Aplicativo da carteira de trabalho digital; <br> Conexão à internet; <br> Aplicativo com dados do FGTS e INSS. |
| Episódios | 1. O trabalhador faz login no aplicativo da carteira de trabalho digital. <br> 2. O trabalhador acessa a aba "Dados do FGTS/INSS". <br> 3. O trabalhador seleciona o dado que deseja verificar (FGTS ou INSS). <br> 4. O sistema recupera e exibe os dados relacionados ao FGTS ou INSS. <br> 5. O trabalhador visualiza as informações em forma de gráficos ou tabelas. <br> 6. O trabalhador verifica se as contribuições estão corretas e atualizadas. <br> 7. Se o sistema detectar uma inconsistência (por exemplo, falta de pagamento), uma mensagem de alerta é exibida ao trabalhador. <br> 8. O trabalhador pode clicar no alerta para obter mais informações sobre a inconsistência. <br> 9. O trabalhador é orientado a entrar em contato com a empresa ou órgão responsável para resolver a inconsistência. |
| Exceção | 1. Se ocorrer um erro na recuperação dos dados, uma mensagem de erro é exibida e o trabalhador é instruído a tentar novamente mais tarde. <br> 2. Se os dados do FGTS/INSS estiverem incompletos ou corrompidos, uma mensagem de erro é exibida e o trabalhador é orientado a entrar em contato com o suporte técnico. |
| Restrição | 1. O trabalhador só pode verificar os dados relacionados ao seu próprio FGTS e INSS. <br> 2. A conexão com a internet deve estar estável durante a verificação dos dados. <br> 3. O sistema deve estar integrado com os dados oficiais do FGTS e INSS. |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>
</details>

## Bibliografia

<b>BRASIL</b>. Ministério do Trabalho e Emprego. Passo a passo CTPS Digital APP e WEB. Disponível em: https://empregabrasil.mte.gov.br/wp-content/uploads/2023/02/Passo_a_Passo_CTPSDigital_APP_e_WEB.pdf. Acesso em: 19 maio 2024.

<b>UNIVERSIDADE DE BRASÍLIA</b>. Requisitos - Aula 013a. Disponível em: https://aprender3.unb.br/pluginfile.php/2845007/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf. Acesso em: 19 maio 2024.


## Histórico de Versão

| Versão | Alteração                                                                             | Responsável     | Revisor         | Data       |
| ------ | ------------------------------------------------------------------------------------- | --------------- | --------------- | ---------- |
| 1.0    | Criação do cenário de trabalhador Visualizar Dados de Contratos de Trabalho           | Larissa Stéfane | Bruno Araújo    | 18/05/2024 |
| 1.1    | Criação do cenário de trabalhador Atualizar dos Contratos de Trabalho                 | Larissa Stéfane | Bruno Araújo    | 18/05/2024 |
| 1.2    | Criação do cenário de trabalhador em canal de denúncias                               | Larissa Stéfane | Bruno Araújo    | 18/05/2024 |
| 1.3    | Criação do cenário de trabalhador escolhe Modo de Status de Procura de Emprego        | Larissa Stéfane | Bruno Araújo    | 18/05/2024 |
| 1.4    | Criação do cenário de empresa escolhe Modo de Status de oferta de Emprego             | Larissa Stéfane | Bruno Araújo    | 18/05/2024 |
| 1.5    | Criação do cenário de empresa adiciona novos contratos de trabalho                    | Larissa Stéfane | Bruno Araújo    | 18/05/2024 |
| 1.6    | Criação do cenário de empresa atualiza contratos de trabalho                          | Larissa Stéfane | Bruno Araújo    | 18/05/2024 |
| 1.7    | Criação do cenário de empresa encerra contratos de trabalho                           | Larissa Stéfane | Bruno Araújo    | 18/05/2024 |
| 1.8    | Adição de introdução, metodologia e desenvolvimento do modelo de tabela para cenários | Iago Passaglia  | Bruno Araújo    | 19/05/2024 |
| 1.9    | Criação do cenário Solicitar Benefício                                                | Bruno Araújo    | Caio Mesquita   | 19/05/2024 |
| 2.0    | Retirada de 5 Cenários                                                                | Larissa Stéfane | Pedro Izarias   | 19/05/2024 |
| 2.1    | Adição do cenário de consulta de seguro desemprego                                    | Pedro Izarias   | Iago Passaglia  | 19/05/2024 |
| 2.2    | Criação do cenário de trabalhador Exportar Relatório de Vínculos Empregatícios        | Luana Medeiros  | Iago Passaglia  | 19/05/2024 |
| 2.3    | Criação do cenário de trabalhador Atualizar informações pessoais                      | Caio Mesquita   | Pedro Izarias   | 19/05/2024 |
| 2.4    | Criação do cenário de trabalhador Verificar direitos trabalhistas                     | Breno Alexandre | Pedro Izarias   | 19/05/2024 |
| 2.5    | Criação do cenário de trabalhador visualiza dados trabalhistas (FGTS e INSS)          | Larissa Stéfane | Breno Alexandre | 20/05/2024 |
