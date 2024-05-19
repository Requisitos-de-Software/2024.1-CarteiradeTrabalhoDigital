# Caso de uso 

## Sumário

Este documento descreve os casos de uso do aplicativo da Carteira de Trabalho Digital. Inclui a introdução, metodologia, elementos do diagrama de casos de uso, o diagrama de casos de uso, especificações detalhadas dos casos de uso, e referências bibliográficas.

## Introdução

Um caso de uso se refere a uma descrição detalhada de como o sistema será utilizado em uma determinada situação ou contexto. Ele descreve as interações entre os usuários e o sistema, apresentando os passos necessários para alcançar um objetivo específico. O objetivo dos casos de uso é auxiliar no processo de desenvolvimento de um sistema, fornecendo uma visão clara dos requisitos funcionais do sistema, descrevendo as ações que os usuários podem realizar e as respostas do sistema a essas ações.

## Metodologia

Para a construção dos casos de uso, utilizamos a técnica de Cenários, que é uma das técnicas de elicitação de requisitos. Essa técnica ajuda a identificar requisitos e prever situações que podem ocorrer no uso do sistema. A metodologia foi baseada na técnica de modelagem de casos de uso apresentada em "Requisitos – Aula 13" (SERRANO; SERRANO, 2017)【1】.

O diagrama de caso de uso é uma representação visual que resume as interações entre os usuários e um sistema, destacando suas funcionalidades e comportamentos. Ele é composto por atores, que representam os usuários, e casos de uso, que descrevem as ações realizadas pelos usuários e as respostas do sistema. Para a realização do caso de uso, utilizamos as técnicas descritas na metodologia da Linguagem de Apoio ao Léxico (LAL)【2】.

## Elementos 

<center>
Tabela 1: Legenda dos elementos do diagrama de caso de uso

|Elementos| Nome | Função |
| - | - | - |
| Ator | Representa os diferentes tipos de usuários externos que interagem com o sistema |
| Caso de Uso | Descreve uma funcionalidade ou uma ação específica que o sistema pode realizar em resposta às interações dos atores |
| Sistema | Representa o sistema ou o bloco em análise, envolve os casos de uso e atores relacionados |
| Relações | Representa as relações ou interações entre atores e casos de uso |

Fonte: [Caio Mesquita]()

</center>

## Diagrama de Casos de Uso

A figura abaixo demonstra o diagrama de casos de uso do aplicativo da Carteira de Trabalho Digital.

<center>
<img src="diagrama_de_casos_de_uso.png" alt="Diagrama de Casos de Uso">
</center>

## Especificação dos Casos de uso

A seguir, são especificados os casos de uso do aplicativo da Carteira de Trabalho Digital.

<center>
Tabela 2: Legenda para as tabelas de caso de Uso

| Elemento | Significado            |
| -------- | ---------------------- |
| UC0X     | Caso de Uso Nº X       |
| FB0X     | Fluxo Básico Nº X      |
| FA0X     | Fluxo Alternativo Nº X |
| FE0X     | Fluxo de exceção Nº X  |

Fonte:[Caio Mesquita]()

</center>

<center>
Tabela X: Caso de uso UC01

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

Fonte: []

</center>

## Referências Bibliográficas

1. MINISTÉRIO DO TRABALHO E EMPREGO. Passo a Passo Carteira de Trabalho Digital APP e WEB. 2023.
2. SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 13. 2017. Apresentação de slides. Disponível em: <https://example.com/Requisitos-Aula-013a.pdf>. Acesso em: 19 mai. 2024.
3. SERRANO, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: <https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf>. Acesso em: 14/05/2023.

## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação documentação. | Bruno Araújo | Bruno Araújo | 19/05/2024 |
