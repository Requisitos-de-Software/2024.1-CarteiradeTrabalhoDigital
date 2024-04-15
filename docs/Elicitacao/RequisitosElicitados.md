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

O desenvolvimento de aplicativos, especialmente aqueles voltados para a esfera governamental e direcionados a uma grande quantidade de pessoas, demanda uma compreensão profunda das necessidades e expectativas dos usuários. Neste contexto, para garantir que o aplicativo da Carteira de Trabalho Digital atenda adequadamente às demandas dos cidadãos, foram empregadas diversas técnicas de elicitação de requisitos, como storytelling, análise de documentos, questionários, entre outras. Este documento apresenta os requisitos identificados por meio dessas abordagens e tem o intuito de fornecer uma base sólida para o estudo da equipe.

## Elicitações

Como foi citado, os requisitos apresentados neste documento foram obtidos por meio da aplicação de diversas técnicas de elicitação, visando capturar as necessidades tanto dos criadores(governo federal) quanto dos usuários de forma abrangente e precisa. Desse modo, a análise se fundamentou em uma variedade de fontes, que incluem documentos oficiais como leis, normas e manuais pertinentes ao contexto da carteira de trabalho digital. Além disso, foram considerados os comentários e experiências compartilhadas por usuários. Portanto, a combinação dessas abordagens permitiu uma compreensão abrangente e detalhada dos requisitos essenciais para o aplicativo. 


## Requisitos Funcionais

Os requisitos funcionais encontrados são mostrados na tabela 1, onde cada requisito possui um identificador e, em rastreabilidade, há um link para a execução da técnica que o elicitou.

Legendas:

- F + número: Requisito funcional número x.


</center>

**Tabela 1**: Requisitos Funcionais.


| Identificação do Requisito | Requisito | Técnica de Elicitação | Implementação |
|-----------------------------|-----------|-----------------------|---------------|
| F1                          | Apresentar dados pessoais com orientações e links para correção | Análise de documentos | Sim |
| F2                          | Listar contratos de trabalho com detalhes | Análise de documentos e storytelling | Sim |
| F3                          | Listar contratos de trabalho corretamente | Storytelling | Não – Parcialmente |
| F4                          | Permitir anotações | Análise de documentos |  Parcialmente |
| F5                          | Apresentar gráficos com histórico de remunerações | Análise de documentos | Sim |
| F6                         | Gerar arquivo PDF com dados da carteira | Análise de documentos e Storytelling | Parcialmente (O pdf apresenta diferenças do impreso) |
| F7                         | Ter aba "Benefícios" | Análise de documentos | Sim |
| F8                          | Mostrar dados como Seguro-Desemprego, Benefício TAC-Taxista, Benefício Emergencial | Análise de documentos e storytelling| Parcialmente (Alguns dados são apresentados errados) |
| F9                          | Oferecer opções como ocultar dados sensíveis, política de privacidade, perguntas frequentes, entre outros. | Análise de documentos | Parcialmente (Não foi encontrado “ocultar dados sensíveis” |
| F10                          | Possibilitar avaliação do aplicativo e acesso à seção "Sobre" | Análise de documentos | Sim |
| F11                         | Acesso à informação de Qualificação Civil e Contratos de Trabalho | Análise de documentos e storytelling | Sim |
| F12                         | Integração com eSocial | Análise de documentos | Sim |
| F13                         | Integração com gov.br | Análise de documentos | Sim |
| F14                        | Permitir integração com outros softwares | Análise de documentos | Sim |
| F15                         | Disponibilizar informações essenciais para os trabalhadores de forma acessível | Storytelling | Parcialmente (Algumas informações não são encontradas) |
| F16                         | Mandar notificações verdadeiras, evitando alarmes falsos | Storytelling | Não |
| F17                         | Estar adaptado para ser instalado em qualquer sistema operacional | Storytelling | Parcialmente (Apresenta problemas em IOS) |
| F18                      | Atualizar os dados do usuário constantemente para evitar defasagem | Storytelling | Não |



  **Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center> 


## Requisitos Não Funcionais

Os requisitos não funcionais encontrados são mostrados na tabela 2, onde cada requisito possui um identificador e, em rastreabilidade, há um link para a execução da técnica que o elicitou.

Legendas:

- NF + número: Requisito não funcional número x.

</center>

**Tabela 2**: Requisitos Não Funcionais.

| Identificação do Requisito | Requisito                                                                                                                                                  | Técnica de Elicitação | Implementação |
|-----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------|---------------|
| NF1                         | Oferecer agilidade na solicitação da carteira.                                                                                                            | Análise de documentos     | Parcialmente          |
| NF2                         | Permitir integração com vários outros software.                                                                                                            | Análise de documentos     | Sim           |
| NF3                         | Ser capaz de ter crescimento escalável e suportar personalização.                                                                                          | Análise de documentos     | Parcialmente (Não possível encontrar a opção de personalização)           |
| NF4                         | Ter a capacidade de atender alterações de demanda no sistema, como mudanças em volumes de dados, de quantidade de transações ou de quantidade de usuários. | Análise de documentos    | Sim           |
| NF5                         | Ser capaz de atender pequenos volumes de transações e de usuários, até demandas de abrangência nacional.                                                   | Análise de documentos     | Parcialmente (Foi relatado casos de lentidão, talvez devido a grande demanda)          |
| NF6                         | Padrões tipográficos e de siglas, de abreviações e de erros de acordo com as normas.                                                                       | Análise de documentos    | Sim           |
| NF7                         | Seguir os manuais de interface de acordo com o gov.br.                                                                                                     | Não especificado     | Sim           |
| NF8                         | Conter os elementos básicos de design para o Padrão Digital de Governo.                                                                                    | Análise de documentos    | Parcialmente           |
| NF9                         | Ter o básico de segurança: Autenticação, Criptografia, Controle de acesso, Auditoria, Atender as diretrizes e a práticas de segurança no controle de acesso à conta única. | Análise de documentos | Sim           |
| NF10                        | Garantir as condições de preservação da privacidade das informações do cidadão.                                                                            | Análise de documentos     | Sim           |
| NF11                        | Em relação à acessibilidade, deve conter: Ampliadores de telas, Leitores de telas, Programas de reconhecimento de voz, Teclados alternativos, Dispositivos apontadores alternativos. | Análise de documentos | Parcialmente.          |
| NF13                         | Apoiar interações do governo e alinhamento com processos de negócios governamentais | Análise de documentos e Storytelling | Parcialmente |
| NF14                        | Utilização de recursos como vocabulários controlados e taxonomias | Análise de documentos | Sim |
| NF15                         | Agilidade na solicitação da carteira | Análise de documentos e storytelling| Parcialmente (Algumas vezes o aplicativo apresenta erro) |
| NF16                        | O aplicativo deve seguir um padrão aceito por empresas e instituições sem provocar transtornos | Storytelling | Parcialmente |
| NF17                         | Acesso a alguns pontos do aplicativo exige biometria eficiente e prática | Storytelling | Parcialmente |
| NF18                         | O aplicativo deve permitir ao usuário atualizar seus dados sem causar transtornos e evitar burocracias | Storytelling | Parcialmente |

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
| 1.0 | Criação e execução do requisitos elicitados | Larissa Stéfane | - |  14/04/2024 |
