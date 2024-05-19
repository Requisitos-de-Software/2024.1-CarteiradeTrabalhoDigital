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





