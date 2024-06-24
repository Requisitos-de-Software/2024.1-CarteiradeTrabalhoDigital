# Matriz de Rastreabilidade

## Sumário
* [Introdução](#Introdução)
* [Metodologia](#Metodologia)
* [Matriz](#Matriz)
* [Conclusão](#Conclusão)
* [Bibliografia](#Bibliografia)
* [Histórico de Versão](#Histórico-de-Versão)
  
## Introdução
A matriz de rastreabilidade é um elemento fundamental no desenvolvimento de software, proporcionando uma visão clara do relacionamento entre os requisitos e outros artefatos do projeto. No contexto do projeto da Carteira Digital de Trabalho, a matriz de rastreabilidade serve para garantir que todos os requisitos definidos sejam adequadamente implementados, verificados e validados. Ela facilita a gestão de mudanças, a identificação de lacunas na cobertura de requisitos e assegura que o produto final atenda às expectativas e necessidades dos usuários e stakeholders. A seguir teremos a metodologia de desenvolvimento e a matriz em sí.

## Metodologia
A metodologia aplicada para a criação da matriz de rastreabilidade no projeto da Carteira Digital de Trabalho envolveu várias etapas integradas. Primeiro, realizamos a identificação e documentação detalhada dos requisitos funcionais e não funcionais do sistema. Em seguida, empregamos a rastreabilidade [Forward-from](https://requisitos-de-software.github.io/2024.1-CarteiradeTrabalhoDigital/#/posRastreabilidade/forwardFrom) para mapear cada requisito aos artefatos correspondentes, assegurando a cobertura completa das necessidades iniciais. Paralelamente, utilizamos a rastreabilidade [Backward-from](https://requisitos-de-software.github.io/2024.1-CarteiradeTrabalhoDigital/#/posRastreabilidade/backwardFrom) para traçar cada elemento de volta aos requisitos originais, garantindo que todas as funcionalidades implementadas eram necessárias e justificadas.

Após a análise de rastreabilidade, organizamos as informações na Tabela 1, formando a matriz de rastreabilidade. Esta matriz permite uma visualização clara das relações entre os requisitos e os artefatos de desenvolvimento. Para assegurar a precisão e a integridade das relações estabelecidas, realizamos uma revisão minuciosa da matriz, confirmando que todos os requisitos foram devidamente abordados. 

## Matriz

 <b>Tabela 1:</b>  Matriz de Rastreabilidade
 
| ID do Requisito      | Nome | Origem | Implementação | Artefatos | Elos |
| -------------------- | ---- | ----   | ----          | ----      | ---- |
|         RF01         | --   |  --    |       --      |    --     | --   | 
|         RF02         | --   |  --    |       --      |    --     | --   | 
|         RF03         | --   |  --    |       --      |    --     | --   | 
|         RF04         | --   |  --    |       --      |    --     | --   | 
|         RF05         | --   |  --    |       --      |    --     | --   | 
|         RF06         | --   |  --    |       --      |    --     | --   | 
|         RF07         | --   |  --    |       --      |    --     | --   | 
|         RF08         | --   |  --    |       --      |    --     | --   | 
|         RF09         | --   |  --    |       --      |    --     | --   | 
|         RF10         | --   |  --    |       --      |    --     | --   | 
|         RF11         | --   |  --    |       --      |    --     | --   | 
|         RF12         | --   |  --    |       --      |    --     | --   | 
|         RF13         | --   |  --    |       --      |    --     | --   | 
|         RF14         | --   |  --    |       --      |    --     | --   | 
|         RF15         | --   |  --    |       --      |    --     | --   | 
|         RF16         | --   |  --    |       --      |    --     | --   | 
|         RF17         | --   |  --    |       --      |    --     | --   | 
|         RF18         | --   |  --    |       --      |    --     | --   | 
|         RF19         | --   |  --    |       --      |    --     | --   | 
|         RF20         | --   |  --    |       --      |    --     | --   | 
|         RF21         | --   |  --    |       --      |    --     | --   | 
|         RF22         | Usuário empresa pode atualizar dados dos funcionários   |  Entrevistas e Análise de Documentos    |Incompleto|    --     |  RF03, RF04, RNF14, RNF18   | 
|         RF23         | Usuário empresa pode consultar contratos de trabalho   |  Entrevistas e Análise de Documentos    |Incompleto   |    --     | RF05, RNF18   | 
|         RF24         | Usuário empresa pode gerar relatórios trabalhistas   |  Entrevistas e Análise de Documentos   |Incompleto|    --     | RF06, RNF12   | 
|         RF25         | Usuário pode recuperar senha   |  Entrevistas  e Análise de Documentos   |Sim|    Histórias de Usuário     | RF05, RNF18   | 
|         RF26         | Usuário pode visualizar histórico de contratações   |  Entrevistas e Análise de Documentos    |Incompleto|    --     | RF07, RNF12   | 
|         RF27         | Usuário pode visualizar notificações   |  Entrevistas e Análise de Documentos   |Incompleto|    --     | RF08, RNF12   | 
|         RF28         | Usuário pode visualizar dados de contato da empresa   |  Entrevistas  e Análise de Documentos    |Não|    Casos de Uso, Histórias de Usuário     | RF10, RNF15   | 
|         RNF01        | --   |  --    |       --      |    --     | --   | 
|         RNF02        | --   |  --    |       --      |    --     | --   | 
|         RNF03        | --   |  --    |       --      |    --     | --   | 
|         RNF04        | --   |  --    |       --      |    --     | --   | 
|         RNF05        | --   |  --    |       --      |    --     | --   | 
|         RNF06        | --   |  --    |       --      |    --     | --   | 
|         RNF07        | --   |  --    |       --      |    --     | --   | 
|         RNF08        | --   |  --    |       --      |    --     | --   | 
|         RNF09        | Conformidade com a LGPD                           | Análise de Documentos                   | Incompleto    | --                          | RF03, RF04, RNF14, RNF18           |
|         RNF10        | Suporte a Ferramentas de Acessibilidade           | Análise de Documentos                   | Incompleto    | --                          | RF05, RNF18                        |
|         RNF11        | Integração com Processos Governamentais           | Análise de Documentos e Storytelling    | Incompleto    | --                          | RF06, RNF12                        |
|         RNF12        | Uso de Vocabulários Controlados                   | Análise de Documentos                   | Sim           | --                          | RF07, RNF12                        |
|         RNF13        | Processamento de Solicitações em 2 Minutos        | Análise de Documentos e Storytelling    | Parcialmente  | --                          | RF08, RNF12                        |
|         RNF14        | Padrões de Design Aceitos                         | Storytelling                            | Parcialmente  | --                          | RF10, RNF15                        |
|         RNF15        | Backup Diário                                     | Análise de Documentos                   | Sim           | --                          | RF11, RNF14                        |
|         RNF16        | --   |  --    |       --      |    --     | --   | 
|         RNF17        | --   |  --    |       --      |    --     | --   | 
|         RNF18        | --   |  --    |       --      |    --     | --   | 
|         RNF19        | --   |  --    |       --      |    --     | --   | 
|         RNF20        | --   |  --    |       --      |    --     | --   | 
|         RNF21        | --   |  --    |       --      |    --     | --   | 
|         RNF22        | --   |  --    |       --      |    --     | --   | 
|         RNF23        | --   |  --    |       --      |    --     | --   | 
|         RNF24        | --   |  --    |       --      |    --     | --   | 
|         RNF25        | --   |  --    |       --      |    --     | --   | 

<b> Autor: </b> <a href=".https://github.com/Izarias">Pedro Izarias</a>, <b> Autor: </b> <a href=".https://github.com/brunocva">Bruno Araújo</a>

## Conclusão
A matriz de rastreabilidade desenvolvida para o projeto da Carteira Digital de Trabalho provou ser uma ferramenta fundamental para assegurar a conformidade entre os requisitos especificados e os artefatos produzidos ao longo do ciclo de desenvolvimento. Através da metodologia aplicada, foi possível mapear de forma eficaz cada requisito aos seus correspondentes artefatos, garantindo a cobertura completa das necessidades iniciais e a justificativa das funcionalidades implementadas.

## Bibliografia
1. POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamentals: A Study Guide for the Certified Professional for Requirements Engineering Exam - Foundation Level - IREB compliant. ed. Berlin: Springer, 2015. Acesso feito em 22/06/2024.

2. SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Acesso em: 22 de jun de 2024.

## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação do documento | Pedro Izarias |  Bruno Araújo  |  22/06/2024  |
| 1.1 |  Adição da Introdução, Desenvolvimento e Matriz de rastreabilidade | Pedro Izarias |  Bruno Araújo  |  22/06/2024  |
