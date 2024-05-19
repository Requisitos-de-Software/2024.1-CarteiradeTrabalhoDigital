# Requisitos Elicitados

## Sumário

* [Introdução](#Introdução)
* [Elicitações](#Principais-Funções-do-Aplicativo)
* [Requisitos Funcionais](#Requisitos-Funcionais)
* [Requisitos Não Funcionais](#Requisitos-Não-Funcionais)
* [Conclusão](#Conclusão)
* [Bibliografia](#Bibliografia)
* [Histórico de versão](#Histórico-de-versão)

## Introdução

O desenvolvimento de aplicativos, especialmente aqueles voltados para a esfera governamental e direcionados a uma grande quantidade de pessoas, demanda uma compreensão profunda das necessidades e expectativas dos usuários. Neste contexto, para garantir que o aplicativo da Carteira de Trabalho Digital atenda adequadamente às demandas dos cidadãos, foram empregadas diversas técnicas de elicitação de requisitos, como storytelling, análise de documentos, questionários, entre outras. Assim, este documento apresenta os requisitos identificados por meio dessas abordagens e tem o intuito de fornecer uma base sólida para o estudo da equipe.

## Elicitações

Como foi citado, os requisitos apresentados neste documento foram obtidos por meio da aplicação de diversas técnicas de elicitação, visando capturar as necessidades tanto dos criadores(governo federal) quanto dos usuários de forma abrangente e precisa. Desse modo, a análise se fundamentou em uma variedade de fontes, que incluem documentos oficiais como leis, normas e manuais pertinentes ao contexto da carteira de trabalho digital. Além disso, foram considerados os comentários e experiências compartilhadas por usuários. Portanto, a combinação dessas abordagens permitiu uma compreensão abrangente e detalhada dos requisitos essenciais para o aplicativo. 


## Requisitos Funcionais

Em engenharia de software, um requisito funcional estabelece uma função específica que um sistema de software ou um de seus componentes deve desempenhar, ou seja, são as funcionalidades e tarefas que se espera que o sistema tenha.

Os requisitos funcionais encontrados são mostrados na tabela 1, onde cada requisito possui um identificador e, em rastreabilidade, há um link para a execução da técnica que o elicitou.

**Observação:*** Para visualizar a tabela 1, clicque em "Requisitos Funcionais elicitados".

Legendas:

- F + número: Requisito funcional número x.

<details>
  <summary size="20"><b> Requisitos Funcionais elicitados </b></summary> 

</center>

**Tabela 1**: Requisitos Funcionais.


| Identificação do Requisito | Requisito | Técnica de Elicitação | Implementação |
|-----------------------------|-----------|-----------------------|---------------|
| F01                          | Usuário se registrar no aplicativo | Análise de documentos | Sim |
| F02                          | Usuário poder fazer login para entrar na sua página pessoal | Análise de documentos | Sim |
| F03                          | Usuário pode consultar suas informações pessoais | Análise de documentos | Sim |
| F04                          | Usuário pode atualizar suas informações pessoais | entrevistas | Não |
| F05                          | Usuário trabalhador pode consultar contratos de trabalho | Análise de documentos | Sim |
| F06                          | Usuário trabalhador pode atualizar contratos de trabalho | Entrevistas | não |
| F07                          | Usuário pode gerar PDF com dados da carteira | Análise de documentos | Sim |
| F08                          | Usuário trabalhador visualizar gráficos com históricos e remunerações dos seus trabalhos | Análise de documentos | Sim |
| F09                          | Usuário pode realizar anotações | Análise de documentos | Sim |
| F10                          | Usuário trabalhador pode fazer denúncias trabalhistas contra a empresa | Entrevistas | Não |
| F11                          | Usuário trabalhador pode consultar informações sobre o FGTS | Storytelling | Não |
| F12                          | Usuário trabalhador pode consultar benefícios (13º salário, férias remuneradas, adicional noturno, vale-transporte, vale-refeição, plano de saúde, abono salarial, benefício TAC-Taxista)| Análise de documentos, Entrevistas e Storytelling| incompleto |
| F13                          | Usuário trabalhador pode solicitar benefícios | Análise de documentos e entrevistas | Incompleto |
| F14                          | Usuário trabalhador pode atualizar(declarar) currículo | Entrevistas e Storytelling | Não |
| F15                          | Usuário trabalhador pode  ativar modo de status (procurando emprego ou não) | Entrevistas | Não |
| F16                          | Usuário trabalhador por verificar processor seletivos abertos | Análise de documentos | Incompleto |
| F17                          | Usuário pode ocultar dados sensíveis | Análise de documentos e storytelling | Sim |
| F18                          | Usuário trabalhador pode consultar o número da carteira e de série como CIPS | Storytelling | Não |
| F19                          | Usuário recebem notificações do aplicativo | Análise de documentos e Storytelling | Não |
| F20                          | Usuário pode consultar perguntas frequêntes | Storytelling e Entrevista| Não |
| F21                          | Usuário empresa pode consultar dados dos funcionários | Entrevistas e análse de documento | Sim |
| F22                          | Usuário empresa pode atualizar dados dos funcionários | Entrevistas e análse de documento | Incompleto |
| F23                          | Usuário empresa pode consultar contratos de trabalho | Entrevistas e análse de documento | Incompleto |
| F24                          | Usuário empresa pode gerar relatórios trabalhistas | Entrevistas | Incompleto |
| F25                          | Usuário empresa pode receber notificação de denúncias trabalhistas | Entrevistas | Incompleto |
| F26                          | Usuário empresa pode gerenciar contratos de trabalho (adicionar novos, atualizar já existentes e encerrar contratos)| Entrevistas | Sim |
| F27                          | Usuário empresa pode cadastrar benefícios para a empresa | Entrevistas e análse de documento | Incompleto |
| F28                          | Usuário empresa pode gerenciar benefícios trabalhistas | Entrevistas | Incompleto |
| F29                          | Usuário empresa escolher modo de status: "Possui vagas de emprego" ou "Não posui vagas de emprego" | Entrevistas | Não |


  **Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

 </center> 
 </details>

## Requisitos Não Funcionais

Os requisitos não funcionais especificam as qualidades ou atributos que o sistema deve possuir, como desempenho, segurança, usabilidade e confiabilidade. Diferentemente dos requisitos funcionais, que se concentram no que o sistema faz, os requisitos não funcionais estão mais relacionados a como o sistema deve realizar suas funções.

Os requisitos não funcionais encontrados são mostrados na tabela 2, onde cada requisito possui um identificador e, em rastreabilidade, há um link para a execução da técnica que o elicitou.

**Observação:*** Para visualizar a tabela 2, clicque em "Requisitos Não Funcionais elicitados".

Legendas:

- NF + número: Requisito não funcional número x.

<details>
  <summary size="20"><b> Requisitos Não Funcionais elicitados </b></summary> 
 
</center>

**Tabela 2**: Requisitos Não Funcionais Verificáveis.

| Identificação do Requisito | Requisito                                                                                                                                                  | Técnica de Elicitação | Implementação |
|-----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------|---------------|
| NF01                         | O sistema deve processar solicitações da carteira de trabalho em no máximo 2 minutos.                                                                                                            | Análise de documentos     | Parcialmente          |
| NF02                         | O sistema deve ser capaz de escalar para suportar até 1 milhão de usuários simultâneos e permitir personalização das interfaces de usuário.                                                                                          | Análise de documentos     | Parcialmente            |
| NF03                         | O sistema deve suportar um aumento de 100% no volume de dados, transações e número de usuários sem degradação perceptível no desempenho. | Análise de documentos    | Sim           |
| NF04                         | O sistema deve ser capaz de processar até 10.000 transações por segundo, mesmo em picos de uso nacional.                                                   | Análise de documentos     | Parcialmente (Foi relatado casos de lentidão, talvez devido a grande demanda)          |
| NF05                         | Todos os textos do sistema devem seguir os padrões tipográficos e de siglas, abreviações e erros conforme as normas.                                                                       | Análise de documentos    | Sim           |
| NF06                         | A interface do usuário deve estar em conformidade com os manuais de interface gov.br.                                                                                                     | Análise de documentos     | Parcialmente           |
| NF07                         | A interface do sistema deve incluir todos os elementos básicos de design do Padrão Digital de Governo.                                                                                    | Análise de documentos    | Parcialmente           |
| NF08                         | O sistema deve implementar autenticação multifator, criptografia AES-256, controle de acesso baseado em funções, e logs de auditoria detalhados. | Análise de documentos | Sim           |
| NF09                      | O sistema deve garantir a conformidade com a LGPD (Lei Geral de Proteção de Dados).                                                                            | Análise de documentos     | Sim           |
| NF10                       | O sistema deve oferecer suporte a ampliadores de telas, leitores de telas, programas de reconhecimento de voz, teclados alternativos e dispositivos apontadores alternativos, e ser testado com pelo menos duas ferramentas de acessibilidade diferentes. | Análise de documentos | Parcialmente          |
| NF11                         | O sistema deve permitir a integração completa com os processos de negócios governamentais, conforme especificado na documentação de requisitos. | Análise de documentos e Storytelling | Parcialmente |
| NF12                        | O sistema deve utilizar vocabulários controlados e taxonomias padrão do governo, conforme especificado na documentação.| Análise de documentos | Sim |
| NF13                         | O sistema deve processar solicitações de carteira de trabalho em no máximo 2 minutos, com uma taxa de sucesso de 99%. | Análise de documentos e storytelling| Parcialmente (Algumas vezes o aplicativo apresenta erro) |
| NF14                       | O aplicativo deve seguir padrões de design aceitos por empresas e instituições, com uma taxa de conformidade de 95% nas avaliações de usabilidade. | Storytelling | Parcialmente |
| NF15                         | O acesso às funcionalidades principais do aplicativo deve exigir autenticação biométrica e ser completado em menos de 30 segundos. | Storytelling | Parcialmente |
| NF16                         | O sistema deve permitir ao usuário atualizar seus dados em no máximo 15 minutos, sem a necessidade de intermediários, com uma taxa de sucesso de 95%. | Storytelling | Parcialmente |
| NF17                         | O sistema deve apresentar dados pessoais com orientações claras e links para correção, com uma taxa de conformidade de 100% nas verificações. | Storytelling | Parcialmente |
| NF18                         | O sistema deve listar contratos de trabalho com todos os detalhes relevantes, atualizados em tempo real. | Análise de documentos e storytelling | Parcialmente|
| NF20                         | O sistema deve ser totalmente integrado com o eSocial, com uma taxa de sincronização de dados de 99%. | Análise de documentos | Parcialmente |
| NF21                         | O sistema deve ser totalmente integrado com o portal gov.br, com uma taxa de sincronização de dados de 99%. | Análise de documentos | Parcialmente |
| NF22                         | O sistema deve permitir integração com pelo menos cinco outros sistemas de software, conforme especificado na documentação de requisitos. | Análise de documentos     | Parcialmente          |
| NF23                         | O sistema deve enviar notificações precisas com uma taxa de falsos positivos inferior a 5%. | Storytelling | Parcialmente |
| NF24                         | O aplicativo deve ser compatível com iOS, Android e Windows, sem apresentar falhas críticas em nenhum dos sistemas operacionais suportados. | Storytelling | Parcialmente (Apresenta problemas em iOS) |
| NF25                         | O sistema deve atualizar os dados do usuário automaticamente a cada 24 horas para evitar defasagem, com uma taxa de sucesso de 99%. | Storytelling | Parcialmente |


**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

</details>

## Conclusão

Ao longo deste documento, foram apresentados os requisitos elicitados do aplicativo da carteira de trabalho digital. Sendo assim, foi possível classificar os requisitos como funcionais ou não funcionais por meio de tabelas. Além disso, a compreensão detalhada desses requisitos é fundamental para a continuação do estudo.


##  Bibliografia


1. **Execução da técnica de análise de documentos**. Disponível em <https://github.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/blob/main/docs/TecnicasElicitacao/Execucao/AnaliseDocumentos.md > Acesso em 14 de abril de 2024.
2. **Execução da técnica de storytelling**. Disponível em < https://github.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/blob/main/docs/TecnicasElicitacao/Execucao/Storytelling.md> Acesso em 14 de abril de 2024.


## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação e execução do requisitos elicitados | Larissa Stéfane | Breno Alexandre |  14/04/2024 |
| 1.1 | Correção e adição de requisitos| Larissa Stéfane | Bruno Araújo |  18/05/2024 |
| 1.2 | Corrigindo os requisitos não funcioanis para serem verificáveis| Larissa Stéfane | - |  19/05/2024 |
