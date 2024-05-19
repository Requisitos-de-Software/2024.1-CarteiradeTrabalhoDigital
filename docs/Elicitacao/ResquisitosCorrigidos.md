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

Legendas:

- F + número: Requisito funcional número x.


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
| F09                          | Usuário pode gerar PDF com dados da carteira | Análise de documentos | Sim |
| F10                          | Usuário pode realizar anotações | Análise de documentos | Sim |
| F11                          | Usuário trabalhador pode fazer denúncias trabalhistas contra a empresa | Entrevistas | Não |
| F12                          | Usuário trabalhador pode consultar informações sobre o FGTS | Storytelling | Não |
| F13                          | Usuário trabalhador pode consultar benefícios (13º salário, férias remuneradas, adicional noturno, vale-transporte, vale-refeição, plano de saúde, abono salarial, benefício TAC-Taxista)| Análise de documentos, Entrevistas e Storytelling| incompleto |
| F14                          | Usuário trabalhador pode solicitar benefícios | Análise de documentos e entrevistas | Incompleto |
| F15                          | Usuário trabalhador pode atualizar(declarar) currículo | Entrevistas e Storytelling | Não |
| F16                          | Usuário trabalhador pode  ativar modo de status (procurando emprego ou não) | Entrevistas | Não |
| F17                          | Usuário trabalhador por verificar processor seletivos abertos | Análise de documentos | Incompleto |
| F18                          | Usuário pode ocultar dados sensíveis | Análise de documentos e storytelling | Sim |
| F19                          | Usuário trabalhador pode consultar o número da carteira e de série como CIPS | Storytelling | Não |
| F20                          | Usuário recebem notificações do aplicativo | Análise de documentos e Storytelling | Não |
| F21                          | Usuário pode consultar perguntas frequêntes | Storytelling e Entrevista| Não |
| F22                          | Usuário empresa pode consultar dados dos funcionários | Entrevistas e análse de documento | Sim |
| F23                          | Usuário empresa pode atualizar dados dos funcionários | Entrevistas e análse de documento | Incompleto |
| F24                          | Usuário empresa pode consultar contratos de trabalho | Entrevistas e análse de documento | Incompleto |
| F25                          | Usuário empresa pode gerar relatórios trabalhistas | Entrevistas | Incompleto |
| F26                          | Usuário empresa pode receber notificação de denúncias trabalhistas | Entrevistas | Incompleto |
| F27                          | Usuário empresa pode gerenciar contratos de trabalho (adicionar novos, atualizar já existentes e encerrar contratos)| Entrevistas | Sim |
| F28                          | Usuário empresa pode cadastrar benefícios para a empresa | Entrevistas e análse de documento | Incompleto |
| F29                          | Usuário empresa pode gerenciar benefícios trabalhistas | Entrevistas | Incompleto |
| F30                          | Usuário empresa escolher modo de status: "Possui vagas de emprego" ou "Não posui vagas de emprego" | Entrevistas | Não |


  **Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center> 


## Requisitos Não Funcionais

Os requisitos não funcionais especificam as qualidades ou atributos que o sistema deve possuir, como desempenho, segurança, usabilidade e confiabilidade. Diferentemente dos requisitos funcionais, que se concentram no que o sistema faz, os requisitos não funcionais estão mais relacionados a como o sistema deve realizar suas funções.

Os requisitos não funcionais encontrados são mostrados na tabela 2, onde cada requisito possui um identificador e, em rastreabilidade, há um link para a execução da técnica que o elicitou.

Legendas:

- NF + número: Requisito não funcional número x.

</center>

**Tabela 2**: Requisitos Não Funcionais.

| Identificação do Requisito | Requisito                                                                                                                                                  | Técnica de Elicitação | Implementação |
|-----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------|---------------|
| NF1                         | Oferecer agilidade na solicitação da carteira.                                                                                                            | Análise de documentos     | Parcialmente          |
| NF2                         | Ser capaz de ter crescimento escalável e suportar personalização.                                                                                          | Análise de documentos     | Parcialmente (Não possível encontrar a opção de personalização)           |
| NF3                         | Ter a capacidade de atender alterações de demanda no sistema, como mudanças em volumes de dados, de quantidade de transações ou de quantidade de usuários. | Análise de documentos    | Sim           |
| NF4                         | Ser capaz de atender desde pequenos volumes de transações e de usuários, até demandas de abrangência nacional.                                                   | Análise de documentos     | Parcialmente (Foi relatado casos de lentidão, talvez devido a grande demanda)          |
| NF5                         | Padrões tipográficos e de siglas, de abreviações e de erros de acordo com as normas.                                                                       | Análise de documentos    | Sim           |
| NF6                         | Seguir os manuais de interface de acordo com o gov.br.                                                                                                     | Não especificado     | Sim           |
| NF7                         | Conter os elementos básicos de design para o Padrão Digital de Governo.                                                                                    | Análise de documentos    | Parcialmente           |
| NF8                         | Ter o básico de segurança: Autenticação, Criptografia, Controle de acesso, Auditoria, Atender as diretrizes e a práticas de segurança no controle de acesso à conta única. | Análise de documentos | Sim           |
| NF9                      | Garantir as condições de preservação da privacidade das informações do cidadão.                                                                            | Análise de documentos     | Sim           |
| NF10                       | Em relação à acessibilidade, deve conter: Ampliadores de telas, Leitores de telas, Programas de reconhecimento de voz, Teclados alternativos, Dispositivos apontadores alternativos. | Análise de documentos | Parcialmente          |
| NF11                         | Apoiar interações do governo e alinhamento com processos de negócios governamentais | Análise de documentos e Storytelling | Parcialmente |
| NF12                        | Utilização de recursos como vocabulários controlados e taxonomias | Análise de documentos | Sim |
| NF13                         | Agilidade na solicitação da carteira | Análise de documentos e storytelling| Parcialmente (Algumas vezes o aplicativo apresenta erro) |
| NF14                       | O aplicativo deve seguir um padrão aceito por empresas e instituições sem provocar transtornos | Storytelling | Parcialmente |
| NF15                         | Acesso a alguns pontos do aplicativo exige biometria eficiente e prática | Storytelling | Parcialmente |
| NF16                         | O aplicativo deve permitir ao usuário atualizar seus dados sem causar transtornos e evitar burocracias | Storytelling | Parcialmente |
| NF17                         | Apresentar dados pessoais com orientações e links para correção | Storytelling | Parcialmente |
| NF18                         | Listar contratos de trabalho com detalhes | Análise de documentos e storytelling | Sim |
| NF20                         | Integração com eSocial | Análise de documentos | Sim |
| NF21                         | Integração com gov.br | Análise de documentos | Sim |
| NF22                         |Permitir integração com vários outros software.    | Análise de documentos     | Parcialmente          |
| NF23                         |Mandar notificações verdadeiras, evitando alarmes falsos | Storytelling | Parcialmente |
| NF24                         |Estar adaptado para ser instalado em qualquer sistema operacional | Storytelling | Parcialmente (Apresenta problemas em IOS) |
| NF25                         | Atualizar os dados do usuário constantemente para evitar defasagem | Storytelling | Parcialmente |


**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

## Conclusão

Ao longo deste documento, foram apresentados os requisitos elicitados do aplicativo da carteira de trabalho digital. Sendo assim, foi possível classificar os requisitos como funcionais ou não funcionais por meio de tabelas. Além disso, a compreensão detalhada desses requisitos é fundamental para a continuação do estudo.


##  Bibliografia


1. **Execução da técnica de análise de documentos**. Disponível em <https://github.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/blob/main/docs/TecnicasElicitacao/Execucao/AnaliseDocumentos.md > Acesso em 14 de abril de 2024.
2. **Execução da técnica de storytelling**. Disponível em < https://github.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/blob/main/docs/TecnicasElicitacao/Execucao/Storytelling.md> Acesso em 14 de abril de 2024.


## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação e execução do requisitos elicitados | Larissa Stéfane | Breno Alexandre |  14/04/2024 |
| 1.1 | Correção e adição de requisitos| Larissa Stéfane | - |  18/05/2024 |
