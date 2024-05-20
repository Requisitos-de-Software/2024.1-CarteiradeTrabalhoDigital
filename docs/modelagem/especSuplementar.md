# Especificação Suplementar

## Sumário
* [Introdução](#Introdução)
* [Metodologia](#Metodologia)
* [Suportabilidade](#Suportabilidade)
* [Restrições de Design](#Restrições-de-Design)
* [Conclusão](#Conclusão)
* [Referências Bibliográficas](#Referências-Bibliográficas)
* [Histórico de versão](#Histórico-de-versão)

  
## Introdução
A Especificação Suplementar é um documento essencial em projetos de desenvolvimento de sistemas que captura e detalha requisitos não cobertos pelos casos de uso. Seu objetivo é complementar esses casos ao incluir requisitos legais, regulamentares, padrões de aplicativos, atributos de qualidade, requisitos de suporte e compatibilidade, além de restrições de design. Utilizando a metodologia FURPS+ (Funcionalidade, Usabilidade, Confiabilidade, Desempenho e Suportabilidade, além de outros fatores), a Especificação Suplementar assegura que todas as necessidades do sistema sejam consideradas, resultando em um produto final robusto e de alta qualidade.

## Metodologia
A metodologia FURPS+ é uma abordagem usada para classificar e organizar os requisitos de um sistema em uma Especificação Suplementar. A sigla FURPS+ representa diferentes categorias de requisitos: funcionalidade, usabilidade, confiabilidade, desempenho e suportabilidade. Funcionalidade refere-se aos requisitos funcionais que descrevem as ações e serviços que o sistema deve realizar. Usabilidade abrange requisitos relacionados à facilidade de uso, interface do usuário e experiência do usuário. Confiabilidade especifica a robustez, disponibilidade, tolerância a falhas e recuperação do sistema. Desempenho define a rapidez, eficiência, tempo de resposta e capacidade do sistema. Suportabilidade aborda a facilidade de manutenção, escalabilidade, adaptabilidade e suporte técnico. O "+" na sigla FURPS+ indica a inclusão de outros aspectos importantes, como requisitos de implementação, que envolvem conformidade com padrões e especificações técnicas; requisitos de interface, que dizem respeito à capacidade do sistema de se comunicar e funcionar em conjunto com outros sistemas; requisitos físicos, que consideram o ambiente físico onde o sistema será utilizado; e restrições de design, que são limitações e diretrizes específicas para o desenvolvimento do sistema. A FURPS+ fornece uma estrutura abrangente para assegurar que todos os aspectos críticos do sistema sejam considerados e documentados, garantindo um desenvolvimento mais completo e eficaz.

## Suportabilidade

A tabela x a seguir apresenta os requisitos associados ao suporte e manutenção do sistema. Esses requisitos incluem a facilidade de manutenção, a capacidade de modificação e atualização do sistema, a disponibilidade de documentação adequada, e a facilidade de teste e diagnóstico de problemas.

<font><p style="text-align: center">Tabela x - Requisitos de Suportabilidade.</p></font>

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

A tabela x a seguir apresenta os requisitos referentes ao "+" da metodologia escolhida, esses requisitos podem ser classificados como Requisitos de Implementação, Requisitos de Sistema de Ajuda e de Documentação de Usuário On-line.

### Requisitos de implementação

<font><p style="text-align: center">Tabela x - Requisitos de Implementação.</p></font>

| ID    | Descrição                                                                                                                                                   |
| ----- | -------------------------------------------------------------------------------------------------------------------------------------------------------------|
| F12   | Integração com eSocial                                                                                                                                         |
| F13   | Integração com gov.br                                                                                                                                          |
| F14   | Permitir integração com vários outros software                                                                                                                |
| F17   | Estar adaptado para ser instalado em qualquer sistema operacional                                                                                             |
| NF3 | Ter a capacidade de atender alterações de demanda no sistema, como mudanças em volumes de dados, de quantidade de transações ou de quantidade de usuários. |
| NF6 | Seguir os manuais de interface de acordo com o gov.br. |
| NF8 | Ter o básico de segurança: Autenticação, Criptografia, Controle de acesso, Auditoria, Atender as diretrizes e as práticas de segurança no controle de acesso à conta única. |
| NF9 | Garantir as condições de preservação da privacidade das informações do cidadão. |
| NF12 | Utilização de recursos como vocabulários controlados e taxonomias. |

<font size="3"><p style="text-align: center">Fonte: [Pedro Izarias](https://github.com/Izarias).</p></font>

### Requisitos de Sistema de Ajuda e de Documentação de Usuário On-line

<font><p style="text-align: center">Tabela x - Requisitos de Sistema de Ajuda e de Documentação de Usuário On-line.</p></font>

| ID | Descrição |
|--------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| NF6 | Seguir os manuais de interface de acordo com o gov.br. |
| NF12 | Utilização de recursos como vocabulários controlados e taxonomias. |

<font size="3"><p style="text-align: center">Fonte: [Pedro Izarias](https://github.com/Izarias).</p></font>


## Observações Legais - Normas a serem seguidas

O desenvolvimento de aplicativos governamentais requer não apenas funcionalidades eficientes, mas também conformidade com uma série de normas, regulamentos e diretrizes legais. Assim, no contexto da carteira digital do trabalho, é fundamental que o sistema atenda aos requisitos não funcionais relacionados a normas para garantir uma melhor e mais segura experiência para o usuário. Com isso, abaixo, a tabela 2 detalha os requisitos relacionados a normas que o aplicativo da carteira digital do trabalho deve seguir para o cumprimento dos padrões governamentais.

**Tabela 4:** Normas que precisam ser seguidas

| ID    | Descrição                                                                                                                                                                                                                                                                  |
| ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------|
| SUP06 |  Todos os textos do sistema devem seguir os padrões tipográficos e de siglas, abreviações e erros conforme as normas do  [padrões de deign](https://www.gov.br/ds/padroes/visao-geral)   e do [componentes](https://www.gov.br/ds/components/visao-geral)     |
| SUP07 | A interface do usuário deve estar em conformidade com os manuais de interface gov.br. em [Padrão Digital de Governo](https://www.gov.br/ds/home ), [Padrão mínimo de interface](https://www.gov.br/ds/introducao/padrao-minimo ), [Visão Geral dos Fundamentos Visuais](https://www.gov.br/ds/fundamentos-visuais/visao-geral ) e [Padrão de Design](https://www.gov.br/ds/padroes/visao-geral )  |
| SUP08 |  A interface do sistema deve incluir todos os elementos básicos de design do Padrão Digital de Governo em  [Padrões para Android e IOS](https://www.gov.br/ds/padroes/mobile/android-e-ios).   |
| SUP09 |  O sistema deve garantir a conformidade com a LGPD (Lei Geral de Proteção de Dados).                      |
| SUP10 |  O sistema deve oferecer suporte a ampliadores de telas, leitores de telas, programas de reconhecimento de voz, teclados alternativos e dispositivos apontadores alternativos, e ser testado com pelo menos duas ferramentas de acessibilidade diferentes.                       |
| SUP11 | O sistema deve utilizar vocabulários controlados e taxonomias padrão do governo, conforme especificado na documentação: [tipografia](https://www.gov.br/ds/fundamentos-visuais/tipografia)  |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

O sistema deve seguir os padrões definidos pelas normas internacionais para garantir qualidade, segurança e compatibilidade. Os padrões aplicáveis incluem:

**Tabela 5:** Padrões e normas que precisam ser seguidos
| ID    | Descrição                                                                            |
| ----- | ------------------------------------------------------------------------------------ |
| PAD01 | O sistema deve seguir as diretrizes de acessibilidade WCAG.                          |
| PAD02 | Deve estar em conformidade com a norma ISO 9241-11 sobre usabilidade.                |
| PAD03 | Deve cumprir as normas de qualidade ISO 9000 e ISO 9001-3.                           |
| PAD04 | Deve seguir a norma ISO 12207 para processos de ciclo de vida de software.           |
| PAD05 | Deve atender aos requisitos de segurança da ISO 27001.                               |
| PAD06 | O design e interface devem seguir os guias de estilo dos sistemas Android e iOS.     |

## Requisitos Físicos

O sistema deve ser compatível com diversos dispositivos, garantindo acessibilidade e experiência consistente para todos os usuários:

**Tabela 6:** Padrões e normas estabelecidos.
| ID    | Descrição                                                                                       |
| ----- | ------------------------------------------------------------------------------------------------|
| FIS01 | O sistema deve ser compatível com computadores desktop e laptops modernos.                      |
| FIS02 | Deve ser otimizado para tablets e smartphones com navegação responsiva.                         |
| FIS03 | Deve operar em sistemas Android 5.0 ou superior e iOS 11.0 ou posterior.                        |
| FIS04 | Recursos adicionais devem estar especificados nos manuais dos sistemas operacionais.           |

**Fonte:** [Bruno Araújo](https://github.com/brunocva)

## Referências Bibliográficas

## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 |   Adição da Suportabilidade           | Iago Passaglia |    |  19/05/2024  |
| 1.1 |   Adição da Introdução e Metodologia  | Luana Medeiros |     |  19/05/2024  |
| 1.2 |   Adição dos requisitos suplementares  | Pedro Izarias |   -  |  19/05/2024  |
| 1.3 | Adição de observações legais ou normas | Larissa Stéfane | Bruno Araújo  |  19/05/2024  |
| 1.4 | Adição de Padrões Apláveis e Requisitos Físicos | Bruno Araújo | -  |  19/05/2024  |
