# História de Usuários

## Sumário
* [Introdução](#Introdução)
* [Definição das Histórias dos Usuários](#Definição-das-Histórias-dos-Usuários)
* [Motivações e Objetivos](#Motivações-e-Objetivos)
* [Metodologia](#Metodologia)
* [Template](#Template)
* [Histórias de Usuários](#Histórias-de-Usuários)
* [Participantes](#Participantes)
* [Validação com Usuário](#Validação-com-Usuário)
* [Observações do Usuário](#Observações-do-Usuário)
* [Conclusão](#Conclusão)
* [Referências Bibliográficas](#Referências-Bibliográficas)
* [Bibliografia](#Bibliografia)
* [Histórico de Versão](#Histórico-de-Versão)

## Introdução

No desenvolvimento de um sistema, compreender as necessidades dos usuários e dos clientes é essencial para o sucesso de um projeto e uma bordagem amplamente adotada para capturar e comunicar essas necessidades são as histórias de usuário. Assim, este artefato apresenta as histórias de usuário trabalhadas pela equipe durante o desenvolvimento desse projeto sobre o aplicativo da Carteira de Trabalho Digital. Isso porque, como foi explicado, as histórias de usuário são essenciais para garantir que a execução do projeto esteja alinhada com as necessidades reais dos usuários. Desse modo, este documento visa detalhar as motivações, os objetivos e a metodologia adotada para a criação dessas histórias, além de apresentar as histórias de usuário padronizadas e validadas por um usuário.

## Definição das Histórias dos Usuários

Segundo o artigo "[Combinando Design Participativo e História de Usuários para Levantamento de Funcionalidades no OpenDesign](https://www.ic.unicamp.br/~reltech/2018/18-12.pdf)"¹, as histórias de usuário são descrições concisas das funcionalidades de um sistema vistas do ponto de vista do usuário final. Assim, elas são utilizadas para expressar as necessidades e os requisitos de software de forma compreensível e centrada no usuário. Segundo Cohn (2004), citado no mesmo artigo "[Combinando Design Participativo e História de Usuários para Levantamento de Funcionalidades no OpenDesign](https://www.ic.unicamp.br/~reltech/2018/18-12.pdf)"¹, uma história de usuário é composta por três aspectos principais:

- **Cartão(card)**: Uma descrição escrita da história, geralmente utilizada para planejamento ou como lembrete.

- **Conversa (Converation)**: Diálogos informais que detalham a história, permitindo esclarecer pontos e responder a dúvidas.

- **Confirmação(confirmation)**: Testes escritos que documentam os detalhes da história e permitem verificar se ela foi implementada corretamente.

Portanto, para facilitar a elaboração de cartões de histórias de usuário, Cohn (2004) propôs um modelo que destaca os diferentes papéis ou tipos de usuários envolvidos e o valor que cada papel agrega à funcionalidade desejada, mais precisamente, ao objetivo a ser alcançado. Dessa forma, o formato sugerido é: "Eu, como um (tipo de usuário), gostaria de (funcionalidade/objetivo), para que (benefício de negócio)". Esse modelo pode ser adotado para descrever as histórias nos cartões.

## Motivações e Objetivos

No contexto do projeto da Carteira de Trabalho Digital, a utilização de histórias de usuário é motivada pela necessidade de desenvolver uma solução centrada nas necessidades reais dos usuários envolvidos, uma vez que a Carteira de Trabalho Digital visa modernizar e simplificar o processo de emissão e gerenciamento da carteira de trabalho com o intuito de facilitar a vida dos cidadãos neste contexto.

Desse modo, a motivação para adotar as histórias de usuário reside na capacidade dessa abordagem em capturar de concisamente as expectativas, os desejos e as necessidades dos usuários finais da carteira de trabalho digital ao expressar as funcionalidades do ponto de vista do usuário, o que a equipe compreenda melhor o contexto e os requisitos do projeto e garanta a solução entregue realmente agregue valor aos usuários.

Assim, os objetivos que buscam ser alcançados são:

- Garantir que a solução desenvolvida atenda às necessidades e expectativas dos usuários finais.

- Priorizar as funcionalidades com base no valor que agregam aos usuários e ao negócio, garantindo que os esforços de desenvolvimento sejam direcionados para as áreas de maior impacto.

## Metodologia

A metodologia da criação das histórias dos usuários será baseada no artigo “O que são as histórias de usuário e como escrevê-las bem?”². Assim, inicialmente, cada integrante do grupo irá revisar individualmente o conteúdo dos artigos para compreender os princípios e diretrizes para escrever histórias de usuário eficazes. Após essa etapa, cada membro irá elaborar suas próprias histórias de usuário com base nas funcionalidades que trabalhou nos [casos de uso](modelagem/casoDeUso.md), seguindo o formato padronizado sugerido no template. Em seguida, as histórias serão validadas por um usuário.

## Template

Há um conjunto de questões que precisam ser respondidas e pontuadas nas histórias de usuário, desse modo, a tabela 1 mostra o template que deve ser seguido.

O código da história de usuário é HU + Número.

<center>

** Tabela 1:** Template dos casos de uso.

| Código História de Usuário | - |
|------------------|--------|
| Título           | - |
| Código do requisito funcional | - |
| Rastreabilidade  | -  |
| Quem?           | - |
| O que é?           | - |
| Por que ?         |  - |
| Critérios de Aceitação | - |
| Prioridade       | -    |

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

### Casos de Uso

</center>

</details>

<details>
  <summary size="20"><b> Solicitação de benefícios.   </b></summary> 
 
</center>

## Casos de Uso para Sistema de Solicitação de Benefícios

A tabela 2 detalha os casos de uso do sistema de solicitação de benefícios, incluindo o código e título de cada história de usuário, requisitos funcionais, rastreabilidade, atores envolvidos, objetivos, razões, critérios de aceitação e prioridade. 

**Tabela 2: Solicitação de Benefícios**

| Código História de Usuário | US01 |
|------------------|--------|
| **Título**           | Preencher formulário de solicitação de benefício |
| **Código do requisito funcional** | F01 |
| **Rastreabilidade**  | RF01  |
| **Quem?**           | Usuário |
| **O que é?**           | Preencher um formulário de solicitação de benefício de forma simples e guiada |
| **Por que ?**         | Para garantir que todas as informações necessárias sejam fornecidas corretamente |
| **Critérios de Aceitação** | <ul><li>O formulário deve ser fácil de entender e preencher.</li><li>Deve haver orientações claras para cada campo.</li><li>Usuário deve ser capaz de submeter o formulário com sucesso.</li></ul> |
| **Prioridade**       | Must    |

| Código História de Usuário | US02 |
|------------------|--------|
| **Título**           | Anexar documentos no aplicativo |
| **Código do requisito funcional** | F02 |
| **Rastreabilidade**  | RF02  |
| **Quem?**           | Usuário |
| **O que é?**           | Anexar documentos diretamente no aplicativo |
| **Por que ?**         | Para facilitar o processo de solicitação de benefício |
| **Critérios de Aceitação** | <ul><li>Usuário deve poder anexar documentos em diferentes formatos.</li><li>O processo de anexar documentos deve ser simples e rápido.</li><li>Documentos anexados devem ser salvos e enviados com a solicitação.</li></ul> |
| **Prioridade**       | Must    |

| Código História de Usuário | US03 |
|------------------|--------|
| **Título**           | Receber notificações sobre o status da solicitação de benefício |
| **Código do requisito funcional** | F03 |
| **Rastreabilidade**  | RF03  |
| **Quem?**           | Usuário |
| **O que é?**           | Receber notificações sobre o status da solicitação de benefício |
| **Por que ?**         | Para estar sempre informado sobre o andamento |
| **Critérios de Aceitação** | <ul><li>Usuário deve ser notificado em cada etapa do processo de solicitação.</li><li>Notificações devem ser claras e informativas.</li><li>Usuário deve poder visualizar o histórico de notificações.</li></ul> |
| **Prioridade**       | Should    |

| Código História de Usuário | US04 |
|------------------|--------|
| **Título**           | Visualizar o status detalhado da solicitação de benefício |
| **Código do requisito funcional** | F04 |
| **Rastreabilidade**  | RF04  |
| **Quem?**           | Usuário |
| **O que é?**           | Visualizar o status detalhado da solicitação de benefício, incluindo previsão de pagamento |
| **Por que ?**         | Para acompanhar de perto o processo |
| **Critérios de Aceitação** | <ul><li>Usuário deve ver um resumo detalhado do status de cada solicitação.</li><li>Previsão de pagamento deve ser atualizada regularmente.</li><li>Detalhes devem ser facilmente acessíveis.</li></ul> |
| **Prioridade**       | Must    |

| Código História de Usuário | US05 |
|------------------|--------|
| **Título**           | Visualizar o histórico detalhado de todos os benefícios solicitados e recebidos |
| **Código do requisito funcional** | F05 |
| **Rastreabilidade**  | RF05  |
| **Quem?**           | Usuário |
| **O que é?**           | Visualizar o histórico detalhado de todos os benefícios solicitados e recebidos |
| **Por que ?**         | Para ter um controle completo e organizado das minhas solicitações |
| **Critérios de Aceitação** | <ul><li>Usuário deve acessar facilmente o histórico de solicitações.</li><li>Histórico deve incluir todas as solicitações e benefícios recebidos.</li><li>Informações devem ser apresentadas de forma clara e organizada.</li></ul> |
| **Prioridade**       | Should    |

| Código História de Usuário | US06 |
|------------------|--------|
| **Título**           | Personalizar notificações sobre benefícios |
| **Código do requisito funcional** | F06 |
| **Rastreabilidade**  | RF06  |
| **Quem?**           | Usuário |
| **O que é?**           | Personalizar as notificações que recebe sobre benefícios |
| **Por que ?**         | Para receber apenas informações relevantes |
| **Critérios de Aceitação** | <ul><li>Usuário deve poder escolher que notificações deseja receber.</li><li>Configurações de notificações devem ser fáceis de ajustar.</li><li>Notificações personalizadas devem ser enviadas de acordo com as preferências do usuário.</li></ul> |
| **Prioridade**       | Could    |

| Código História de Usuário | US07 |
|------------------|--------|
| **Título**           | Interagir com um assistente virtual para obter respostas rápidas e suporte |
| **Código do requisito funcional** | F07 |
| **Rastreabilidade**  | RF07  |
| **Quem?**           | Usuário |
| **O que é?**           | Interagir com um assistente virtual para obter respostas rápidas e suporte |
| **Por que ?**         | Para melhorar minha experiência no uso do aplicativo |
| **Critérios de Aceitação** | <ul><li>Assistente virtual deve responder a perguntas comuns de forma precisa e rápida.</li><li>Usuário deve poder acessar o assistente virtual facilmente.</li><li>Respostas do assistente virtual devem ser úteis e relevantes.</li></ul> |
| **Prioridade**       | Should    |

Autor:[Bruno Araújo](https://github.com/brunocva)

</center>

</details>

## Referências Bibliográficas

1. Reis, J. C. dos, Maike, V. R. M. L., Duarte, E. F., Gonçalves, F. M., França, B. B. N. de, Bonacin, R., Pereira, R., & Baranauskas, M. C. C. (2018). **Combinando Design Participativo e História de Usuários para Levantamento de Funcionalidades no OpenDesign**. Instituto de Computação, Universidade Estadual de Campinas (UNICAMP), Disponível em <https://www.ic.unicamp.br/~reltech/2018/18-12.pdf>. Acessado em 26 de maio de 2024.

2. Gustavo Guasti, Italo. Carneiro, Tiago. **O que são as histórias de usuário e como escrevê-las bem?**. TerraLab. Disponível em <https://www2.decom.ufop.br/terralab/o-que-sao-as-historias-de-usuario-e-como-escreve-las-bem/>  Acessado em 26 de maio de 2024.


## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 |  Adição da introdução, da definição e dos objetivos, da metodologia e do template   |  Larissa Stéfane   |   Iago Passaglia  | 26/05/2024  |
