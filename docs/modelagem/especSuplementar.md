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

## Referências Bibliográficas

## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 |   Adição da Suportabilidade           | Iago Passaglia |   -  |  19/05/2024  |
| 1.1 |   Adição da Introdução e Metodologia  | Luana Medeiros |   -  |  19/05/2024  |
