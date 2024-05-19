# Cenários

## Sumário
* [Introdução](#Introdução)
* [Metodologia](#Metodologia)
* [Histórico de versão](#Histórico-de-versão)
## Introdução

Um cenário é uma descrição detalhada de uma situação específica na qual o aplicação do Carteira de Trabalho Digital será utilizado. Esses cenários ajudam a capturar as necessidades e expectativas dos usuários, fornecendo contexto sobre como o software deve funcionar em condições reais. Eles são fundamentais para orientar o desenvolvimento e garantir que todas as funcionalidades relevantes sejam contempladas. Além disso, servem como uma base para testes, validação e refinamento dos requisitos ao longo do ciclo de vida do projeto.

## Metodologia

Para a elaboração dos cenários, cada um dos integrantes construiiu o cenário de acordo com uma funcionalidade específica. o layout base utilizado para a construção desse cenários está definido na tabela 0

<center>
Tabela 0:

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
<center>

## Cenários

## O Trabalhador (Funcionário com Carteira Assinada) como Protagonista do Cenário (Usuário primário)

### Visualizar Dados de Contratos de Trabalho 

A tabela 1 mostra o cenário para quando um trabalhador deseja visualizar os seus dados de trabalho. 

<details>
  <summary size="20"><b> Tabela 1: Trabalhador deseja visualizar Dados de Contratos de Trabalho </b></summary> 

<center>

**Tabela 1**: Visualizar Dados de Contratos de Trabalho 

| Denominação | Acessar Detalhes dos Contratos de Trabalho |
| - | - | 
| Objetivo/meta | Permitir ao trabalhador visualizar os detalhes dos seus vínculos trabalhistas, incluindo anotações, observações e gráficos sobre sua vida laboral. |
| Contexto | **Contexto**: O trabalhador deseja consultar informações detalhadas sobre seus contratos de trabalho, incluindo histórico de remunerações e outras anotações importantes. <br> **Local**: Na aba "Contratos de Trabalho". <br> **Tempo**: O processo de visualização dos dados é imediato, geralmente leva de 1 a 4 minutos para carregar e visualizar as informações. <br> **Pré-condição**: O trabalhador deve estar autenticado no sistema.|
| Atores | Trabalhador (Usuário Primário); <br>  Sistema de Banco de Dados (Usuário Secundário). |
| Recursos | Aplicativo da carteira de trabalho digital; <br>  Conexão à internet; <br>  Banco de dados de contratos de trabalho. |
| Episódios | 1. O trabalhador faz login no aplicativo da carteira de trabalho digital. <br> 2. O trabalhador clica no ícone "Contratos de Trabalho" na interface do aplicativo. <br> 3. O sistema recupera e exibe uma lista de todos os contratos de trabalho do trabalhador. <br> 4. O trabalhador seleciona um contrato específico da lista. <br> 5. O sistema exibe os detalhes do contrato selecionado, incluindo: <br> - Período trabalhado <br> - Endereço do empregador <br> - Ocupação inicial <br> - Tipo de contrato <br> - Salário contratual <br> - Remuneração inicial e última remuneração informada <br> - Relação de trabalho <br> - Tipo de admissão <br> - Fonte da informação <br> 6. O trabalhador pode visualizar anotações e observações relacionadas ao contrato. <br> 7. O trabalhador pode visualizar gráficos que mostram o histórico de remunerações ao longo do tempo. |
| Exceção | 1. Se ocorrer um erro na recuperação dos dados, o sistema exibe uma mensagem de erro apropriada e sugere ações corretivas, como tentar novamente mais tarde ou verificar a conexão com a internet. <br> 2. Se o trabalhador não tiver contratos de trabalho registrados, o sistema exibe uma mensagem informando que não há contratos disponíveis. <br> 3. Se a sessão do trabalhador expirar durante a consulta, o sistema redireciona o trabalhador para a página de login com uma mensagem de sessão expirada. <br> 4. Se houver um problema de comunicação com o banco de dados, o sistema exibe uma mensagem de erro e pede para tentar novamente mais tarde. <br> 5. Se os dados do contrato forem incompletos ou estiverem corrompidos, o sistema exibe uma mensagem de erro e orienta o trabalhador a entrar em contato com o suporte técnico. |
| Restrição | 1. O trabalhador deve estar autenticado no sistema para acessar os detalhes dos contratos de trabalho. <br> 2. A conexão com a internet deve estar estável. <br> 3. O sistema deve ter acesso contínuo ao banco de dados. <br> 4. Os dados exibidos devem estar atualizados e sincronizados com as informações mais recentes do banco de dados oficial. |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

 </center> 
 </details>

### Atualização dos Contratos de Trabalho

A tabela 2 mostra o cenário para quando um trabalhador deseja atualizar seus contratos de trabalho

<details>
  <summary size="20"><b> Tabela 2: Trabalhador deseja atualizar dados de Contratos de Trabalho </b></summary> 

<center>

**Tabela 2**: Atualização dos Contratos de Trabalho

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

A tabela 3 mostra o cenário para quando um trabalhador deseja relacionar uma denúncia sobre a empresa onde trabalha.

<details>
  <summary size="20"><b> Tabela 3: Trabalhador no Canal de Denúncias </b></summary> 

<center>
  
**Tabela 3**:  Trabalhador no Canal de Denúncias


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


A tabela 4 mostra o cenário para quando um trabalhador deseja escolher o seu modo de status em relação a procura de emprego

<details>
  <summary size="20"><b> Tabela 4: Trabalhador deseja escolher Modo de Status de Procura de Emprego </b></summary> 

<center>

**Tabela 4**:  Escolher Modo de Status de Procura de Emprego

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

## A Empresa como Protagonista do Cenário (Usuária primária)

### Escolher Modo de Status de Oferta de Emprego

A tabela 5 mostra o cenário para quando uma empresa deseja divulgar que está com oferta de empregos

<details>
  <summary size="20"><b> Tabela 5: Empresa deseja escolher Modo de Status de oferta de Emprego </b></summary> 

<center>

**Tabela 5**:  Escolher Modo de Status de Oferta de Emprego

| Denominação | Escolher Modo de Status de Oferta de Emprego |
| - | - |
| Objetivo/meta | Permitir que a empresa ative o modo de "Vagas de Emprego" para buscar por funcionários e desative-o quando não houver mais vagas disponíveis. |
| Contexto |  **Contexto:** A empresa tem vagas de emprego disponíveis e deseja ativar o modo de "Vagas de Emprego" para buscar candidatos qualificados. <br> **Local:** Nas configurações de perfil. <br> **Tempo:** A ativação ou desativação do modo de status de oferta de emprego pode levar de 5 a 10 minutos. <br> **Pré-condição:** A empresa deve estar autenticada no sistema e ter as vagas de emprego definidas.|
| Atores | Empresa (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário); <br> Trabalhador (Usuário Secundário). |
| Recursos | Aplicativo da carteira de trabalho digital da empresa; <br> Conexão à internet; <br> Banco de dados de currículos; <br> Perfis de trabalhadores. |
| Episódios | 1. A empresa faz login no aplicativo da carteira de trabalho digital e acessa as configurações de perfil. <br> 2. A empresa seleciona a opção de ativar o modo de "Vagas de Emprego" e preenche os requisitos necessários para a vaga, como cargo, habilidades requeridas e localização. <br> 3. O sistema compara os requisitos da vaga com os dados dos currículos dos trabalhadores que têm o status de "Procurando Emprego". <br> 4. Se um currículo corresponder aos requisitos da vaga, o sistema envia uma notificação ou e-mail para o trabalhador informando sobre a oportunidade de emprego e solicitando que entre em contato com a empresa. <br> 5. Quando a empresa não tem mais vagas disponíveis, ela acessa as configurações de perfil e seleciona a opção de desativar o modo de "Vagas de Emprego". |
| Exceção | 1. Se houver um erro na ativação ou desativação do modo de "Vagas de Emprego", uma mensagem de erro é exibida e a empresa é orientada a tentar novamente. <br> 2. Se não houver currículos correspondentes aos requisitos da vaga, o sistema exibe uma mensagem informando que não foram encontrados candidatos compatíveis no momento. |
| Restrição | 1. A empresa deve fornecer requisitos claros e precisos para as vagas de emprego. <br> 2. A cada três meses, o sistema verifica se a empresa está com o modo "Vagas de Emprego" ativado por mais de três meses consecutivos. Se a empresa estiver com o modo ativado por mais de três meses, o sistema envia uma mensagem de lembrete para verificar se ainda há vagas disponíveis ou se é necessário desativar o modo.

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center> 
 </details>

### Adicionar Novos Contratos de Trabalho

A tabela 6 mostra o cenário para quando uma empresa deseja registrar novos contratos de trabalho

<details>
  <summary size="20"><b> Tabela 6: Empresa registra novos contratos de trabalho </b></summary> 

<center>

**Tabela 6**:  Empresa registra novos contratos de trabalho

| Denominação | Adicionar Novos Contratos de Trabalho |
| - | - |
| Objetivo/meta | Permitir que a empresa adicione novos contratos de trabalho ao sistema. |
| Contexto |  **Contexto:** A empresa contratou um novo funcionário e deseja registrar essas informações no sistema. <br> **Local:** Na seção de gerenciamento de contratos de trabalho.  <br> **Tempo:** O processo de adição de um novo contrato pode levar de 15 a 30 minutos, dependendo da quantidade de informações. <br> **Pré-condição:** A empresa deve estar autenticada no sistema e ter todas as informações necessárias do novo contrato. |
| Atores | Empresa (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário). |
| Recursos | Aplicativo da carteira de trabalho digital da empresa; <br> Conexão à internet; <br> Banco de dados de contratos de trabalho |
| Episódios | 1. A empresa faz login no aplicativo da carteira de trabalho digital. 2. A empresa acessa a seção de gerenciamento de contratos de trabalho. <br> 3. A empresa seleciona a opção de adicionar um novo contrato de trabalho e preenche os detalhes necessários, como nome do funcionário, cargo, data de início, salário... <br> 3. O sistema valida as informações fornecidas pela empresa e adiciona o novo contrato ao banco de dados. <br> 4. O sistema também atualiza os dados no perfil do trabalhador para refletir o novo contrato adicionado. <br> 5. Após a confirmação bem-sucedida, a empresa recebe uma mensagem de confirmação informando que o contrato foi adicionado com sucesso. |
| Exceção | 1. Se houver algum erro na validação das informações fornecidas pela empresa, uma mensagem de erro é exibida e a empresa é orientada a corrigir os dados inseridos. <br> 2. Se ocorrer um problema de conexão com o banco de dados durante a adição do contrato, uma mensagem de erro é exibida e a empresa é instruída a tentar novamente mais tarde. |
| Restrição | 1. A empresa só pode adicionar contratos para os quais tenha autoridade e legitimidade. <br> 2. Os dados inseridos devem estar em conformidade com as políticas e regulamentos trabalhistas. |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center> 
 </details>
 
### Atualizar Contratos de Trabalho Existente

A tabela 7 mostra o cenário para quando uma empresa deseja atualizar contratos de trabalho

<details>
  <summary size="20"><b> Tabela 7: Empresa atualiza contratos de trabalho </b></summary> 

<center>

**Tabela 7**:  Empresa atualiza contratos de trabalho

| Denominação | Atualizar Contratos de Trabalho Existente |
| - | - |
| Objetivo/meta | Permitir que a empresa atualize informações de contratos de trabalho existentes. |
| Contexto |  **Contexto:**  A empresa identificou a necessidade de atualizar informações em um contrato de trabalho existente, como alteração de salário, posição, entre outros.  <br> **Local:** Na seção de gerenciamento de contratos de trabalho.  <br> **Tempo:** A atualização de um contrato existente pode levar de 15 a 30 minutos, dependendo das alterações necessárias. <br> **Pré-condição:** A empresa deve estar autenticada no sistema e ter as informações atualizadas prontas para inserção. |
| Atores | Empresa (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário). |
| Recursos | Aplicativo da carteira de trabalho digital da empresa; <br> Conexão à internet; <br> Banco de dados de contratos de trabalho. |
| Episódios | 1. A empresa faz login no aplicativo da carteira de trabalho digital. <br> 2. A empresa acessa a seção de gerenciamento de contratos de trabalho. <br> 3. A empresa seleciona o contrato de trabalho que deseja atualizar e escolhe a opção de edição. <br> 4. A empresa faz as alterações necessárias nos detalhes do contrato, como salário, cargo, entre outros. <br> 5. O sistema valida as alterações e atualiza os dados do contrato no banco de dados. <br> 6. O sistema também atualiza os dados no perfil do trabalhador para refletir as alterações feitas no contrato. <br> 7. Após a confirmação bem-sucedida, a empresa recebe uma mensagem de confirmação informando que o contrato foi atualizado com sucesso. |
| Exceção | 1. Se houver algum erro na validação das alterações feitas pela empresa, uma mensagem de erro é exibida e a empresa é orientada a corrigir as informações. <br> 2. Se ocorrer um problema de conexão com o banco de dados durante a atualização do contrato, uma mensagem de erro é exibida e a empresa é instruída a tentar novamente mais tarde. |
| Restrição | 1. A empresa só pode atualizar contratos para os quais tenha autoridade e legitimidade. <br> 2. As alterações devem estar de acordo com as políticas e regulamentos trabalhistas. |


**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center> 
 </details>
 
### Encerrar Contratos de Trabalho

A tabela 8 mostra o cenário para quando uma empresa deseja registrar encerramento de contratos de trabalho

<details>
  <summary size="20"><b> Tabela 8: Empresa registra encerramento contratos de trabalho </b></summary> 

<center>

**Tabela 8**:  Empresa registra encerramento contratos de trabalho

| Denominação | Encerrar Contratos de Trabalho |
| - | - |
| Objetivo/meta | Permitir que a empresa encerre contratos de trabalho existentes. |
| Contexto |  **Contexto:** A empresa precisa encerrar um contrato de trabalho devido a demissão, término do contrato ou outra razão relevante. |
| Atores | Empresa (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário). <br> **Local:** Na seção de gerenciamento de contratos de trabalho. <br> **Tempo:** O encerramento de um contrato pode levar de 15 a 30 minutos.  <br> **Pré-condição:** A empresa deve estar autenticada no sistema e ter um motivo válido para o encerramento do contrato.|
| Recursos | Aplicativo da carteira de trabalho digital da empresa; <br> Conexão à internet; <br> Banco de dados de contratos de trabalho |
| Episódios | 1. A empresa faz login no aplicativo da carteira de trabalho digital; <br> A empresa acessa a seção de gerenciamento de contratos de trabalho. <br> 3. A empresa seleciona o contrato de trabalho que deseja encerrar e escolhe a opção correspondente. <br> 3. A empresa fornece o motivo para o encerramento do contrato e confirma a ação. <br> 4. O sistema registra o encerramento do contrato no banco de dados e atualiza o status do contrato para refletir o encerramento. <br> 5. O sistema também atualiza os dados no perfil do trabalhador para refletir o encerramento do contrato. <br> 6. O trabalhador é notificado sobre o encerramento do contrato via e-mail ou notificação no aplicativo. <br> 7. Após a confirmação bem-sucedida, a empresa recebe uma mensagem de confirmação informando que o contrato foi encerrado com sucesso. |
| Exceção | 1. Se ocorrer um erro durante o processo de encerramento do contrato, uma mensagem de erro é exibida e a empresa é orientada a tentar novamente. <br> 2. Se houver questões pendentes relacionadas ao contrato, o sistema pode exibir uma mensagem de alerta recomendando a resolução dessas questões antes do encerramento. <br> 3. Se a empresa não tiver autorização para encerrar o contrato, uma mensagem de erro é exibida e a ação é bloqueada. |
| Restrição | 1. A empresa só pode encerrar contratos para os quais tenha autoridade e legitimidade. <br> 2. O encerramento do contrato deve estar em conformidade com as políticas e regulamentos trabalhistas. <br> 3. O sistema deve garantir que todos os dados relacionados ao contrato e ao perfil do trabalhador estejam atualizados antes de concluir o encerramento. |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center> 
 </details>




## Referências Bibliográficas

## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 |  Criação do cenário de trabalhador Visualizar Dados de Contratos de Trabalho   |  Larissa Stéfane   | Bruno Araújo   |   18/05/2024    |
| 1.1 |  Criação do cenário de trabalhador Atualizar dos Contratos de Trabalho   |  Larissa Stéfane   | Bruno Araújo    |   18/05/2024     |
| 1.2 |  Criação do cenário de trabalhador em canal de denúncias   |  Larissa Stéfane   | Bruno Araújo    |    18/05/2024    |
| 1.3 |  Criação do cenário de trabalhador escolhe Modo de Status de Procura de Emprego   |  Larissa Stéfane   |  Bruno Araújo  |   18/05/2024     |
| 1.4 |  Criação do cenário de empresa escolhe Modo de Status de oferta de Emprego   |   Larissa Stéfane  | Bruno Araújo    |  18/05/2024      |
| 1.5 |  Criação do cenário de empresa adiciona novos contratos de trabalho  |   Larissa Stéfane  | Bruno Araújo    |    18/05/2024    |
| 1.6 |  Criação do cenário de empresa atualiza contratos de trabalho  |  Larissa Stéfane   |  Bruno Araújo   |    18/05/2024    |
| 1.7 |  Criação do cenário de empresa encerra contratos de trabalho  |  Larissa Stéfane   | Bruno Araújo    |   18/05/2024     |
| 1.8 |  Adição de introdução, metodologia e desenvolvimento do modelo de tabela para cenários |  Iago Passaglia   |      |   19/05/2024     |

