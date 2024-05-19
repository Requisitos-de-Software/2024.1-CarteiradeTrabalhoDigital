# Caso de uso 

## Sumário
 
* [Introdução](#Introdução)
* [Metodologia](#Metodologia)
* [Diagrama](#Diagrama-de-Casos-de-Uso)
* [Especificação](#Especificação-dos-Casos-de-uso)
* [Bibliografia](#Bibliografia)
* [Histórico de versão](#Histórico-de-versão)

## Introdução

Um caso de uso se refere a uma descrição detalhada de como o sistema será utilizado em uma determinada situação ou contexto. Ele descreve as interações entre os usuários e o sistema, apresentando os passos necessários para alcançar um objetivo específico. O objetivo dos casos de uso é auxiliar no processo de desenvolvimento de um sistema, fornecendo uma visão clara dos requisitos funcionais do sistema, descrevendo as ações que os usuários podem realizar e as respostas do sistema a essas ações.

## Metodologia

Para a construção dos casos de uso, utilizamos a técnica de Cenários, que é uma das técnicas de elicitação de requisitos. Essa técnica ajuda a identificar requisitos e prever situações que podem ocorrer no uso do sistema. A metodologia foi baseada na técnica de modelagem de casos de uso apresentada em "Requisitos – Aula 13" (SERRANO; SERRANO, 2017)【2】.

O diagrama de caso de uso é uma representação visual que resume as interações entre os usuários e um sistema, destacando suas funcionalidades e comportamentos. Ele é composto por atores, que representam os usuários, e casos de uso, que descrevem as ações realizadas pelos usuários e as respostas do sistema. Abaixo temos uma tabela onde há os elementos contidos no [Diagrama](#Diagrama-de-Casos-de-Uso)


<center>

<b>Tabela 1</b>: Legenda dos elementos do diagrama de caso de uso

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/assets/LegendaCasoUso.jpg" alt="Legenda elementos de caso de uso" width="800">

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

## Diagrama de Casos de Uso

A figura abaixo demonstra o diagrama de casos de uso do aplicativo da Carteira de Trabalho Digital.

<center>
<img src="diagrama_de_casos_de_uso.png" alt="Diagrama de Casos de Uso">
</center>

## Especificação dos Casos de uso

A seguir, são especificados os casos de uso do aplicativo da Carteira de Trabalho Digital.

<b>Tabela 2:</b> Legenda para as tabelas de caso de Uso

| Elemento | Significado            |
| -------- | ---------------------- |
| UC0X     | Caso de Uso Nº X       |
| FB0X     | Fluxo Básico Nº X      |
| FA0X     | Fluxo Alternativo Nº X |
| FE0X     | Fluxo de exceção Nº X  |

Fonte: [Caio Mesquita](https://github.com/caiomesvie)



<center>
Tabela 3: Caso de uso UC01

| UC01                | Solicitar Benefício                                              |
| ------------------- | ---------------------------------------------------------------- |
| Descrição           | Permitir que o trabalhador solicite um benefício, como seguro-desemprego ou auxílio-doença. |
| Atores              | Trabalhador (Usuário Primário); Sistema de Banco de Dados (Usuário Secundário); Órgão Governamental (Usuário Secundário) |
| Frequência          | Sempre que o trabalhador precisar solicitar um benefício.        |
| Pré-condições       | O trabalhador deve estar autenticado no sistema e ter os documentos necessários para a solicitação. |
| Fluxo Básico        | <b> FB01 </b> <ol> <li>O trabalhador faz login no aplicativo da carteira de trabalho digital. <li>O trabalhador acessa a aba "Benefícios". <li>O trabalhador seleciona o benefício desejado. <li>O sistema exibe os requisitos e documentos necessários para a solicitação do benefício. <li>O trabalhador preenche o formulário de solicitação e anexa os documentos necessários. <li>O sistema verifica a consistência das informações e documentos fornecidos. <li>Se todas as informações estiverem corretas, o sistema envia a solicitação para o órgão governamental responsável. <li>O trabalhador recebe uma confirmação de que a solicitação foi enviada com sucesso. </ol> |
| Fluxos Alternativos | <b> FA01 </b> <ol> <li>Se o trabalhador não tiver todos os documentos necessários, ele pode salvar a solicitação como rascunho e completá-la posteriormente. </ol>             |
| Fluxos de exceção   | <b> FE01 </b> <ol> <li>Se ocorrer um erro na validação das informações ou documentos, uma mensagem de erro é exibida e o trabalhador é orientado a corrigir os dados inseridos. <li>Se houver um problema de comunicação com o órgão governamental, uma mensagem de erro é exibida e o trabalhador é instruído a tentar novamente mais tarde. <li>Se a solicitação for rejeitada pelo órgão governamental, o trabalhador recebe uma notificação com o motivo da rejeição. </ol>             |
| Pós-condições       | A solicitação de benefício é registrada e enviada ao órgão governamental responsável para análise. |
| Data de Criação     | 19/05/2024                                                        |
| Rastreabilidade     | [Requisitos Funcionais RF01, RF02]                              |

**Fonte:** [Bruno Araújo](https://github.com/brunocva)

</center>

<center>
Tabela 4: Caso de uso UC02

| UC02                | Visualizar aba "Emprego"                                         |
| ------------------- | ---------------------------------------------------------------- |
| Descrição           | Permitir ao trabalhador acessar e completar informações pessoais para visualizar a aba "Emprego". |
| Atores              | Trabalhador (Usuário Primário); Plataforma gov.br (Usuário Secundário) |
| Frequência          | Sempre que o trabalhador precisar visualizar ou atualizar suas informações de emprego. |
| Pré-condições       | O trabalhador deve estar autenticado no sistema.                 |
| Fluxo Básico        | <b> FB02 </b> <ol> <li>O trabalhador faz login no aplicativo da carteira de trabalho digital. <li>O trabalhador acessa a aba "Emprego". <li>O trabalhador seleciona a opção "Quero me cadastrar". <li>O sistema exibe o formulário de "Dados Pessoais". <li>O trabalhador preenche o formulário de "Dados Pessoais". <li>O sistema exibe o formulário de "Endereço". <li>O trabalhador preenche o formulário de "Endereço". <li>O sistema exibe o formulário de "Contato". <li>O trabalhador preenche o formulário de "Contato". <li>O trabalhador envia os formulários e conclui a tarefa. </ol> |
| Fluxos Alternativos | <b> FA02 </b> <ol> <li>Se o trabalhador optar por abandonar a tarefa, ele fecha o aplicativo ou volta à tela inicial sem completar o processo de preenchimento dos formulários. |
| Fluxos de exceção   | <b> FE02 </b> <ol> <li>Se ocorrer um erro na validação das informações, uma mensagem de erro é exibida e o trabalhador é orientado a corrigir os dados inseridos. <li>Se houver um problema de comunicação com o órgão governamental, uma mensagem de erro é exibida e o trabalhador é instruído a tentar novamente mais tarde. <li>Em dispositivos IOS, se o teclado virtual permanecer sobre o botão de "Concluir" na última etapa, inviabilizando a conclusão da tarefa. </ol> |
| Restrição           | 1. O trabalhador deve estar autenticado no sistema para efetuar o cadastro.<br>2. A conexão com a internet deve estar estável durante o processo de solicitação. |
| Pós-condições       | As informações pessoais do trabalhador são registradas e a aba "Emprego" será disponibilizada por completo para o usuário. |
| Data de Criação     | 19/05/2024                                                        |
| Rastreabilidade     | [RF02, RF03]                                                      |


**Fonte:** [Iago Passaglia](https://github.com/Paxxaglia)

</center>

## Bibliografia

1. MINISTÉRIO DO TRABALHO E EMPREGO. Passo a Passo Carteira de Trabalho Digital APP e WEB. 2023.
2. SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 13. 2017. Apresentação de slides. Disponível em: <https://example.com/Requisitos-Aula-013a.pdf>. Acesso em: 19 mai. 2024.
3. SERRANO, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: <https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf>. Acesso em: 14/05/2023.

## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação documentação. | Bruno Araújo | Iago Passaglia | 19/05/2024 |
| 1.1 | Caso de uso UC02. | Iago Passaglia | - | 19/05/2024 |
