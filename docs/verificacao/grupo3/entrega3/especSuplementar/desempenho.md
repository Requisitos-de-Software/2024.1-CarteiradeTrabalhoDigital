# Avaliação Rich Pictures Grupo 03

## Sumário
1. [Introdução](#introdução)
2. [Metodologia](#metodologia)
3. [Tabela de Avaliação](#tabela-de-avaliação)
4. [Avaliação](#avaliação)
5. [Bibliografia](#bibliografia)
6. [Histórico de Versões](#histórico-de-versões)

## Introdução

Este documento tem como objetivo avaliar se os requisitos de desempenho dentro de especificação suplementar foram feitos de forma correta pelo Grupo 3. 

## Metodologia

Para a avaliação dos requisitos de desempenho dentro de especificação suplementar do Grupo 3, desenvolvemos uma lista de verificação com x perguntas focadas na parte de desempenho  de validação e um membro do nosso grupo irá avaliar a entrevista utilizando essa lista e preenchendo uma tabela de avaliação. Após a avaliações, compilaremos os resultados para fornecer um feedback abrangente e construtivo ao Grupo 3.

## Tabela de avaliação

Tabela 1: Perguntas para avaliação

<br>

| Nº da Pergunta |                                                               Pergunta                                                               | Referência |
|----------------|--------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| 1              | O documento possui especificações claras dos tempos máximos aceitáveis de resposta para diferentes tipos de solicitações do usuário? | [Referência](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjo7e2Oh9KGAxWcmZUCHSICB4gQFnoECBAQAQ&url=https%3A%2F%2Fpdp.mctic.gov.br%2FMCTI-PDP%2Fguidances%2Fexamples%2Fresources%2FSiglaProjeto_EspecificacaoSuplementar.docx&usg=AOvVaw2wnS4aM5dnm6xkrde-iuok&opi=89978449) |
| 2              | O documento menciona o número máximo de conexões simultâneas que o sistema deve suportar sem degradação de desempenho? | [Referência](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjo7e2Oh9KGAxWcmZUCHSICB4gQFnoECBAQAQ&url=https%3A%2F%2Fpdp.mctic.gov.br%2FMCTI-PDP%2Fguidances%2Fexamples%2Fresources%2FSiglaProjeto_EspecificacaoSuplementar.docx&usg=AOvVaw2wnS4aM5dnm6xkrde-iuok&opi=89978449) |
| 3              | O documento define os tempos máximos de latência aceitáveis para operações críticas do sistema? | [Referência](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjo7e2Oh9KGAxWcmZUCHSICB4gQFnoECBAQAQ&url=https%3A%2F%2Fpdp.mctic.gov.br%2FMCTI-PDP%2Fguidances%2Fexamples%2Fresources%2FSiglaProjeto_EspecificacaoSuplementar.docx&usg=AOvVaw2wnS4aM5dnm6xkrde-iuok&opi=89978449) |
| 4              | O documento inclui métricas de confiabilidade, como a taxa de erros permitida e a frequência de falhas aceitável? | [Referência](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjo7e2Oh9KGAxWcmZUCHSICB4gQFnoECBAQAQ&url=https%3A%2F%2Fpdp.mctic.gov.br%2FMCTI-PDP%2Fguidances%2Fexamples%2Fresources%2FSiglaProjeto_EspecificacaoSuplementar.docx&usg=AOvVaw2wnS4aM5dnm6xkrde-iuok&opi=89978449) |
| 5              | O documento especifica os tempos máximos de recuperação aceitáveis após falhas ou reinicializações? | [Referência](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjo7e2Oh9KGAxWcmZUCHSICB4gQFnoECBAQAQ&url=https%3A%2F%2Fpdp.mctic.gov.br%2FMCTI-PDP%2Fguidances%2Fexamples%2Fresources%2FSiglaProjeto_EspecificacaoSuplementar.docx&usg=AOvVaw2wnS4aM5dnm6xkrde-iuok&opi=89978449) |
| 6             | O documento descreve os métodos ou ferramentas a serem usados para medir e testar o desempenho do sistema? | [Referência](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjo7e2Oh9KGAxWcmZUCHSICB4gQFnoECBAQAQ&url=https%3A%2F%2Fpdp.mctic.gov.br%2FMCTI-PDP%2Fguidances%2Fexamples%2Fresources%2FSiglaProjeto_EspecificacaoSuplementar.docx&usg=AOvVaw2wnS4aM5dnm6xkrde-iuok&opi=89978449) |
| 7             | O documento especifica como o sistema deve se comportar durante picos de carga? Estão previstas estratégias de mitigação de sobrecarga? | [Referência](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjo7e2Oh9KGAxWcmZUCHSICB4gQFnoECBAQAQ&url=https%3A%2F%2Fpdp.mctic.gov.br%2FMCTI-PDP%2Fguidances%2Fexamples%2Fresources%2FSiglaProjeto_EspecificacaoSuplementar.docx&usg=AOvVaw2wnS4aM5dnm6xkrde-iuok&opi=89978449) |
| 8             | O documento define as especificações para o monitoramento contínuo e registro de dados de desempenho em tempo real? | [Referência](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjo7e2Oh9KGAxWcmZUCHSICB4gQFnoECBAQAQ&url=https%3A%2F%2Fpdp.mctic.gov.br%2FMCTI-PDP%2Fguidances%2Fexamples%2Fresources%2FSiglaProjeto_EspecificacaoSuplementar.docx&usg=AOvVaw2wnS4aM5dnm6xkrde-iuok&opi=89978449) |



<br>

Autor: [Iago Passaglia](https://github.com/paxxaglia)


## Avaliação


Tabela 2: Respostas da avaliação

<br>

| Nº da Pergunta |                                                               Pergunta                                                               | Resposta |
|----------------|--------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| 1              | O documento possui especificações claras dos tempos máximos aceitáveis de resposta para diferentes tipos de solicitações do usuário? | Não |
| 2              | O documento menciona o número máximo de conexões simultâneas que o sistema deve suportar sem degradação de desempenho? | Não |
| 3              | O documento define os tempos máximos de latência aceitáveis para operações críticas do sistema? | Não |
| 4              | O documento inclui métricas de confiabilidade, como a taxa de erros permitida e a frequência de falhas aceitável? | Não |
| 5              | O documento especifica os tempos máximos de recuperação aceitáveis após falhas ou reinicializações? | Não |
| 6             | O documento descreve os métodos ou ferramentas a serem usados para medir e testar o desempenho do sistema? | Não |
| 7             | O documento especifica como o sistema deve se comportar durante picos de carga? Estão previstas estratégias de mitigação de sobrecarga? | Não |
| 8             | O documento define as especificações para o monitoramento contínuo e registro de dados de desempenho em tempo real? | Não |


<br>

Autor: [Iago Passaglia](https://github.com/paxxaglia)

## Conclusão

Os requisitos descritos pelo grupo na parte de desempenho são pouco específicos com tempos de resposta, erros aceitáveis e etc. Além disso, alguns requisitos de desempenho listados na tabela não dizem respeito ao desempenho do aplicativo. Alguns requisitos estão adequados, porém estão pouco específicos quanto a sua eficácia, por exemplo: "O cálculo de preços e prazos de encomendas deve ser preciso e rápido", a partir dessa frase, não conseguimos saber o quão rápido e quão preciso esse cálculo deve ser.


## Histórico de Versões

| Versão | Descrição                     | Autor           | Revisor | Data       |
|--------|-------------------------------|-----------------|------------|---------|
| 1.0    | Adição de introdução e metodologia | Iago Passaglia  | -| 10/06/2024 |
| 1.1    | Adição das tabelas de avaliação | Iago Passaglia  | - | 10/06/2024 |
| 1.2    | Avaliação| Iago Passaglia  | - | 10/06/2024 |
