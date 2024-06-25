# Rastreabilidade Backward From

## Sumário

* [Introdução](#Introdução)
* [Metodologia](#Metodologia)
* [Rastreabilidade dos Requisitos Funcionais](#Rastreabilidade-dos-Requisitos-Funcionais)
* [Rastreabilidade dos Requisitos Não Funcionais](#Rastreabilidade-dos-Requisitos-Não-Funcionais)
* [Conclusão](#Conclusão)
* [Referências Bibliográficas](#Referências-Bibliográficas)
* [Histórico de Versão](#Histórico-de-Versão)

## Introdução

A rastreabilidade de requisitos é fundamental para o desenvolvimento do nosso projeto da Carteira de Trabalho Digital, uma vez que ela permite acompanhar a evolução dos requisitos desde sua origem até a implementação final. Sendo assim, este documento tem o objetivo de detalhar como os requisitos funcionais e não funcionais elicitados no início do projeto são descritos com base no rastreamento do Meta-Modelo de Toranzo e são relacionados mediante diferentes tipos de elos, como satisfação, recurso, responsabilidade, representação, alocado e agregação.

## Metodologia

### O que é a rastreabilidade Backward From?

Conforme a monografia [Rastreabilidade de Requisitos](https://www-di.inf.puc-rio.br/~julio/rastre.pdf), da PUC, e com o artigo [Suporte automatizado à rastreabilidade em um processo de teste de software baseado em documentação](https://sol.sbc.org.br/index.php/sbqs/article/view/15615/15458), a rastreabilidade **backward-from** refere-se à prática de estabelecer e documentar conexões entre requisitos específicos e as suas fontes de origem. Com isso, essa técnica permite acompanhar como cada requisito está fundamentado nas necessidades de negócio, nas regulamentações e nas decisões estratégicas da equipe de desenvolvedores. Portanto, ao traçar essas conexões, é possível que cada requisito seja justificado e compreendido ao longo do ciclo de vida do projeto, o que facilita também a gestão do projeto.

### Meta-Modelo de Toranzo

Em [Rastreabilidade de Requisitos](https://www-di.inf.puc-rio.br/~julio/rastre.pdf), é explicado que o meta-modelo proposto por Toranzo é uma estrutura fundamental para a prática de rastreabilidade de requisitos. Isso porque ele oferece uma abordagem sistemática para definir e para organizar como os requisitos estão relacionados às suas fontes de origem, o que é essencial para garantir a consistência e a integridade ao longo do ciclo de vida do desenvolvimento de software.

Desse modo, o meta-modelo de Toranzo define quatro níveis de informações a serem rastreadas: ambiental, organizacional, gerencial e desenvolvimento. Cada um desses níveis abrange diferentes aspectos que influenciam ou são influenciados pelos requisitos do sistema.

#### Estrutura da Definição do Requisito

Sendo assim, para garantir consistência na definição de requisitos, cada integrante da equipe deve seguir o modelo estruturado abaixo:

- **Origem do Requisito:** onde foi elicitado o requisito.

- **Descrição:** descrição sucinta do requisito.

- **Ambiental:** informações do ambiente externo que impactam o requisito.

- **Organizacional:** missão, objetivos, metas e padrões organizacionais relacionados ao requisito.

- **Gerencial:** tarefas associadas ao requisito que auxiliam na gerência do projeto.

- **Desenvolvimento:** artefatos gerados no processo de desenvolvimento relacionados ao requisito.

- **Nível de Priorização:** Indica qual o nível de pirorização de acordo com os resultados das técnicas elicitadas.

<b>Tabela 1:</b> Template das estruturas.

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | - |
| Origem do Requisito  | - |
| Descrição            | - |
| Ambiental            | - |
| Organizacional       | - |
| Gerencial            | - |
| Desenvolvimento      | - |
| Nível de Priorização | - |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a> e  </b> <a href="https://github.com/brenoalexandre0">Breno Alexandre</a> 

### Os Elos

Ainda de acordo com [Rastreabilidade de Requisitos](https://www-di.inf.puc-rio.br/~julio/rastre.pdf), no meta-modelo de Toranzo, os elos são conexões essenciais para estabelecer e manter a rastreabilidade de requisitos ao longo do ciclo de vida do projeto. Eles são categorizados da seguinte forma:

- **Satisfação:** Indica que um requisito satisfaz as necessidades de outro.

- **Recurso:** Indica que um requisito depende de recursos fornecidos por outro.

- **Responsabilidade:** Registra a participação, responsabilidade e ação de pessoas sobre artefatos.

- **Representação:** Captura a modelagem ou representação de requisitos em outras linguagens, ou formatos.

- **Alocado:** Indica que um requisito está relacionado a um subsistema ou componente específico.

- **Agregação:** indica a composição de elementos, como sub cenários ou requisitos menores em requisitos maiores.

**Observação:** Na tabela será evidenciado apenas o elo mais relevante.

#### Template para a tabela dos Elos

Com base nos Elos acima, os requisitos devem ser definidos com base na tabela 1.


<b>Tabela 2:</b> Template dos Elos.

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| - | - | - | - | - |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a> e  </b> <a href="https://github.com/brenoalexandre0">Breno Alexandre</a> 


## Rastreabilidade dos Requisitos Funcionais


<details>
  <summary><b> RF01 - Iago Passaglia  </b></summary> 

<b>Tabela 3:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário se registrar no aplicativo |
| Origem do Requisito  | [Análise de documentos	](https://requisitos-de-software.github.io/2024.1-CarteiradeTrabalhoDigital/#/Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos) | 
| Descrição            | Esse requisito estabelece que o usuário deve ser capaz de realizar o cadastro pelo aplicativo.  |
| Ambiental            | O contexto do requisito está relacionado à necessidade de novos usuários de acessar o aplicativo com todas suas funções e acessar informações pessoais.  |
| Organizacional       | Entre os objetivos e as estratégias do aplicativo CTD, este requisito alinha-se com a missão de proteger e armazenar as informações dos usuários. |
| Gerencial            | Do ponto de vista gerencial, este requisito indica que será necessário armazenar as informações dos usuários conta à conta. Assim, ele indica que a gerência deve focar tanto na integração do sistema com os bancos de dados e em como os usuários visualizarão esses dados. |
| Desenvolvimento      |  Durante o desenvolvimento, esse requisito implica na criação da integração de outras funcionalidades com as novas contas dos usuários. Isso também implica na criação de um botão de cadastro na tela inicial do aplicativo caso o usuário não estivesse logado ainda. |
| Nível de Priorização | - |

<b> Autor: </b> <a href="https://github.com/Paxxaglia"> Iago Passaglia </a>.

### Elos de Rastreabilidade

A tabela 2 mostra os elos do requisito RF01.

<center> 

<b>Tabela 4:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados |
| -------------------- | ---------- | ---------- |  ---------- |  ---------- | 
| Satisfação | Desenvolvimento | <li> Módulo de Cadastro <br> <li> Componente de Manipulação de Dados da Carteira. | Este elo de satisfação indica que o desenvolvimento do módulo de cadastro e do componente de manipulação de dados da carteira é essencial para atender ao requisito de permitir que o usuário se registre no aplicativo. Esses elementos são necessários para criar novas contas de usuários e garantir que os dados sejam armazenados e gerenciados adequadamente, proporcionando uma experiência integrada e segura. | RF02:	Usuário poder fazer login para entrar na sua página pessoal  | 



<b> Autor: </b> <a href="https://github.com/Paxxaglia">Iago Passaglia</a>.

</center>

</details>




<details>
  <summary><b> RF02 - Iago Passaglia </b></summary> 

<b>Tabela 5:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário poder fazer login para entrar na sua página pessoal |
| Origem do Requisito  | [Análise de documentos	](https://requisitos-de-software.github.io/2024.1-CarteiradeTrabalhoDigital/#/Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos) |
| Descrição            | Esse requisito estabelece que o usuário deve ser capaz de realizar o login com seu cadastro prévio e acessar suas informações pessoais. |
| Ambiental            | O contexto do requisito está relacionado à necessidade de usuários com cadastro prévio de acessar o aplicativo e acessar informações pessoais. |
| Organizacional       | Entre os objetivos e as estratégias do aplicativo CTD, este requisito alinha-se com a missão de proteger e armazenar as informações dos usuários. |
| Gerencial            | Do ponto de vista gerencial, este requisito indica que será necessário armazenar as informações dos usuários conta à conta. Assim, ele indica que a gerência deve focar tanto na integração do sistema com os bancos de dados e em como os usuários visualizarão esses dados. |
| Desenvolvimento      |  Durante o desenvolvimento, esse requisito implica na criação da integração de outras funcionalidades com as contas dos usuários. Isso também implica na criação de um botão de login na tela inicial do aplicativo caso o usuário já tenha criado sua conta. |
| Nível de Priorização | - |

<b> Autor: </b> <a href="https://github.com/Paxxaglia">Iago Passaglia</a>.

### Elos de Rastreabilidade

A tabela 3 mostra os elos do requisito RF02.

<center> 

<b>Tabela 6:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| Recurso | Desenvolvimento | <li> Módulo de Login <br> <li> Componente de Manipulação de Dados da Carteira. | Este elo indica que o requisito depende da integração de funcionalidades com as contas dos usuários e da criação de botões de acesso rápido. | RF01: Usuário se registrar no aplicativo  |


<b> Autor: </b> <a href="https://github.com/Paxxaglia">Iago Passaglia</a>.

</center>

</details>


<details>
  <summary><b> RF03 - Iago Passaglia </b></summary> 

<b>Tabela 7:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário pode consultar suas informações pessoais |
| Origem do Requisito  | [Análise de documentos	](https://requisitos-de-software.github.io/2024.1-CarteiradeTrabalhoDigital/#/Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos). |
| Descrição            | Esse requisito estabelece que o usuário deve ser capaz de acessar suas informações pessoais relacionadas a carteira de trabalho e conta. |
| Ambiental            | O contexto do requisito está relacionado à necessidade de usuários de acessar informações pessoais. |
| Organizacional       | Entre os objetivos e as estratégias do aplicativo CTD, este requisito alinha-se com a missão de proteger e armazenar as informações dos usuários. |
| Gerencial            | Do ponto de vista gerencial, este requisito indica que será necessário armazenar as informações dos usuários conta à conta. Assim, ele indica que a gerência deve focar tanto na integração do sistema com os bancos de dados e em como os usuários visualizarão esses dados. |
| Desenvolvimento      |  Durante o desenvolvimento, esse requisito implica na criação da integração de outras funcionalidades com as contas dos usuários. Isso também implica na criação de botões de acesso rápido à informações pessoais de cadastro.  |
| Nível de Priorização | - |

<b> Autor: </b> <a href="https://github.com/Paxxaglia">Iago Passaglia</a>.

### Elos de Rastreabilidade

A tabela 4 mostra os elos do requisito RF03.

<center> 

<b>Tabela 8:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| Recurso | Desenvolvimento | <li> Módulo de Informações Pessoais <br> <li> Componente de Manipulação de Dados da Carteira. | Este elo indica que o requisito depende da integração de funcionalidades com as contas dos usuários e da criação de botões de acesso rápido. | RF02: Usuário poder fazer login para entrar na sua página pessoal |

<b> Autor: </b> <a href="https://github.com/Paxxaglia">Iago Passaglia</a>.

</center>

</details>

<details>
  <summary><b> RF04 - Iago Passaglia </b></summary> 

<b>Tabela 9:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário pode atualizar suas informações pessoais |
| Origem do Requisito  | [Entrevistas](https://requisitos-de-software.github.io/2024.1-CarteiradeTrabalhoDigital/#/Elicitacao/TecnicasElicitacao/Execucao/Storytelling/Storytelling). |
| Descrição            | Esse requisito estabelece que o usuário deve ser capaz de alterar/atualizar suas informações pessoais. |
| Ambiental            | O contexto do requisito está relacionado à necessidade de usuários de atualizar informações pessoais. |
| Organizacional       | Entre os objetivos e as estratégias do aplicativo CTD, este requisito alinha-se com a missão de permitir que o usuário sempre tenha suas informações atualizadas. |
| Gerencial            | Do ponto de vista gerencial, este requisito indica que será necessário armazenar as informações dos usuários conta à conta. Assim, ele indica que a gerência deve focar tanto na integração do sistema com os bancos de dados e em como os usuários visualizarão esses dados. |
| Desenvolvimento      |  Durante o desenvolvimento, esse requisito implica implica na criação de botões de acesso rápido à informações pessoais de cadastro.  |
| Nível de Priorização | - |

<b> Autor: </b> <a href="https://github.com/Paxxaglia">Iago Passaglia</a>.

### Elos de Rastreabilidade

A tabela 5 mostra os elos do requisito RF04.

<center> 

<b>Tabela 10:</b> Elo do Requisito


| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| Recurso | Desenvolvimento | <li> Módulo de Informações Pessoais <br> <li> Componente de Manipulação de Dados da Carteira. | Este elo indica que o requisito depende da integração de funcionalidades com as contas dos usuários e da criação de botões de acesso rápido. | RF02: Usuário poder fazer login para entrar na sua página pessoal |


<b> Autor: </b> <a href="https://github.com/Paxxaglia">Iago Passaglia</a>.


</center>

</details>



<details>
  <summary><b> RF05 - Iago Passaglia </b></summary> 

 <b>Tabela 11:</b> Estrutura do requisito
 
| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário trabalhador pode consultar contratos de trabalho |
| Origem do Requisito  | [Análise de documentos	](https://requisitos-de-software.github.io/2024.1-CarteiradeTrabalhoDigital/#/Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos). |
| Descrição            | Este requisito estabelece que o usuário trabalhador deve ser capaz de consultar seus contratos de trabalho através do aplicativo, visualizando detalhes como datas de início e término, cargos, empresas, e condições contratuais. |
| Ambiental            | O contexto do requisito está relacionado à necessidade de usuários trabalhadores de acessar informações detalhadas sobre seus contratos de trabalho. |
| Organizacional       | Entre os objetivos e as estratégias do aplicativo CTD, este requisito alinha-se com a missão de proteger e armazenar as informações dos usuários, além de facilitar o acesso a dados importantes de forma segura e eficiente. |
| Gerencial            | Do ponto de vista gerencial, este requisito indica que será necessário armazenar as informações dos contratos de trabalho de cada usuário de forma organizada e segura. A gerência deve focar na integração do sistema com os bancos de dados e na interface de usuário para a visualização dessas informações. |
| Desenvolvimento      | Durante o desenvolvimento, esse requisito implica na criação de funcionalidades que permitam a visualização detalhada dos contratos de trabalho, incluindo a integração com os bancos de dados que armazenam essas informações e a criação de botões e telas específicos no aplicativo para facilitar o acesso dos usuários. |
| Nível de Priorização | - |

<b> Autor: </b> <a href="https://github.com/Paxxaglia">Iago Passaglia</a>.


### Elos de Rastreabilidade

A tabela 6 mostra os elos do requisito RF05.

<center> 

<b>Tabela 12:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| Recurso | Desenvolvimento | <li> Módulo de Informações Trabalhistas <br> <li> Componente de Manipulação de Dados da Carteira. | Este elo indica que o requisito depende da integração de funcionalidades com os bancos de dados de contratos de trabalho e da criação de interfaces específicas para essa consulta. | RF02: Usuário poder fazer login para entrar na sua página pessoal |


<b> Autor: </b> <a href="https://github.com/Paxxaglia">Iago Passaglia</a>.

</center>

</details>



<details>
  <summary><b> RF06 - Iago Passaglia </b></summary> 

<b>Tabela 13:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário trabalhador pode atualizar contratos de trabalho |
| Origem do Requisito  | [Entrevistas](https://requisitos-de-software.github.io/2024.1-CarteiradeTrabalhoDigital/#/Elicitacao/TecnicasElicitacao/Execucao/Storytelling/Storytelling). |
| Descrição            | Este requisito estabelece que o usuário trabalhador deve ser capaz de atualizar seus contratos de trabalho através do aplicativo. |
| Ambiental            | O contexto do requisito está relacionado à necessidade de usuários trabalhadores de atualizar informações sobre seus contratos de trabalho. |
| Organizacional       | Entre os objetivos e as estratégias do aplicativo CTD, este requisito alinha-se com a missão de proteger e armazenar as informações dos usuários, além de permitir a atualização de dados importantes de forma segura e eficiente. |
| Gerencial            | Do ponto de vista gerencial, este requisito indica que será necessário armazenar as atualizações dos contratos de trabalho de cada usuário de forma organizada e segura. A gerência deve focar na integração do sistema com os bancos de dados e na interface de usuário para a atualização dessas informações. |
| Desenvolvimento      | Durante o desenvolvimento, esse requisito implica na criação de funcionalidades que permitam a atualização detalhada dos contratos de trabalho, incluindo a integração com os bancos de dados que armazenam essas informações e a criação de botões e telas específicos no aplicativo para facilitar o acesso dos usuários. |
| Nível de Priorização | - |

<b> Autor: </b> <a href="https://github.com/Paxxaglia">Iago Passaglia</a>.

### Elos de Rastreabilidade

A tabela 7 mostra os elos do requisito RF06.

<center> 

<b>Tabela 14:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| Recurso | Desenvolvimento | <li> Módulo de Informações Trabalhistas <br> <li> Componente de Manipulação de Dados da Carteira. | Este elo indica que o requisito depende da integração de funcionalidades com os bancos de dados de contratos de trabalho e da criação de interfaces específicas para essa consulta. | RF02: Usuário poder fazer login para entrar na sua página pessoal |

<b> Autor: </b> <a href="https://github.com/Paxxaglia">Iago Passaglia</a>.

</center>

</details>




<details>
  <summary><b> RF07 - Larissa Stéfane </b></summary> 

 <b>Tabela 15:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito | Usuário pode gerar PDF com dados da carteira |
| Onde foi elicitado  | [Análise de Documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md) por meio de [Manual da Carteira de Trabalho Digital](https://empregabrasil.mte.gov.br/wp-content/uploads/2023/02/Passo_a_Passo_CTPSDigital_APP_e_WEB.pdf) e [Cartilha da Carteira de Trabalho Digital](https://www.focuscontabil.com/wp-content/uploads/2020/05/Cartilha-CTP-Digital-02.pdf). |
| Descrição            | Esse requisito estabelece que o usuário deve ser capaz de gerar um arquivo PDF contendo os dados de sua Carteira de Trabalho Digital. Assim, o arquivo de PDF pode incluir informações sobre os contratos de trabalho, os dados pessoais, e outras movimentações profissionais. Além disso, o PDF gerado deve poder ser baixado, enviado por e-mail, ou impresso. |
| Ambiental            | O contexto do requisito está relacionado à necessidade dos usuários de acessar e de compartilhar facilmente as suas informações trabalhistas. Desse modo, essa funcionalidade deve permitir que os usuários gerem um PDF que inclui dados como detalhes de seus vínculos empregatícios e outras movimentações. Além disso, o PDF pode ser usado para comprovar experiências profissionais e é uma resposta à demanda por maior portabilidade de informações. |
| Organizacional       | Entre os objetivos e as estratégias do aplicativo CTD, este requisito alinha-se com a missão de fornecer um serviço digital acessível que auxilia na coordenação e no manejo de informações por parte do usuário. Isso porque esse requisito apoia a estratégia de digitalizar os processos e melhorar a usabilidade dos serviços oferecidos. Portanto, a capacidade de gerar PDFs com dados da Carteira de Trabalho facilita a vida dos usuários trabalhadores ao permitir que eles verifiquem e compartilhem seus dados. |
| Gerencial            | Do ponto de vista gerencial, este requisito indica que será necessário criar um molde com a localização de cada dado quando eles forem recuperados nos bancos de dados quando o PDF for gerado. Assim, ele indica que a gerência deve focar tanto na integração do sistema com os bancos de dados e em como os usuários visualizarão esses dados. |
| Desenvolvimento      | Durante o desenvolvimento, esse requisito implica na criação de funcionalidades específicas que permitam a exportação dos dados da Carteira de Trabalho Digital em formato PDF. Isso inclui a implementação de um botão ou ícone na interface do usuário para gerar o PDF, bem como a lógica de backend para compilar e para formatar os dados corretamente, como foi citado em **geracional**. Os desenvolvedores também precisam garantir que o PDF gerado possa ser baixado e enviado por e-mail ou impresso. |
| Nível de Priorização | [Médio segundo o backlog com o stakeholder](modelagemAgil/backlog.md) |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

### Elos de Rastreabilidade

A tabela 8 mostra os elos do requisito RF07.

<center> 

<b>Tabela 16:</b> Elo do Requisito

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| -------------- | -----------------  | ----------------------------------------------------- | -------------| ---- |
| Recurso | Desenvolvimento | <li> Módulo de Geração de Relatórios <br> <li> Biblioteca de Geração de Documentos PDF <br> <li> Documentos/Informações que deram origem ao PDFs gerado. <br> <li> Componente de Manipulação de Dados da Carteira.| O Módulo de Geração de Relatórios utiliza a Biblioteca de Geração de Documentos PDF, os documentos que deram origem ao PDFs gerado e o componente de manipulação de dados como recurso para implementar a funcionalidade de geração de contratos em PDF. | **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li> RF04: Usuário pode atualizar suas informações pessoais <br> <li> RF06: Usuário trabalhador pode atualizar contratos de trabalho <br> <li> RF14: Usuário trabalhador pode atualizar(declarar) currículo <br> <li> RF22: Usuário empresa pode atualizar dados dos funcionários <br> <li> RF25: Usuário empresa pode gerenciar contratos de trabalho (adicionar novos, atualizar já existentes e encerrar contratos) <br> <br>  Requisitos não funcionais: <br> <li> RNF05: Todos os textos do sistema devem seguir os padrões tipográficos e de siglas, abreviações e erros conforme as normas. <br> <li> RNF18: O sistema deve listar contratos de trabalho com todos os detalhes relevantes, atualizados em tempo real. <br> <li> RNF20: O sistema deve ser totalmente integrado com o eSocial, com uma taxa de sincronização de dados de 99%. |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

</center>

</details>



<details>
  <summary><b> RF08 - Larissa Stéfane  </b></summary> 

  <b>Tabela 17:</b> Estrutura do requisito
  
| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário trabalhador visualizar gráficos com históricos e remunerações dos seus trabalhos |
| Origem do Requisito  | [Análise de Documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md) por meio de [Manual da Carteira de Trabalho Digital](https://empregabrasil.mte.gov.br/wp-content/uploads/2023/02/Passo_a_Passo_CTPSDigital_APP_e_WEB.pdf) e [Cartilha da Carteira de Trabalho Digital](https://www.focuscontabil.com/wp-content/uploads/2020/05/Cartilha-CTP-Digital-02.pdf). |
| Descrição            | Este requisito estabelece que o usuário deve ser capaz de visualizar gráficos com históricos e remunerações dos seus trabalhos. Esses gráficos devem apresentar uma visão detalhada das remunerações ao longo do tempo e das variações nos diferentes empregos. Assim, deve ter gráficos tanto de cada emprego quanto no geral. Desse modo, esse requisito indica que deve-se permitir que os usuários visualizem gráficos que incluem dados como salários mensais, bônus, e outras remunerações associadas aos seus vínculos empregatícios.|
| Ambiental            | O contexto do requisito está relacionado à necessidade dos usuários de acompanhar e analisar a evolução de suas remunerações ao longo do tempo. |
| Organizacional       | Entre os objetivos e as estratégias do aplicativo CTD, este requisito alinha-se com a missão de fornecer um serviço digital que auxilia na coordenação e no manejo de informações por parte do usuário. <br> Isso porque a capacidade de visualizar gráficos de remunerações facilita o acesso dos usuários ao permitir que eles analisem suas informações de maneira visual. |
| Gerencial            | Este requisito indica que será necessário desenvolver uma interface que permita a visualização de gráficos de remunerações. Isso implica na necessidade de integração do sistema com bancos de dados que armazenam informações salariais e na criação de ferramentas analíticas que gerem os gráficos automaticamente. |
| Desenvolvimento      | Durante o desenvolvimento, esse requisito etimula a criação de funcionalidades e o uso de recursos que permitam a exibição de gráficos.  Sendo assim, isso inclui a implementação de componentes de front-end para renderização dos gráficos e a lógica de back-end para recuperar e processar os dados corretamente. |
| Nível de Priorização | [Baixo segundo o backlog com o stakeholder](modelagemAgil/backlog.md) |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

### Elos de Rastreabilidade

A tabela 9 mostra os elos do requisito RF08.

<center> 

<b>Tabela 18:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| Satisfação | Desenvolvimento | <li> Módulo de geração de gráficos. <br> <li> Dados do usuário sobre os seus contratos de trabalho. <br> <li> Componentes que permitem a interação com os gráficos. | O módulo de geração de geração de gráficos junto com os dados o usuário sobre os seus contratos de trabalho e os componentes que permitem interação com os gráficos **satifazem** as necessidades para se implementar o requisito de visualizar gráficos com históricos e remunerações de trabalho.  |  **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li> RF06: Usuário trabalhador pode atualizar contratos de trabalho <br> <li> RF12: Usuário trabalhador pode consultar benefícios (13º salário, férias remuneradas, adicional noturno, vale-transporte, vale-refeição, plano de saúde, abono salarial, benefício TAC-Taxista, Seguro Desemprego) (pode verificar o valor desses benefícios em gráficos)  <br> <li> RF22: Usuário empresa pode atualizar dados dos funcionários <br> <li> RF25: Usuário empresa pode gerenciar contratos de trabalho (adicionar novos, atualizar já existentes e encerrar contratos) <br> <li> RF27: Usuário empresa pode gerenciar benefícios trabalhistas <br> <br>  Requisitos não funcionais: <br> <li> RNF06: A interface do usuário deve estar em conformidade com os manuais de interface gov.br. <br> <li> RNF07: A interface do sistema deve incluir todos os elementos básicos de design do Padrão Digital de Governo.  <br> <li> RNF18: O sistema deve listar contratos de trabalho com todos os detalhes relevantes, atualizados em tempo real. <br> <li> RNF20: O sistema deve ser totalmente integrado com o eSocial, com uma taxa de sincronização de dados de 99% |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.
</center>

</details>



<details>
  <summary><b> RF09 - Larissa Stéfane </b></summary> 

 <b>Tabela 19:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário pode realizar anotações |
| Origem do Requisito  | [Análise de Documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md) por meio de [Manual da Carteira de Trabalho Digital](https://empregabrasil.mte.gov.br/wp-content/uploads/2023/02/Passo_a_Passo_CTPSDigital_APP_e_WEB.pdf) e [Cartilha da Carteira de Trabalho Digital](https://www.focuscontabil.com/wp-content/uploads/2020/05/Cartilha-CTP-Digital-02.pdf). |
| Descrição            | Esse requisito é usado para permitir que o usuário faça anotações diretamente no aplicativo em diversos pontos, por exemplo, adicionar observações em alguns contratos de trabalho ou em alguns benefícios, ou seja, essas anotações podem ser relacionadas a qualquer informação ou função disponível no aplicativo. Além disso, essas anotações podem ser visíveis apenas para o usuário ou para qualquer um que tenha acesso à informação. |
| Ambiental | O contexto do requisito está relacionado à necessidade de fornecer aos usuários uma ferramenta para fazer anotações ou observações, pois alguns usuários podem gostar de adiconar algo para  verificar no futuro. |
| Organizacional | A inclusão deste requisito está alinhada com o objetido do CTD em fornecer um aplicativo que facilite a organização pessoal dos usuários.  |
| Gerencial | Do ponto de vista gerencial, este requisito exige a garantia de que as anotações sejam integradas com outras funcionalidades do sistema e com o banco de dados, se necessário. |
| Desenvolvimento      | A implementação deste requisito requer a criação de uma interface de para a inserção, a edição e a exclusão de anotações, além do armazenamento seguro dos dados.|
| Nível de Priorização | [Baixo segundo o backlog com o stakeholder](modelagemAgil/backlog.md) |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

### Elos de Rastreabilidade

A tabela 10 mostra os elos do requisito RF09.

<center> 

<b>Tabela 20:</b> Elo do Requisito

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| -------------- | -----------------  | ----------------------------------------------------- | -------------| ---- |
| Recurso | Desenvolvimento | <li> Módulo de Anotações <br> <li> Banco de Dados para Armazenamento de Anotações <br> <li> Interface de Usuário para Inserção, Edição e Exclusão de Anotações.| O banco de dados para armazenar as anotações realizadas pelos usuários e a interface de usuário para permitir a inserção, edição e exclusão dessas anotações **são recursos** o módulo de anotações| **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li> RF03: Usuário pode consultar suas informações pessoais <br> <li> RF04: Usuário pode atualizar suas informações pessoais <br> <li> RF14: Usuário trabalhador pode atualizar(declarar) currículo <br> <br>  Requisitos não funcionais: <br> <li> RNF14: O aplicativo deve seguir padrões de design aceitos por empresas e instituições, com uma taxa de conformidade de 95% nas avaliações de usabilidade. <br> <li> RNF18: O sistema deve listar contratos de trabalho com todos os detalhes relevantes, atualizados em tempo real.|

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

</center>

</details>

<details>
  <summary><b> RF10 - Larissa Stéfane </b></summary> 

 <b>Tabela 21:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito | Usuário trabalhador pode fazer denúncias trabalhistas contra a empresa |
| Onde foi elicitado  | Entrevista |
| Descrição            | Este requisito permite que o usuário trabalhador faça denúncias anonimamente sobre questões trabalhistas através do aplicativo da Carteira de Trabalho Digital. Assim, o processo deve incluir acesso à aba "Canal de Denúncias Trabalhistas", preenchimento dos detalhes da denúncia (como data, descrição do incidente e possíveis documentos), validação das informações pelo sistema, e envio da denúncia anonimamente para o departamento responsável, ou seja, o minitério dos recursos humanos. |
| Ambiental            | O contexto do requisito está relacionado à necessidade dos trabalhadores de relatar violações de direitos trabalhistas anonimamente e com segurança ao utilizar o aplicativo como meio. |
| Organizacional       | Este requisito contribui para a missão do aplicativo da Carteira de Trabalho Digital em facilitar o acesso e a gestão de informações trabalhistas ao promover a transparência e a proteção dos direitos dos trabalhadores. |
| Gerencial            | Do ponto de vista gerencial, a implementação deste requisito envolve a integração do sistema de denúncias trabalhistas, e um programa de back-end para a verificação dos dados inseridos pelos usuários nas denúncias. Além disso, tembém é necesário garantir o anonimato e a segurança no envio das denúncias. |
| Desenvolvimento | Durante o desenvolvimento, é necessário implementar uma interface para o acesso ao Canal de Denúncias Trabalhistas, assim, a interface deve permitir ao usuário iniciar, salvar como rascunho, revisar e finalizar o processo de denúncia. Além disso, deve ser desenvolvido uma lógica de verificação de dados, isso inclui validação da data e a verificação de integridade de documentos e mídias anexadas (como fotos ou áudios). Também deve-se utilizar protocolos de segurança para proteger a identidade do usuário denunciante. |
| Nível de Priorização | [Médio segundo o backlog com o stakeholder](modelagemAgil/backlog.md) |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

### Elos de Rastreabilidade

A tabela 11 mostra os elos do requisito RF10.

<center> 

<b>Tabela 22:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados |
| -------------- | ----------------- | ----------------------------------------------------- | -------------| ---- |
| Satisfação | Desenvolvimento | <li> Integração com canal de denúncias trabalhistas no aplicativo da Carteira de Trabalho Digital <br> <li> Banco de dados de denúncias trabalhistas <br> <li> Lógica de validação de dados inseridos. <br> <li> Código/Criptografia de proteção da identidade do denunciante.  | A integração com “Canal de Denúncias”, o banco de dados de denúncias, a lógica de verificação dos dados inseridos e o método de proteção da identidade **são recursos** necessários para implementar o requisito de fazer denúncias trabalhistas. | **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li> RF01: Usuário trabalhador pode acessar informações sobre seus contratos de trabalho <br> <li> RF03: Usuário pode consultar suas informações pessoais. <br> <li> RF09:Usuário pode realizar anotações. <br> <li> RF11: Usuário trabalhador pode consultar informações sobre o FGTS e o INSS. <br> <li> RF12:Usuário trabalhador pode consultar benefícios (13º salário, férias remuneradas, adicional noturno, vale-transporte, vale-refeição, plano de saúde, abono salarial, benefício TAC-Taxista, Seguro Desemprego) . <br> <br> Requisitos não funcionais: <br> <li> RNF06: A interface do usuário deve estar em conformidade com os manuais de interface gov.br. <br> <li> RNF09: O sistema deve garantir a conformidade com a LGPD (Lei Geral de Proteção de Dados). <br> <li> RNF11: O sistema deve permitir a integração completa com os processos de negócios governamentais, conforme especificado na documentação de requisitos. <br> <li> RNF20: O sistema deve ser totalmente integrado com o eSocial, com uma taxa de sincronização de dados de 99%. <br> <li> RNF22: O sistema deve permitir integração com pelo menos cinco outros sistemas de software, conforme especificado na documentação de requisitos. | 


<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

</center>

</details>

<details>
  <summary><b> RF11 - Larissa Stéfane </b></summary> 

<b>Tabela 23:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário trabalhador pode consultar informações sobre o FGTS e o INSS |
| Origem do Requisito  | [Storytelling](docs/Elicitacao/TecnicasElicitacao/Execucao/Storytelling/Entrevistas.md) |
| Descrição            | Este requisito permite que o usuário trabalhador consulte informações sobre ele em relação ao Fundo de Garantia do Tempo de Serviço (FGTS) e o Instituto Nacional do Seguro Social (INSS) por meio do aplicativo da Carteira de Trabalho Digital. Com isso, as informações disponíveis incluem o saldo do FGTS, os extratos de movimentações, as contribuições previdenciárias, entre outros dados relevantes. |
| Ambiental            | O contexto desse requisito está relacionado à necessidade dos trabalhadores de acessarem informações atualizadas sobre os seus direitos trabalhistas e previdenciários de maneira digital e integrada. Com isso, a ideia de implementar o acesso a essas informações no aplicativo da carteira de trabalho digital é uma forma de facilitar o acesso a aesses dados.  |
| Organizacional       | Este requisito contribui para a missão do aplicativo em fornecer uma plataforma centralizada para gestão de informações trabalhistas e previdenciárias ao aumentar a transparência e a acessibilidade para os usuários. |
| Gerencial            | Do ponto de vista gerencial, a implementação deste requisito envolve a integração com sistemas de gestão do FGTS e do INSS. Além disso, requer a conformidade com normativas legais e regulatórias relacionadas à proteção de dados e a privacidade dos usuários, uma vez que esses dados não podem ser expostos para qualquer pessoa. |
| Desenvolvimento      | Durante o desenvolvimento, é necessário implementar, na interface, o acesso às informações do FGTS e INSS de forma organizada, o que envolve a integração com APIs dos sistemas responsáveis pelos dados. Também é necessário mecanismos de segurança para proteção das informações pessoais dos usuários. <br> Um observação importânte é que a interface deve ser projetada de acordo com os padrões estabelecidos pelo gov.br. |
| Nível de Priorização | [Alto segundo o backlog com o stakeholder](modelagemAgil/backlog.md) |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

### Elos de Rastreabilidade

A tabela 24 mostra os elos do requisito RF11.

<center> 

<b>Tabela 24:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| Recurso | Desenvolvimento | <li> Componentes na interface para consulta de informações do FGTS e INSS. <br> <li> Integração com APIs dos sistemas do FGTS e INSS. <br> <li> Mecanismos para segurança de dados | Os componentes para consultar as informações do FGTS e INSS no aplicativo da Carteira de Trabalho Digital e a integração com APIs dos sistemas do FGTS e INSS e os mecanismos de segurança **são recursos** necessários para implementar o requisito de consulta de informações. | **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li> RF05: Usuário trabalhador pode consultar contratos de trabalho <br> <li> RF12: Usuário trabalhador pode consultar benefícios (13º salário, férias remuneradas, adicional noturno, Hora extra)  <br> <br>  Requisitos não funcionais: <br> <li> RNF06: A interface do usuário deve estar em conformidade com os manuais de interface gov.br. <br> <li> RNF09: O sistema deve garantir a conformidade com a LGPD (Lei Geral de Proteção de Dados). <br> <li> RNF11: O sistema deve permitir a integração completa com os processos de negócios governamentais, conforme especificado na documentação de requisitos. <br> <li> RNF18: O sistema deve listar contratos de trabalho com todos os detalhes relevantes, atualizados em tempo real. |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

</center>

</details>




<details>
  <summary><b> RF12 - Larissa Stéfane </b></summary> 

<b>Tabela 25:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário trabalhador pode consultar benefícios (13º salário, férias remuneradas, adicional noturno, vale-transporte, vale-refeição, plano de saúde, abono salarial, benefício TAC-Taxista, Seguro Desemprego) |
| Origem do Requisito  | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md) e [Storytelling](Elicitacao/TecnicasElicitacao/Execucao/Storytelling/Entrevistas.md) |
| Descrição            | Este requisito permite que o usuário consulte diversos benefícios relacionados ao seu trabalho, tais como 13º salário, férias remuneradas, adicional noturno, vale-transporte, vale-refeição, plano de saúde, abono salarial, benefício TAC-Taxista e Seguro Desemprego. Desse modo, a consulta deve ser fácil e acessível e fornecer as informações detalhadas sobre cada benefício. |
| Ambiental            | A demanda por acesso fácil e rápido às informações sobre benefícios trabalhistas é crescente entre os trabalhadores, especialmente aqueles que desejam gerenciar melhor suas finanças e planejar suas atividades profissionais. Com isso, esse requisito responde a essa necessidade. |
| Organizacional       | A implementação desse requisito alinha-se com a estratégia organizacional de promover transparência e autonomia aos usuários trabalhadores, fornecendo ferramentas digitais que facilitam o acesso às informações essenciais. |
| Gerencial            | Do ponto de vista gerencial, este requisito implica na integração de fontes de dados que fornecem informações precisas sobre cada benefício listado. Além disso, é necessário garantir a segurança e a privacidade das informações consultadas pelos usuários. |
| Desenvolvimento      | Durante o desenvolvimento, será necessário criar uma componentes de interface que permitam aos usuários consultar facilmente cada benefício listado. Além disso, também é necessária a implementação de consultas de dados em tempo real e a apresentação das informações obtidas. |
| Nível de Priorização | [Alto segundo o backlog com o stakeholder](modelagemAgil/backlog.md) |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

### Elos de Rastreabilidade

A tabela 26 mostra os elos do requisito RF12.

<center> 

<b>Tabela 26:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO | Requisitos Relacionados |
| -------------- | ----------------- | ----------------------------------------------------- | ------------- | ------------- |
| Recurso | Desenvolvimento | <li> Componentes de interface para consulta de benefícios <br> <li> Integração com APIs ou Banco de dados, como eSocial. <br> <li> Dados dos contratos de trabalho.| Os componentes na interface para consulta de benefícios no aplicativo da Carteira de Trabalho Digital e a integração com APIs ou bancos de dados **são recursos** necessários para implementar o requisito de consulta de benefícios. | **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li> RF13: Usuário trabalhador pode solicitar benefícios. <br> <li> RF05: Usuário trabalhador pode consultar contratos de trabalho. <br> <li> RF22: Usuário empresa pode atualizar dados dos funcionários <br> <li> RF25: Usuário empresa pode gerenciar contratos de trabalho (adicionar novos, atualizar já existentes e encerrar contratos) <br> <br>  Requisitos não funcionais: <br> <li> RNF05: Todos os textos do sistema devem seguir os padrões tipográficos e de siglas, abreviações e erros conforme as normas. <br> <li> RNF18: O sistema deve listar contratos de trabalho com todos os detalhes relevantes, atualizados em tempo real. <br> <li> RNF20: O sistema deve ser totalmente integrado com o eSocial, com uma taxa de sincronização de dados de 99%. |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

</center>

</details>


<details>
  <summary><b> RF13 - Larissa Stéfane </b></summary> 

 <b>Tabela 27:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário trabalhador pode solicitar benefícios |
| Origem do Requisito  | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md) |
| Descrição            | Este requisito permite que usuários que são trabalhadores solicitem benefícios através do sistema, passando por análise de documentos ou justiicativa para verificação de elegibilidade do pedido. Então, a empresa recebe o pedido. |
| Ambiental | O contexto do requisito está relacionado à necessidade dos usuários de acessar e de solicitar benefícios de forma simplificada e digital. | 
| Organizacional | Entre os objetivos e as estratégias do aplicativo CTD, este requisito alinha-se com a missão de digitalizar e otimizar os processos de gestão, que inclui a gestão de benefícios. Sendo assim, o foco está em melhorar a acessibilidade e a transparência no acesso aos pedidos por benefícios. |
| Gerencial | Do ponto de vista gerencial, este requisito indica que será necessário estabelecer métricas para o monitoramento contínuo do processo de solicitação de benefícios para assegurar conformidade com as políticas organizacionais e regulatórias e facilitar a solicitação por um benefício.|
| Desenvolvimento | Durante o desenvolvimento, esse requisito implica na criação de componentes de interfaces para a solicitação de benefícios, na implementação de lógica de negócio para validar os documentos que possam ser enviados, e na integração com sistemas ou bancos de dados externos. |
| Nível de Priorização | [Alto segundo o backlog com o stakeholder](modelagemAgil/backlog.md) |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

### Elos de Rastreabilidade

A tabela 28 mostra os elos do requisito RF13.

<center> 

<b>Tabela 28:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO | Requisitos Relacionados |
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| Recurso | Desenvolvimento | <li> Componentes de interface para solicitar o benefícios, por exemplo, local para escrever a solicitação. <br> <li> Integração com APIs ou Banco de dados, como eSocial. <br> <li> Dados dos contratos de trabalho. <br> <li> Dados sobre a empresa | Os componentes para implementar na interface, a integração com APIs e com Banco de Dados e os dados dos contratos de trabalho e das empresas são recursos para a implementação do requisito de solicitar benefício.| **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li>  RF05: Usuário trabalhador pode consultar contratos de trabalho. <br> <li>  RF12: Usuário trabalhador pode consultar benefícios (13º salário, férias remuneradas, adicional noturno, vale-transporte, vale-refeição, plano de saúde, abono salarial, benefício TAC-Taxista, Seguro Desemprego)  <br> <li> RF24: Usuário empresa pode gerar relatórios trabalhistas <br> <li> RF25: Usuário empresa pode gerenciar contratos de trabalho (adicionar novos, atualizar já existentes e encerrar contratos) <br> <br>  Requisitos não funcionais: <br> <li> RNF05: Todos os textos do sistema devem seguir os padrões tipográficos e de siglas, abreviações e erros conforme as normas. <br> <li> RNF18: O sistema deve listar contratos de trabalho com todos os detalhes relevantes, atualizados em tempo real. <br> <li> RNF20: O sistema deve ser totalmente integrado com o eSocial, com uma taxa de sincronização de dados de 99%. |


<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

</center>

</details>



<details>
  <summary><b> RF14 - Larissa Stéfane </b></summary> 

 <b>Tabela 29:</b> Estrutura do requisito
 
| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário trabalhador pode atualizar (declarar) currículo |
| Origem do Requisito  | [Storytelling](Elicitacao/TecnicasElicitacao/Execucao/Storytelling) |
| Descrição            | Este requisito permite que usuários trabalhadores atualizem ou declarem informações de seus currículos através do sistema, incluindo dados como experiências profissionais, formação acadêmica, habilidades e certificações. |
| Ambiental            | O contexto do requisito está relacionado à necessidade dos usuários de manterem seus currículos atualizados para fins de candidatura a empregos e para que empregadores possam acessar informações atualizadas sobre os seus empregados. |
| Organizacional       | Entre os objetivos e as estratégias do aplicativo CTD, este requisito alinha-se com a missão de proporcionar uma plataforma centralizada na gestão de informações profissionais. |
| Gerencial            | Do ponto de vista gerencial, este requisito indica que será necessário definir processos para a atualização e para a verificação das informações inseridas pelos usuários, garantindo que os dados confiáveis. Além disso, há a necessidade de monitoramento dos currículos. |
| Desenvolvimento      | Durante o desenvolvimento, esse requisito implica na criação de formulários de entrada de dados, integração com bancos de dados para armazenamento e verificação das informações do currículo, e a implementação de mecanismos de validação para garantir a integridade dos dados. Além disso, deve-se permitir a edição e  a exclusão de informações caso o usuário deseje.|
| Nível de Priorização | [Baixo segundo o backlog com o stakeholder](modelagemAgil/backlog.md) |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

### Elos de Rastreabilidade

A tabela 30 mostra os elos do requisito RF14.

<center> 

<b>Tabela 30:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO | Requisitos Relacionados |
| -------------- | ----------------- | ----------------------------------------------------- | ------------- | ------------- |
| Alocado | Desenvolvimento | <li> Módulo de Atualização de Currículo <br> <li> Banco de dados de currículos <br> <li> Interface de usuário para entrada e edição de dados dos currículos. | Este elo indica que os currículos estão **relacionados ou alocados** aos componentes dos contratos de trabalho, uma vez que se utilizam os contratos anteriores no currículo como experiência e se utiliza o currículo para contratar ou procurar emprego. | **Os requisitos que fornecem os recursos necessários são:** <br><br> Requisitos Funcionais: <br> <li> RF04: Usuário pode atualizar suas informações pessoais <br> <li> RF06: Usuário trabalhador pode atualizar contratos de trabalho <br> <li> RF24: Usuário empresa pode gerar relatórios trabalhistas <br> <li> RF25: Usuário empresa pode gerenciar contratos de trabalho (adicionar novos, atualizar já existentes e encerrar contratos) <br><br> Requisitos não funcionais: <br> <li> RNF05: Todos os textos do sistema devem seguir os padrões tipográficos e de siglas, abreviações e erros conforme as normas. <br> <li> RNF18: O sistema deve listar contratos de trabalho com todos os detalhes relevantes, atualizados em tempo real. <br> <li> RNF20: O sistema deve ser totalmente integrado com o eSocial, com uma taxa de sincronização de dados de 99%. <br> <li> RNF22: O sistema deve permitir integração com pelo menos cinco outros sistemas de software, conforme especificado na documentação de requisitos. | 

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

</center>

</details>


<details>
  <summary><b> RF15 - Luana Medeiros </b></summary> 
 
<b>Tabela 31:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário trabalhador pode ativar modo de status (procurando emprego ou não) |
| Origem do Requisito  | 	Entrevistas |
| Descrição            | Este requisito estabelece que o usuário trabalhador deve ser capaz de ativar ou desativar um modo de status indicando se está procurando emprego ou não. Este status deve ser facilmente alterável através do aplicativo e visível para empregadores e outras entidades relevantes. |
| Ambiental            | O contexto do requisito está relacionado à necessidade de usuários trabalhadores de informar seu status de disponibilidade para novas oportunidades de emprego, facilitando a comunicação e a visibilidade no mercado de trabalho. |
| Organizacional       | Entre os objetivos e as estratégias do aplicativo CTD, este requisito alinha-se com a missão de facilitar a interação entre trabalhadores e empregadores, promovendo a empregabilidade e a transparência das informações. |
| Gerencial            | Do ponto de vista gerencial, este requisito indica que será necessário desenvolver mecanismos que permitam a alteração e o armazenamento seguro do status de emprego dos usuários. A gerência deve assegurar a implementação de uma interface intuitiva para os trabalhadores e a integração com sistemas de visibilidade para empregadores. |
| Desenvolvimento      | Durante o desenvolvimento, esse requisito implica na criação de funcionalidades que permitam ao usuário ativar ou desativar seu status de procura de emprego, incluindo a implementação de botões de alternância no aplicativo, armazenamento seguro deste status no banco de dados e a atualização das interfaces de empregadores que consultam essas informações. |
| Nível de Priorização | - |

<b> Autora: </b> <a href="https://github.com/LuaMedeiros">Luana Medeiros</a>.

### Elos de Rastreabilidade

A tabela 32 mostra os elos do requisito RF15.

<center> 

<b>Tabela 32:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| Recurso | Desenvolvimento | <li> Módulo de Gerenciamento de Status <br> <li> Banco de Dados para Armazenamento de Status de Emprego <br> <li> Interface de Usuário para Alteração de Status | O módulo de gerenciamento de status, o banco de dados para armazenamento do status de emprego e a interface de usuário para alteração do status são recursos necessários para implementar este requisito. | **Os requisitos que fornecem os recursos necessários são:** <br><br> Requisitos Funcionais: <br> <li> RF01 Usuário se registrar no aplicativo (necessário para acessar o recurso de ativação de status) <br> <li> RF02 Usuário poder fazer login para entrar na sua página pessoal (necessário para alterar status) <br> <li> RF03 Usuário pode consultar suas informações pessoais (relevante para verificar o status atual) <br> <li> RF19 Usuário recebe notificações do aplicativo (notificar mudanças de status) <br> <li> RF28 Usuário empresa escolher modo de status: "Possui vagas de emprego" ou "Não possui vagas de emprego" (para interação entre status do trabalhador e ofertas de emprego da empresa) <br><br> Requisitos não funcionais: <br> <li> RNF08 O sistema deve implementar autenticação multifator, criptografia AES-256, controle de acesso baseado em funções, e logs de auditoria detalhados (segurança e conformidade) <br> <li> RNF09 O sistema deve garantir a conformidade com a LGPD (Lei Geral de Proteção de Dados) (proteção de dados pessoais) <br> <li> RNF15 O acesso às funcionalidades principais do aplicativo deve exigir autenticação biométrica e ser completado em menos de 30 segundos (segurança e rapidez no acesso) |


<b> Autora: </b> <a href="https://github.com/LuaMedeiros">Luana Medeiros</a>.

</center>

</details>


<details>
  <summary><b> RF16 - Luana Medeiros </b></summary> 

 <b>Tabela 33:</b> Estrutura do requisito
 
| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário trabalhador por verificar processor seletivos abertos |
| Origem do Requisito  | 	Análise de documentos |
| Descrição            | Este requisito estabelece que o usuário trabalhador deve ser capaz de verificar processos seletivos abertos através do aplicativo, visualizando detalhes como nome da vaga, empresa contratante, requisitos do cargo, e datas de início e término das inscrições. |
| Ambiental            | O contexto do requisito está relacionado à necessidade de usuários trabalhadores de acessar informações sobre oportunidades de emprego disponíveis, facilitando a busca e a candidatura a vagas adequadas ao seu perfil. |
| Organizacional       | Entre os objetivos e as estratégias do aplicativo CTD, este requisito alinha-se com a missão de facilitar o acesso dos trabalhadores a novas oportunidades de emprego, promovendo a empregabilidade e conectando trabalhadores a empregadores de forma eficiente. |
| Gerencial            | Do ponto de vista gerencial, este requisito indica que será necessário armazenar e atualizar informações sobre processos seletivos abertos de forma organizada e segura. A gerência deve focar na integração do sistema com bancos de dados de vagas de emprego e na interface de usuário para a visualização dessas informações. |
| Desenvolvimento      | Durante o desenvolvimento, esse requisito implica na criação de funcionalidades que permitam a visualização detalhada dos processos seletivos abertos, incluindo a integração com bancos de dados que armazenam essas informações e a criação de telas e filtros específicos no aplicativo para facilitar o acesso dos usuários às vagas de interesse. |
| Nível de Priorização | - |

<b> Autora: </b> <a href="https://github.com/LuaMedeiros">Luana Medeiros</a>.

### Elos de Rastreabilidade

A tabela 34 mostra os elos do requisito RF16.

<center> 

<b>Tabela 34:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| Recurso | Desenvolvimento | <li> Módulo de Consulta de Processos Seletivos <br> <li> Banco de Dados de Vagas de Emprego <br> <li> Interface de Usuário para Visualização de Vagas | O módulo de consulta de processos seletivos, o banco de dados de vagas de emprego e a interface de usuário para visualização das vagas são recursos necessários para implementar este requisito. | **Os requisitos que fornecem os recursos necessários são:** <br><br> Requisitos Funcionais: <br> <li> RF01 Usuário se registrar no aplicativo (necessário para acessar o recurso de ativação de status) <br> <li> RF02 Usuário poder fazer login para entrar na sua página pessoal (necessário para alterar status) <br> <li> RF03 Usuário pode consultar suas informações pessoais (relevante para verificar o status atual) <br> <li> RF15 Usuário trabalhador pode ativar modo de status (procurando emprego ou não) (para filtrar processos seletivos) <br> <li> RF19 Usuário recebe notificações do aplicativo (para informar sobre novos processos seletivos) <br><br> Requisitos não funcionais: <br> <li> RNF08 O sistema deve implementar autenticação multifator, criptografia AES-256, controle de acesso baseado em funções, e logs de auditoria detalhados (segurança e conformidade) <br> <li> RNF09 O sistema deve garantir a conformidade com a LGPD (Lei Geral de Proteção de Dados) (proteção de dados pessoais) <br> <li> RNF15 O acesso às funcionalidades principais do aplicativo deve exigir autenticação biométrica e ser completado em menos de 30 segundos (segurança e rapidez no acesso) |

<b> Autora: </b> <a href="https://github.com/LuaMedeiros">Luana Medeiros</a>.

</center>

</details>


<details>
  <summary><b> RF17 - Luana Medeiros </b></summary> 

 <b>Tabela 35:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário pode ocultar dados sensíveis |
| Origem do Requisito  | Análise de documentos e storytelling |
| Descrição            | Este requisito estabelece que o usuário deve ser capaz de ocultar dados sensíveis, como informações pessoais, através do aplicativo. O usuário pode selecionar quais dados serão ocultados, garantindo maior privacidade e segurança de suas informações. |
| Ambiental            | O contexto do requisito está relacionado à necessidade de proteger a privacidade dos usuários, permitindo que eles tenham controle sobre quais informações pessoais estão visíveis para terceiros. |
| Organizacional       | Entre os objetivos e as estratégias do aplicativo CTD, este requisito alinha-se com a missão de proteger as informações dos usuários, oferecendo mecanismos de privacidade que permitam a ocultação de dados sensíveis conforme a preferência de cada indivíduo. |
| Gerencial            | Do ponto de vista gerencial, este requisito indica que será necessário desenvolver funcionalidades que permitam a configuração de privacidade pelos usuários, além de garantir que essas preferências sejam respeitadas e mantidas no sistema. A gerência deve assegurar a implementação de interfaces intuitivas e a segurança dos dados ocultos. |
| Desenvolvimento      | Durante o desenvolvimento, esse requisito implica na criação de funcionalidades que permitam ao usuário selecionar e ocultar dados sensíveis. Isso inclui a implementação de opções de configuração de privacidade no aplicativo, o armazenamento seguro dessas preferências no banco de dados e a garantia de que dados ocultados não serão acessíveis por entidades não autorizadas. |
| Nível de Priorização | - |

<b> Autora: </b> <a href="https://github.com/LuaMedeiros">Luana Medeiros</a>.


### Elos de Rastreabilidade

A tabela 36 mostra os elos do requisito RF17.

<center> 

<b>Tabela 36:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| Recurso | Desenvolvimento | <li> Módulo de Configuração de Privacidade <br> <li> Banco de Dados para Armazenamento de Preferências de Privacidade <br> <li> Interface de Usuário para Configuração de Privacidade | O módulo de configuração de privacidade, o banco de dados para armazenamento das preferências de privacidade e a interface de usuário para configuração de privacidade são recursos necessários para implementar este requisito. | **Os requisitos que fornecem os recursos necessários são:** <br><br> Requisitos Funcionais: <br> <li> RF01 Usuário se registrar no aplicativo (necessário para acessar o recurso de ativação de status) <br> <li> RF02 Usuário poder fazer login para entrar na sua página pessoal (necessário para alterar status) <br> <li> RF03 Usuário pode consultar suas informações pessoais (relevante para verificar o status atual) <br> <li> RF04 Usuário pode atualizar suas informações pessoais (para modificar configurações de privacidade) <br> <li> RF19 Usuário recebe notificações do aplicativo (para informar sobre novos processos seletivos) <br><br> Requisitos não funcionais: <br> <li> RNF08 O sistema deve implementar autenticação multifator, criptografia AES-256, controle de acesso baseado em funções, e logs de auditoria detalhados (segurança e conformidade) <br> <li> RNF09 O sistema deve garantir a conformidade com a LGPD (Lei Geral de Proteção de Dados) (proteção de dados pessoais) |

<b> Autora: </b> <a href="https://github.com/LuaMedeiros">Luana Medeiros</a>.

</center>

</details>



<details>
  <summary><b> RF18 - Luana Medeiros </b></summary> 
 
<b>Tabela 37:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário trabalhador pode consultar o número da carteira e de série como CIPS |
| Origem do Requisito  | Storytelling |
| Descrição            | Este requisito estabelece que o usuário trabalhador deve ser capaz de consultar o número da carteira de trabalho e de série (CIPS) através do aplicativo. Essas informações devem ser facilmente acessíveis e visualizáveis pelo usuário. |
| Ambiental            | O contexto do requisito está relacionado à necessidade de os usuários trabalhadores acessarem facilmente informações essenciais de sua carteira de trabalho, como o número da carteira e de série, para diversos fins administrativos e legais. |
| Organizacional       | Entre os objetivos e as estratégias do aplicativo CTD, este requisito alinha-se com a missão de centralizar e facilitar o acesso às informações dos usuários, garantindo que dados importantes como o número da carteira de trabalho e de série sejam prontamente disponíveis e seguros. |
| Gerencial            | Do ponto de vista gerencial, este requisito indica que será necessário armazenar e organizar as informações da carteira de trabalho dos usuários de maneira segura. A gerência deve focar na integração do sistema com os bancos de dados que contêm esses números e na interface de usuário para a visualização dessas informações de forma clara e segura. |
| Desenvolvimento      | Durante o desenvolvimento, esse requisito implica na criação de funcionalidades que permitam a visualização do número da carteira de trabalho e de série (CIPS) no aplicativo. Isso inclui a integração com bancos de dados que armazenam essas informações, a criação de telas específicas no aplicativo para acesso fácil e a implementação de medidas de segurança para proteger esses dados. |
| Nível de Priorização | - |

<b> Autora: </b> <a href="https://github.com/LuaMedeiros">Luana Medeiros</a>.

### Elos de Rastreabilidade

A tabela 38 mostra os elos do requisito RF18.

<center> 

<b>Tabela 38:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| Recurso | Desenvolvimento | <li> Módulo de Consulta de Informações da Carteira de Trabalho <br> <li> Banco de Dados de Informações da Carteira de Trabalho <br> <li> Interface de Usuário para Consulta de Dados | O módulo de consulta de informações da carteira de trabalho, o banco de dados de informações da carteira de trabalho e a interface de usuário para consulta de dados são recursos necessários para implementar este requisito. | **Os requisitos que fornecem os recursos necessários são:** <br><br> Requisitos Funcionais: <br> <li> RF01 Usuário se registrar no aplicativo (necessário para acessar o recurso de ativação de status) <br> <li> RF02 Usuário poder fazer login para entrar na sua página pessoal (necessário para alterar status) <br> <li> RF03 Usuário pode consultar suas informações pessoais (relevante para verificar o status atual) <br> <li> RF05 Usuário trabalhador pode consultar contratos de trabalho (relevante para relacionar contratos com o número da carteira) <br> <li> RF19 Usuário recebe notificações do aplicativo (para informar sobre novos processos seletivos) <br><br> Requisitos não funcionais: <br> <li> RNF08 O sistema deve implementar autenticação multifator, criptografia AES-256, controle de acesso baseado em funções, e logs de auditoria detalhados (segurança e conformidade) <br> <li> RNF09 O sistema deve garantir a conformidade com a LGPD (Lei Geral de Proteção de Dados) (proteção de dados pessoais) <br> <li> RNF18 O sistema deve listar contratos de trabalho com todos os detalhes relevantes, atualizados em tempo real (atualização em tempo real dos dados da carteira) |

<b> Autora: </b> <a href="https://github.com/LuaMedeiros">Luana Medeiros</a>.
</center>

</details>


<details>
  <summary><b> RF19 - Luana Medeiros </b></summary> 

<b>Tabela 39:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário recebem notificações do aplicativo |
| Origem do Requisito  | Análise de documentos e Storytelling |
| Descrição            | Este requisito estabelece que o usuário deve receber notificações do aplicativo sobre diversas atualizações e eventos importantes, como novos processos seletivos, alterações no status de emprego, lembretes de compromissos e outras comunicações relevantes. |
| Ambiental            | O contexto do requisito está relacionado à necessidade de manter os usuários informados e engajados com atualizações e eventos importantes que podem impactar sua vida profissional e o uso do aplicativo. |
| Organizacional       | Entre os objetivos e as estratégias do aplicativo CTD, este requisito alinha-se com a missão de manter uma comunicação eficaz com os usuários, garantindo que eles estejam sempre cientes de informações relevantes e possam agir prontamente em resposta a essas notificações. |
| Gerencial            | Do ponto de vista gerencial, este requisito indica que será necessário desenvolver e manter um sistema de notificações eficiente e confiável. A gerência deve assegurar a configuração adequada das notificações, incluindo a personalização das preferências do usuário e a garantia de que as notificações sejam entregues de maneira oportuna e segura. |
| Desenvolvimento      | Durante o desenvolvimento, esse requisito implica na criação de funcionalidades que permitam o envio e a gestão de notificações. Isso inclui a implementação de uma infraestrutura de backend para o envio de notificações, a criação de interfaces no aplicativo onde os usuários possam configurar suas preferências de notificação, e a integração com serviços de push notification para garantir a entrega eficiente das mensagens. |
| Nível de Priorização | - |

<b> Autora: </b> <a href="https://github.com/LuaMedeiros">Luana Medeiros</a>.

### Elos de Rastreabilidade

A tabela 40 mostra os elos do requisito RF19.

<center> 

<b>Tabela 40:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| Recurso | Desenvolvimento | <li> Módulo de Notificações <br> <li> Serviço de Push Notification <br> <li> Interface de Usuário para Configuração de Notificações | O módulo de notificações, o serviço de push notification e a interface de usuário para configuração de notificações são recursos necessários para implementar este requisito. | **Os requisitos que fornecem os recursos necessários são:** <br><br> Requisitos Funcionais: <br> <li> RF01 Usuário se registrar no aplicativo (necessário para acessar o recurso de ativação de status) <br> <li> RF02 Usuário poder fazer login para entrar na sua página pessoal (necessário para alterar status) <br> <li> RF03 Usuário pode consultar suas informações pessoais (relevante para verificar o status atual) <br> <li> RF15 Usuário trabalhador pode ativar modo de status (procurando emprego ou não) (notificações relacionadas ao status de emprego) <br> <li> RF16 Usuário trabalhador pode verificar processos seletivos abertos (notificações sobre novos processos seletivos) <br> <li> RF17 Usuário pode ocultar dados sensíveis (notificações sobre alterações na privacidade) <br> <li> RF18 Usuário trabalhador pode consultar o número da carteira e de série como CIPS (notificações sobre alterações nos dados da carteira) <br> <li> RF21 Usuário empresa pode consultar dados dos funcionários (notificações para empresas sobre alterações nos dados dos funcionários) <br><br> Requisitos não funcionais: <br> <li> RNF08 O sistema deve implementar autenticação multifator, criptografia AES-256, controle de acesso baseado em funções, e logs de auditoria detalhados (segurança e conformidade) <br> <li> RNF09 O sistema deve garantir a conformidade com a LGPD (Lei Geral de Proteção de Dados) (proteção de dados pessoais) <br> <li> RNF23 O sistema deve enviar notificações precisas com uma taxa de falsos positivos inferior a 5% (eficiência das notificações) |

<b> Autora: </b> <a href="https://github.com/LuaMedeiros">Luana Medeiros</a>.

</center>

</details>


<details>
  <summary><b> RF20 - Luana Medeiros </b></summary> 

<b>Tabela 41:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário pode consultar perguntas frequentes |
| Origem do Requisito  | Storytelling e Entrevista |
| Descrição            | Este requisito estabelece que o usuário deve ser capaz de consultar uma seção de perguntas frequentes (FAQ) através do aplicativo, onde encontrará respostas para as dúvidas mais comuns sobre o uso do aplicativo, funcionalidades, procedimentos, e políticas. |
| Ambiental            | O contexto do requisito está relacionado à necessidade de fornecer suporte e esclarecer dúvidas comuns dos usuários, permitindo que eles encontrem rapidamente respostas sem a necessidade de contatar o suporte técnico. |
| Organizacional       | Entre os objetivos e as estratégias do aplicativo CTD, este requisito alinha-se com a missão de melhorar a experiência do usuário e aumentar a eficiência do suporte ao usuário, reduzindo a carga de trabalho do atendimento ao cliente e facilitando o autoatendimento. |
| Gerencial            | Do ponto de vista gerencial, este requisito indica que será necessário desenvolver e manter uma base de conhecimento organizada e acessível. A gerência deve assegurar que as perguntas frequentes sejam atualizadas regularmente, sejam de fácil navegação e contenham informações precisas e úteis. |
| Desenvolvimento      | Durante o desenvolvimento, esse requisito implica na criação de funcionalidades que permitam a visualização e navegação na seção de perguntas frequentes. Isso inclui a implementação de uma interface de usuário intuitiva, a integração com a base de dados que armazena as perguntas e respostas, e a criação de mecanismos de busca e filtragem para facilitar o acesso às informações relevantes. |
| Nível de Priorização | - |

<b> Autora: </b> <a href="https://github.com/LuaMedeiros">Luana Medeiros</a>.


### Elos de Rastreabilidade

A tabela 42 mostra os elos do requisito RF20.

<center> 

Tabela 42: Elos do requisito RF20

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| Recurso | Desenvolvimento | <li> Módulo de Perguntas Frequentes (FAQ)  <br> <li> Banco de Dados de Perguntas e Respostas <br> <li> Interface de Usuário para Navegação no FAQ | O módulo de perguntas frequentes, o banco de dados de perguntas e respostas e a interface de usuário para navegação no FAQ são recursos necessários para implementar este requisito. | **Os requisitos que fornecem os recursos necessários são:** <br><br> Requisitos Funcionais: <br> <li> RF01 Usuário se registrar no aplicativo (necessário para acessar o recurso de ativação de status) <br> <li> RF02 Usuário poder fazer login para entrar na sua página pessoal (necessário para alterar status) <br> <li> RF03 Usuário pode consultar suas informações pessoais (relevante para verificar o status atual) <br> <li> RF19 Usuário recebe notificações do aplicativo (para informar sobre novas perguntas frequentes ou atualizações) <br> <br> Requisitos não funcionais: <br> <li> RNF08 O sistema deve implementar autenticação multifator, criptografia AES-256, controle de acesso baseado em funções, e logs de auditoria detalhados (segurança e conformidade) <br> <li> RNF09 O sistema deve garantir a conformidade com a LGPD (Lei Geral de Proteção de Dados) (proteção de dados pessoais) <br> <li> RNF24 O aplicativo deve ser compatível com iOS, Android e Windows, sem apresentar falhas críticas em nenhum dos sistemas operacionais suportados (compatibilidade e usabilidade) |


<b> Autora: </b> <a href="https://github.com/LuaMedeiros">Luana Medeiros</a>.

</center>

</details>



<details>
  <summary><b> RF21 - Luana Medeiros </b></summary> 

<b>Tabela 43:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário empresa pode consultar dados dos funcionários |
| Origem do Requisito  | Entrevistas e análise de documento |
| Descrição            | Este requisito estabelece que o usuário empresa deve ser capaz de consultar os dados de seus funcionários através do aplicativo. Esses dados podem incluir informações pessoais, históricos de emprego, qualificações, e status de contrato. |
| Ambiental            | O contexto do requisito está relacionado à necessidade das empresas de acessar e gerenciar informações sobre seus funcionários de forma eficiente e segura, facilitando processos administrativos e de recursos humanos. |
| Organizacional       | Entre os objetivos e as estratégias do aplicativo CTD, este requisito alinha-se com a missão de fornecer uma ferramenta robusta para as empresas gerenciarem os dados dos funcionários, promovendo a eficiência operacional e a segurança das informações. |
| Gerencial            | Do ponto de vista gerencial, este requisito indica que será necessário desenvolver funcionalidades que permitam às empresas acessar e visualizar dados dos funcionários de maneira segura e organizada. A gerência deve assegurar a implementação de controles de acesso adequados para proteger a privacidade dos dados dos funcionários e garantir a conformidade com regulamentos de proteção de dados. |
| Desenvolvimento      | Durante o desenvolvimento, esse requisito implica na criação de funcionalidades que permitam ao usuário empresa acessar e consultar os dados dos funcionários. Isso inclui a implementação de uma interface de usuário específica para empresas, a integração com bancos de dados que armazenam essas informações e a aplicação de medidas de segurança robustas para proteger os dados contra acessos não autorizados. |
| Nível de Priorização | - |

<b> Autora: </b> <a href="https://github.com/LuaMedeiros">Luana Medeiros</a>.


### Elos de Rastreabilidade

A tabela 44 mostra os elos do requisito RF21.

<center> 

<b>Tabela 44:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| Recurso | Desenvolvimento | <li> Módulo de Consulta de Dados de Funcionários  <br> <li> Banco de Dados de Informações dos Funcionários <br> <li> Interface de Usuário para Consulta de Dados | O módulo de consulta de dados de funcionários, o banco de dados de informações dos funcionários e a interface de usuário para consulta de dados são recursos necessários para implementar este requisito. | **Os requisitos que fornecem os recursos necessários são:** <br><br> Requisitos Funcionais: <br> <li> RF01 Usuário se registrar no aplicativo (necessário para acessar o recurso de ativação de status) <br> <li> RF02 Usuário poder fazer login para entrar na sua página pessoal (necessário para alterar status) <br> <li> RF03 Usuário pode consultar suas informações pessoais (relevante para verificar o status atual) <br> <li> RF04 Usuário pode atualizar suas informações pessoais (relevante para manter dados dos funcionários atualizados) <br> <li> RF05 Usuário trabalhador pode consultar contratos de trabalho (dados relevantes para empresas) <br> <li> RF06 Usuário trabalhador pode atualizar contratos de trabalho (dados relevantes para empresas) <br> <li> RF17 Usuário pode ocultar dados sensíveis (privacidade dos dados dos funcionários) <br><li> RF22 Usuário empresa pode atualizar dados dos funcionários (manutenção e atualização dos dados) <br><li> RF23 Usuário empresa pode consultar contratos de trabalho (informações contratuais dos funcionários) <br><li> RF24 Usuário empresa pode gerar relatórios trabalhistas (análise de dados dos funcionários) <br> <li> RF25 Usuário empresa pode gerenciar contratos de trabalho (adicionar novos, atualizar já existentes e encerrar contratos) (gestão completa dos contratos) <br><br> Requisitos não funcionais: <br> <li> RNF08 O sistema deve implementar autenticação multifator, criptografia AES-256, controle de acesso baseado em funções, e logs de auditoria detalhados (segurança e conformidade) <br> <li> RNF09 O sistema deve garantir a conformidade com a LGPD (Lei Geral de Proteção de Dados) (proteção de dados pessoais) <br> <li> RNF18 O sistema deve listar contratos de trabalho com todos os detalhes relevantes, atualizados em tempo real (atualização em tempo real dos dados contratuais) <br> <li> RNF20 O sistema deve ser totalmente integrado com o eSocial, com uma taxa de sincronização de dados de 99% (integra|

<b> Autora: </b> <a href="https://github.com/LuaMedeiros">Luana Medeiros</a>.

</center>

</details>


<details>
  <summary><b> RF22 - Pedro Izarias </b></summary> 

 <b>Tabela 45:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário empresa pode atualizar dados dos funcionários |
| Origem do Requisito  | Entrevistas e Análise de Documentos |
| Descrição            | Esse requisito permite que empresas possam atualizar os dados de seus funcionários diretamente no aplicativo, garantindo que as informações estejam sempre atualizadas e corretas. Isso inclui a atualização de informações pessoais e profissionais dos funcionários. |
| Ambiental | O contexto do requisito está relacionado à necessidade das empresas de manterem as informações dos funcionários atualizadas, refletindo mudanças como promoções, alterações salariais, entre outras. |
| Organizacional | Alinhado com o objetivo do CTD em fornecer uma ferramenta completa para a gestão de informações trabalhistas tanto para trabalhadores quanto para empregadores. |
| Gerencial | Do ponto de vista gerencial, é importante garantir a integração segura e eficiente das atualizações de dados com o banco de dados do sistema. |
| Desenvolvimento      | A implementação deste requisito requer a criação de uma interface para a atualização de dados dos funcionários e a integração com o banco de dados para armazenamento seguro das informações atualizadas. |
| Nível de Priorização | - |

<b> Autor: </b> <a href="https://github.com/Izarias">Pedro Izarias</a>.

### Elos de Rastreabilidade

A tabela 46 mostra os elos do requisito RF22.

<center> 

<b>Tabela 46:</b> Elo do Requisito

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| -------------- | -----------------  | ----------------------------------------------------- | -------------| ---- |
| Recurso | Desenvolvimento | <li> Módulo de Atualização de Dados de Funcionários <br> <li> Banco de Dados para Armazenamento de Dados de Funcionários <br> <li> Interface de Usuário para Atualização de Dados. | O banco de dados para armazenar os dados dos funcionários atualizados e a interface de usuário para permitir a atualização dessas informações são recursos necessários. | **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li> RF03: Usuário pode consultar suas informações pessoais <br> <li> RF04: Usuário pode atualizar suas informações pessoais <br> <br>  Requisitos não funcionais: <br> <li> RNF14: O aplicativo deve seguir padrões de design aceitos por empresas e instituições, com uma taxa de conformidade de 95% nas avaliações de usabilidade. <br> <li> RNF18: O sistema deve listar contratos de trabalho com todos os detalhes relevantes, atualizados em tempo real.|

<b> Autor: </b> <a href="https://github.com/Izarias">Pedro Izarias</a>.

</center>

</details>

<details>
  <summary><b> RF23 - Pedro Izarias </b></summary> 

 <b>Tabela 47:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário empresa pode consultar contratos de trabalho |
| Origem do Requisito  | Entrevistas e Análise de Documentos |
| Descrição            | Esse requisito permite que empresas possam consultar contratos de trabalho dos funcionários, verificando informações como datas de início e término, salários, e outros detalhes relevantes. |
| Ambiental | O contexto do requisito está relacionado à necessidade das empresas de verificar os contratos de trabalho de seus funcionários para fins administrativos e de conformidade legal. |
| Organizacional | Alinhado com o objetivo do CTD em fornecer uma ferramenta completa para a gestão de informações trabalhistas tanto para trabalhadores quanto para empregadores. |
| Gerencial | Do ponto de vista gerencial, é importante garantir a integração segura e eficiente das consultas de contratos de trabalho com o banco de dados do sistema. |
| Desenvolvimento      | A implementação deste requisito requer a criação de uma interface para a consulta de contratos de trabalho e a integração com o banco de dados para acesso seguro às informações. |
| Nível de Priorização | - |

<b> Autor: </b> <a href="https://github.com/Izarias">Pedro Izarias</a>.

### Elos de Rastreabilidade

A tabela 48 mostra os elos do requisito RF23.

<center> 

<b>Tabela 48:</b> Elo do Requisito

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| -------------- | -----------------  | ----------------------------------------------------- | -------------| ---- |
| Recurso | Desenvolvimento | <li> Módulo de Consulta de Contratos de Trabalho <br> <li> Banco de Dados para Armazenamento de Contratos de Trabalho <br> <li> Interface de Usuário para Consulta de Contratos. | O banco de dados para armazenar os contratos de trabalho e a interface de usuário para permitir a consulta dessas informações são recursos necessários. | **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li> RF05: Usuário trabalhador pode consultar contratos de trabalho <br> <br>  Requisitos não funcionais: <br> <li> RNF18: O sistema deve listar contratos de trabalho com todos os detalhes relevantes, atualizados em tempo real.|

<b> Autor: </b> <a href="https://github.com/Izarias">Pedro Izarias</a>.

</center>

</details>

<details>
  <summary><b> RF24 - Pedro Izarias </b></summary> 

 <b>Tabela 49:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário empresa pode gerar relatórios trabalhistas |
| Origem do Requisito  | Entrevistas e Análise de Documentos |
| Descrição            | Esse requisito permite que empresas possam gerar relatórios trabalhistas, incluindo informações sobre contratos de trabalho, benefícios, e outros dados relevantes para a administração da força de trabalho. |
| Ambiental | O contexto do requisito está relacionado à necessidade das empresas de gerar relatórios trabalhistas para fins de gestão interna e conformidade com regulamentações trabalhistas. |
| Organizacional | Alinhado com o objetivo do CTD em fornecer uma ferramenta completa para a gestão de informações trabalhistas tanto para trabalhadores quanto para empregadores. |
| Gerencial | Do ponto de vista gerencial, é importante garantir que a geração de relatórios seja eficiente e que os dados estejam sempre atualizados. |
| Desenvolvimento      | A implementação deste requisito requer a criação de uma interface para a geração de relatórios e a integração com o banco de dados para acesso seguro e eficiente às informações necessárias. |
| Nível de Priorização | - |

<b> Autor: </b> <a href="https://github.com/Izarias">Pedro Izarias</a>.

### Elos de Rastreabilidade

A tabela 50 mostra os elos do requisito RF24.

<center> 

<b>Tabela 50:</b> Elo do Requisito

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| -------------- | -----------------  | ----------------------------------------------------- | -------------| ---- |
| Recurso | Desenvolvimento | <li> Módulo de Geração de Relatórios <br> <li> Banco de Dados para Armazenamento de Informações Trabalhistas <br> <li> Interface de Usuário para Geração de Relatórios. | O banco de dados para armazenar as informações trabalhistas e a interface de usuário para permitir a geração de relatórios são recursos necessários. | **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li> RF06: Usuário trabalhador pode consultar benefícios <br> <br>  Requisitos não funcionais: <br> <li> RNF12: O sistema deve permitir a exportação de dados em formatos compatíveis com outros sistemas de gestão.|

<b> Autor: </b> <a href="https://github.com/Izarias">Pedro Izarias</a>.

</center>

</details>

<details>
  <summary><b> RF25 - Pedro Izarias </b></summary> 

 <b>Tabela 51:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário empresa pode gerenciar contratos de trabalho (adicionar novos, atualizar já existentes e encerrar contratos) |
| Origem do Requisito  | Entrevistas |
| Descrição            | Este requisito permite que os usuários empresariais gerenciem os contratos de trabalho dos seus funcionários através do aplicativo. Eles podem adicionar novos contratos, atualizar informações existentes e encerrar contratos quando necessário. |
| Ambiental | Este requisito surge da necessidade das empresas em gerenciar de forma eficiente e centralizada os contratos de trabalho de seus funcionários. |
| Organizacional | Alinhado com o objetivo do CTD de fornecer ferramentas de gestão completas para empresas e seus funcionários. |
| Gerencial | Do ponto de vista gerencial, é crucial garantir que o processo de gerenciamento de contratos seja seguro, eficiente e esteja em conformidade com as regulamentações trabalhistas. |
| Desenvolvimento      | A implementação deste requisito envolve a criação de uma interface para gerenciamento de contratos, integração com o banco de dados para armazenamento seguro e atualização das informações. |
| Nível de Priorização | - |

<b> Autor: </b> <a href="https://github.com/Izarias">Pedro Izarias</a>.

### Elos de Rastreabilidade

A tabela 52 mostra os elos do requisito RF25.

<center> 

<b>Tabela 52:</b> Elo do Requisito

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| -------------- | -----------------  | ----------------------------------------------------- | -------------| ---- |
| Recurso | Desenvolvimento | <li> Módulo de Gerenciamento de Contratos de Trabalho <br> <li> Banco de Dados para Armazenamento de Contratos <br> <li> Interface de Usuário para Gerenciamento de Contratos. | O módulo de gerenciamento de contratos de trabalho e a interface de usuário para permitir o gerenciamento são recursos necessários. | **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li> RF05: Usuário trabalhador pode consultar contratos de trabalho <br> <br>  Requisitos não funcionais: <br> <li> RNF18: O sistema deve listar contratos de trabalho com todos os detalhes relevantes, atualizados em tempo real.|

<b> Autor: </b> <a href="https://github.com/Izarias">Pedro Izarias</a>.

</center>

</details>

<details>
  <summary><b> RF26 - Pedro Izarias </b></summary> 

 <b>Tabela 53:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário empresa pode cadastrar benefícios para a empresa |
| Origem do Requisito  | Entrevistas e análise de documento |
| Descrição            | Este requisito permite que os usuários empresariais cadastrem benefícios para seus funcionários através do aplicativo. Os benefícios podem incluir vantagens adicionais oferecidas pela empresa, como plano de saúde, vale-refeição, entre outros. |
| Ambiental | Surge da necessidade das empresas em oferecer benefícios atrativos para retenção e motivação dos funcionários. |
| Organizacional | Alinhado com o objetivo do CTD de fornecer ferramentas de gestão completas para empresas e seus funcionários. |
| Gerencial | Do ponto de vista gerencial, é importante garantir que o cadastro de benefícios seja fácil de realizar e que os benefícios sejam claros e bem comunicados aos funcionários. |
| Desenvolvimento      | A implementação deste requisito envolve a criação de uma interface para cadastro de benefícios, integração com o sistema para armazenamento seguro das informações e possibilidade de atualização conforme necessário. |
| Nível de Priorização | - |

<b> Autor: </b> <a href="https://github.com/Izarias">Pedro Izarias</a>.

### Elos de Rastreabilidade

A tabela 54 mostra os elos do requisito RF26.

<center> 

<b>Tabela 54:</b> Elo do Requisito

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| -------------- | -----------------  | ----------------------------------------------------- | -------------| ---- |
| Recurso | Desenvolvimento | <li> Módulo de Cadastro de Benefícios <br> <li> Banco de Dados para Armazenamento de Benefícios <br> <li> Interface de Usuário para Cadastro de Benefícios. | O módulo de cadastro de benefícios e a interface de usuário para permitir o cadastro são recursos necessários. | **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li> RF07: Usuário trabalhador pode consultar dados de contato <br> <br>  Requisitos não funcionais: <br> <li> RNF12: O sistema deve permitir a exportação de dados em formatos compatíveis com outros sistemas de gestão.|

<b> Autor: </b> <a href="https://github.com/Izarias">Pedro Izarias</a>.

</center>

</details>

<details>
  <summary><b> RF27 - Pedro Izarias </b></summary> 

 <b>Tabela 55:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário empresa pode gerenciar benefícios trabalhistas |
| Origem do Requisito  | Entrevistas |
| Descrição            | Este requisito permite que os usuários empresariais gerenciem os benefícios trabalhistas oferecidos aos seus funcionários através do aplicativo. Eles podem configurar novos benefícios, atualizar informações existentes e desativar benefícios quando necessário. |
| Ambiental | Este requisito surge da necessidade das empresas em oferecer e gerenciar benefícios competitivos para atrair e reter talentos. |
| Organizacional | Alinhado com o objetivo do CTD de fornecer ferramentas de gestão completas para empresas e seus funcionários. |
| Gerencial | Do ponto de vista gerencial, é crucial garantir que o gerenciamento de benefícios seja flexível e permita personalização conforme as necessidades da empresa e dos funcionários. |
| Desenvolvimento      | A implementação deste requisito envolve a criação de uma interface para gerenciamento de benefícios, integração com o sistema para armazenamento seguro das informações e suporte a atualizações dinâmicas. |
| Nível de Priorização | - |

<b> Autor: </b> <a href="https://github.com/Izarias">Pedro Izarias</a>.

### Elos de Rastreabilidade

A tabela 56 mostra os elos do requisito RF27.

<center> 

<b>Tabela 56:</b> Elo do Requisito

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| -------------- | -----------------  | ----------------------------------------------------- | -------------| ---- |
| Recurso | Desenvolvimento | <li> Módulo de Gerenciamento de Benefícios Trabalhistas <br> <li> Banco de Dados para Armazenamento de Benefícios <br> <li> Interface de Usuário para Gerenciamento de Benefícios. | O módulo de gerenciamento de benefícios trabalhistas e a interface de usuário para permitir o gerenciamento são recursos necessários. | **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li> RF08: Usuário pode gerenciar informações trabalhistas <br> <br>  Requisitos não funcionais: <br> <li> RNF12: O sistema deve permitir a exportação de dados em formatos compatíveis com outros sistemas de gestão.|

<b> Autor: </b> <a href="https://github.com/Izarias">Pedro Izarias</a>.

</center>

</details>

<details>
  <summary><b> RF28 - Pedro Izarias </b></summary> 

 <b>Tabela 57:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | Usuário empresa escolher modo de status: "Possui vagas de emprego" ou "Não possui vagas de emprego" |
| Origem do Requisito  | Entrevistas |
| Descrição            | Este requisito permite que os usuários empresariais configurem o status da empresa em relação à disponibilidade de vagas de emprego através do aplicativo. Eles podem escolher entre indicar que a empresa possui vagas de emprego disponíveis ou que não possui vagas disponíveis no momento. |
| Ambiental | Surge da necessidade das empresas em comunicar claramente sua situação de contratação aos potenciais candidatos. |
| Organizacional | Alinhado com o objetivo do CTD de facilitar a interação entre empresas e candidatos a emprego de forma transparente. |
| Gerencial | Do ponto de vista gerencial, é importante que a configuração do status seja fácil de atualizar e que as informações sejam refletidas de forma precisa no aplicativo. |
| Desenvolvimento      | A implementação deste requisito envolve a criação de uma interface para configuração do status, integração com o sistema para atualização em tempo real e garantia de que as informações sejam acessíveis aos candidatos. |
| Nível de Priorização | - |

<b> Autor: </b> <a href="https://github.com/Izarias">Pedro Izarias</a>.

### Elos de Rastreabilidade

A tabela 58 mostra os elos do requisito RF28.

<center> 

<b>Tabela 58:</b> Elo do Requisito

| Tipo de Elo | Categoria         | Elementos Rastreáveis                                    | Descrição do ELO| Requisitos Relacionados | 
| -------------- | -----------------  | ----------------------------------------------------- | -------------| ---- |
| Recurso | Desenvolvimento | <li> Interface de Usuário para Configuração de Status de Vagas de Emprego <br> <li> Integração com Sistema para Atualização em Tempo Real <br> <li> Garantia de Acessibilidade das Informações aos Candidatos. | A interface para configuração do status e a integração com o sistema são recursos essenciais para o requisito. | **Os requisitos que fornecem os recursos necessários são:** <br> <br> Requisitos Funcionais: <br> <li> RF10: Usuário pode buscar vagas de emprego disponíveis <br> <br>  Requisitos não funcionais: <br> <li> RNF15: O sistema deve garantir que as informações de vagas de emprego sejam atualizadas em tempo real.|

<b> Autor: </b> <a href="https://github.com/Izarias">Pedro Izarias</a>.

</center>

</details>


## Rastreabilidade dos Requisitos Não Funcionais

<details>
  <summary><b> RNF01 - Breno Alexandre </b></summary> 

<b>Tabela 59:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | - |
| Origem do Requisito  | - |
| Descrição            | - |
| Ambiental            | - |
| Organizacional       | - |
| Gerencial            | - |
| Desenvolvimento      | - |
| Nível de Priorização | - |

<b> Autora: </b> <a href=""> </a>.

### Elos de Rastreabilidade

A tabela 60 mostra os elos do requisito RNF01.

<center> 

<b>Tabela 60:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| - | - | - | - | - |

<b> Autora: </b> <a href=""></a>.

</center>

</details>

<details>
  <summary><b> RNF02 - Breno Alexandre </b></summary> 

<b>Tabela 61:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | - |
| Origem do Requisito  | - |
| Descrição            | - |
| Ambiental            | - |
| Organizacional       | - |
| Gerencial            | - |
| Desenvolvimento      | - |
| Nível de Priorização | - |

<b> Autora: </b> <a href=""> </a>.

### Elos de Rastreabilidade

A tabela 62 mostra os elos do requisito RNF02.

<center> 

<b>Tabela 62:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| - | - | - | - | - |

<b> Autora: </b> <a href=""> </a>.

</center>

</details>

<details>
  <summary><b> RNF03 - Breno Alexandre </b></summary> 

<b>Tabela 63:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | - |
| Origem do Requisito  | - |
| Descrição            | - |
| Ambiental            | - |
| Organizacional       | - |
| Gerencial            | - |
| Desenvolvimento      | - |
| Nível de Priorização | - |

<b> Autora: </b> <a href=""> </a>.

### Elos de Rastreabilidade

A tabela 64 mostra os elos do requisito RNF03.

<center> 

<b>Tabela 64:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| - | - | - | - | - |

<b> Autora: </b> <a href=""> </a>.

</center>

</details>

<details>
  <summary><b> RNF04 - Breno Alexandre </b></summary> 

<b>Tabela 65:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | - |
| Origem do Requisito  | - |
| Descrição            | - |
| Ambiental            | - |
| Organizacional       | - |
| Gerencial            | - |
| Desenvolvimento      | - |
| Nível de Priorização | - |

<b> Autora: </b> <a href=""> </a>.

### Elos de Rastreabilidade

A tabela 66 mostra os elos do requisito RNF04.

<center> 

<b>Tabela 66:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| - | - | - | - | - |

<b> Autora: </b> <a href=""> </a>.

</center>

</details>

<details>
  <summary><b> RNF05 - Breno Alexandre </b></summary> 

<b>Tabela 67:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | - |
| Origem do Requisito  | - |
| Descrição            | - |
| Ambiental            | - |
| Organizacional       | - |
| Gerencial            | - |
| Desenvolvimento      | - |
| Nível de Priorização | - |

<b> Autora: </b> <a href=""> </a>.

### Elos de Rastreabilidade

A tabela 68 mostra os elos do requisito RNF05.

<center> 

<b>Tabela 68:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| - | - | - | - | - |

<b> Autora: </b> <a href=""> </a>.

</center>

</details>

<details>
  <summary><b> RNF06 - Breno Alexandre </b></summary> 

<b>Tabela 69:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | - |
| Origem do Requisito  | - |
| Descrição            | - |
| Ambiental            | - |
| Organizacional       | - |
| Gerencial            | - |
| Desenvolvimento      | - |
| Nível de Priorização | - |

<b> Autora: </b> <a href=""> </a>.

### Elos de Rastreabilidade

A tabela 70 mostra os elos do requisito RNF06.

<center> 

<b>Tabela 70:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| - | - | - | - | - |


<b> Autora: </b> <a href=""> </a>.

</center>

</details>

<details>
  <summary><b> RNF07 - Breno Alexandre </b></summary> 

<b>Tabela 71:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | - |
| Origem do Requisito  | - |
| Descrição            | - |
| Ambiental            | - |
| Organizacional       | - |
| Gerencial            | - |
| Desenvolvimento      | - |
| Nível de Priorização | - |

<b> Autora: </b> <a href=""> </a>.

### Elos de Rastreabilidade

A tabela 72 mostra os elos do requisito RNF07.

<center> 

<b>Tabela 72:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| - | - | - | - | - |


<b> Autora: </b> <a href=""> </a>.

</center>

</details>

<details>
  <summary><b> RNF08 - Breno Alexandre </b></summary> 

<b>Tabela 73:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | - |
| Origem do Requisito  | - |
| Descrição            | - |
| Ambiental            | - |
| Organizacional       | - |
| Gerencial            | - |
| Desenvolvimento      | - |
| Nível de Priorização | - |

<b> Autora: </b> <a href=""> </a>.

### Elos de Rastreabilidade

A tabela 74 mostra os elos do requisito RNF08.

<center> 

<b>Tabela 74:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| - | - | - | - | - |

<b> Autora: </b> <a href=""> </a>.

</center>

</details>

<details>
  <summary><b> RNF09 - 	Bruno Araújo </b></summary> 
  
**Tabela 75: Estrutura do Requisito**

| Características      | Explicação                                                                                               |
| -------------------- | -------------------------------------------------------------------------------------------------------- |
| Nome do Requisito    | Conformidade com a LGPD                                                                                  |
| Origem do Requisito  | Análise de documentos e entrevista                                                                       |
| Descrição            | O sistema deve garantir a conformidade com a LGPD (Lei Geral de Proteção de Dados).                      |
| Ambiental            | O requisito está relacionado ao contexto legal e regulatório, especificamente às normas da LGPD.         |
| Organizacional       | Alinhado com a missão de fornecer um sistema seguro e conforme às regulamentações vigentes.              |
| Gerencial            | Gerenciamento de dados sensíveis conforme as políticas de segurança e privacidade.                       |
| Desenvolvimento      | Implementação de funcionalidades para garantir a conformidade com a LGPD em todas as fases do sistema.   |
| Nível de Priorização | Alto                                                                                                     |

**Autor:** [Bruno Araújo](https://github.com/brunocva)

### Tabela 76: Elo do Requisito

**Tabela 76: Elo do Requisito**

| Tipo de Elo | Categoria       | Elementos Rastreáveis                                | Descrição do ELO | Requisitos Relacionados |
| ----------- | --------------- | ---------------------------------------------------- | ---------------- | ----------------------- |
| Recurso     | Desenvolvimento | <li>Política de Conformidade <br><li> Auditoria de Conformidade | O sistema deve seguir políticas e realizar auditorias para assegurar a conformidade com a LGPD. | RNF09, RNF12 |

**Autor:** [Bruno Araújo](https://github.com/brunocva)

</center>

</details>

<details>
  <summary><b> RNF10 - 	Bruno Araújo </b></summary> 
  
**Tabela 77: Estrutura do Requisito**

| Características      | Explicação                                                                                                         |
| -------------------- | ------------------------------------------------------------------------------------------------------------------ |
| Nome do Requisito    | Suporte a Ferramentas de Acessibilidade                                                                            |
| Origem do Requisito  | Análise de documentos e entrevista                                                                                 |
| Descrição            | O sistema deve oferecer suporte a ampliadores de telas, leitores de telas, programas de reconhecimento de voz, teclados alternativos e dispositivos apontadores alternativos, e ser testado com pelo menos duas ferramentas de acessibilidade diferentes. |
| Ambiental            | Necessidade de suporte a diversas ferramentas de acessibilidade para garantir inclusão digital.                     |
| Organizacional       | Alinhado com a política de inclusão e acessibilidade da organização.                                               |
| Gerencial            | Garantir que as ferramentas de acessibilidade sejam compatíveis e bem integradas no sistema.                        |
| Desenvolvimento      | Implementação de testes de acessibilidade e suporte técnico para ferramentas específicas.                           |
| Nível de Priorização | Médio                                                                                                               |

**Autor:** [Bruno Araújo](https://github.com/brunocva)

### Tabela 78: Elo do Requisito

**Tabela 78: Elo do Requisito**

| Tipo de Elo | Categoria       | Elementos Rastreáveis                                      | Descrição do ELO | Requisitos Relacionados |
| ----------- | --------------- | --------------------------------------------------------- | ---------------- | ----------------------- |
| Recurso     | Desenvolvimento | <li> Ferramentas de Acessibilidade <br><li> Relatório de Testes de Acessibilidade | O sistema deve ser compatível com várias ferramentas de acessibilidade e deve ser testado adequadamente. | RNF10, RNF14 |

**Autor:** [Bruno Araújo](https://github.com/brunocva)


</center>

</details>

<details>
  <summary><b> RNF11 - 	Bruno Araújo </b></summary> 
  
**Tabela 79: Estrutura do Requisito**

| Características      | Explicação                                                                                                     |
| -------------------- | -------------------------------------------------------------------------------------------------------------- |
| Nome do Requisito    | Integração com Processos Governamentais                                                                        |
| Origem do Requisito  | Análise de documentos e entrevista                                                                             |
| Descrição            | O sistema deve permitir a integração completa com os processos de negócios governamentais, conforme especificado na documentação de requisitos. |
| Ambiental            | Contexto governamental e regulatório, garantindo a integração com sistemas governamentais.                     |
| Organizacional       | Alinhado com a missão de facilitar a comunicação e integração com entidades governamentais.                    |
| Gerencial            | Gerenciamento de interfaces e processos de integração com sistemas externos.                                   |
| Desenvolvimento      | Implementação de APIs e interfaces de integração conforme especificações governamentais.                        |
| Nível de Priorização | Médio                                                                                                          |

**Autor:** [Bruno Araújo](https://github.com/brunocva)

### Tabela 80: Elo do Requisito

**Tabela 80: Elo do Requisito**

| Tipo de Elo | Categoria       | Elementos Rastreáveis                            | Descrição do ELO | Requisitos Relacionados |
| ----------- | --------------- | ------------------------------------------------ | ---------------- | ----------------------- |
| Recurso     | Desenvolvimento | <li> Interfaces Governamentais <br><li> Documentação de Integração | O sistema deve integrar-se com os processos e sistemas governamentais, conforme especificações. | RNF11, RNF12 |

**Autor:** [Bruno Araújo](https://github.com/brunocva)

</center>

</details>

<details>
  <summary><b> RNF12 - 	Bruno Araújo </b></summary> 

**Tabela 81: Estrutura do Requisito**

| Características      | Explicação                                                                                         |
| -------------------- | -------------------------------------------------------------------------------------------------- |
| Nome do Requisito    | Uso de Vocabulários Controlados e Taxonomias Padrão                                                |
| Origem do Requisito  | Análise de documentos e entrevista                                                                 |
| Descrição            | O sistema deve utilizar vocabulários controlados e taxonomias padrão do governo, conforme especificado na documentação. |
| Ambiental            | Necessidade de seguir padrões e vocabulários controlados para consistência e interoperabilidade.    |
| Organizacional       | Alinhado com as políticas governamentais de padronização de terminologia.                          |
| Gerencial            | Gerenciamento de terminologias e taxonomias conforme padrões estabelecidos.                        |
| Desenvolvimento      | Implementação de vocabulários controlados e taxonomias nas funcionalidades do sistema.              |
| Nível de Priorização | Médio                                                                                              |

**Autor:** [Bruno Araújo](https://github.com/brunocva)

### Tabela 82: Elo do Requisito

**Tabela 82: Elo do Requisito**

| Tipo de Elo | Categoria       | Elementos Rastreáveis                                      | Descrição do ELO | Requisitos Relacionados |
| ----------- | --------------- | --------------------------------------------------------- | ---------------- | ----------------------- |
| Recurso     | Desenvolvimento | <li> Vocabulários Controlados <br><li> Documentação de Padrões | O sistema deve utilizar vocabulários controlados e taxonomias padrão para garantir consistência. | RNF12, RNF14 |

**Autor:** [Bruno Araújo](https://github.com/brunocva)


</center>

</details>

<details>
  <summary><b> RNF13 - 	Bruno Araújo </b></summary> 
  
**Tabela 83: Estrutura do Requisito**

| Características      | Explicação                                                                                                                     |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| Nome do Requisito    | Processamento de Solicitações em 2 Minutos                                                                                     |
| Origem do Requisito  | Análise de documentos e entrevista                                                                                             |
| Descrição            | O sistema deve processar solicitações de carteira de trabalho em no máximo 2 minutos, com uma taxa de sucesso de 99%.           |
| Ambiental            | Necessidade de um processamento rápido para melhorar a eficiência e a experiência do usuário.                                   |
| Organizacional       | Alinhado com a meta de eficiência e rapidez nos serviços oferecidos pelo sistema.                                              |
| Gerencial            | Garantir que o sistema tenha capacidade e infraestrutura adequadas para processar solicitações rapidamente.                    |
| Desenvolvimento      | Implementação de algoritmos eficientes e infraestrutura de suporte para processamento rápido das solicitações.                  |
| Nível de Priorização | Alto                                                                                                                           |

**Autor:** [Bruno Araújo](https://github.com/brunocva)

### Tabela 84: Elo do Requisito

**Tabela 84: Elo do Requisito**

| Tipo de Elo | Categoria       | Elementos Rastreáveis                            | Descrição do ELO | Requisitos Relacionados |
| ----------- | --------------- | ------------------------------------------------ | ---------------- | ----------------------- |
| Recurso     | Desenvolvimento | <li> Logs de Processamento <br><li> Documentação de Algoritmos | Garante o processamento de solicitações dentro do tempo esperado através de algoritmos eficientes e logs. | RNF13, RNF14 |

**Autor:** [Bruno Araújo](https://github.com/brunocva)

</center>

</details>

<details>
  <summary><b> RNF14 - Bruno Araújo</b></summary> 

**Tabela 85: Estrutura do Requisito**

| Características      | Explicação                                                                                                                            |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| Nome do Requisito    | Padrões de Design Aceitos                                                                                                             |
| Origem do Requisito  | Análise de documentos e entrevista                                                                                                    |
| Descrição            | O aplicativo deve seguir padrões de design aceitos por empresas e instituições, com uma taxa de conformidade de 95% nas avaliações de usabilidade. |
| Ambiental            | Necessidade de adesão a padrões de design estabelecidos para garantir uma experiência de usuário consistente e intuitiva.              |
| Organizacional       | Alinhado com as melhores práticas e padrões de design da indústria para assegurar a qualidade do produto.                             |
| Gerencial            | Gerenciar a implementação de padrões de design e realizar avaliações de usabilidade para assegurar a conformidade.                    |
| Desenvolvimento      | Implementação dos padrões de design na interface do usuário e realização de testes de usabilidade.                                     |
| Nível de Priorização | Médio                                                                                                                                 |

**Autor:** [Bruno Araújo](https://github.com/brunocva)

### Tabela 86: Elo do Requisito

**Tabela 86: Elo do Requisito**

| Tipo de Elo | Categoria       | Elementos Rastreáveis                                      | Descrição do ELO | Requisitos Relacionados |
| ----------- | --------------- | --------------------------------------------------------- | ---------------- | ----------------------- |
| Recurso     | Desenvolvimento | <li> Padrões de Design <br><li> Avaliações de Usabilidade | O aplicativo deve seguir padrões de design aceitos por empresas e instituições, com uma taxa de conformidade de 95% nas avaliações de usabilidade. | RNF14, RNF15 |

**Autor:** [Bruno Araújo](https://github.com/brunocva)

</center>

</details>

<details>
  <summary><b> RNF15 - 	Bruno Araújo </b></summary> 

**Tabela 87: Estrutura do Requisito**

| Características      | Explicação                                                                                                                             |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| Nome do Requisito    | Backup Diário                                                                                                                          |
| Origem do Requisito  | Análise de documentos e entrevista                                                                                                     |
| Descrição            | O sistema deve realizar backup diário automático de todos os dados para garantir a recuperação em caso de falhas.                       |
| Ambiental            | Necessidade de garantir a segurança e a disponibilidade dos dados em caso de falhas ou desastres.                                       |
| Organizacional       | Alinhado com as políticas de continuidade de negócios e recuperação de desastres da organização.                                        |
| Gerencial            | Gerenciar a realização e a verificação regular dos backups para assegurar a integridade dos dados.                                      |
| Desenvolvimento      | Implementação de rotinas automáticas de backup e mecanismos de verificação da integridade dos dados.                                    |
| Nível de Priorização | Alto                                                                                                                                   |

**Autor:** [Bruno Araújo](https://github.com/brunocva)

### Tabela 88: Elo do Requisito

**Tabela 88: Elo do Requisito**

| Tipo de Elo | Categoria       | Elementos Rastreáveis                            | Descrição do ELO | Requisitos Relacionados |
| ----------- | --------------- | ------------------------------------------------ | ---------------- | ----------------------- |
| Recurso     | Desenvolvimento | <li> Logs de Backup <br><li> Documentação de Backup | Garante a realização e integridade dos backups diários através de logs e documentação detalhada. | RNF15, RNF12 |

**Autor:** [Bruno Araújo](https://github.com/brunocva)

</center>

</details>

<details>
  <summary><b> RNF16 - Caio Mesquita </b></summary> 

<b>Tabela 89:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | O sistema deve permitir ao usuário atualizar seus dados em no máximo 15 minutos, sem a necessidade de intermediários, com uma taxa de sucesso de 95%. |
| Origem do Requisito  | [Storytelling](Elicitacao/TecnicasElicitacao/Execucao/Storytelling/Storytelling.md) |
| Descrição            | O requisito afirma que o usuário deve poder atualizar seus dados pessoais com no máximo 15 minutos de ações, sem a necessidade de algum fator terceiro para intermediar a ação e com uma taxa de sucesso acima de 95% das tentativas. |
| Ambiental            | No contexto ambiental, o requisito está ligado a qualidade do serviço oferecido ao usuário por parte do aplicativo |
| Organizacional       | No aspecto organizacional, o requisito está ligado diretamente com fornecer um uso flúido e eficaz do aplicativo por parte dos usuários |
| Gerencial            | O requisito está ligado com a otimização de processos a fim de melhorar a performance da aplicação |
| Desenvolvimento      | A implementação do requisito está ligado a criação de uma interface para envio e acompanhamento dos status dos documentos para atualização cadastral |
| Nível de Priorização | - |

<b> Autor: Caio Mesquita </b> <a href="https://github.com/Caiomesvie"> </a>.

### Elos de Rastreabilidade

A tabela 90 mostra os elos do requisito RNF16.

<center> 

<b>Tabela 90:</b> Elo do Requisito

| Tipo de Elo | Categoria        | Elementos Rastreáveis                                                                                                   | Descrição do ELO                                                                                                    | Requisitos Relacionados |
|-------------|------------------|--------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|-------------------------|
| Recurso     | Desenvolvimento  | <li> Módulo de atualização de dados do usuário. <br> <li> Sistema de autenticação e autorização. <br> <li> Banco de dados com suporte a atualizações em tempo real. <br> <li> Ferramentas de monitoramento e análise de desempenho. | O módulo de atualização de dados do usuário, o sistema de autenticação e autorização, o banco de dados com suporte a atualizações em tempo real e as ferramentas de monitoramento e análise de desempenho **fornecem os recursos necessários** para garantir que o usuário possa atualizar seus dados em no máximo 15 minutos, sem intermediários, e com uma taxa de sucesso de 95%. | <li> RF04: Usuário pode atualizar suas informações pessoais <br> <li> RF22: Usuário empresa pode atualizar dados dos funcionários <br>  |




<b> Autor: Caio Mesquita </b> <a href="https://github.com/Caiomesvie"> </a>.

</center>

</details>

<details>
  <summary><b> RNF17 - Caio Mesquita </b></summary> 

<b>Tabela 91:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | 	O sistema deve apresentar dados pessoais com orientações claras e links para correção, com uma taxa de conformidade de 100% nas verificações. |
| Origem do Requisito  | Storytelling |
| Descrição            | O requisito descreve que os dados pessoais dos usuários devem ser retornados visiveis a eles e com passo a passo para que eles sejam alterados, caso haja a necessidade por parte do usuário. |
| Ambiental            | Este requisito está contexualizado na necessidade de fornecer um uso de qualidade do aplicativo por parte do usuário. |
| Organizacional       | Neste contexto, o requisito está ligado com a missão de ofercer um aplicativo de uso amplo e fácil acesso a fim de atingir o maior número de usuários com maior acessibilidade.  |
| Gerencial            | Do ponto de vista gerencial,  a implementação deste requisito está ligado com a realização de um estudo de UI e UX design visando a busca pela maior intuitividade possível. |
| Desenvolvimento      | No âmbito do desenvolvimento, a implementação deste requisot exige a validação por parte dos usuários e póssiveis alterações no design e organização da interface.|
| Nível de Priorização | - |

<b> Autor: Caio Mesquita </b> <a href="https://github.com/Caiomesvie"> </a>.

### Elos de Rastreabilidade

A tabela 92 mostra os elos do requisito RNF17.

<center> 

<b>Tabela 92:</b> Elo do Requisito

| Tipo de Elo | Categoria| Elementos Rastreáveis | Descrição do ELO  | Requisitos Relacionados |
|-------------|------------------|--------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|-------------------------|
| Satisfação  | Desenvolvimento  | <li> Interface de usuário para visualização de dados pessoais. <br> <li> Sistema de orientação e ajuda. <br> <li> Links para páginas de correção de dados. <br> <li> Módulo de verificação de conformidade. | A interface de usuário para visualização de dados pessoais, o sistema de orientação e ajuda, os links para páginas de correção de dados e o módulo de verificação de conformidade **satisfazem as necessidades** para garantir que o sistema apresente dados pessoais com orientações claras e links para correção, com uma taxa de conformidade de 100% nas verificações. | <li> RF03: Usuário pode consultar suas informações pessoais <br> <li> RF04: Usuário pode atualizar suas informações pessoais <br> <li> RF22: Usuário empresa pode atualizar dados dos funcionários <br> <li> RNF09: O sistema deve garantir a conformidade com a LGPD (Lei Geral de Proteção de Dados). |




<b> Autor: Caio Mesquita </b> <a href="https://github.com/Caiomesvie"> </a>.

</center>

</details>

<details>
  <summary><b> RNF18 - Caio Mesquita </b></summary> 

<b>Tabela 93:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | O sistema deve listar contratos de trabalho com todos os detalhes relevantes, atualizados em tempo real.	 |
| Origem do Requisito  | Análise de documentos e storytelling |
| Descrição            | A aplicação deve ter uma aba com uma lista contendo todos os contratos de trabalho que pertencem ao usuário, com a opção de detalhar os dados do contrato. |
| Ambiental            | Este requisito está ligado ao contexto do usuário acessar os seus dados trabalhistas, uma das principais funções do aplicativo CTD.|
| Organizacional       | Entre os objetivos e as estratégias do aplicativo CTD, este requisito alinha-se com a missão de garantir o acesso do usuário aos seus dados pessoais e registros de documentos. |
| Gerencial            | No contexto gerencial,  é importante assegurar a integração com o orgão que fornece os dados dos vínculos empregatícios do usuário|
| Desenvolvimento      | No âmbito do desenvolvimento, é necessário a implantação de uma interface onde há a lista de contratos de trabalho e a garantia da integração com os dados do Ministério do Trabalho |
| Nível de Priorização | - |

<b> Autor: Caio Mesquita </b> <a href="https://github.com/Caiomesvie"> </a>.

### Elos de Rastreabilidade

A tabela 94 mostra os elos do requisito RNF18.

<center> 

<b>Tabela 94:</b> Elo do Requisito

 | Tipo de Elo | Categoria        | Elementos Rastreáveis                                                                                                   | Descrição do ELO                                                                                                    | Requisitos Relacionados |
|-------------|------------------|--------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|-------------------------|
| Recurso     | Desenvolvimento  | <li> Módulo de listagem de contratos de trabalho. <br> <li> Sistema de atualização em tempo real. <br> <li> Banco de dados com suporte a atualizações em tempo real. <br> <li> Ferramentas de monitoramento e análise de desempenho. | O módulo de listagem de contratos de trabalho, o sistema de atualização em tempo real, o banco de dados com suporte a atualizações em tempo real e as ferramentas de monitoramento e análise de desempenho **fornecem os recursos necessários** para garantir que o sistema liste contratos de trabalho com todos os detalhes relevantes, atualizados em tempo real. | <li> RF05: Usuário trabalhador pode consultar contratos de trabalho. <br> <li> RF23: Usuário empresa pode consultar contratos de trabalho. <br> <li> RF25: Usuário empresa pode gerenciar contratos de trabalho (adicionar novos, atualizar já existentes e encerrar contratos). <br> <li> RNF18: O sistema deve listar contratos de trabalho com todos os detalhes relevantes, atualizados em tempo real. |



<b> Autor: Caio Mesquita </b> <a href="https://github.com/Caiomesvie"> </a>.

</center>

</details>


<details>
  <summary><b> RNF20 - Caio Mesquita </b></summary> 

<b>Tabela 95:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | O sistema deve ser totalmente integrado com o eSocial, com uma taxa de sincronização de dados de 99%.	 |
| Origem do Requisito  | Análise de documentos |
| Descrição            | O aplicativo da CTD deve ser integrado com o eSocial, sistema onde há a comunicação com o governo a respeito de  situação de vínculos empregatícios, contribuições previdenciárias, folhas de pagamento, acidente de trabalho, avisos prévios, escriturações fiscais, além de informações sobre o FGTS. |
| Ambiental            | Este Requisto está ligado com o uso dos dados do eSocial a fim de expôr de forma mais fácil para o usuário estes dados. |
| Organizacional       | Este requisito está ligado com a missão de expôr para o usuário seus dados pessoais acerca da sua vida trabalhista. |
| Gerencial            | Do ponto de vista da Gerência, este requisito está ligado com a integração plena com o eSocial e como os dados serão entregues ao usuário. |
| Desenvolvimento      | Do ponto de vista de desenvolvimento, o requisito exige que haja a integração funcional com o banco de dados do eSocial e formas de como expôr esses dados para o usuário e de formas diferentes, divididos em tópicos específicos para os diferentes tipos de dados. |
| Nível de Priorização | - |

<b> Autor: Caio Mesquita </b> <a href="https://github.com/Caiomesvie"> </a>.

### Elos de Rastreabilidade

A tabela 96 mostra os elos do requisito RNF20.

<center> 

<b>Tabela 96:</b> Elo do Requisito

| Tipo de Elo | Categoria        | Elementos Rastreáveis                                                                                                   | Descrição do ELO                                                                                                    | Requisitos Relacionados |
|-------------|------------------|--------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|-------------------------|
| Recurso     | Desenvolvimento  | <li> Módulo de integração com eSocial. <br> <li> Sistema de sincronização de dados. <br> <li> Banco de dados com suporte a integração em tempo real. <br> <li> Interface de usuário para exibição dos dados do eSocial. | O módulo de integração com o eSocial, o sistema de sincronização de dados, o banco de dados com suporte a integração em tempo real e a interface de usuário para exibição dos dados do eSocial **fornecem os recursos necessários** para garantir que o sistema seja totalmente integrado com o eSocial, com uma taxa de sincronização de dados de 99%. | <li> RF11: Usuário trabalhador pode consultar informações sobre o FGTS e o INSS. <br> <li> RF23: Usuário empresa pode consultar contratos de trabalho. <br> <li> RF27: Usuário empresa pode gerenciar benefícios trabalhistas. |




<b> Autor: Caio Mesquita </b> <a href="https://github.com/Caiomesvie"> </a>.

</center>

</details>

<details>
  <summary><b> RNF21 - Caio Mesquita </b></summary> 

<b>Tabela 97:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | O sistema deve ser totalmente integrado com o portal gov.br, com uma taxa de sincronização de dados de 99%.	 |
| Origem do Requisito  | Análise de documentos	 |
| Descrição            | O sistema deve ser integrado com o portal do Governo Federal, gov.br |
| Ambiental            | O requisito está ligado a utilização dos dados fornecidos pelo portal na aplicação do CTD |
| Organizacional       | Este requisito está alinhado com a missão de simplificar as ações do usuário puxando dados direto do portal gov.br |
| Gerencial            | Do ponto de vista gerencial,  é importante que os usuários saibam como estão sendo feito os processos de integração em uma linguagem que eles entendam que seus dados não serão violados|
| Desenvolvimento      | No âmbito de desenvolvimento, este requisito requer a integração funcional com uma API que recupere os dados do portal gov.br e a integração com o login pelo mesmo |
| Nível de Priorização | - |

<b> Autor: Caio Mesquita </b> <a href="https://github.com/Caiomesvie"> </a>.

### Elos de Rastreabilidade

A tabela 98 mostra os elos do requisito RNF21.

<center> 

<b>Tabela 98:</b> Elo do Requisito

| Tipo de Elo | Categoria        | Elementos Rastreáveis                                                                                                   | Descrição do ELO                                                                                                    | Requisitos Relacionados |
|-------------|------------------|--------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|-------------------------|
| Recurso     | Desenvolvimento  | <li> Módulo de integração com portal gov.br. <br> <li> Sistema de sincronização de dados. <br> <li> Banco de dados com suporte a integração em tempo real. <br> <li> Interface de usuário para exibição e atualização dos dados do portal gov.br. | O módulo de integração com o portal gov.br, o sistema de sincronização de dados, o banco de dados com suporte a integração em tempo real e a interface de usuário para exibição e atualização dos dados do portal gov.br **fornecem os recursos necessários** para garantir que o sistema seja totalmente integrado com o portal gov.br, com uma taxa de sincronização de dados de 99%. | <li> RF02: Usuário pode fazer login para entrar na sua página pessoal. <br> <li> RF04: Usuário pode atualizar suas informações pessoais. <br> <li> RNF09: O sistema deve garantir a conformidade com a LGPD (Lei Geral de Proteção de Dados). <br> <li> RNF16: O sistema deve permitir ao usuário atualizar seus dados em no máximo 15 minutos, sem a necessidade de intermediários, com uma taxa de sucesso de 95%. <br> <li> RNF25: O sistema deve atualizar os dados do usuário automaticamente a cada 24 horas para evitar defasagem, com uma taxa de sucesso de 99%. |


<b> Autor: Caio Mesquita </b> <a href="https://github.com/Caiomesvie"> </a>.

</center>

</details>

<details>
  <summary><b> RNF22 - Caio Mesquita </b></summary> 

<b>Tabela 99:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    |O sistema deve permitir integração com pelo menos cinco outros sistemas de software, conforme especificado na documentação de requisitos.	 |
| Origem do Requisito  | Análise de documentos	 |
| Descrição            | O aplicativo do CTD deverá ter integração com outros softwares visando uma melhor experiência de usuário em termos gerais |
| Ambiental            | No contexto ambiental, este requisito está ligado a integrar mais funcionalidades a aplicação utilizando softwares externos |
| Organizacional       | No quesíto organizacional, este requisito alinha-se com a missão de melhorar a experiência de usuário |
| Gerencial            | Do ponto de vista gerencial, o requisito exige um estudo para análise de quais softwares não oferecem risco para o uso e integração com a aplicação|
| Desenvolvimento      | No aspecto do Desenvolvimento, este requisto trás a necessidade de integração de aplicações como por exemplo o software de biometria do celular do usuário, ou até o uso do microsoft Authenticator para mais segurança da aplicação |
| Nível de Priorização | - |

<b> Autor: Caio Mesquita </b> <a href="https://github.com/Caiomesvie"> </a>.

### Elos de Rastreabilidade

A tabela 100 mostra os elos do requisito RNF22.

<center> 

<b>Tabela 100:</b> Elo do Requisito

| Tipo de Elo | Categoria       | Elementos Rastreáveis                                                                                                      | Descrição do ELO                                                                                                           | Requisitos Relacionados |
|-------------|-----------------|-----------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|-------------------------|
| Alocado     | Desenvolvimento | <li> Módulo de integração com Sistema A. <br> <li> Módulo de integração com Sistema B. <br> <li> Módulo de integração com Sistema C. <br> <li> Módulo de integração com Sistema D. <br> <li> Módulo de integração com Sistema E. | Os módulos de integração com os cinco sistemas especificados fornecem os recursos necessários para permitir a integração do sistema com pelo menos cinco outros sistemas de software. |   <li> RNF20: O sistema deve ser totalmente integrado com o eSocial, com uma taxa de sincronização de dados de 99%.	 <br> <li>RNF21: O sistema deve ser totalmente integrado com o portal gov.br, com uma taxa de sincronização de dados de 99%.	 <br> <li> RNF09: O sistema deve garantir a conformidade com a LGPD (Lei Geral de Proteção de Dados).     |



<b> Autor: Caio Mesquita </b> <a href="https://github.com/Caiomesvie"> </a>.

</center>

</details>

<details>
  <summary><b> RNF23 - Caio Mesquita </b></summary> 

<b>Tabela 101:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | O sistema deve enviar notificações precisas com uma taxa de falsos positivos inferior a 5%.	 |
| Origem do Requisito  | Storytelling |
| Descrição            | O aplicativo deve apresentar as notificações relativas ao aplicativo para o usuário, com uma quantidade inferior a 5% de falhas em apresentar notificações que sejam incoerentes |
| Ambiental            | Este requisito está ligado à necessidade do usuário de estar sempre atualizado sobre qualquer alteração e mudanças na aplicação|
| Organizacional       | Na questão organizacional, este requisito se alinha com a missão de manter o usuário sempre atualizado e melhorar a utilização da aplicação |
| Gerencial            | No aspecto gerencial, este requisito indica a necessidade de realização de testes com relação a acurácia dos acertos das notificações |
| Desenvolvimento      | Na questão do desenvolvimento, há necessidade de otimização das notificações para que elas sejam acessíveis para todos os tipos de usuários com diferentes aparelhos celulares |
| Nível de Priorização | - |

<b> Autor: Caio Mesquita </b> <a href="https://github.com/Caiomesvie"> </a>.

### Elos de Rastreabilidade

A tabela 102 mostra os elos do requisito RNF23.

<center> 

<b>Tabela 102:</b> Elo do Requisito

| Tipo de Elo | Categoria       | Elementos Rastreáveis                                                                 | Descrição do ELO                                                                                                       | Requisitos Relacionados |
|-------------|-----------------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|-------------------------|
| Satisfação  | Desenvolvimento | <li> Algoritmo de geração de notificações. <br> <li> Conjunto de regras de validação. | O algoritmo de geração de notificações e o conjunto de regras de validação **satisfazem** a necessidade de enviar notificações precisas com taxa de falsos positivos inferior a 5%. |<li> **RF19** Usuário recebem notificações do aplicativo	</li>   |




<b> Autor: Caio Mesquita </b> <a href="https://github.com/Caiomesvie"> </a>.

</center>

</details>

<details>
  <summary><b> RNF24 - Caio Mesquita </b></summary> 

<b>Tabela 103:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | O aplicativo deve ser compatível com iOS, Android e Windows, sem apresentar falhas críticas em nenhum dos sistemas operacionais suportados.	 |
| Origem do Requisito  | Storytelling |
| Descrição            | O aplicativo do CTD deve funcionar em diferentes sistemas operacionais e aparelhos telefônicos, principalmente Android, IOS e Windows e deve funcionar sem erros críticos q comprometam o uso da aplicação |
| Ambiental            | Este requisito está ligado aos diversos aparelhos passíveis de serem usasdos pelos usuários para acessar a aplicação |
| Organizacional       | Este requisito está ligado com a missão de forcener o aplicativo de forma mais ampla, atingindo o maior público possível e abrangendo o máximo de usuários que puder |
| Gerencial            | Do ponto de vista gerencial, deverá ser monitorado possíveis erros que podem ser gerados pela implementação em diferentes sistemas operacionais  |
| Desenvolvimento      | Do aspecto de desenvolvimento, deverá ocorrer a implementação das interfaces com a mínima diferença póssivel entre os difentes aparelhos que suportarão o aplicativo |
| Nível de Priorização | - |

<b> Autor: Caio Mesquita </b> <a href="https://github.com/Caiomesvie"> </a>.

### Elos de Rastreabilidade

A tabela 104 mostra os elos do requisito RNF24.

<center> 

<b>Tabela 104:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| Alocado     | Desenvolvimento | <li> Testes de compatibilidade com iOS. <br> <li> Testes de compatibilidade com Android. <br> <li> Testes de compatibilidade com Windows. | Os testes de compatibilidade com iOS, Android e Windows **alocam** recursos para garantir que o aplicativo seja compatível sem falhas críticas em nenhum dos sistemas operacionais suportados. | <li> RNF14: O aplicativo deve seguir padrões de design aceitos por empresas e instituições, com uma taxa de conformidade de 95% nas avaliações de usabilidade. <br>  |

<b> Autor: Caio Mesquita </b> <a href="https://github.com/Caiomesvie"> </a>.

</center>

</details>

<details>
  <summary><b> RNF25 - Iago Passaglia </b></summary> 

<b>Tabela 105:</b> Estrutura do requisito

| Características      | Explicação |
| -------------------- | ---------- |
| Nome do Requisito    | O sistema deve atualizar os dados do usuário automaticamente a cada 24 horas para evitar defasagem, com uma taxa de sucesso de 99%. |
| Origem do Requisito  | [Entrevistas](https://requisitos-de-software.github.io/2024.1-CarteiradeTrabalhoDigital/#/Elicitacao/TecnicasElicitacao/Execucao/Storytelling/Storytelling). |
| Descrição            | Este requisito estabelece que o sistema deve atualizar automaticamente os dados do usuário a cada 24 horas para evitar defasagem, garantindo uma taxa de sucesso de 99% |
| Ambiental            | O contexto do requisito está relacionado à necessidade de manter os dados dos usuários atualizados regularmente e de forma automatizada. |
| Organizacional       | Entre os objetivos e as estratégias do aplicativo CTD, este requisito alinha-se com a missão de garantir a integridade e a atualização contínua das informações dos usuários. |
| Gerencial            | Do ponto de vista gerencial, este requisito indica que será necessário desenvolver mecanismos automáticos de atualização de dados e monitoramento de sua eficácia para assegurar uma taxa de sucesso de 99%. |
| Desenvolvimento      | Durante o desenvolvimento, esse requisito implica na criação de processos automatizados de atualização de dados, integração com sistemas de backend, e mecanismos de verificação e validação para garantir a taxa de sucesso especificada. |
| Nível de Priorização | - |

<b> Autor: </b> <a href="https://github.com/Paxxaglia">Iago Passaglia</a>.

### Elos de Rastreabilidade

A tabela 106 mostra os elos do requisito RNF25.

<center> 

<b>Tabela 106:</b> Elo do Requisito

| Tipo de Elo | Categoria | Elementos Rastreáveis | Descrição do ELO| Requisitos Relacionados | 
| -------------- | ----------------- | ----------------------------------------------------- | -------------|-------------|
| Recurso | Desenvolvimento | <li> Módulo de Informações Trabalhistas <br> <li> Módulo de Informações Pessoais. <br> <li> Componente de Manipulação de Dados da Carteira. | Este elo indica que o requisito depende da integração com sistemas de backend e de mecanismos de monitoramento para assegurar a taxa de sucesso de 99%. | RF02: Usuário poder fazer login para entrar na sua página pessoal |


<b> Autor: </b> <a href="https://github.com/Paxxaglia">Iago Passaglia</a>.


</center>

</details>




## Referências Bibliográficas

1. CRUZ, Jorge Luiz da; JINO, Mario. Suporte automatizado à rastreabilidade em um processo de teste de software baseado em documentação. CenPRA / Faculdades Hoyler; UNICAMP. Disponível em <https://sol.sbc.org.br/index.php/sbqs/article/view/15615/15458>. Acesso em 16 junho 2024.

2.  Miriam Sayão, Julio Cesar Sampaio do Prado Leite. Monografias em Ciência da Computação n° 20/05 - Rastreabilidade de Requisitos. PUC. Departamento de Informática, PUC-Rio. 2005. Disponível em: <https://www-di.inf.puc-rio.br/~julio/rastre.pdf>. Acesso em 16 junho 2024.


## Histórico de Versão

| Versão | Alteração                              | Responsável     | Revisor         | Data       |
| ------ | -------------------------------------- | --------------- | --------------- | ---------- |
| 1.0    |  Criação do modelo e estrutura         | Larissa Stéfane | Bruno Araújo    | 15/06/2024 |
| 1.0.1    |  Adição da introdução e da metodologia | Larissa Stéfane | Bruno Araújo    | 16/06/2024 |
| 1.0.2    |  Adição da rastreabilidade da RF07     | Larissa Stéfane | Bruno Araújo    | 16/06/2024 |
| 1.0.3    |  Correção dos templates                | Breno Alexandre | Larissa Stéfane | 20/06/2024 |
| 1.0.4    |  Reorganização do artefato             | Larissa Stéfane | Pedro Izarias   | 20/06/2024 |
| 1.0.5    |  Adição dos requisitos RF07 até RF14   | Larissa Stéfane | Pedro Izarias   | 22/06/2024 |
| 1.0.6    |  Adição dos requisitos RF22 até RF28   | Pedro Izarias   | Iago Passaglia  | 23/06/2024 |
| 1.0.7    |  Adição dos requisitos RF01 até RF06 e RNF25  | Iago Passaglia | Bruno Araújo | 23/06/2024 |
| 1.0.8    |  Adição dos requisitos RNF 09 ao 15    | Bruno Araújo    | -               | 23/06/2024 |
| 1.0.9    |  Adição dos requisitos RF 15 ao 21     | Luana Medeiros  | -               | 23/06/2024 |
| 1.1    |  Adição dos requisitos RNF 16 ao 24     | Caio Mesquita  | -               | 24/06/2024 |
