# Verificação dos Cenários

## Sumário
* [Introdução](#Introdução)
* [Metodologia](#Metodologia)
* [Lista de Verificação](#Lista-de-Verificação)
* [Avaliação](#Avaliação)
* [Conclusão e Observações](#Conclusão-e-Observações)
* [Referências Bibliográficas](#Referências-Bibliográficas)
* [Histórico de versão](#Histórico-de-versão)


## Introdução

Este documento tem como objetivo apresentar a verificação e a avaliação dos [cenários elaborados no projeto dos Correios](https://requisitos-de-software.github.io/2024.1-Correios/modelagem/cenarios/) desenvolvido pelo grupo 3. Desse modo, para garantir a conformidade dos cenários com os padrões estabelecidos, foi criada uma lista de verificação baseada em referências acadêmicas e práticas na área de engenharia de requisitos. Com isso, esta lista de verificação será utilizada para revisar detalhadamente cada cenário, assegurando que todos os elementos essenciais estejam presentes e adequadamente descritos.

## Metodologia

Inicialmente, a integrante [Larissa Stéfane](https://github.com/SkywalkerSupreme) será responsável por elaborar a lista de verificações, que servirá como base para a análise dos cenários do projeto dos Correios. Em seguida, cada integrante da nossa equipe, o grupo 2, ficará responsável por avaliar ao menos um cenário específico do projeto dos Correios utilizando a lista de verificação elaborada. Durante a avaliação, os integrantes documentarão suas observações.

## Lista de Verificação

A tabela 1 apresenta a lista de verificação para os [cenários do projeto dos correios](https://requisitos-de-software.github.io/2024.1-Correios/modelagem/cenarios/) com base em pontos citados em livros e artigos.

Esses livros e artigos podem ser acessados por meio dos links na coluna **Rastreabilidade**.

<center>

**Tabela 1:** Lista de verificação para os cenários


| ID | Pergunta da Verificação | Explicação | Rastreabilidade |
|----|------------------------|-----------------------|-----------------|
| 1  | O título do cenário representa explicitamente o tema? | É necessário que o título do cenário seja descritivo e forneça uma ideia clara do conteúdo do cenário. | [Cenários - PUC-Rio](https://www-di.inf.puc-rio.br/~julio/bnncap3.pdf) |
| 2  | O objetivo do cenário está claramente definido? | Certificar-se de que os objetivos que motivam as ações realizadas pelos atores estão definidos na descrição do cenário. | [Cenários - PUC-Rio](https://www-di.inf.puc-rio.br/~julio/bnncap3.pdf)  e Interação Humano-Computador e Expectativas dos Usuários – Capítulo 8, página 172 |
| 3  | O contexto do cenário está bem descrito, incluindo pré-condições, local e tempo? | Verificar se o contexto do cenário fornece informações suficientes sobre a situação, as pré-condições, o local e o tempo. | [Cenários - PUC-Rio](https://www-di.inf.puc-rio.br/~julio/bnncap3.pdf) |
| 4  | Os recursos envolvidos no cenário estão identificados? | Os recursos, ou seja, os objetos com os quais  os atores lidam precisam estar identificados. | [Cenários - PUC-Rio](https://www-di.inf.puc-rio.br/~julio/bnncap3.pdf) |
| 5  | Os atores envolvidos no cenário estão definidos? | Verificar se os atores, ou seja, as pessoas ou estruturas organizacionais que têm um papel no cenário, estão identificados de acordo com a sua característica principal. Por exemplo, Cidadão usuário do aplicativo dos correios. | [Cenários - PUC-Rio](https://www-di.inf.puc-rio.br/~julio/bnncap3.pdf) e Interação Humano-Computador e Expectativas dos Usuários – Capítulo 8, página 172|
| 6  | Os episódios do cenário estão bem definidos? | Certificar-se de que cada episódio do cenário representa uma ação realizada por um ator, incluindo outros atores envolvidos e os recursos utilizados, ou seja, mostra o passo a passo para o cenário se concretizar. | [Cenários - PUC-Rio](https://www-di.inf.puc-rio.br/~julio/bnncap3.pdf) |
| 7 | As ações dos atores estão descritas de forma observável? | Certificar-se de que as ações dos atores são descritas de forma clara e sequêncial para o contexto do cenário, assim, não há nenhuma falta de algum passo.  | Interação Humano-Computador e Expectativas dos Usuários – Capítulo 8, página 172 |
| 8  | As restrições e as exceções dos episódios estão explicitadas? | É necessário que as restrições e as  exceções que afetam os episódios do cenário estejam explicitadas e detalhadas | [Cenários - PUC-Rio](https://www-di.inf.puc-rio.br/~julio/bnncap3.pdf) |
| 9  | O ambiente ou contexto do cenário está detalhado? | Verificar se os detalhes do ambiente ou do contexto que motivam ou explicam os objetivos, as ações e as reações dos atores do cenário estão descritos. | Interação Humano-Computador e Expectativas dos Usuários – Capítulo 8, página 172|
| 10 | O cenário está escrito em linguagem natural simples? | Verificar se o cenário está escrito em linguagem natural simples,  ou seja, se a compreensão por parte dos leitores é fluida e não confusa. | [Retraining: Requirements Engineering](https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-cenarios) |
| 11 | Há a descrição do que o sistema e os usuários esperam quando o cenário se finalizar ?| É necessário ter a explicação do que acontece no final do cenário | [Retraining: Requirements Engineering](https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-cenarios) |
| 12 | As possíveis falhas e as suas tratativas estão descritas? | Verificar se as possíveis falhas que podem ocorrer durante o cenário e as suas tratativas estão descritas na narrativa. | [Retraining: Requirements Engineering](https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-cenarios) |
| 13 | As informações sobre acontecimentos que podem ocorrer durante o cenário estão incluídas? | Verificar se acontecimentos que podem acontecer durante os episódios do cenário estão incluídos na descrição do cenário. | [Retraining: Requirements Engineering](https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-cenarios) |
| 14 | Há uma descrição sobre o estado inicial e o final do contexto no cenário? | Certificar-se de que o estado inicial e final estejam descritos. | [Retraining: Requirements Engineering](https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-cenarios) |
| 15 | Os requisitos presentes estão descritos no cenário? | Verificar se os requisitos ou as funcionalidades e os serviços esperados do sistema estão descritos e com rastreabilidade no projeto. | [Uso de cenários para especificação de requisitos de qualidade e avaliação de arquitetura](https://www.devmedia.com.br/uso-de-cenarios-para-especificacao-de-requisitos-de-qualidade-e-avaliacao-de-arquitetura/22528) |

**Autora:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>


## Avaliação

<details>
  <summary size="20"><b> Cenário 1 - Calcular preços e prazos de entrega </b></summary> 

  <br>

A tabela 2 mostra a avaliação do cenário de calcular preços e prazos de entrega.

**Tabela 2**: Avaliação do cenário de calcular preços e prazos de entrega.

<br>

| ID | Pergunta | Resposta <br> Sim/Não/Incompleto | Observação |
|--------|-------------------------------| ---------| ---------| 
|    1    | O título do cenário representa explicitamente o tema? | Sim | - | 
|    2    | O objetivo do cenário está claramente definido? | Sim | - |
|    3    | O contexto do cenário está bem descrito, incluindo pré-condições, local e tempo? | Sim | - |
|    4    | Os recursos envolvidos no cenário estão identificados? | Sim | -. |
|    5    | Os atores envolvidos no cenário estão definidos?| Sim | - |
|    6    | Os episódios do cenário estão bem definidos? | Sim | - |
|    7    | As ações dos atores estão descritas de forma observável? | Incompleto | Falta detalhamento dos passos seguidos pelo autor |
|    8    | As restrições e as exceções dos episódios estão explicitadas? | Incompleto | Falta restrições, poderia ser mais completo |
|    9    | O ambiente ou contexto do cenário está detalhado? | Não | Falta especificar o motivo do usuário querer executar tal ação |
|    10   | O cenário está escrito em linguagem natural simples? | Sim | - |
|    11   | Há a descrição do que o sistema e os usuários esperam quando o cenário se finalizar ? | Incompleto | Falta detalhamento da expectativa do usuário |
|    12   | As possíveis falhas e as suas tratativas estão descritas? | Incompleto |  Não possui possíveis soluções para as falhas |
|    13   | As informações sobre outras atividades que podem acontecer ao mesmo tempo estão incluídas? | Sim | - | 
|    14   | Há uma descrição sobre o estado inicial e o final do contexto no cenário? | Incompleto | Falta detalhamento do contexto, não é possível identificar com clareza o estado inicial nem o estado final do contexto |
|    15   | Os requisitos presentes estão descritos no cenário? | Não | Não possui indicação de qual/quais requisitos estão ligados a ação de calcular preços e prazos de entrega |
<br>

**Autora:** [Luana Medeiros](https://github.com/LuaMedeiros)

</details>

<details>
  <summary size="20"><b> Cenário 2 - Mudar endereço de recebimento </b></summary> 

  <br>

A tabela 3 mostra a avaliação do cenário de mudar endereço de recebimento.

**Tabela 3**: Avaliação do cenário de mudar endereço de recebimento.

<br>

| ID | Pergunta | Resposta <br> Sim/Não/Incompleto | Observação |
|--------|-------------------------------| ---------| ---------| 
|    1    | O título do cenário representa explicitamente o tema? | Sim | - | 
|    2    | O objetivo do cenário está claramente definido? | Sim | - |
|    3    | O contexto do cenário está bem descrito, incluindo pré-condições, local e tempo? | Sim | - |
|    4    | Os recursos envolvidos no cenário estão identificados? | Sim | - |
|    5    | Os atores envolvidos no cenário estão definidos?| Sim | - |
|    6    | Os episódios do cenário estão bem definidos? | Sim | - |
|    7    | As ações dos atores estão descritas de forma observável? | Sim | - |
|    8    | As restrições e as exceções dos episódios estão explicitadas? | Sim | - |
|    9    | O ambiente ou contexto do cenário está detalhado? | Incompleto | Falta detalhar o ambiente de forma mais clara |
|    10   | O cenário está escrito em linguagem natural simples? | Sim | - |
|    11   | Há a descrição do que o sistema e os usuários esperam quando o cenário se finalizar ? | Sim | - |
|    12   | As possíveis falhas e as suas tratativas estão descritas? | Sim | - |
|    13   | As informações sobre outras atividades que podem acontecer ao mesmo tempo estão incluídas? | Não | Não menciona atividades simultâneas |
|    14   | Há uma descrição sobre o estado inicial e o final do contexto no cenário? | Incompleto | Estado inicial e final poderiam ser mais detalhados |
|    15   | Os requisitos presentes estão descritos no cenário? | Não | Não possui indicação de quais requisitos estão ligados a ação de mudar endereço de recebimento |
<br>

**Autor:** [Bruno Araújo](https://github.com/brunocva)

</details>

<details>
  <summary size="20"><b> Cenário 3 - Realizar compras na loja online </b></summary> 

  <br>

A tabela 4 mostra a avaliação do cenário de Realizar compras na loja online.

**Tabela 4**: Avaliação do cenário de Realizar compras na loja online.

<br>

| ID | Pergunta | Resposta <br> Sim/Não/Incompleto | Observação |
|--------|-------------------------------| ---------| ---------| 
|    1    | O título do cenário representa explicitamente o tema? | Sim | O título explica bem a ação desenvolvida no cenário. | 
|    2    | O objetivo do cenário está claramente definido? | Sim | - |
|    3    | O contexto do cenário está bem descrito, incluindo pré-condições, local e tempo? | Sim | Possui todos os requisitos. |
|    4    | Os recursos envolvidos no cenário estão identificados? | Sim |  |
|    5    | Os atores envolvidos no cenário estão definidos?| Sim | Os atores estão indicados e bem descritos. |
|    6    | Os episódios do cenário estão bem definidos? | Sim | - |
|    7    | As ações dos atores estão descritas de forma observável? | Sim | - |
|    8    | As restrições e as exceções dos episódios estão explicitadas? | Incompleto | As restrições poderiam ser melhor detalhadas |
|    9    | O ambiente ou contexto do cenário está detalhado? | Sim | - |
|    10   | O cenário está escrito em linguagem natural simples? | Sim | - |
|    11   | Há a descrição do que o sistema e os usuários esperam quando o cenário se finalizar ? | Não | Não há descrição da expectativa do usuário ao fim do cenário. |
|    12   | As possíveis falhas e as suas tratativas estão descritas? | Sim |  Na parte de excessões |
|    13   | As informações sobre outras atividades que podem acontecer ao mesmo tempo estão incluídas? | Não | - | 
|    14   | Há uma descrição sobre o estado inicial e o final do contexto no cenário? | Incompleto | Está descrito de maneira sucinta. |
|    15   | Os requisitos presentes estão descritos no cenário? | Não | Não informa quais requisitos estão presentes no cenário. |
<br>

**Autora:** [Pedro Izarias](https://github.com/Izarias)

</details>

<details>
  <summary size="20"><b> Cenário 4 - Rastreamento de Encomendas - Larissa Stéfane </b></summary> 

  <br>

A tabela 5 mostra a avaliação do cenário de rastreamento de encomendas.

**Tabela 5**: Avaliação do cenário de rastreamento de encomendas.

<br>

| ID | Pergunta                      | Resposta <br> Sim/Não/Incompleto | Observação |
|--------|-------------------------------| ---------| ---------| 
|    1    | O título do cenário representa explicitamente o tema? | Sim | - | 
|    2    | O objetivo do cenário está claramente definido? | Sim | - |
|    3    | O contexto do cenário está bem descrito, incluindo pré-condições, local e tempo? | Sim | - |
|    4    | Os recursos envolvidos no cenário estão identificados? | Incompleto | Os recursos não abrangem todas as possibilidades. Por exemplo, poderia se adicionar o uso de tablets. |
|    5    | Os atores envolvidos no cenário estão definidos?| Sim | - |
|    6    | Os episódios do cenário estão bem definidos? | Incompleto | Os espisódios poderiam ter mais passos mostrando o que o usuário realiza e explicá-los melhor. Por exemplo, a parte de inserir o código poderia ser mais explicada. |
|    7    | As ações dos atores estão descritas de forma observável? | Incompleto | Os episódios estão bem apresentados, mas poderiam ser mais completos. |
|    8    | As restrições e as exceções dos episódios estão explicitadas? | Incompleto | Algumas restrições faltaram, por exemplo, o aplicativo precisa estar atualizado. |
|    9    | O ambiente ou contexto do cenário está detalhado? | Não | Faltou um campo ou um tópico explicando o porquê desse cenário ser relevante para o projeto. Não há uma explicação do porquê o usuário se sente motivado a realizar. |
|    10   | O cenário está escrito em linguagem natural simples? | Sim | - |
|    11   | Há a descrição do que o sistema e os usuários esperam quando o cenário se finalizar ? | Não | No início do cenário, na sua apresentação/contextualização não foi mostrado o que se espera no final, ou seja, não tem como comparar se o que acontece no final dos episodios realmente é o que realmente se espera com os objetivos. |
|    12    | As possíveis falhas e as suas tratativas estão descritas? | Incompleto |  Não há as tratativas/soluções. |
|    13    | As informações sobre outras atividades que podem acontecer ao mesmo tempo estão incluídas? | Sim | - | 
|    14   | Há uma descrição sobre o estado inicial e o final do contexto no cenário? | Incompleto | Pois essas informações não estão explicitas e é algo que o leitor tira as próprias conclusões. Poderia-se adicionar esses tópicos para deixar esses pontos mais explicados e detalhados. |
|    15   | Os requisitos presentes estão descritos no cenário? | Não | Não há uma rastreabilidade ou indicação de qual requisito que pede para fazer o rastreamento de encomendas. |
<br>

**Autora:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

Para realizar a avaliação do cenário 4, de rastreamento de encomendas, foi gravado um vídeo da avaliação, que se encontra no vídeo 1.

**Vídeo 1:** Verificação do cenário de rastreamento de encomendas.

<iframe width="1280" height="720" src="https://www.youtube.com/embed/jFZn7e4QQOc" title="Requisitos - Verificação - Verificação do cenário 4 do projeto dos correios." frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**Autora:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

Caso o vídeo não funcione, abra pelo [link](https://youtu.be/jFZn7e4QQOc)


</details>


<details>
  <summary size="20"><b> Cenário 5 -  Buscar por documentos perdidos </b></summary> 

  <br>

A tabela 6 mostra a avaliação do cenário de Buscar por documentos perdidos.

**Tabela 6**: Avaliação do cenário de  Buscar por documentos perdidos.

<br>

| ID | Pergunta | Resposta <br> Sim/Não/Incompleto | Observação |
|--------|-------------------------------| ---------| ---------| 
|    1    | O título do cenário representa explicitamente o tema? | Sim | - | 
|    2    | O objetivo do cenário está claramente definido? | Sim | - |
|    3    | O contexto do cenário está bem descrito, incluindo pré-condições, local e tempo? | Sim | - |
|    4    | Os recursos envolvidos no cenário estão identificados? | Sim | -. |
|    5    | Os atores envolvidos no cenário estão definidos?| Sim | - |
|    6    | Os episódios do cenário estão bem definidos? | Sim | - |
|    7    | As ações dos atores estão descritas de forma observável? | Sim | - |
|    8    | As restrições e as exceções dos episódios estão explicitadas? | Sim | |
|    9    | O ambiente ou contexto do cenário está detalhado? | Não | Não há motivo para o usuário usar a funcionalidade |
|    10   | O cenário está escrito em linguagem natural simples? | Sim | - |
|    11   | Há a descrição do que o sistema e os usuários esperam quando o cenário se finalizar ? | Incompleto | Não há expectativa do usuário |
|    12   | As possíveis falhas e as suas tratativas estão descritas? | Incompleto |  - |
|    13   | As informações sobre outras atividades que podem acontecer ao mesmo tempo estão incluídas? | Sim | - | 
|    14   | Há uma descrição sobre o estado inicial e o final do contexto no cenário? | Não | Não é possível encontrar a descrição sobre o estado no contexto do cenário |
|    15   | Os requisitos presentes estão descritos no cenário? | Não |Não há rastreabilidade quanto aos requisitos |
<br>

**Autora:** [Iago Passaglia](https://github.com/Paxxaglia)

</details>


<details>
  <summary size="20"><b> Cenário 6 -  Gerenciar minhas importações </b></summary> 

  <br>

A tabela 7 mostra a avaliação do cenário de Gerenciar minhas importações.

**Tabela 7**: Avaliação do cenário de Gerenciar minhas importações.

<br>

| ID | Pergunta | Resposta <br> Sim/Não/Incompleto | Observação |
|--------|-------------------------------| ---------| ---------| 
|    1    | O título do cenário representa explicitamente o tema? | Sim | - | 
|    2    | O objetivo do cenário está claramente definido? | Sim | - |
|    3    | O contexto do cenário está bem descrito, incluindo pré-condições, local e tempo? | Sim | - |
|    4    | Os recursos envolvidos no cenário estão identificados? | Sim | - |
|    5    | Os atores envolvidos no cenário estão definidos? | Sim | - |
|    6    | Os episódios do cenário estão bem definidos? | Sim | - |
|    7    | As ações dos atores estão descritas de forma observável? | Sim | - |
|    8    | As restrições e as exceções dos episódios estão explicitadas? | Sim | |
|    9    | O ambiente ou contexto do cenário está detalhado? | Não | - |
|    10   | O cenário está escrito em linguagem natural simples? | Sim | - |
|    11   | Há a descrição do que o sistema e os usuários esperam quando o cenário se finalizar ? | Não | - |
|    12   | As possíveis falhas e as suas tratativas estão descritas? | Não |  - |
|    13   | As informações sobre outras atividades que podem acontecer ao mesmo tempo estão incluídas? | Sim | - | 
|    14   | Há uma descrição sobre o estado inicial e o final do contexto no cenário? | Não | Não é possível encontrar a descrição sobre o estado no contexto do cenário |
|    15   | Os requisitos presentes estão descritos no cenário? | Não |Não há rastreabilidade quanto aos requisitos |
<br>

<b> Autor: </b> <a href="https://github.com/brenoalexandre0/"> Breno Alexandre </a>.

</details>

<details>
  <summary size="20"><b> Cenário 7 -  Receber em um local não residencial </b></summary> 

  <br>

A tabela 8 mostra a avaliação do cenário de Receber em um local não residencial.

**Tabela 8**: Avaliação do cenário de Receber em um local não residencial.

<br>

| ID | Pergunta | Resposta <br> Sim/Não/Incompleto | Observação |
|--------|-------------------------------| ---------| ---------| 
|    1    | O título do cenário representa explicitamente o tema? | Sim | - | 
|    2    | O objetivo do cenário está claramente definido? | Sim | - |
|    3    | O contexto do cenário está bem descrito, incluindo pré-condições, local e tempo? | Sim | - |
|    4    | Os recursos envolvidos no cenário estão identificados? | Sim | - |
|    5    | Os atores envolvidos no cenário estão definidos? | Sim  | - |
|    6    | Os episódios do cenário estão bem definidos? | Sim | - |
|    7    | As ações dos atores estão descritas de forma observável? | Sim | - |
|    8    | As restrições e as exceções dos episódios estão explicitadas? | Sim | |
|    9    | O ambiente ou contexto do cenário está detalhado? | Não | - |
|    10   | O cenário está escrito em linguagem natural simples? | Sim | - |
|    11   | Há a descrição do que o sistema e os usuários esperam quando o cenário se finalizar ? | Não | - |
|    12   | As possíveis falhas e as suas tratativas estão descritas? | Não |  - |
|    13   | As informações sobre outras atividades que podem acontecer ao mesmo tempo estão incluídas? | Sim | - | 
|    14   | Há uma descrição sobre o estado inicial e o final do contexto no cenário? | Não | Não é possível encontrar a descrição sobre o estado no contexto do cenário |
|    15   | Os requisitos presentes estão descritos no cenário? | Não |Não há rastreabilidade quanto aos requisitos |
<br>

<b> Autor: </b> <a href="https://github.com/brenoalexandre0/"> Breno Alexandre </a>.

</details>


<details>
  <summary size="20"><b> Cenário 8 - Realizar pré-postagem </b></summary> 

  <br>

A tabela 9 mostra a avaliação do cenário de Realizar pré-postagem

**Tabela 9**: Avaliação do cenário de Realizar pré-postagem

<br>

| ID | Pergunta | Resposta <br> Sim/Não/Incompleto | Observação |
|--------|-------------------------------| ---------| ---------| 
|    1    | O título do cenário representa explicitamente o tema? | sim | - | 
|    2    | O objetivo do cenário está claramente definido? | sim | - |
|    3    | O contexto do cenário está bem descrito, incluindo pré-condições, local e tempo? | Sim | - |
|    4    | Os recursos envolvidos no cenário estão identificados? |  Sim | -. |
|    5    | Os atores envolvidos no cenário estão definidos?| Sim | - |
|    6    | Os episódios do cenário estão bem definidos? | Sim | - |
|    7    | As ações dos atores estão descritas de forma observável? |  Sim | - |
|    8    | As restrições e as exceções dos episódios estão explicitadas? |  |-|
|    9    | O ambiente ou contexto do cenário está detalhado? | Sim|- |
|    10   | O cenário está escrito em linguagem natural simples? | Sim | - |
|    11   | Há a descrição do que o sistema e os usuários esperam quando o cenário se finalizar ? | Sim | - |
|    12   | As possíveis falhas e as suas tratativas estão descritas? | Incompleto | Não há trativas para possiveis falhas |
|    13   | As informações sobre outras atividades que podem acontecer ao mesmo tempo estão incluídas? | Não | - | 
|    14   | Há uma descrição sobre o estado inicial e o final do contexto no cenário? | Sim | - |
|    15   | Os requisitos presentes estão descritos no cenário? | Não | - |
<br>

**Autor:** [Caio Mesquita Vieira]()

</details>


## Conclusão e Observações

## Referências Bibliográficas

1. Cenários. PUC-RIO. Disponível em: <https://www-di.inf.puc-rio.br/~julio/bnncap3.pdf> . Acesso em 09 junnho de 2024.

2. Cenários. Retraining: Requirements Engineering. Disponível em: <https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-cenarios> . Acesso em 09 junnho de 2024.

3. Interação Humano-Computador e Experiência do Usuário. Simone Diniz Junqueira Barbosa edição de 03 de maio de 2021.

4. Uso de cenários para especificação de requisitos de qualidade e avaliação de arquitetura. DevMedia. Disponível em: <https://www.devmedia.com.br/uso-de-cenarios-para-especificacao-de-requisitos-de-qualidade-e-avaliacao-de-arquitetura/22528> . Acesso em 09 junnho de 2024.

5. VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira de. Engenharia de Software de Requisitos – Software Orientado ao Negócio. Editoras FATTOS e Brasport. Disponível em: <https://analisederequisitos.com.br/wp-content/uploads/2023/06/engenharia-de-requisitos-software-orientado-ao-negocio.pdf> . Acesso em 09 junnho de 2024.

   

## Histórico de versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Adição da tabela de verificação | Larissa Stéfane | - | 09/06/2024 |
| 1.1 | Adição da introdução e da metodologia | Larissa Stéfane | - | 09/06/2024 |
| 1.2 | Adição da avaliação do cenário de rastreamento de encomendas | Larissa Stéfane | - | 10/06/2024 |
| 1.3 | Adição do vídeo da  avaliação do cenário de rastreamento de encomendas | Larissa Stéfane | - | 10/06/2024 |
| 1.4 | Adição da avaliação do cenário de calcular preços e prazos de entrega | Luana Medeiros | Pedro Izarias | 10/06/2024 |
| 1.5 | Adição da avaliação do cenário de calcular Realizar compras na loja online | Pedro Izarias | Iago Passaglia | 10/06/2024 |
| 1.6 | Adição da avaliação do cenário de Buscar por documentos perdidos | Iago Passaglia  | Pedro Izarias | 10/06/2024 |
| 1.7 | Adição da avaliação do cenário de Gerenciar minhas importações e Receber em um local não residencial | Breno Alexandre | -   | 10/06/2024 |
| 1.7 | Adição da avaliação do cenário de Realizar pré-postagem | Caio Mesquita | -   | 10/06/2024 |
