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
| Data de Criação     | 19/05/2024                                                 |
| Rastreabilidade     | [F05](Elicitacao/ResquisitosCorrigidos.md), [F07](Elicitacao/ResquisitosCorrigidos.md), [NF05](Elicitacao/ResquisitosCorrigidos.md), [nf20](Elicitacao/ResquisitosCorrigidos.md), [NF22](Elicitacao/ResquisitosCorrigidos.md)                                                    |

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)
</center>


## Trabalhador - Atualização de Contrato  

<center>
Tabela 3: Atualização dos Contratos de Trabalho

<center>
Tabela 2: Atualização dos Contratos de Trabalho

| UC02                | Atualização de Contrato                                  |
| ------------------- | ---------------------------------------------------------- |
| Descrição           | Este caso de uso permite que o usuário (trabalhador) atualize as informações de um contrato de trabalho existente. |
| Atores              | Trabalhador (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário); <br> Empresa (Usuário Secundário) |
| Frequência          | Conforme necessidade do usuário (trabalhador) para consultar seus contratos de trabalho. No entanto, é importante observar que quanto mais atualizações forem feitas, menor será a necessidade de futuras atualizações, o que pode diminuir a frequência. |
| Pré-condições       | 1. O usuário (trabalhador) deve estar autenticado no sistema. <br> 2. O usuário (trabalhador) deve ter acesso à internet. <br> 3. O usuário (trabalhador) deve ter o aplicativo da carteira de trabalho instalado em seu dispositivo móvel. <br> 4. O contrato de trabalho a ser atualizado deve estar registrado no sistema. |
| Fluxo Básico        | <b> FB01 </b> <ol> <li>O usuário (trabalhador) faz login no aplicativo da carteira de trabalho digital.</li> <li>O usuário (trabalhador) acessa a aba "Contratos de Trabalho".</li> <li>O usuário (trabalhador) seleciona o contrato que deseja atualizar.</li> <li>O usuário (trabalhador) verifica que os dados estão desatualizados e clica em "Atualizar" para solicitar a atualização.</li> <li>O sistema apresenta um formulário com os campos do contrato de trabalho para atualização.</li> <li>O usuário (trabalhador) modifica os dados necessários e confirma a atualização.</li> <li>O sistema valida as alterações e verifica a compatibilidade com os dados da empresa.</li> <li>Se os dados forem compatíveis, o sistema atualiza imediatamente o contrato de trabalho no perfil do usuário (trabalhador).</li> <li>Se os dados forem inconsistentes, o sistema notifica a empresa sobre a solicitação de atualização pendente.</li> <li>Após a atualização bem-sucedida, o sistema exibe uma mensagem de confirmação e retorna à visualização dos contratos de trabalho.</li> </ol> |
| Fluxos Alternativos | <b> FA01 </b> <ol> <li>O usuário (trabalhador) seleciona um campo opcional para atualização que não está disponível para alteração. <br> - O sistema exibe uma mensagem informando que o campo selecionado não pode ser alterado.</li> </ol> |
| Fluxos de exceção   | <b> FE01 </b> <ol> <li>Se ocorrer um erro na validação das alterações pelo sistema, uma mensagem de erro é exibida e o usuário (trabalhador) é orientado a corrigir os dados inseridos.</li> <li>Se houver um problema de comunicação com o banco de dados durante a atualização, uma mensagem de erro é exibida e o usuário (trabalhador) é instruído a tentar novamente mais tarde.</li> </ol> |
| Pós-condições       | O contrato de trabalho é atualizado com sucesso no perfil do usuário (trabalhador). |
| Data de Criação     | 19/05/2024                                                 |
| Rastreabilidade     | [F06](Elicitacao/ResquisitosCorrigidos.md), [F22](Elicitacao/ResquisitosCorrigidos.md), [NF18](Elicitacao/ResquisitosCorrigidos.md), [NF16](Elicitacao/ResquisitosCorrigidos.md)               |

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)
</center>




