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
  <summary size="20"><b> Cenário 5 - Rastreamento de Encomendas </b></summary> 

  <br>

A tabela dois mostra a avaliação do cenário de rastreamento de encomendas.

**Tabela 2**: Avaliação do cenário de rastreamento de encomendas.

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

Para realizar a avaliação do cenário 5, de rastreamento de encomendas, foi gravado um vídeo da avaliação, que se encontra no vídeo 1.

**Vídeo 1:** Verificação do cenário de rastreamento de encomendas.

<iframe width="1280" height="720" src="https://www.youtube.com/embed/jFZn7e4QQOc" title="Requisitos - Verificação - Verificação do cenário 5 do projeto dos correios." frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**Autora:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

Caso o vídeo não funcione, abra pelo [link](https://youtu.be/jFZn7e4QQOc)


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


