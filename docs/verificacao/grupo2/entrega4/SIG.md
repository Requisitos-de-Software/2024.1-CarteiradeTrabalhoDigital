# Lista de Verificação de SIG Softgoal Interdependency Graph

## Sumário
* [Introdução](#Introdução)
* [Metodologia](#Metodologia)
* [Lista de Verificação](#Lista-de-Verificação)
* [Erros da Lista](#Erros-da-Lista)
* [Inspeção](#Inspeção)
* [Erros Encontrados](#Erros-Encontrados)
* [Referências Bibliográficas](#Referências-Bibliográficas)
* [Histórico de versão](#Histórico-de-versão)

## Introdução

Este documento apresenta uma lista de verificação para a análise dos SIG. Nesse contexto, através desta lista de verificação abrangente, busca-se assegurar que cada cartão de especificação atenda aos critérios de independência, negociabilidade, valor, estimabilidade, adequação entre outros ponto necessários. 

## Metodologia

A metodologia adotada para a avaliação dos SIG no projeto da Carteira de Trabalho Digital será fundamentada em uma abordagem sistemática. Assim, inicialmente, a integrante do grupo  irá estudar sobr eu assunto e criar uma lista de verificação. Em seguida, os outros integrantes do grupo irão avaliar as histórias de usuários. 

## Lista de Verificação

A tabela 2 mostra a lista de verificação dos SIGs.

<center>

**Tabela 2:** Lista de verificação para o SIG

| ID | Pergunta de Verificação                                              | Explicação                                                                                          | Rastreabilidade                              | Capturas de Tela |
 |----|----------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|----------------------------------------------|---- |
| 1  | Os softgoals NFR foram utilizados corretamente?                      | Verificar se os softgoals NFR representam os requisitos não funcionais e estão organizados de forma hierárquica no SIG. | [Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados – Páginas 31 e 32](https://repositorio.ufpe.br/bitstream/123456789/34150/1/DISSERTA%c3%87%c3%83O%20Reinaldo%20Ant%c3%b4nio%20da%20Silva.pdf) | [Captura de Tela](https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/ImagensDiagrama/imagensRastreabilidade/SIG/Screenshot%20from%202024-07-01%2015-06-47.png) |
| 2  | As interdependências entre os softgoals foram definidas corretamente? | Verificar se as relações entre os softgoals refletem com precisão como eles se influenciam mutuamente. | [Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados – Página 32](https://repositorio.ufpe.br/bitstream/123456789/34150/1/DISSERTA%c3%87%c3%83O%20Reinaldo%20Ant%c3%b4nio%20da%20Silva.pdf)          | [Captura de Tela](https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/ImagensDiagrama/imagensRastreabilidade/SIG/Screenshot%20from%202024-07-01%2015-07-43.png) |
| 3  | Os refinamentos dos softgoals foram feitos de forma adequada?         | Verificar se os softgoals sãor refinados conforme o necessário para detalhar as suas características e relações. | [Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados – Página 32](https://repositorio.ufpe.br/bitstream/123456789/34150/1/DISSERTA%c3%87%c3%83O%20Reinaldo%20Ant%c3%b4nio%20da%20Silva.pdf)        | <li> [Captura de Tela 01](https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/ImagensDiagrama/imagensRastreabilidade/SIG/Screenshot%20from%202024-07-01%2015-07-43.png) <br> <br> <li> [Captura de Tela 02](https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/ImagensDiagrama/imagensRastreabilidade/SIG/Screenshot%20from%202024-07-01%2015-08-15.png) |
| 4  | As contribuições dos softgoals descendentes foram identificadas corretamente? | É essencial entender como os softgoals inferiores contribuem para a satisfação dos softgoals superiores. | [Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados – Página 33](https://repositorio.ufpe.br/bitstream/123456789/34150/1/DISSERTA%c3%87%c3%83O%20Reinaldo%20Ant%c3%b4nio%20da%20Silva.pdf) | [Captura de Tela](https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/ImagensDiagrama/imagensRastreabilidade/SIG/Screenshot%20from%202024-07-01%2015-08-57.png) |
| 5  | Os rótulos atribuídos aos softgoals refletem adequadamente seu estado de satisfação? | Os rótulos como "satisfeito", "negado", "indeterminado", entre outros, devem refletir fielmente a condição dos softgoals no contexto do projeto. | [Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados – Página 38](https://repositorio.ufpe.br/bitstream/123456789/34150/1/DISSERTA%c3%87%c3%83O%20Reinaldo%20Ant%c3%b4nio%20da%20Silva.pdf)    | [Captura de Tela](https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/ImagensDiagrama/imagensRastreabilidade/SIG/Screenshot%20from%202024-07-01%2015-10-14.png) |
| 6  | A análise dos softgoals de nível mais baixo impacta de forma apropriada nos softgoals de nível mais alto? | Verificar se as decisões tomadas em níveis inferiores da hierarquia influenciam os softgoals em níveis superiores para garantir coerência no SIG. | [Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados – Página 37](https://repositorio.ufpe.br/bitstream/123456789/34150/1/DISSERTA%c3%87%c3%83O%20Reinaldo%20Ant%c3%b4nio%20da%20Silva.pdf)       | [Captura de Tela](https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/ImagensDiagrama/imagensRastreabilidade/SIG/Screenshot%20from%202024-07-01%2015-10-43.png) |
| 7  | Os softgoals de afirmação foram utilizados conforme necessário?         | Verificar se os softgoals de afirmação são empregados para justificar decisões de desenvolvimento e priorizar requisitos de forma apropriada. | [Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados – Página 31](https://repositorio.ufpe.br/bitstream/123456789/34150/1/DISSERTA%c3%87%c3%83O%20Reinaldo%20Ant%c3%b4nio%20da%20Silva.pdf)        |  [Captura de Tela](https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/ImagensDiagrama/imagensRastreabilidade/SIG/Screenshot%20from%202024-07-01%2015-06-47.png) |
| 8  | Os softgoals de operacionalização estão representando soluções de implementação de maneira adequada? | Veriicar se os softgoals de operacionalização descrevem as operações, os processos, as representações de dados, as estruturações ou as restrições no sistema alvo de forma clara. | [Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados – Página 33](https://repositorio.ufpe.br/bitstream/123456789/34150/1/DISSERTA%c3%87%c3%83O%20Reinaldo%20Ant%c3%b4nio%20da%20Silva.pdf)       | [Captura de Tela](https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/ImagensDiagrama/imagensRastreabilidade/SIG/Screenshot%20from%202024-07-01%2015-06-47.png) |
| 9  | As contribuições dos softgoals foram documentadas de maneira clara e concisa? | As contribuições devem ser explicadas de forma compreensível no SIG para facilitar a análise do impacto de cada softgoal. | [Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados – Página 31](https://repositorio.ufpe.br/bitstream/123456789/34150/1/DISSERTA%c3%87%c3%83O%20Reinaldo%20Ant%c3%b4nio%20da%20Silva.pdf)         | [Captura de Tela](https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/ImagensDiagrama/imagensRastreabilidade/SIG/Screenshot%20from%202024-07-01%2015-07-14.png) |
| 10 | O SIG mostra as decisões de desenvolvimento tomadas? | Verificar se o SIG serve como um registro das decisões de desenvolvimento, incluindo alternativas consideradas e justificativas associadas. | [Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados – Página 33](https://repositorio.ufpe.br/bitstream/123456789/34150/1/DISSERTA%c3%87%c3%83O%20Reinaldo%20Ant%c3%b4nio%20da%20Silva.pdf)  | [Captura de Tela](https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/ImagensDiagrama/imagensRastreabilidade/SIG/Screenshot%20from%202024-07-01%2015-08-15.png) |
| 11 | As relações entre os softgoals estão sendo representadas graficamente de acordo com as convenções estabelecidas? | A representação gráfica dos softgoals e suas interdependências deve seguir padrões definidos para garantir clareza e compreensão. | [Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados – Páginas 34 e 35](https://repositorio.ufpe.br/bitstream/123456789/34150/1/DISSERTA%c3%87%c3%83O%20Reinaldo%20Ant%c3%b4nio%20da%20Silva.pdf)        | [Captura de Tela](https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/ImagensDiagrama/imagensRastreabilidade/SIG/Screenshot%20from%202024-07-01%2015-12-15.png) |


<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

</center>


## Erros da Lista

A tabela a seguir mostra os erros encontrados na lista de verficação, assim como os locais e as soluções usadas.

<center>

<b>Tabela 1:</b> Verificação da lista de verificação para NOME.

| Erro    | Explicação | Local | Solução |
| ------- | ---------- | ----- | ------- |
| erroTal | explicacao | local | solucao |

<b>Autor:</b> <a href="https://github.com/nome">Nome</a>.

</center>

## Inspeção

<center>

Tabela 2: Identificação do artefato avaliado
 
| Entrega | Nome | Versão | Data de desenvolvimento | Autor(es) | Revisor |
| ------- | ---- | ------ | ----------------------- | --------- | ------- |
| ------- | ---- | ------ | ----------------------- | --------- | ------- |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

</center>

<center>

Tabela 3: Inspeção do questionário

| ID |  Pergunta | Resposta <br> Sim/Não/ Incompleto/ Não se aplica | Observação | 
| -- | ----------| ---------- | --------------- | 
| -- | ----------| ---------- | --------------- | 
| -- | ----------| ---------- | --------------- | 
| -- | ----------| ---------- | --------------- | 

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.


### Vídeo da inspeção

O vídeo a seguir a inspeção gravada sobre o artefato NOME.


### Erros Encontrados

A tabela a seguir mostra as sugestões de melhorias a cerca do artefato nomeArtefato.

<center>

<b>Tabela 4:</b> Sugestões de melhoria para NOME.

| ID |  Sugestões de melhoria | 
| -- | ---------------------- |
| 1  | sugestao/sugestoes     |

<b>Autor:</b> <a href="https://github.com/nome">Nome</a>.

</center>



## Referências Bibliográficas

1. Silva, R. A. (2019). NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Recife: Universidade Federal de Pernambuco. Disponível em <https://repositorio.ufpe.br/bitstream/123456789/34150/1/DISSERTA%c3%87%c3%83O%20Reinaldo%20Ant%c3%b4nio%20da%20Silva.pdf>. Acessado em 09 de junho de 2024.

2. James & Suzanne Robertson. Volere - Modelo para Especificações de Requisitos. 2009. Disponível em <https://www.volere.org/wp-content/uploads/2018/12/template14_ptbra.pdf>.  Acessado em 09 de junho de 2024.
   


## Histórico de versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Adição da tabela de verificação | Larissa Stéfane | Luana Medeiros | 30/06/2024 |
