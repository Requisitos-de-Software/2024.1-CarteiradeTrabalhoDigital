## Trabalhador acessa detalhes dos contratos de trabalho

<center>
Tabela 2: Caso de uso UC01 - Acessar Detalhes dos Contratos de Trabalho


| UC01                | Nome do caso                                               |
| ------------------- | ---------------------------------------------------------- |
| Descrição           | Permitir ao usuário(trabalhador) visualizar os detalhes dos seus vínculos trabalhistas, incluindo anotações, observações e gráficos sobre sua vida laboral. |
| Atores              | Usuário(trabalhador) (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário). |
| Frequência          | Conforme necessidade do usuário(trabalhador) para consultar seus contratos de trabalho. |
| Pré-condições       | <ul> <li> O usuário(trabalhador) deve estar autenticado no sistema. <li> O usuário(trabalhador) deve ter o aplicativo da carteira de trabalho digital instalado em seu smartphone. <li> O usuário(trabalhador) deve ter acesso à internet. <li> O sistema deve estar operacional e acessível. <li> O banco de dados de contratos de trabalho deve estar atualizado e acessível. </ul> |
| Fluxo Básico        | **FB01** <ol> <li> O usuário(trabalhador) faz login no aplicativo da carteira de trabalho digital. <li> O usuário(trabalhador) clica no ícone "Contratos de Trabalho" na interface do aplicativo. <li> O sistema recupera e exibe uma lista de todos os contratos de trabalho do usuário(trabalhador). <li> O usuário(trabalhador) seleciona um contrato específico da lista. <li> O sistema exibe os detalhes do contrato selecionado, incluindo: <ul><li> Período trabalhado <li> Endereço do empregador <li> Ocupação inicial <li> Tipo de contrato <li> Salário contratual <li> Remuneração inicial e última remuneração informada <li> Relação de trabalho <li> Tipo de admissão <li> Fonte da informação</ul> <li> O usuário(trabalhador) pode visualizar anotações e observações relacionadas ao contrato. <li> O usuário(trabalhador) pode visualizar gráficos que mostram o histórico de remunerações ao longo do tempo.</ol> |
| Fluxos Alternativos | **FA01** <ol> <li> Se o usuário(trabalhador) deseja exportar os detalhes do contrato: <ul><li> O usuário(trabalhador) clica em "Exportar Contrato" na interface do aplicativo. <li> O sistema gera um arquivo PDF com todos os detalhes do contrato selecionado. <li> O usuário(trabalhador) faz o download do PDF para seu dispositivo.</ul></ol> |
| Fluxos de exceção   | **FE01** <ol> <li> Se ocorrer um erro na recuperação dos dados: <ul><li> O usuário(trabalhador) clica no ícone "Contratos de Trabalho". <li> O sistema tenta recuperar os dados do banco de dados, mas falha. <li> O sistema exibe uma mensagem de erro: "Erro ao recuperar os dados. Por favor, tente novamente mais tarde." <li> O usuário(trabalhador) clica em "OK" para fechar a mensagem de erro. <li> O usuário(trabalhador) pode verificar a conexão com a internet e tentar novamente mais tarde.</ul> <li> Se o usuário(trabalhador) não tiver contratos de trabalho registrados: <ul><li> O usuário(trabalhador) clica no ícone "Contratos de Trabalho". <li> O sistema recupera os dados e verifica que não há contratos registrados. <li> O sistema exibe uma mensagem: "Nenhum contrato de trabalho disponível." <li> O usuário(trabalhador) clica em "OK" para fechar a mensagem.</ul> <li> Se houver um problema de comunicação com o banco de dados: <ul><li> O usuário(trabalhador) clica no ícone "Contratos de Trabalho". <li> O sistema tenta se comunicar com o banco de dados, mas falha. <li> O sistema exibe uma mensagem de erro: "Problema de comunicação com o banco de dados. Tente novamente mais tarde." <li> O usuário(trabalhador) clica em "OK" para fechar a mensagem e pode tentar novamente mais tarde.</ul> <li> Se os dados do contrato forem incompletos ou estiverem corrompidos: <ul><li> O usuário(trabalhador) seleciona um contrato da lista. <li> O sistema tenta carregar os detalhes do contrato, mas os dados estão incompletos ou corrompidos. <li> O sistema exibe uma mensagem de erro: "Dados do contrato incompletos ou corrompidos. Entre em contato com o suporte técnico." <li> O usuário(trabalhador) clica em "OK" para fechar a mensagem e pode contatar o suporte técnico para resolver o problema.</ul> </ol> |
| Pós-condições       | O usuário(trabalhador) visualiza os detalhes do contrato de trabalho selecionado. |
| Data de Criação     | 18/05/2024                                                 |
| Rastreabilidade     | [F05](Elicitacao/ResquisitosCorrigidos.md), [F07](Elicitacao/ResquisitosCorrigidos.md), [NF05](Elicitacao/ResquisitosCorrigidos.md), [nf20](Elicitacao/ResquisitosCorrigidos.md), [NF22](Elicitacao/ResquisitosCorrigidos.md)                                                    |

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)
</center>


## Trabalhador - Atualização de Contrato  

<center>
Tabela 3: Atualização dos Contratos de Trabalho

| UC02                | Atualização de Contrato                                  |
| ------------------- | ---------------------------------------------------------- |
| Descrição           | Este caso de uso permite que o usuário (trabalhador) atualize as informações de um contrato de trabalho existente. |
| Atores              | Trabalhador (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário); <br> Empresa (Usuário Secundário) |
| Frequência          | Conforme necessidade do usuário (trabalhador) para consultar seus contratos de trabalho. No entanto, é importante observar que quanto mais atualizações forem feitas, menor será a necessidade de futuras atualizações, o que pode diminuir a frequência. |
| Pré-condições       | 1. O usuário (trabalhador) deve estar autenticado no sistema. <br> 2. O usuário (trabalhador) deve ter acesso à internet. <br> 3. O usuário (trabalhador) deve ter o aplicativo da carteira de trabalho instalado em seu dispositivo móvel. <br> 4. O contrato de trabalho a ser atualizado deve estar registrado no sistema. |
| Fluxo Básico        | <b> FB02 </b> <ol> <li>O usuário (trabalhador) faz login no aplicativo da carteira de trabalho digital.</li> <li>O usuário (trabalhador) acessa a aba "Contratos de Trabalho".</li> <li>O usuário (trabalhador) seleciona o contrato que deseja atualizar.</li> <li>O usuário (trabalhador) verifica que os dados estão desatualizados e clica em "Atualizar" para solicitar a atualização.</li> <li>O sistema apresenta um formulário com os campos do contrato de trabalho para atualização.</li> <li>O usuário (trabalhador) modifica os dados necessários e confirma a atualização.</li> <li>O sistema valida as alterações e verifica a compatibilidade com os dados da empresa.</li> <li>Se os dados forem compatíveis, o sistema atualiza imediatamente o contrato de trabalho no perfil do usuário (trabalhador).</li> <li>Se os dados forem inconsistentes, o sistema notifica a empresa sobre a solicitação de atualização pendente.</li> <li>Após a atualização bem-sucedida, o sistema exibe uma mensagem de confirmação e retorna à visualização dos contratos de trabalho.</li> </ol> |
| Fluxos Alternativos | <b> FA02 </b> <ol> <li>O usuário (trabalhador) seleciona um campo opcional para atualização que não está disponível para alteração. <br> - O sistema exibe uma mensagem informando que o campo selecionado não pode ser alterado.</li> </ol> |
| Fluxos de exceção   | <b> FE02 </b> <ol> <li>Se ocorrer um erro na validação das alterações pelo sistema, uma mensagem de erro é exibida e o usuário (trabalhador) é orientado a corrigir os dados inseridos.</li> <li>Se houver um problema de comunicação com o banco de dados durante a atualização, uma mensagem de erro é exibida e o usuário (trabalhador) é instruído a tentar novamente mais tarde.</li> </ol> |
| Pós-condições       | O contrato de trabalho é atualizado com sucesso no perfil do usuário (trabalhador). |
| Data de Criação     | 18/05/2024                                                 |
| Rastreabilidade     | [F06](Elicitacao/ResquisitosCorrigidos.md), [F22](Elicitacao/ResquisitosCorrigidos.md), [NF18](Elicitacao/ResquisitosCorrigidos.md), [NF16](Elicitacao/ResquisitosCorrigidos.md)               |

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)
</center>


## Trabalhador - Realizar Denúncias Trabalhistas
<center>
Tabela 4: Realização de denúncias trabalhistas


### Tabela X: Caso de uso UC03

| UC03                | Realizar Denúncias Trabalhistas                                                                           |
|---------------------|----------------------------------------------------------------------------------------------------------|
| Descrição           | Permitir que o trabalhador faça denúncias anônimas sobre questões trabalhistas através do aplicativo digital.      |
| Atores              | Trabalhador (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário); <br> Departamento/Órgão responsável (Usuário Secundário) |
| Frequência          | Conforme necessidade do usuário (trabalhador) para denunciar violações de direitos trabalhistas.          |
| Pré-condições       | O usuário (trabalhador) deve estar autenticado no sistema; <br> O usuário (trabalhador) deve possuir informações detalhadas sobre a denúncia; <br> O usuário (trabalhador) deve ter acesso à internet e ao aplicativo da carteira de trabalho digital instalado em seu dispositivo. |
| Fluxo Básico        | <b>FB03</b> <ol><li>O usuário (trabalhador) faz login no aplicativo da carteira de trabalho digital.</li> <li>O usuário (trabalhador) acessa a aba "Canal de Denúncias Trabalhistas".</li> <li>O usuário (trabalhador) inicia o processo de denúncia.</li> <li>O usuário (trabalhador) preenche os detalhes da denúncia, incluindo data, descrição do incidente e, opcionalmente, documentos ou mídias de suporte, como fotos ou áudios.</li> <li>O sistema verifica a consistência das informações fornecidas, incluindo a validade da data e a integridade dos documentos ou mídias anexadas.</li> <li>Se todas as informações estiverem corretas, a denúncia é enviada anonimamente para o departamento.</li> <li>O sistema exibe uma mensagem de confirmação para o usuário (trabalhador) informando que a denúncia foi enviada com sucesso.</li></ol> |
| Fluxos Alternativos | <b>FA03</b> <ol><li>O usuário (trabalhador) faz login no aplicativo da carteira de trabalho digital.</li> <li>O usuário (trabalhador) acessa a aba "Canal de Denúncias Trabalhistas".</li> <li>O usuário (trabalhador) inicia o processo de denúncia.</li> <li>O usuário (trabalhador) preenche parcialmente os detalhes da denúncia e decide salvar a denúncia como rascunho.</li> <li>O sistema salva os dados parcialmente preenchidos como rascunho.</li> <li>O usuário (trabalhador) pode acessar o rascunho posteriormente para completar e enviar a denúncia.</li> <li>O sistema exibe uma mensagem de confirmação informando que o rascunho foi salvo com sucesso.</li></ol> |
| Fluxos de exceção   | **FE03** <ol> <li>Se ocorrer um erro na validação das informações fornecidas pelo usuário (trabalhador): <ul><li>O sistema exibe uma mensagem de erro informando sobre a inconsistência dos dados.</li> <li>O usuário (trabalhador) é orientado a corrigir os dados inseridos.</li></ul> <li>Se os documentos ou mídias anexadas estiverem corrompidos ou não puderem ser verificados: <ul><li>O sistema exibe uma mensagem de erro informando que os arquivos anexados estão corrompidos ou não podem ser verificados.</li> <li>O usuário (trabalhador) é instruído a tentar novamente com arquivos válidos.</li></ul> </ol> |
| Pós-condições       | A denúncia é enviada anonimamente para o departamento responsável para investigação e ação adequada.       |
| Data de Criação     | 19/05/2024                                                                                                |
| Rastreabilidade     | [F10](Elicitacao/ResquisitosCorrigidos.md), [F09](Elicitacao/ResquisitosCorrigidos.md), [F25](Elicitacao/ResquisitosCorrigidos.md), [FN09](Elicitacao/ResquisitosCorrigidos.md), [NF22](Elicitacao/ResquisitosCorrigidos.md)                                                                                                   |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>


## Trabalhador - Escolher Modo de Status de Procura de Emprego

<center>
Tabela 5: Trabalhador escolhe o modo de status de procura de emprego

| UC04                  | Escolher Modo de Status                       |
|-----------------------|-----------------------------------------------|
| **Descrição**         | Permitir que o Usuário(trabalhador) escolha entre os modos de "Procurando Emprego" e "Não Procurando Emprego" para ajudá-lo na procura por empregos que sejam compatíveis com seu currículo. |
| **Atores**            | Usuário(trabalhador) (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário); <br> Empresas (Usuário Secundário). |
| **Frequência**        | Conforme necessidade do Usuário(trabalhador).         |
| **Pré-condições**     | 1. O Usuário(trabalhador) deve estar autenticado no sistema. <br> 2. O Usuário(trabalhador) deve ter seu currículo, de preferência, atualizado. |
| **Fluxo Básico**      | <b>FB04</b> <ol> <li>O Usuário(trabalhador) faz login no aplicativo da carteira de trabalho digital.</li> <li>O Usuário(trabalhador) acessa as configurações de perfil.</li> <li>O Usuário(trabalhador) seleciona o modo de status desejado: "Procurando Emprego" ou "Não Procurando Emprego".</li> <li>Se o Usuário(trabalhador) escolher o modo "Procurando Emprego", ele tem a opção de atualizar seu currículo e indicar a cidade onde está procurando emprego.</li> <li>O sistema analisa o currículo em relação aos requisitos de ofertas dadas pelas empresas.</li> <li>Se uma empresa tiver uma vaga compatível com os requisitos do currículo do Usuário(trabalhador), o sistema envia uma notificação ou e-mail informando sobre a vaga de emprego.</li> <li>O Usuário(trabalhador), ao conseguir a vaga desativa o modo "procurando emprego", ou seja, fica como "Não procurando emprego". <br> **Observação:** O usuário(trabalhador) pode ajustar o modo de status a qualquer momento, alternando entre "Procurando Emprego" e "Não Procurando Emprego".</li> </ol> |
| **Fluxos Alternativos** | **FA04** <ol> <li>Se o Usuário(trabalhador) não tiver interesse em atualizar seu currículo ou indicar uma cidade de interesse:<ul><li>O sistema exibe uma mensagem informando sobre a conclusão da ação sem alterações.</li></ul></li> </ol> |
| **Fluxos de Exceção** | **FE04** <ol> <li>Se ocorrer um erro na atualização do currículo ou na indicação da cidade de interesse:<ul><li>O sistema exibe uma mensagem de erro informando sobre a inconsistência dos dados.</li><li>O Usuário(trabalhador) é orientado a corrigir as informações inseridas.</li></ul></li><li>Se houver um problema de comunicação com o sistema de envio de currículos ou com a base de dados de vagas de emprego:<ul><li>O sistema exibe uma mensagem de erro informando sobre o problema de comunicação.</li><li>O Usuário(trabalhador) é instruído a tentar novamente mais tarde.</li></ul></li><li>Se o Usuário(trabalhador) escolher o modo "Procurando Emprego" mas não atualizar seu currículo ou indicar uma cidade de interesse:<ul><li>Uma mensagem de alerta é exibida recomendando a conclusão dessas ações para melhorar suas chances de encontrar emprego.</li></ul></li></ol> |
| **Pós-condições**     | O modo de status é atualizado no perfil do Usuário(trabalhador). |
| **Data de Criação**   | 19/05/2024                                     |
| **Rastreabilidade**   | [F15](Elicitacao/ResquisitosCorrigidos.md), [F14](Elicitacao/ResquisitosCorrigidos.md), [FN16](Elicitacao/ResquisitosCorrigidos.md), [NF20](Elicitacao/ResquisitosCorrigidos.md) , [NF22](Elicitacao/ResquisitosCorrigidos.md) 


## Empresa - Escolher modo de vagas de emprego

<center>

Tabela 6: Escolher Modo de Status de Oferta de Emprego


| UC05                  | Escolher Modo de Status de Oferta de Emprego |
|-----------------------|-----------------------------------------------|
| **Descrição**         | Permitir que o usuário(empresa) ative o modo de "Vagas de Emprego" para buscar por funcionários e desative-o quando não houver mais vagas disponíveis. |
| **Atores**            | Usuário(Empresa) (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário); <br> Usuário(Trabalhador) (Usuário Secundário). |
| **Frequência**        | Conforme necessidade do usuário(empresa).         |
| **Pré-condições**     | 1. O usuário(empresa) deve estar autenticado no sistema. <br> 2. O usuário(empresa) deve ter as vagas de emprego definidas. |
| **Fluxo Básico**      | <b>FB05</b> <ol> <li>O usuário(empresa) faz login no aplicativo da carteira de trabalho digital e acessa as configurações de perfil.</li> <li>O usuário(empresa) seleciona a opção de ativar o modo de "Vagas de Emprego" e preenche os requisitos necessários para a vaga, como cargo, habilidades requeridas e localização.</li> <li>O sistema compara os requisitos da vaga com os dados dos currículos dos usuários(trabalhadores) que têm o status de "Procurando Emprego".</li> <li>Se um currículo corresponder aos requisitos da vaga, o sistema envia uma notificação ou e-mail para o usuário(trabalhador) informando sobre a oportunidade de emprego e solicitando que entre em contato com a empresa.</li> <li>Quando o usuário(empresa) não tem mais vagas disponíveis, ele acessa as configurações de perfil e seleciona a opção de desativar o modo de "Vagas de Emprego".</li> </ol> |
| **Fluxos Alternativos** | **FA05** <ol> <li>Se o usuário(empresa) não fornecer requisitos claros e precisos para as vagas de emprego:<ul><li>O sistema exibe uma mensagem de erro informando sobre a necessidade de fornecer requisitos claros e precisos.</li><li>O usuário(empresa) é orientado a preencher corretamente os requisitos.</li></ul></li> <li>Se o usuário(empresa) mantiver o modo "Vagas de Emprego" ativado por mais de três meses consecutivos:<ul><li>O sistema envia uma mensagem de lembrete ao usuário(empresa) para verificar se ainda há vagas disponíveis ou se é necessário desativar o modo.</li></ul></li> </ol> |
| **Fluxos de Exceção** | **FE05** <ol> <li>Se houver um erro na ativação ou desativação do modo de "Vagas de Emprego":<ul><li>O sistema exibe uma mensagem de erro informando sobre o problema.</li><li>O usuário(empresa) é orientado a tentar novamente.</li></ul></li><li>Se não houver currículos correspondentes aos requisitos da vaga:<ul><li>O sistema exibe uma mensagem informando que não foram encontrados candidatos compatíveis no momento.</li></ul></li><li>Se o usuário(empresa) não fornecer requisitos claros e precisos para as vagas de emprego:<ul><li>O sistema exibe uma mensagem de erro informando sobre a necessidade de fornecer requisitos claros e precisos.</li><li>O usuário(empresa) é orientado a preencher corretamente os requisitos.|
| **Pós-condições**     | O modo de "Vagas de Emprego" é ativado ou desativado no perfil do usuário(empresa). |
| **Data de Criação**   | 19/05/2024                                     |
| **Rastreabilidade**   | [F29](Elicitacao/ResquisitosCorrigidos.md),[FN16](Elicitacao/ResquisitosCorrigidos.md), [NF20](Elicitacao/ResquisitosCorrigidos.md) , [NF22](Elicitacao/ResquisitosCorrigidos.md)  | 

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

## Empresa - Adicionar Novos contratos de emprego

<center>

Tabela 7: Adicionar novos contratos de emprego

| UC06                               | Adicionar Novos Contratos de Trabalho |
|------------------------------------|---------------------------------------|
| **Descrição**                      | Permitir que o usuário(empresa) adicione novos contratos de trabalho ao sistema. |
| **Atores**                         | Usuário(empresa) (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário). |
| **Frequência**                     | Conforme necessário para registrar novos contratos de trabalho. |
| **Pré-condições**                  | 1. O usuário(empresa) deve estar autenticado no sistema. <br> 2. O usuário(empresa) deve ter acesso à seção de gerenciamento de contratos de trabalho. <br> 3. O usuário(empresa) deve possuir todas as informações necessárias do novo contrato de trabalho. |
| **Fluxo Básico**                   | **FB06** <ol> <li> O usuário(empresa) faz login no aplicativo da carteira de trabalho digital. <li> O usuário(empresa) acessa a seção de gerenciamento de contratos de trabalho. <li> O usuário(empresa) seleciona a opção de adicionar um novo contrato de trabalho. <li> O usuário(empresa) preenche os detalhes necessários do novo contrato, como nome do funcionário, cargo, data de início, salário, etc. <li> O sistema valida as informações fornecidas pela empresa. <li> O sistema adiciona o novo contrato ao banco de dados. <li> O sistema atualiza os dados no perfil do trabalhador para refletir o novo contrato adicionado. <li> Após a confirmação bem-sucedida, o usuário(empresa) recebe uma mensagem de confirmação informando que o contrato foi adicionado com sucesso. </ol> |
| **Fluxos Alternativos**            | **FA06** <ol> <li> Se o usuário(empresa) deseja adicionar um contrato com condições especiais, como contrato temporário ou contrato por projeto: <ul><li> O usuário(empresa) seleciona a opção de adicionar um novo contrato. <li> O usuário(empresa) escolhe a opção de contrato com condições especiais. <li> O usuário(empresa) preenche os detalhes específicos do contrato especial. <li> O sistema valida as informações fornecidas pela empresa. <li> O sistema adiciona o novo contrato ao banco de dados. <li> O sistema atualiza os dados no perfil do trabalhador para refletir o novo contrato adicionado. <li> Após a confirmação bem-sucedida, o usuário(empresa) recebe uma mensagem de confirmação informando que o contrato foi adicionado com sucesso.</ul></ol> |
| **Fluxos de Exceção**              | **FE06** <ol> <li> Se houver algum erro na validação das informações fornecidas pela empresa: <ul><li> O sistema exibe uma mensagem de erro informando sobre a inconsistência dos dados. <li> O usuário(empresa) é orientado a corrigir as informações inseridas.</ul> <li> Se ocorrer um problema de conexão com o banco de dados durante a adição do contrato: <ul><li> O sistema exibe uma mensagem de erro informando sobre o problema de conexão. <li> O usuário(empresa) é instruído a tentar novamente mais tarde.</ul> </ol> |
| **Pós-condições**                  | Os novos contratos de trabalho são adicionados ao sistema e refletidos nos perfis dos trabalhadores. |
| **Data de Criação**                | 19/05/2024                            |
| **Rastreabilidade**                |  [F26](Elicitacao/ResquisitosCorrigidos.md),[FN13](Elicitacao/ResquisitosCorrigidos.md), [NF18](Elicitacao/ResquisitosCorrigidos.md) , [NF22](Elicitacao/ResquisitosCorrigidos.md)  |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

## Empresa - Atualizar contratos de emprego

<center>

Tabela 8: Atualizar contratos de emprego

| UC07                                   | Atualizar Contratos de Trabalho Existente |
|----------------------------------------|-------------------------------------------|
| **Descrição**                          | Permitir que a empresa atualize informações de contratos de trabalho existentes. |
| **Atores**                             | Empresa (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário). |
| **Frequência**                         | Conforme necessário para atualizar informações em contratos de trabalho existentes. |
| **Pré-condições**                      | 1. A empresa deve estar autenticada no sistema. <br> 2. A empresa deve ter acesso à seção de gerenciamento de contratos de trabalho. <br> 3. A empresa deve possuir as informações atualizadas prontas para inserção. |
| **Fluxo Básico**                       | **FB07** <ol> <li> A empresa faz login no aplicativo da carteira de trabalho digital. <li> A empresa acessa a seção de gerenciamento de contratos de trabalho. <li> A empresa seleciona o contrato de trabalho que deseja atualizar e escolhe a opção de edição. <li> A empresa faz as alterações necessárias nos detalhes do contrato, como salário, cargo, entre outros. <li> O sistema valida as alterações. <li> O sistema atualiza os dados do contrato no banco de dados. <li> O sistema também atualiza os dados no perfil do trabalhador para refletir as alterações feitas no contrato. <li> Após a confirmação bem-sucedida, a empresa recebe uma mensagem de confirmação informando que o contrato foi atualizado com sucesso. </ol> |
| **Fluxos Alternativos**                | **FA07** <ol> <li> Se a empresa deseja cancelar a atualização do contrato: <ul><li> A empresa seleciona a opção de cancelar ou voltar sem salvar as alterações. <li> O sistema descarta as alterações feitas no contrato e retorna à tela anterior.</ul> </ol> |
| **Fluxos de Exceção**                  | **FE07** <ol> <li> Se houver algum erro na validação das alterações feitas pela empresa: <ul><li> O sistema exibe uma mensagem de erro informando sobre a inconsistência dos dados. <li> A empresa é orientada a corrigir as informações inseridas.</ul> <li> Se ocorrer um problema de conexão com o banco de dados durante a atualização do contrato: <ul><li> O sistema exibe uma mensagem de erro informando sobre o problema de conexão. <li> A empresa é instruída a tentar novamente mais tarde.</ul> </ol> |
| **Restrição**                          | 1. A empresa só pode atualizar contratos para os quais tenha autoridade e legitimidade. <br> 2. As alterações devem estar de acordo com as políticas e regulamentos trabalhistas. |
| **Pós-condições**                      | O contrato de trabalho existente é atualizado no sistema e refletido no perfil do trabalhador. |
| **Data de Criação**                    | 19/05/2024                                |
| **Rastreabilidade**                    |  [F26](Elicitacao/ResquisitosCorrigidos.md),[FN13](Elicitacao/ResquisitosCorrigidos.md), [NF18](Elicitacao/ResquisitosCorrigidos.md) , [NF22](Elicitacao/ResquisitosCorrigidos.md)  |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

