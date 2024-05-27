# NFR Framework

## Sumário
* [Introdução](#Introdução)
* [O que é NFR?](#O-que-é-NFR?)
* [O que é NFR framework?](#O-que-é-NFR-framework?)
* [Cartões de Especificação](#Cartões-de-Especificação)
* [Framework](#Framework)
* [Referências Bibliográficas](#Referências-Bibliográficas)
* [Histórico de Versão](#Histórico-de-Versão)
  
## Introdução

Este artefato tem como objetivo apresentar o framework de Requisitos Não Funcionais (RNF) para o desenvolvimento do aplicativo da Carteira de Trabalho Digital. Além disso, visa detalhar o cartão de especificação para os requisitos não funcionais identificados. Isso porque os RNF são fundamentais para garantir a qualidade, aeficiência e a usabilidade do aplicativo ao abordar  aspectos como desempenho, segurança, confiabilidade, entre outros. 

## O que é NFR?

Segundo a dissertação “Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados”¹, Mairiza, Zowghi e Nurmuliani (2010), definem que os requisitos não funcionais podem ser definidos a partir de duas perspectivas:

1. RNFs descrevem propriedades, características ou restrições que o sistema deve atender.

2. RNFs descrevem atributos de qualidade que o produto deve possuir.


## O que é NFR framework?

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

Para criar os cartões de especificação dos requisitos não funcionais, será utilizado o modelo [Volere](https://www.volere.org/wp-content/uploads/2018/12/template14_ptbra.pdf)², que oferece uma estrutura organizada e detalhada para capturar a maioria dos aspectos essenciais desses requisitos. Desse modo, inicialmente, será utilizado o código de identificação dos [requisitos não funcionais definidos na etapa de elicitação](Elicitacao/ResquisitosCorrigidos.md) com o intuito de garantir a sua rastreabilidade. Em seguida, será especificado o tipo de requisito (como desempenho, segurança, usabilidade, entre outros) para classificar adequadamente cada necessidade do sistema. Além disso, também haverá critérios de aceitação definidos para cada um deles, estabelecendo condições claras para a verificação da sua satisfação.

Cada cartão de especificação também incluirá a origem ou a fonte do requisito, pois terá como eles foram elicitados, por exemplo, [análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md). Além disso, serão documentadas as interdependências com outros requisitos ou componentes do sistema, o que ajudará a entender como os diferentes aspectos do sistema se relacionam. Ademais, com base na priorização dos requisitos, a prioridade de cada requisito será categorizada como alta, média ou baixa, auxiliando na gestão e na implementação das necessidades mais críticas. Assim, essa estrutura garantirá que os requisitos não funcionais sejam claramente definidos, compreendidos e ajudará a que eles sejam implementados de forma eficaz.

### Template

Para ser mais fácil de ser visualizado e planejado, a tabela 1 mostra o Template do cartão de especificação que será utilizado.

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

### Cartões de Especfiicação de Restrições de Design

Abaixo, as tabelas de 2 a 5 mostram os cartões de especificação de design para as restrições de design.

<details>
  <summary size="20"><b> Padrões Tipográficos e de Siglas </b></summary> 
 
</center>

**Tabela 2:** Padrões Tipográficos e de Siglas

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [RNF05](Elicitacao/ResquisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Padrões Tipográficos e de Siglas                                                                                                                      |
| **Tipo de Requisito**      | Restrição de Design                                                                                                                                    |
| **Descrição**              | Todos os textos do sistema devem seguir os padrões tipográficos, de ícones e de siglas, abreviações e erros conforme as normas dispostas em [Tipografia](https://www.gov.br/ds/fundamentos-visuais/tipografia), [Iconografia](https://www.gov.br/ds/fundamentos-visuais/iconografia), [Espaçamento](https://www.gov.br/ds/fundamentos-visuais/espacamento),         [Densidade](https://www.gov.br/ds/padroes/design/densidade)                      |
| **Justificativa/Racionalidade** | É necessário garantir consistência e legibilidade em toda a interface do usuário para promover uma experiência de uso mais intuitiva e mais profissional. Para isso, deve-se Seguir os padrões tipográficos adequados que ajudam a evitar ambiguidades e erros de interpretação e são essenciais para a clareza e precisão na comunicação com os usuário.                   |
| **Critérios de Aceitação** |  <li> Em relação a tipografia, as fontes utilizadas devem ser “Raleway” ou “sans-serif” <li> Nenhuma fonte deve estar fora da escala definida no DS: Minor Third <li> O tamanho da fonte base é de 14px (1em) e peso da fonte normal (400). <li> A seleção de ícones deve estar de acordo com a coleção “Font Awesome“(versão 5.10.2) <li> Em relação ao espagamento, o comportamento das dimensões de um objeto é determinada pela regra: box-sizing: border-box, ou seja, as propriedades de largura (width) e de altura (height) incluem o tamanho do padding e do border, mas não incluem a margin. <li> Quando houver dois ou mais elementos posicionados horizontalmente ou verticalmente em sequência, deve-se evitar somar as margens mínimas de segurança destes elementos. <li>    A escala de densidade é uma gradação de valores que varia de 4px em 4px e pode crescer ou diminuir sem limites, de acordo com a necessidade.  </ul>                                                      |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                       |
| **Prioridade**             | Média Prioridade                                                                                                                                              |
| **Interdependências**      | RNF06 (Conformidade com manuais de interface gov.br)                                                                                                   |
| **Notas e Comentários**    | Há um conjunto de normas no site do gov para os aplicativos do governo e todas essas normas devem ser consideradas.                                               |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

</details>


### Cartões de Especificação de Usabilidade

### Cartões de Especificação Design de Desempenho

### Cartões de Especificação deInterface 

### Cartões de Acessiibilidade


### 

## Referências Bibliográficas

 1. SILVA, Reinaldo Antônio. **NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados**. Recife, 2019. Disponível em <http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER20/21_WER_2020_paper_36.pdf> Acessado em 26/05/2024

2. ROBERTSON, James; ROBERTSON, Suzanne. Modelo para Especificações de Requisitos. Edição 14. Associação Atlântica de Sistemas, agosto 2009. Disponível em <https://www.volere.org/wp-content/uploads/2018/12/template14_ptbra.pdf> Acessado em 26/05/2024 



## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 |  Adição da explicação do que é NFR e o que é framework  |   Larissa Stéfane  |  Iago Passaglia   |    26/05/2024   |
| 1.1 |  Adição da metodologia e do Template dos cartões de especificação  |   Larissa Stéfane  |  Iago Passaglia   |    26/05/2024   |
| 1.2 | Adicionar  Cartões de Especfiicação de Restrições de Design |   Larissa Stéfane  |  Iago Passaglia   |    26/05/2024   |
