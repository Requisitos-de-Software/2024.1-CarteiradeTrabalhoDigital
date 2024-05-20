# Especificação Suplementar

## Sumário
* [Introdução](#Introdução)
* [Metodologia](#Metodologia)
* [Funcionalidade](#Funcionalidade)
* [Usabilidade](#Usabilidade)
* [Suportabilidade](#Suportabilidade)
* [Restrições de Design](#Restrições-de-Design)
* [Conclusão](#Conclusão)
* [Referências Bibliográficas](#Referências-Bibliográficas)
* [Histórico de versão](#Histórico-de-versão)

  
## Introdução
A Especificação Suplementar é um documento essencial em projetos de desenvolvimento de sistemas que captura e detalha requisitos não cobertos pelos casos de uso. Seu objetivo é complementar esses casos ao incluir requisitos legais, regulamentares, padrões de aplicativos, atributos de qualidade, requisitos de suporte e compatibilidade, além de restrições de design. Utilizando a metodologia FURPS+ (Funcionalidade, Usabilidade, Confiabilidade, Desempenho e Suportabilidade, além de outros fatores), a Especificação Suplementar assegura que todas as necessidades do sistema sejam consideradas, resultando em um produto final robusto e de alta qualidade.

## Metodologia
A metodologia FURPS+ é uma abordagem usada para classificar e organizar os requisitos de um sistema em uma Especificação Suplementar. A sigla FURPS+ representa diferentes categorias de requisitos: funcionalidade, usabilidade, confiabilidade, desempenho e suportabilidade. Funcionalidade refere-se aos requisitos funcionais que descrevem as ações e serviços que o sistema deve realizar. Usabilidade abrange requisitos relacionados à facilidade de uso, interface do usuário e experiência do usuário. Confiabilidade especifica a robustez, disponibilidade, tolerância a falhas e recuperação do sistema. Desempenho define a rapidez, eficiência, tempo de resposta e capacidade do sistema. Suportabilidade aborda a facilidade de manutenção, escalabilidade, adaptabilidade e suporte técnico. O "+" na sigla FURPS+ indica a inclusão de outros aspectos importantes, como requisitos de implementação, que envolvem conformidade com padrões e especificações técnicas; requisitos de interface, que dizem respeito à capacidade do sistema de se comunicar e funcionar em conjunto com outros sistemas; requisitos físicos, que consideram o ambiente físico onde o sistema será utilizado; e restrições de design, que são limitações e diretrizes específicas para o desenvolvimento do sistema. A FURPS+ fornece uma estrutura abrangente para assegurar que todos os aspectos críticos do sistema sejam considerados e documentados, garantindo um desenvolvimento mais completo e eficaz.

## Funcionalidade 

Os Requisitos de Funcionalidade, ou Requisitos Funcionais, foram coletados durante o processo de elicitação utilizando as técnicas [questionário](Elicitacao/TecnicasElicitacao/Execucao/Questionários/Questionario.md), [storytelling](Elicitacao/TecnicasElicitacao/Execucao/Storytelling/Storytelling.md),  [análse de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md) e a [encenação adaptada](Elicitacao/TecnicasElicitacao/Execucao/EncenacaoAdaptada.md). Os requisitos funcionais se encontram na [Tabela 1](Elicitacao/ResquisitosCorrigidos.md) no artefato de requisitos elicitados com a sua devida rasteabilidade.


## Usabilidade

Neste tópico, é visto a importância dos requisitos de usabilidade, que serão listados a seguir na tabela 1, uma vez que a interação do usário com a interface depende completamente do seu nível de usabilidade para que as tarefas sejam concluidas com sucesso

<center>
<b>Tabela 1:</b> Requisitos de Usabilidade

|ID|Descrição|
|-|-|
|US01|O aplicativo deve ser responsivo, adaptando-se automaticamente a diferentes tamanhos de tela e dispositivos, como smartphones, tablets e desktops.|
|US02|As ações realizadas pelo usuário, como cliques e navegações entre telas, devem ter um tempo de resposta de no máximo 4 segundos.|
|US03|O aplicativo deve incluir um tutorial interativo inicial que guie os novos usuários pelas funcionalidades principais na primeira vez que acessarem.|
|US04|O aplicativo deve incluir uma função de busca eficiente que permita aos usuários encontrar informações rapidamente, com sugestões de autocompletar.|
|US05|O aplicativo deve ter uma seção de ajuda e suporte de fácil acesso, com FAQs, tutoriais em vídeo e opção de contato com o suporte técnico.|
|US06|O aplicativo deve proporcionar maneiras fáceis para os usuários corrigirem erros, como a possibilidade de desfazer ações recentes ou editar informações submetidas.|
|US07|O aplicativo deve fornecer feedback imediato após cada ação do usuário, como confirmação de envio de dados ou mensagens de erro claras.
|

Fonte: [Caio Mesquita ](https://github.com/Caiomesvie)

</center>

## Confiabilidade

Trata-se do quão confiável é o sistema, se baseando na frequência de falhas, possibilidade de recuperação e prevenção e tempo entre as falhas.

Os requisitos identificados nesta categoria estão na tabela 1 a seguir.

<p align="center"> Tabela 1 - Requisitos de confiabilidade. </p>

| ID    | Descrição                                                                                                                          |
| ----- | ---------------------------------------------------------------------------------------------------------------------------------- |
| CON01 | O sistema deve ser acessível 24 horas por dia, todos os dias.                                                                      |
| CON02 | O sistema deve possuir as informações atualizadas e condizentes com a realidade.                                                   |
| CON03 | O sistema deve manter íntegra as informações sobre o usuário e seus contratos de trabalho.                                         |
| CON04 | O sistema deve seguir a Lei Geral de Proteção de Dados (LGPD).                                                                     |
| CON05 | O sistema deve permitir que o usuário se recupere de problemas e erros.                                                            |
| CON06 | O sistema deve impedir que o usuário realize atividades que possam colocar a integridade do sistema e de outros usuários em risco. |

<b>Fonte:</b> <a href="https://github.com/brenoalexandre0"> Breno Alexandre </a>.

## Desempenho

Trata-se das condições que os requisitos devem executar. 
Os requisitos identificados nesta categoria estão na tabela 2 a seguir.

<p align="center"> Tabela 2 - Requisitos de desempenho. </p>

| ID    | Descrição                                                                                          |
| ----- | -------------------------------------------------------------------------------------------------- |
| DES01 | O sistema não deve ter um tempo de resposta superior a 1 segundo.                                  |
| DES02 | O sistema deve permitir mais de 500 mil de requisições por segundo.                                |
| DES03 | O sistema deve possuir uma navegação fluida, sem engasgo e caminhos seguindo uma sequência lógica. |
| DES04 | O sistema deve possuir uma interface leve, com no máximo 10 elementos na mesma tela.               |

<b>Fonte:</b> <a href="https://github.com/brenoalexandre0"> Breno Alexandre </a>.

## Suportabilidade

A tabela 3 a seguir apresenta os requisitos associados ao suporte e manutenção do sistema. Esses requisitos incluem a facilidade de manutenção, a capacidade de modificação e atualização do sistema, a disponibilidade de documentação adequada, e a facilidade de teste e diagnóstico de problemas.

<font><p style="text-align: center">Tabela 3 - Requisitos de Suportabilidade.</p></font>

| ID    | Descrição                                                                                                                                                                                                                                                                  |
| ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------|
| SUP01 | O sistema deve registrar logs detalhados de eventos e atividades do aplicativo para facilitar a depuração e o monitoramento do desempenho.                  |
| SUP02 | O sistema deve possuir documentação completa e atualizada para o código-fonte do aplicativo, incluindo instruções de instalação, configuração e uso de APIs.|
| SUP03 | O sistema deve Implementar um gerenciamento robusto de erros e exceções para lidar com falhas inesperadas e garantir uma experiência do usuário suave.      |
| SUP04 | O sistema deve possuir uma uma arquitetura flexível e modular, permitindo fácil manutenção e adição de novos recursos no futuro.                            |
| SUP05 | O sistema deve ser responsivo e compatível com uma variedade de dispositivos móveis com diferentes tamanhos e resoluções de tela.                           |

<font size="3"><p style="text-align: center">Fonte: [Iago Passaglia](https://github.com/Paxxaglia).</p></font>


## Restrições de Design

O app Carteira de Trabalho Digital deve adotar restrições de design rigorosas para garantir sua segurança, como criptografia robusta para proteger dados sensíveis dos usuários, seguir as melhores práticas de autenticação e autorização. Além disso, é fundamental que o aplicativo seja acessível a todos, incluindo opções de contraste, aumento do tamanho das fontes e etc. Quanto às tecnologias utilizadas, é importante que o aplicativo seja compatível com uma variedade de dispositivos e sistemas operacionais, assegurando uma experiência consistente para todos os usuários. Por fim, o design da interface deve ser intuitivo e amigável, facilitando a navegação e o uso do aplicativo por parte dos usuários.

## Suplementares

A tabela 4 a seguir apresenta os requisitos referentes ao "+" da metodologia escolhida, esses requisitos podem ser classificados como Requisitos de Implementação, Requisitos de Sistema de Ajuda e de Documentação de Usuário On-line.

### Requisitos de implementação

<font><p style="text-align: center">Tabela 4 - Requisitos de Implementação.</p></font>

| ID    | Descrição                                                                                                                                                   |
| ----- | -------------------------------------------------------------------------------------------------------------------------------------------------------------|
| RI01   | Integração com eSocial                                                                                                                                         |
| RI02   | Integração com gov.br                                                                                                                                          |
| RI03   | Permitir integração com vários outros software                                                                                                                |
| RI04   | Estar adaptado para ser instalado em qualquer sistema operacional                                                                                             |
| RI05 | Ter a capacidade de atender alterações de demanda no sistema, como mudanças em volumes de dados, de quantidade de transações ou de quantidade de usuários. |
| RI06 | Seguir os manuais de interface de acordo com o gov.br. |
| RI07 | Ter o básico de segurança: Autenticação, Criptografia, Controle de acesso, Auditoria, Atender as diretrizes e as práticas de segurança no controle de acesso à conta única. |
| RI08 | Garantir as condições de preservação da privacidade das informações do cidadão. |
| RI09 | Utilização de recursos como vocabulários controlados e taxonomias. |

<font size="3"><p style="text-align: center">Fonte: [Pedro Izarias](https://github.com/Izarias).</p></font>

### Requisitos de Sistema de Ajuda e de Documentação de Usuário On-line

<font><p style="text-align: center">Tabela 5 - Requisitos de Sistema de Ajuda e de Documentação de Usuário On-line.</p></font>

| ID | Descrição |
|--------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| RSD01 | Seguir os manuais de interface de acordo com o gov.br. |
| RSD02 | Utilização de recursos como vocabulários controlados e taxonomias. |

<font size="3"><p style="text-align: center">Fonte: [Pedro Izarias](https://github.com/Izarias).</p></font>


## Observações Legais - Normas a serem seguidas

O desenvolvimento de aplicativos governamentais requer não apenas funcionalidades eficientes, mas também conformidade com uma série de normas, regulamentos e diretrizes legais. Assim, no contexto da carteira digital do trabalho, é fundamental que o sistema atenda aos requisitos não funcionais relacionados a normas para garantir uma melhor e mais segura experiência para o usuário. Com isso, abaixo, a tabela 2 detalha os requisitos relacionados a normas que o aplicativo da carteira digital do trabalho deve seguir para o cumprimento dos padrões governamentais.

**Tabela 6:** Normas que precisam ser seguidas

| ID    | Descrição                                                                                                                                                                                                                                                                  |
| ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------|
| SUP06 |  Todos os textos do sistema devem seguir os padrões tipográficos e de siglas, abreviações e erros conforme as normas do  [padrões de deign](https://www.gov.br/ds/padroes/visao-geral)   e do [componentes](https://www.gov.br/ds/components/visao-geral)     |
| SUP07 | A interface do usuário deve estar em conformidade com os manuais de interface gov.br. em [Padrão Digital de Governo](https://www.gov.br/ds/home ), [Padrão mínimo de interface](https://www.gov.br/ds/introducao/padrao-minimo ), [Visão Geral dos Fundamentos Visuais](https://www.gov.br/ds/fundamentos-visuais/visao-geral ) e [Padrão de Design](https://www.gov.br/ds/padroes/visao-geral )  |
| SUP08 |  A interface do sistema deve incluir todos os elementos básicos de design do Padrão Digital de Governo em  [Padrões para Android e IOS](https://www.gov.br/ds/padroes/mobile/android-e-ios).   |
| SUP09 |  O sistema deve garantir a conformidade com a LGPD (Lei Geral de Proteção de Dados).                      |
| SUP10 |  O sistema deve oferecer suporte a ampliadores de telas, leitores de telas, programas de reconhecimento de voz, teclados alternativos e dispositivos apontadores alternativos, e ser testado com pelo menos duas ferramentas de acessibilidade diferentes.                       |
| SUP11 | O sistema deve utilizar vocabulários controlados e taxonomias padrão do governo, conforme especificado na documentação: [tipografia](https://www.gov.br/ds/fundamentos-visuais/tipografia)  |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

## Padrões Aplicáveis

O sistema deve seguir os padrões definidos pelas normas internacionais para garantir qualidade, segurança e compatibilidade. Os padrões aplicáveis incluem:

### Tabela 7: Padrões e Normas que Precisam ser Seguidos

| ID    | Descrição                                                   |
|-------|-------------------------------------------------------------|
| PAD01 | O sistema deve seguir as diretrizes de acessibilidade WCAG. |
| PAD02 | Deve estar em conformidade com a norma ISO 9241-11 sobre usabilidade. |
| PAD03 | Deve cumprir as normas de qualidade ISO 9000 e ISO 9001-3.  |
| PAD04 | Deve seguir a norma ISO 12207 para processos de ciclo de vida de software. |
| PAD05 | Deve atender aos requisitos de segurança da ISO 27001.      |
| PAD06 | O design e interface devem seguir os guias de estilo dos sistemas Android e iOS. |
| PAD07 | O aplicativo deve ser capaz de funcionar corretamente em uma variedade de resoluções de tela, ajustando o layout de forma responsiva. |
| PAD08 | O aplicativo deve exigir no máximo 100 MB de espaço de armazenamento no dispositivo para instalação e operação regular. |
| PAD09 | O aplicativo deve funcionar em dispositivos com no mínimo 2 GB de RAM, garantindo um desempenho fluido. |
| PAD10 | O aplicativo deve ser capaz de operar em redes 3G, 4G, 5G e Wi-Fi, com funcionalidades básicas disponíveis offline e sincronização de dados quando a conectividade for restaurada. |
| PAD11 | O aplicativo deve suportar autenticação por impressão digital e reconhecimento facial, disponíveis em dispositivos que possuam esses recursos. |
| PAD12 | O aplicativo deve ser capaz de utilizar o GPS do dispositivo para funções que requeiram geolocalização, como registro de ponto geolocalizado. |
| PAD13 | O aplicativo deve utilizar a câmera do dispositivo para funcionalidades como captura de documentos e reconhecimento facial. |
| PAD14 | O aplicativo deve aproveitar os módulos de segurança do hardware, como Secure Enclave em dispositivos Apple ou Trusted Execution Environment (TEE) em dispositivos Android, para proteger dados sensíveis. |
| PAD15 | O aplicativo deve poder acessar sensores do dispositivo, como acelerômetro e giroscópio, para funções que possam requerer essas capacidades. |
| PAD16 | O aplicativo deve ser compatível com dispositivos que possuem Near Field Communication (NFC) para funções como leitura de documentos compatíveis ou autenticação segura. |
| PAD17 | O aplicativo deve ser otimizado para minimizar o consumo de energia, prolongando a vida útil da bateria dos dispositivos móveis. |
| PAD18 | O aplicativo deve ser compatível com os sistemas de backup nativos dos dispositivos (iCloud para iOS, Google Drive para Android) para garantir a recuperação de dados em caso de perda ou troca de aparelho. |
| PAD19 | O aplicativo deve ser capaz de rodar em dispositivos com processadores de 64 bits para garantir desempenho adequado e suporte a futuras atualizações. |
| PAD20 | O aplicativo deve garantir consistência de funcionalidades e design em todas as plataformas suportadas (iOS, Android), proporcionando uma experiência de usuário unificada e eficiente. |

## Requisitos Físicos

O sistema deve ser compatível com diversos dispositivos, garantindo acessibilidade e experiência consistente para todos os usuários:

### Tabela 8: Padrões e Normas Estabelecidos

| ID    | Descrição                                                        |
|-------|------------------------------------------------------------------|
| FIS01 | Deve ser otimizado para tablets e smartphones com navegação responsiva. |
| FIS02 | Deve operar em sistemas Android 5.0 ou superior e iOS 11.0 ou posterior. |
| FIS03 | Recursos adicionais devem estar especificados nos manuais dos sistemas operacionais. |
| FIS04 | O aplicativo deve funcionar corretamente em uma variedade de resoluções de tela, ajustando o layout de forma responsiva. |
| FIS05 | O aplicativo deve exigir no máximo 100 MB (o app possui 29MB aproximadamente) de espaço de armazenamento no dispositivo para instalação e operação regular. |
| FIS06 | O aplicativo deve funcionar em dispositivos com no mínimo 2 GB de RAM, garantindo um desempenho fluido. |
| FIS07 | O aplicativo deve ser capaz de operar em redes 3G, 4G, 5G e Wi-Fi, com funcionalidades básicas disponíveis offline e sincronização de dados quando a conectividade for restaurada. |
| FIS08 | O aplicativo deve suportar autenticação por impressão digital e reconhecimento facial, disponíveis em dispositivos que possuam esses recursos. |
| FIS09 | O aplicativo deve utilizar a câmera do dispositivo para funcionalidades como captura de documentos e reconhecimento facial. |
| FIS10 | O aplicativo deve aproveitar os módulos de segurança do hardware, como Secure Enclave em dispositivos Apple ou Trusted Execution Environment (TEE) em dispositivos Android, para proteger dados sensíveis. |
| FIS11 | O aplicativo deve garantir consistência de funcionalidades e design em todas as plataformas suportadas (iOS, Android), proporcionando uma experiência de usuário unificada e eficiente. |

**Fonte:** [Bruno Araújo](https://github.com/brunocva)

## Referências Bibliográficas

SERRANO, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf. Acesso em: 14/05/2023.

https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital/blob/main/docs/modelagem/especificacao-suplementar.md

## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 |   Adição da Suportabilidade           | Iago Passaglia |  Bruno Araújo   |  19/05/2024  |
| 1.1 |   Adição da Introdução e Metodologia  | Luana Medeiros |  Iago Passaglia   |  19/05/2024  |
| 1.2 |   Adição dos requisitos suplementares  | Pedro Izarias |   Iago Passaglia |  19/05/2024  |
| 1.3 | Adição de observações legais ou normas | Larissa Stéfane | Bruno Araújo  |  19/05/2024  |
| 1.4 | Adição de Padrões Apláveis e Requisitos Físicos | Bruno Araújo | Iago Passaglia  |  19/05/2024  |
| 1.5 | Correção de tabelas | Iago Passaglia | Breno Alexandre  |  19/05/2024  |
| 1.6 | Adição dos tópicos "Confiabilidade" e "Desempenho" | Breno Alexandre | -  |  19/05/2024  |
| 1.7 | Correção das tabelas | Pedro Izarias | -  |  19/05/2024  |
| 1.8 | Adição de Funcionalidade e usabilidade| Caio Mesquita | -  |  19/05/2024  |
| 1.8.1 | Correção em requisitos físicos| Caio Mesquita | -  |  19/05/2024  |

