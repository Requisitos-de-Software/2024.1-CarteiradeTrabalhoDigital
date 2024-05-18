## O trabalhador (Funcionário comcarteira assinada) como protagonista do cenário (Usuário primário)

## Visualizar dados de contratos de trabalho 

| | |
| - | - |
| Denominação | Acessar Detalhes dos Contratos de Trabalho |
| Objetivo/meta | Permitir ao trabalhador visualizar os detalhes dos seus vínculos trabalhistas, incluindo anotações, observações e gráficos sobre sua vida laboral. |
| Contexto | O trabalhador deseja consultar informações detalhadas sobre seus contratos de trabalho, incluindo histórico de remunerações e outras anotações importantes. |
| Atores | Trabalhador (Usuário Primário); <br>  Sistema de Banco de Dados (Usuário Secundário). |
| Recursos | Aplicativo da carteira de trabalho digital; <br>  Conexão à internet; <br>  Banco de dados de contratos de trabalho. |
| Episódios | 1. O trabalhador faz login no aplicativo da carteira de trabalho digital. <br> 2. O trabalhador clica no ícone "Contratos de Trabalho" na interface do aplicativo. <br> 3. O sistema recupera e exibe uma lista de todos os contratos de trabalho do trabalhador. <br> 4. O trabalhador seleciona um contrato específico da lista. <br> 5. O sistema exibe os detalhes do contrato selecionado, incluindo: <br> - Período trabalhado <br> - Endereço do empregador <br> - Ocupação inicial <br> - Tipo de contrato <br> - Salário contratual <br> - Remuneração inicial e última remuneração informada <br> - Relação de trabalho <br> - Tipo de admissão <br> - Fonte da informação <br> 6. O trabalhador pode visualizar anotações e observações relacionadas ao contrato. <br> 7. O trabalhador pode visualizar gráficos que mostram o histórico de remunerações ao longo do tempo. |
| Exceção | 1. Se ocorrer um erro na recuperação dos dados, o sistema exibe uma mensagem de erro apropriada e sugere ações corretivas, como tentar novamente mais tarde ou verificar a conexão com a internet. <br> 2. Se o trabalhador não tiver contratos de trabalho registrados, o sistema exibe uma mensagem informando que não há contratos disponíveis. <br> 3. Se a sessão do trabalhador expirar durante a consulta, o sistema redireciona o trabalhador para a página de login com uma mensagem de sessão expirada. <br> 4. Se houver um problema de comunicação com o banco de dados, o sistema exibe uma mensagem de erro e pede para tentar novamente mais tarde. <br> 5. Se os dados do contrato forem incompletos ou estiverem corrompidos, o sistema exibe uma mensagem de erro e orienta o trabalhador a entrar em contato com o suporte técnico. |
| Restrição | 1. O trabalhador deve estar autenticado no sistema para acessar os detalhes dos contratos de trabalho. <br> 2. A conexão com a internet deve estar estável. <br> 3. O sistema deve ter acesso contínuo ao banco de dados. <br> 4. Os dados exibidos devem estar atualizados e sincronizados com as informações mais recentes do banco de dados oficial. |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)


## Atualização dos contratos de trabalho

| | |
| - | - |
| Denominação | Atualização de Contrato |
| Objetivo/meta | Permitir que o trabalhador atualize as informações de um contrato de trabalho existente. |
| Contexto | O trabalhador precisa fazer uma alteração em um contrato devido a uma mudança nas condições de emprego ou desafagem dos dados. |
| Atores | Trabalhador (Usuário Primário); <br> Sistema de Banco de Dados (Usuário Secundário); <br> Empresa (Usuário Secundário) |
| Recursos | Aplicativo da carteira de trabalho digital; <br> Conexão à internet; <br> Banco de dados de contratos de trabalho. |
| Episódios | 1. O trabalhador faz login no aplicativo da carteira de trabalho digital. <br> 2. O trabalhador acessa a aba "Contratos de Trabalho". <br> 3. O trabalhador seleciona o contrato que deseja verificar. <br> 4. O trabalhador verifica que os dados estão desatualizados e clica em "Atualizar" para solicitar a atualização. <br> 5. O trabalhador indica quais dados deseja atualizar (Já os modificando). <br> 6. O sistema verifica se os dados indicados pelo trabalhador são compatíveis com os dados declarados pela empresa. <br> 7. Se os dados forem compatíveis, o sistema atualiza imediatamente o contrato de trabalho no perfil do trabalhador. <br> 8. Se os dados forem inconsistentes, o sistema envia uma notificação para a empresa informando sobre a solicitação de atualização pendente. <br> 9. Se a empresa atualizar os dados, o sistema atualiza o contrato no perfil do trabalhador. |
| Exceção | 1. Se ocorrer um erro na validação das alterações pelo sistema, uma mensagem de erro é exibida e o trabalhador é orientado a corrigir os dados inseridos. <br> 2. Se houver um problema de comunicação com o banco de dados durante a atualização, uma mensagem de erro é exibida e o trabalhador é instruído a tentar novamente mais tarde. |
| Restrição | 1. O trabalhador só pode atualizar contratos dos quais ele seja o titular. <br> 2. As alterações devem estar de acordo com as políticas e regulamentos da empresa. <br> 3. A conexão com a internet deve estar estável durante o processo de atualização. <br> 4. Após um ano sem atualização por parte da empresa, o sistema envia uma nova notificação lembrando sobre a pendência. |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)
