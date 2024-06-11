# Avaliação de Casos de Uso

## Sumário
1. [Introdução](#introdução)
2. [Metodologia](#metodologia)
3. [Tabela de Verificação](#tabela-de-verificação)
4. [Avaliações](#avaliações)
5. [Bibliografia](#bibliografia)
6. [Histórico de versões](#histórico-de-versões)

## Introdução

Este documento tem como objetivo avaliar os casos de uso desenvolvidos pelo Grupo 3 na disciplina de Requisitos de Software. Através de uma lista de verificação contendo itens essenciais, buscaremos identificar a clareza, precisão, completude e adequação dos casos de uso em relação aos requisitos.

## Metodologia

Para realizar esta avaliação, será utilizada a tabela 0 que contém uma lista de perguntas baseadas nos principais critérios de qualidade para casos de uso. Cada integrante do grupo será responsável por analisar um ou mais casos de uso, preenchendo a tabela com suas respostas e observações.
## Tabela de Verificação

<br>

Tabela 0: Tabela de verificação

| Número da Pergunta | Pergunta                                                                 | Resposta |
|--------------------|--------------------------------------------------------------------------|----------|
| 1                  | O caso de uso está descrito de forma clara e precisa, evitando ambiguidades? |          |
| 2                  | O caso de uso possui um identificador único e um nome descritivo?         |          |
| 3                  | Os atores que interagem com o sistema estão claramente identificados e descritos? |          |
| 4                  | O objetivo ou finalidade do caso de uso está claramente definido?         |          |
| 5                  | As pré-condições (estado do sistema antes do início do caso de uso) estão claramente descritas? |          |
| 6                  | As pós-condições (estado do sistema após a execução do caso de uso) estão claramente descritas? |          |
| 7                  | O fluxo principal de eventos (caminho básico) está detalhado de forma sequencial e lógica? |          |
| 8                  | Existem fluxos alternativos ou secundários descritos para situações excepcionais ou variantes do fluxo principal? |          |
| 9                  | Existem fluxos de exceção claramente descritos para lidar com erros ou condições inesperadas? |          |
| 10                 | Todos os elementos do caso de uso estão devidamente documentados (título, descrição, atores, pré-condições, pós-condições, fluxos, etc.)? |          |

<br>

Autor: [Iago Passaglia](https://github.com/paxxaglia)


## Avaliações

<details>
<summary>Calcular preços e prazos de entrega - Larissa Stéfane </summary>

A tabela 1 mostra as respostas e observações da verificação e avaliação do caso de uso de "Calcular preços e prazos de entrega".

### Tabela 1: Tabela de verificação para Calcular preços e prazos de entrega

| Número da Pergunta | Pergunta                                                                 | Resposta | Observações |
|--------------------|--------------------------------------------------------------------------|----------| ---- |
| 1                  | O caso de uso está descrito de forma clara e precisa, evitando ambiguidades? |     Não     | Alguns pontos do caso de uso estão confusos e pouco claros. Por exemplo, não é indicado qual o usuário específico e o contexto para o caso de uso. <br> A forma como algumas frases foram elaboradas também estão um pouco confusas. |
| 2                  | O caso de uso possui um identificador único e um nome descritivo?         |    Sim      | - |
| 3                  | Os atores que interagem com o sistema estão claramente identificados e descritos? |     Não     | Existe uma abundância de usuários que utilizam o aplicativo dos Correios, todos eles podem apresentar contextos e características distintas no contexto do caso de uso. Contudo, o usuário foi representado de forma muito genérica no caso de uso. |
| 4                  | O objetivo ou finalidade do caso de uso está claramente definido?         |      Não    | Apesar de ser compreensível, a forma como o objetivo foi apresentado está vaga e confusa. |
| 5                  | As pré-condições (estado do sistema antes do início do caso de uso) estão claramente descritas? |     Incompleto     | Poderia complementar mais as pré-condições. Por exemplo, é necessário que o ator/usuário saiba o CEP, entre outras informações que não foram elencadas nas pré-condições. |
| 6                  | As pós-condições (estado do sistema após a execução do caso de uso) estão claramente descritas? |   Sim       | - |
| 7                  | O fluxo principal de eventos (caminho básico) está detalhado de forma sequencial e lógica? |     Sim      | - |
| 8                  | Existem fluxos alternativos ou secundários descritos para situações excepcionais ou variantes do fluxo principal? |     Sim/Incompleto     | Em fluxo alternativo, o fluxo 2 “Acesso à seção "Preços e Prazos" pelo menu” está praticamente idêntico ao fluxo principal. | 
| 9                  | Existem fluxos de exceção claramente descritos para lidar com erros ou condições inesperadas? |    Sim      | - |
| 10                 | Todos os elementos do caso de uso estão devidamente documentados (título, descrição, atores, pré-condições, pós-condições, fluxos, etc.)? |     Nao     | Existem elementos que estão faltando e alguns foram mal elaborados e descritos. |

<br>

 **Autora:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</details>

<details>
<summary>Realizar compras na loja online</summary>

### Tabela 2: Tabela de verificação para Realizar compras na loja online

| Número da Pergunta | Pergunta                                                                 | Resposta | Observações
|--------------------|--------------------------------------------------------------------------|----------| --- |
| 1                  | O caso de uso está descrito de forma clara e precisa, evitando ambiguidades? | Sim | - |
| 2                  | O caso de uso possui um identificador único e um nome descritivo?         | Sim | - |
| 3                  | Os atores que interagem com o sistema estão claramente identificados e descritos? | Incompleto | Falta uma descrição completa dos atores, essencial para entender todas as interações do sistema. |
| 4                  | O objetivo ou finalidade do caso de uso está claramente definido?         | Não | É importante definir claramente o objetivo do caso de uso para garantir que o propósito e os resultados esperados sejam compreendidos. |
| 5                  | As pré-condições (estado do sistema antes do início do caso de uso) estão claramente descritas? | Incompleto | A descrição das pré-condições está incompleta, o que é crucial para estabelecer o contexto inicial necessário para a execução do caso de uso. |
| 6                  | As pós-condições (estado do sistema após a execução do caso de uso) estão claramente descritas? | Incompleto | Falta uma descrição detalhada das pós-condições, fundamental para entender o estado final do sistema após a execução do caso de uso. |
| 7                  | O fluxo principal de eventos (caminho básico) está detalhado de forma sequencial e lógica? | Incompleto | A descrição do fluxo principal está incompleta, essencial para garantir que todos os passos do processo sejam seguidos corretamente. |
| 8                  | Existem fluxos alternativos ou secundários descritos para situações excepcionais ou variantes do fluxo principal? | Sim | - |
| 9                  | Existem fluxos de exceção claramente descritos para lidar com erros ou condições inesperadas? | Sim | - |
| 10                 | Todos os elementos do caso de uso estão devidamente documentados (título, descrição, atores, pré-condições, pós-condições, fluxos, etc.)? | Sim | - |

<br>

Autor: [Luana Medeiros](https://github.com/LuaMedeiros)

</details>

<details>
<summary>Realizar pré-postagem - Pedro Izarias</summary>

### Tabela 3: Tabela de verificação para Realizar pré-postagem

| Número da Pergunta | Pergunta                                                                 | Resposta | Observação |
|--------------------|--------------------------------------------------------------------------|----------|----|
| 1                  | O caso de uso está descrito de forma clara e precisa, evitando ambiguidades? |    Sim      ||
| 2                  | O caso de uso possui um identificador único e um nome descritivo?         |      Sim    |Identificador UC04|
| 3                  | Os atores que interagem com o sistema estão claramente identificados e descritos? |    Incompleto      |Apenas o usuário está identificado como ator|
| 4                  | O objetivo ou finalidade do caso de uso está claramente definido?         |     Não    ||
| 5                  | As pré-condições (estado do sistema antes do início do caso de uso) estão claramente descritas? |  Sim     ||
| 6                  | As pós-condições (estado do sistema após a execução do caso de uso) estão claramente descritas? |    Sim     ||
| 7                  | O fluxo principal de eventos (caminho básico) está detalhado de forma sequencial e lógica? |     Sim     |Está organizado de maneira crescente|
| 8                  | Existem fluxos alternativos ou secundários descritos para situações excepcionais ou variantes do fluxo principal? |   Sim     ||
| 9                  | Existem fluxos de exceção claramente descritos para lidar com erros ou condições inesperadas? |     Incompleto     |Há citação de fluxos de excessão mas não a descrição de como lidar com os mesmos|
| 10                 | Todos os elementos do caso de uso estão devidamente documentados (título, descrição, atores, pré-condições, pós-condições, fluxos, etc.)? |     Sim     ||

<br>

Autor: [Pedro Izarias](https://github.com/Izarias)

</details>

<details>
<summary>Gerenciar minhas importações</summary>

### Tabela 4: Tabela de verificação para Gerenciar minhas importações

| Número da Pergunta | Pergunta                                                                 | Resposta |
|--------------------|--------------------------------------------------------------------------|----------|
| 1                  | O caso de uso está descrito de forma clara e precisa, evitando ambiguidades? |          |
| 2                  | O caso de uso possui um identificador único e um nome descritivo?         |          |
| 3                  | Os atores que interagem com o sistema estão claramente identificados e descritos? |          |
| 4                  | O objetivo ou finalidade do caso de uso está claramente definido?         |          |
| 5                  | As pré-condições (estado do sistema antes do início do caso de uso) estão claramente descritas? |          |
| 6                  | As pós-condições (estado do sistema após a execução do caso de uso) estão claramente descritas? |          |
| 7                  | O fluxo principal de eventos (caminho básico) está detalhado de forma sequencial e lógica? |          |
| 8                  | Existem fluxos alternativos ou secundários descritos para situações excepcionais ou variantes do fluxo principal? |          |
| 9                  | Existem fluxos de exceção claramente descritos para lidar com erros ou condições inesperadas? |          |
| 10                 | Todos os elementos do caso de uso estão devidamente documentados (título, descrição, atores, pré-condições, pós-condições, fluxos, etc.)? |          |

<br>

Autor: [Iago Passaglia](https://github.com/paxxaglia)

</details>

<details>
<summary>Rastrear encomendas</summary>

### Tabela 5: Tabela de verificação para Rastrear encomendas

| Número da Pergunta | Pergunta | Resposta Sim/Não/Incompleto | Observação |
|-------------------|----------|-----------------------------|------------|
| 1 | O caso de uso está descrito de forma clara e precisa, evitando ambiguidades? | Sim | A descrição é clara e precisa. |
| 2 | O caso de uso possui um identificador único e um nome descritivo? | Sim | Identificador: UC06, Nome: Rastrear Encomendas. |
| 3 | Os atores que interagem com o sistema estão claramente identificados e descritos? | Sim | O ator "Usuário" está identificado. |
| 4 | O objetivo ou finalidade do caso de uso está claramente definido? | Sim | O objetivo de rastrear encomendas está claramente definido. |
| 5 | As pré-condições (estado do sistema antes do início do caso de uso) estão claramente descritas? | Sim | As pré-condições são claramente descritas. |
| 6 | As pós-condições (estado do sistema após a execução do caso de uso) estão claramente descritas? | Sim | A pós-condição está claramente descrita. |
| 7 | O fluxo principal de eventos (caminho básico) está detalhado de forma sequencial e lógica? | Sim | O fluxo principal está detalhado de forma sequencial e lógica. |
| 8 | Existem fluxos alternativos ou secundários descritos para situações excepcionais ou variantes do fluxo principal? | Sim | Existem fluxos alternativos descritos. |
| 9 | Existem fluxos de exceção claramente descritos para lidar com erros ou condições inesperadas? | Sim | Existem fluxos de exceção descritos. |
| 10 | Todos os elementos do caso de uso estão devidamente documentados (título, descrição, atores, pré-condições, pós-condições, fluxos, etc.)? | Sim | Todos os elementos estão devidamente documentados. |
<br>

Autor: [Bruno Araújo](https://github.com/brunocva)

</details>

<details>
<summary>Buscar por documentos perdidos</summary>

### Tabela 6: Tabela de verificação para Buscar por documentos perdidos

| Número da Pergunta | Pergunta                                                                 | Resposta |
|--------------------|--------------------------------------------------------------------------|----------|
| 1                  | O caso de uso está descrito de forma clara e precisa, evitando ambiguidades? |          |
| 2                  | O caso de uso possui um identificador único e um nome descritivo?         |          |
| 3                  | Os atores que interagem com o sistema estão claramente identificados e descritos? |          |
| 4                  | O objetivo ou finalidade do caso de uso está claramente definido?         |          |
| 5                  | As pré-condições (estado do sistema antes do início do caso de uso) estão claramente descritas? |          |
| 6                  | As pós-condições (estado do sistema após a execução do caso de uso) estão claramente descritas? |          |
| 7                  | O fluxo principal de eventos (caminho básico) está detalhado de forma sequencial e lógica? |          |
| 8                  | Existem fluxos alternativos ou secundários descritos para situações excepcionais ou variantes do fluxo principal? |          |
| 9                  | Existem fluxos de exceção claramente descritos para lidar com erros ou condições inesperadas? |          |
| 10                 | Todos os elementos do caso de uso estão devidamente documentados (título, descrição, atores, pré-condições, pós-condições, fluxos, etc.)? |          |

<br>

Autor: [Iago Passaglia](https://github.com/paxxaglia)

</details>

<details>
<summary>Mudar endereço de recebimento</summary>

### Tabela 7: Tabela de verificação para Mudar endereço de recebimento

| Número da Pergunta | Pergunta                                                                 | Resposta |
|--------------------|--------------------------------------------------------------------------|----------|
| 1                  | O caso de uso está descrito de forma clara e precisa, evitando ambiguidades? |          |
| 2                  | O caso de uso possui um identificador único e um nome descritivo?         |          |
| 3                  | Os atores que interagem com o sistema estão claramente identificados e descritos? |          |
| 4                  | O objetivo ou finalidade do caso de uso está claramente definido?         |          |
| 5                  | As pré-condições (estado do sistema antes do início do caso de uso) estão claramente descritas? |          |
| 6                  | As pós-condições (estado do sistema após a execução do caso de uso) estão claramente descritas? |          |
| 7                  | O fluxo principal de eventos (caminho básico) está detalhado de forma sequencial e lógica? |          |
| 8                  | Existem fluxos alternativos ou secundários descritos para situações excepcionais ou variantes do fluxo principal? |          |
| 9                  | Existem fluxos de exceção claramente descritos para lidar com erros ou condições inesperadas? |          |
| 10                 | Todos os elementos do caso de uso estão devidamente documentados (título, descrição, atores, pré-condições, pós-condições, fluxos, etc.)? |          |

<br>

Autor: [Iago Passaglia](https://github.com/paxxaglia)

</details>


## Bibliografia
   
1. Artigo Especificação de Casos de Uso - Engenharia de Software 32 Disponível em: <https://www.devmedia.com.br/especificacao-de-casos-de-uso-engenharia-de-software-32/19012>


## Histórico de Versões

| Versão | Descrição                     | Autor           | Revisor | Data       |
|--------|-------------------------------|-----------------|------------|---------|
| 1.0    | Adição de introdução, metodologia e tabela de avaliação | Iago Passaglia  | Bruno Araújo | 09/06/2024 |
| 1.1    | Adição da avaliação do caso de uso de Realizar compras na loja online| Luana Medeiros  | Bruno Araújo | 10/06/2024 |
| 1.2    | Adição da avaliação do caso de uso de Calcular preços e prazos de entrega | Larissa Stéfane  | Bruno Araújo| 10/06/2024 |
| 1.3| Adição da avaliação do caso de uso Rastrear Encomendas | Bruno Araújo  | -- | 10/06/2024 |
