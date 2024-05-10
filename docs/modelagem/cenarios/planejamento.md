# Planejamento dos Cenários
## Sumário
* [Introdução](#Introdução)
* [Conceitos Básicos](#Conceitos-Básicos)
* [Cenários](#Cenários)
  * [Casos de Uso](#Casos-de-Uso)
  * [Inspirações](#Inspirações)
* [Metodologia](#Metodologia)
* [Templete](#Templete)
* [Cronograma](#Cronograma)
* [Conclusão](#Conclusão)
* [Bibliografia](#Bibliografia)
* [Referências Bibliográficas](#[Referências-Bibliográficas)
* [Histórico de versão](#Histórico-de-versão)

## Indrotução

Os cenários desempenham um papel crucial no desenvolvimento do projeto sobre aplicativo da carteira de trabalho digital, uma vez que eles representam situações reais de uso com base nos requisitos que foram elicitados. Dessa forma, é possível entender melhor as necessidades e expectativas dos usuários finais. Além disso, os cenários ajudam a antecipar possíveis problemas.

Com base nisso, este documento tem como objetivo fornecer uma estrutura clara para o desenvolvimento e análise dos cenários e casos de uso relacionados ao projeto. Para isso, será mostrado as inspirações provenientes de projetos anteriores, que servirão como base e a metodologia que será utilizada no desenvolvimento dos cenários.

## Conceitos Básicos
É fundamental estabelecer uma compreensão clara dos conceitos básicos de cenários e de casos de uso. Por isso há a explicação abaixo.

### Cenários
No livro [Engenharia de Requisitos – Software Orientado a Negócio](https://analisederequisitos.com.br/wp-content/uploads/2023/06/engenharia-de-requisitos-software-orientado-ao-negocio.pdf)^1, no capítulo 8, cenários são definidos como descrições detalhadas dos eventos e das condições que compõem um caso de uso específico. Sendo assim, cada cenário representa uma sequência de passos que se desdobram a partir de um evento inicial e das condições que influenciam o comportamento do sistema. Portanto, essas descrições abrangem desde o início até o término do caso de uso, delineando como e quando ele é iniciado, interage com os atores, mantém ou referencia dados e finaliza.

Com base nisso, é importante destacar que no contexto dos cenários, o termo "fluxo" também é utilizado para designar diferentes tipos de sequências de eventos, sendo subdividido em "Principal", "Alternativo" e "Exceção". O cenário principal representa o caminho feliz, enquanto os cenários alternativos e de exceção descrevem comportamentos complementares e associados a condições alternativas e excepcionais, respectivamente.

## Casos de Uso

Ainda de acordo com o livro, [Engenharia de Requisitos – Software Orientado a Negócio](https://analisederequisitos.com.br/wp-content/uploads/2023/06/engenharia-de-requisitos-software-orientado-ao-negocio.pdf)^1, os casos de uso são definidos como os casos de uso são definidos como representações detalhadas dos diversos cenários que um ator pode percorrer para alcançar um objetivo específico utilizando o sistema em questão. Com isso, cada caso de uso abrange um cenário principal, que descreve a sequência padrão de eventos, bem como possíveis cenários alternativos que refletem variações nesse processo. Essa abordagem permite uma compreensão holística das interações entre os usuários e o sistema, garantindo que todos os requisitos funcionais sejam adequadamente especificados.

## Inspirações

Para realizar os cenários, alguns projetos anteriores da disciplina e os documentos serão utilizados como base e inspiração.
Os projetos utilizados como inspiração serão:
- [Projeto Bilheteria Digital](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/) ^2
- [Projeto Tik Tok](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/) ^3
- [Projeto Simpletone](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/) ^4

Em relação aos documentos analisados, são:
- [SimulES)(https://www.dbd.puc-rio.br/depto_informatica/06_34_figueiredo.pdf) ^5

## Metodologia

Para desenvolver os cenários do projeto, será adotada uma estrutura que visa garantir a clareza e eficácia
na definição dos documentos dos cenários. Esta metodologia seguirá as seguintes etapas:
1. Seleção do Caso de Uso: Inicialmente, será feita uma análise dos casos de uso identificados no
escopo do projeto. Então, cada integrante escolherá dois casos para desenvolver.
2. Motivo da Escolha: Após a seleção do caso de uso, o motivo será explicado de forma breve. Isso pode
incluir sua importância para os usuários e a sua relevância para os objetivos do projeto.
3. Definição da Tabela de Dados: Em seguida, será criada uma tabela detalhada que compreende os seguintes elementos:
  -  **Título**: Nome do caso de uso.
  -  **Metas/Objetivo**: O que se espera alcançar com o caso de uso.
  -  **Contexto**: O ambiente ou situação em que o caso de uso ocorre.
  - **Atores**: As entidades externas que interagem com o sistema.
  - **Recursos**: Os recursos do sistema necessários para executar o caso de uso.
  - **Exceção**: Condições excepcionais que podem ocorrer durante a execução do caso de uso.
  - **Episódios**: A sequência de passos ou eventos que compõem o caso de uso.
  - **Narrativa dos Passos**: Com base na tabela de dados, de forma breve, serpa desenvolvida uma narrativa dos passos.

## Templete

Abaixo há o templete da estrutura dos documentos dos cenários.

<details>
<summary size="20"><b> Templete para cenários </b></summary>

  #### Título
  #### Introdução
  #### Motivo da Escolha do Caso de Uso
  #### Tabela de Cenários
  
  | Elemento | Descrição |
  |------------------|-----------------------------------------------------------------------|
  | Título | |
  | Metas/Objetivo | |
  | Contexto | |
  | Atores | |
  | Recursos | |
  | Exceção | |
  | Episódios | |
  
  #### 6. Narrativa dos Passos
  #### 7. Conclusão

</details>

## Cronograma
A tabela 1 mostra o cronograma do desenvolvimento dos cenários, em que cada integrante escolheu uma
ou duas funcionalidade para fazer o cenário.

Tabela 1: Planejamento 

| Funcionalidade | Responsável |
| -------------------- | ------------------ |
| - | Breno Alexandre |
| - | Breno Alexandre |
| - | Bruno Cunha |
| - | Bruno Cunha |
| - | Iago Passaglia |
| - | Iago Passaglia |
| - | Larissa Stéfane |
| - | Larissa Stéfane |
| - | Luana Lima|
| - | Luana Lima|
| - | Pedro Augusto |
| - | Pedro Augusto |

## Conclusão

Portanto, é evidente que uma metodologia estruturada é essencial para garantir a eficácia e a coerência na definição dos documentos dos cenários, pois isso permite que eles sejam elaborados de forma organizada e padronizada entre os integrantes da equipe.

## Referências Bibliográficas

1. Varquez, Carlos Eduardo; Simões, Guilherme Siqueira. Engenharia de Requisitos – Software Orientado a Negócio. Editoras Brasport e Fatto, 2023. Disponível em: https://analisederequisitos.com.br/wp-content/uploads/2023/06/engenharia-de-requisitos-software-orientado-ao-negocio.pdf. Acesso em: 7 maio 2024.

2. Requisitos de Software. Projeto Bilheteria Digital. Disponível em: https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/. Acesso em: 7 maio 2024.

3. Requisitos de Software. Projeto Tik Tok. Disponível em: https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/. Acesso em: 7 maio 2024.

4. Requisitos de Software. Projeto Simpletone. Disponível em: https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/. Acesso em: 7 maio 2024.

5. SimulES. Disponível em: https://www.dbd.puc-rio.br/depto_informatica/06_34_figueiredo.pdf. Acesso em: 7 maio 2024.

## Bibliografia

1. Milene e Mauricio Serrano. Slide da aula 10 de requisitos. Disponível em: https://aprender3.unb.br/pluginfile.php/2845027/mod_resource/content/1/Aula%2010.pdf . Acesso em: 7 maio 2024.

## Histórico de Versão
| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação e realização do documento | Larissa Stéfane | - | 07/05/2024 |
