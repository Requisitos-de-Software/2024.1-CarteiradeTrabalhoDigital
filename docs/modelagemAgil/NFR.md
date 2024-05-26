# NFR Framework

## Sumário

## Introdução

## O que é NFR?

Segundo a dissertação “Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados”¹, Mairiza, Zowghi e Nurmuliani (2010), definem que os requisitos não funcionais podem ser definidos a partir de duas perspectivas:

1. RNFs descrevem propriedades, características ou restrições que o sistema deve atender.

2. RNFs descrevem atributos de qualidade que o produto deve possuir.


## O que é NFR framework ?

Segundo a dissertação “Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados”¹, de Reinaldo Antônio da Silva, o NFR (Non-Functional Requirements) framework, criado por Chung em 2000, é uma abordagem utilizada para o tratamento de Requisitos Não-Funcionais (RNFs) no desenvolvimento de sistemas. Isso porque este framework tem o objetivo de proporcionar uma rica representação desses requisitos, das suas relações e das suas correlações, o que ajuda os desenvolvedores a implementarem soluções personalizadas que atendam às necessidades específicas do sistema em questão.

## Características principais do NFR framework

De acordo com Chung², Há três tipos de softgoals:

- **Softgoals NFR:** Representam os Requisitos Não-Funcionais.
  - Podem estar interrelacionados, organizados em catálogos e apresentados de forma hierárquica.

- **Softgoals de operacionalização**: Essas soluções incluem operações, processos, representações de dados, estruturações e restrições no sistema.

- **Softgoals de Afirmação:** permitem que as características do domínio (como prioridades e carga de trabalho) sejam consideradas e devidamente refletidas no processo de tomada de decisão.
  - Servem como justificativa para apoiar ou negar a forma como os softgoals são priorizados.

## Cartões de Especificação

### Metodologia

Para criar os cartões de especificação dos requisitos não funcionais, será utilizado o modelo [Volere](https://www.volere.org/wp-content/uploads/2018/12/template14_ptbra.pdf), que oferece uma estrutura organizada e detalhada para capturar a maioria dos aspectos essenciais desses requisitos. Desse modo, inicialmente, será utilizado o código de identificação dos [requisitos não funcionais definidos na etapa de elicitação](Elicitacao/ResquisitosCorrigidos.md) com o intuito de garantir a sua rastreabilidade. Em seguida, será especificado o tipo de requisito (como desempenho, segurança, usabilidade, entre outros) para classificar adequadamente cada necessidade do sistema. Além disso, também haverá critérios de aceitação definidos para cada um deles, estabelecendo condições claras para a verificação da sua satisfação.

Cada cartão de especificação também incluirá a origem ou a fonte do requisito, pois terá como eles foram elicitados, por exemplo, [análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md). Além disso, serão documentadas as interdependências com outros requisitos ou componentes do sistema, o que ajudará a entender como os diferentes aspectos do sistema se relacionam. Ademais, com base na priorização dos requisitos, a prioridade de cada requisito será categorizada como alta, média ou baixa, auxiliando na gestão e na implementação das necessidades mais críticas. Assim, essa estrutura garantirá que os requisitos não funcionais sejam claramente definidos, compreendidos e ajudará a que eles sejam implementados de forma eficaz.

### Templete

Para ser mais fácil de ser visualizado e planejado, a tabela 1 mostra o templete do cartão de especificação que será utilizado.

**Tabela 1:** Cartão de Especificação de Requisitos Não Funcionais

| **Elemento**               | **Detalhes**                            |
|----------------------------|-----------------------------------------|
| **Identificador**          | RNF + Número                                 |
| **Nome do Requisito**      |  -         |
| **Origem/Fonte**           | Parte interessada ou documento de origem|
| **Tipo de Requisito**      | Exemplo: Desempenho, Segurança, Usabilidade, entre outros|
| **Descrição**              | -      |
| **Justificativa/Racionalidade** | Razões para a existência do requisito, incluindo benefícios esperados |
| **Critérios de Aceitação** | Condições que definem a verificação do requisito |
| **Prioridade**             | [Alta, Média, Baixa]                    |
| **Interdependências**      | Relação com outros requisitos ou componentes do sistema |
| **Notas e Comentários**    | Informações adicionais ou contextuais   |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)


## Referências Bibliográficas

## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 |  Adição da explicação do que é NFR e o que é framework  |   Larissa Stéfane  |     |    26/05/2024   |
| 1.1 |  Adição da metodologia e do templete dos cartões de especificação  |   Larissa Stéfane  |     |    26/05/2024   |
