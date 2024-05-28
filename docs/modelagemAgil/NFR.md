# NFR Framework

## Sumário
* [Introdução](#Introdução)
* [O que é NFR?](#O-que-é-NFR?)
* [O que é NFR framework?](#O-que-é-NFR-framework?)
* [Requisitos Não Funcionais Elicitados Anteriormente](#Requisitos-Não-Funcionais-Elicitados-Anteriormente)
* [Cartões de Especificação](#Cartões-de-Especificação)
* [SIG ou Softgoal Interdependency Graph](#SIG-ou-Softgoal-Interdependency-Graph)
* [Os NFR framework](#Os-NFR-framework)
* [Referências Bibliográficas](#Referências-Bibliográficas)
* [Histórico de Versão](#Histórico-de-Versão)
  
## Introdução

Este artefato tem como objetivo apresentar o framework de Requisitos Não Funcionais (RNF) para o desenvolvimento do aplicativo da Carteira de Trabalho Digital, assim, aqui serão mostrados sos cartões de especificação e o Softgoal Interdependency Graph (SIG). Isso porque os RNF são fundamentais para garantir a qualidade, a eficiência e a usabilidade do aplicativo ao abordar  aspectos como desempenho, segurança, confiabilidade, restrições de design, entre outros.. 

## O que é NFR?

Segundo a dissertação “Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados”¹, Mairiza, Zowghi e Nurmuliani (2010), definem que os requisitos não funcionais podem ser definidos a partir de duas perspectivas:

1. RNFs descrevem propriedades, características ou restrições que o sistema deve atender.

2. RNFs descrevem atributos de qualidade que o produto deve possuir.


## O que é NFR framework?

Segundo a dissertação “Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados”¹, de Reinaldo Antônio da Silva, o NFR (Non-Functional Requirements) framework, criado por Chung em 2000, é uma abordagem utilizada para o tratamento de Requisitos Não-Funcionais (RNFs) no desenvolvimento de sistemas. Isso porque este framework tem o objetivo de proporcionar uma rica representação desses requisitos, das suas relações e das suas correlações, o que ajuda os desenvolvedores a implementarem soluções personalizadas que atendam às necessidades específicas do aplicativo da carteira de trabalho digital.

Para verificar os rameworks elaborasdos para o projeto, clique em [NFR framework](#Os-NFR-framework)

## Requisitos Não Funcionais Elicitados Anteriormente

Segue na tabela 1 a lista dos Requisitos Não-Funcionais elicitados anteriormente.

<details>
  <summary size="20"><b> Requisitos Não Funcionais </b></summary>

<center>

<p align="center"> <b>Tabela 1:</b> Requisitos Não-Funcionais. </p>

| Identificação do Requisito | Requisito                                                                                                                                              	| Técnica de Elicitação | Implementação |
|-----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------|---------------|
| NF01                     	| O sistema deve processar solicitações da carteira de trabalho em no máximo 2 minutos.                                                                                                        	| Análise de documentos 	| Parcialmente      	|
| NF02                     	| O sistema deve ser capaz de escalar para suportar até 1 milhão de usuários simultâneos e permitir personalização das interfaces de usuário.                                                                                      	| Análise de documentos 	| Parcialmente        	|
| NF03                     	| O sistema deve suportar um aumento de 100% no volume de dados, transações e número de usuários sem degradação perceptível no desempenho. | Análise de documentos	| Sim       	|
| NF04                     	| O sistema deve ser capaz de processar até 10.000 transações por segundo, mesmo em picos de uso nacional.                                               	| Análise de documentos 	| Parcialmente (Foi relatado casos de lentidão, talvez devido a grande demanda)      	|
| NF05                     	| Todos os textos do sistema devem seguir os padrões tipográficos e de siglas, abreviações e erros conforme as normas.                                                                   	| Análise de documentos	| Sim       	|
| NF06                     	| A interface do usuário deve estar em conformidade com os manuais de interface gov.br.                                                                                                 	| Análise de documentos 	| Parcialmente       	|
| NF07                     	| A interface do sistema deve incluir todos os elementos básicos de design do Padrão Digital de Governo.                                                                                	| Análise de documentos	| Parcialmente       	|
| NF08                     	| O sistema deve implementar autenticação multifator, criptografia AES-256, controle de acesso baseado em funções, e logs de auditoria detalhados. | Análise de documentos | Sim       	|
| NF09                  	| O sistema deve garantir a conformidade com a LGPD (Lei Geral de Proteção de Dados).                                                                        	| Análise de documentos 	| Sim       	|
| NF10                   	| O sistema deve oferecer suporte a ampliadores de telas, leitores de telas, programas de reconhecimento de voz, teclados alternativos e dispositivos apontadores alternativos, e ser testado com pelo menos duas ferramentas de acessibilidade diferentes. | Análise de documentos | Parcialmente      	|
| NF11                     	| O sistema deve permitir a integração completa com os processos de negócios governamentais, conforme especificado na documentação de requisitos. | Análise de documentos e Storytelling | Parcialmente |
| NF12                    	| O sistema deve utilizar vocabulários controlados e taxonomias padrão do governo, conforme especificado na documentação.| Análise de documentos | Sim |
| NF13                     	| O sistema deve processar solicitações de carteira de trabalho em no máximo 2 minutos, com uma taxa de sucesso de 99%. | Análise de documentos e storytelling| Parcialmente (Algumas vezes o aplicativo apresenta erro) |
| NF14                   	| O aplicativo deve seguir padrões de design aceitos por empresas e instituições, com uma taxa de conformidade de 95% nas avaliações de usabilidade. | Storytelling | Parcialmente |
| NF15                     	| O acesso às funcionalidades principais do aplicativo deve exigir autenticação biométrica e ser completado em menos de 30 segundos. | Storytelling | Parcialmente |
| NF16                     	| O sistema deve permitir ao usuário atualizar seus dados em no máximo 15 minutos, sem a necessidade de intermediários, com uma taxa de sucesso de 95%. | Storytelling | Parcialmente |
| NF17                     	| O sistema deve apresentar dados pessoais com orientações claras e links para correção, com uma taxa de conformidade de 100% nas verificações. | Storytelling | Parcialmente |
| NF18                     	| O sistema deve listar contratos de trabalho com todos os detalhes relevantes, atualizados em tempo real. | Análise de documentos e storytelling | Parcialmente|
| NF20                     	| O sistema deve ser totalmente integrado com o eSocial, com uma taxa de sincronização de dados de 99%. | Análise de documentos | Parcialmente |
| NF21                     	| O sistema deve ser totalmente integrado com o portal gov.br, com uma taxa de sincronização de dados de 99%. | Análise de documentos | Parcialmente |
| NF22                     	| O sistema deve permitir integração com pelo menos cinco outros sistemas de software, conforme especificado na documentação de requisitos. | Análise de documentos 	| Parcialmente      	|
| NF23                     	| O sistema deve enviar notificações precisas com uma taxa de falsos positivos inferior a 5%. | Storytelling | Parcialmente |
| NF24                     	| O aplicativo deve ser compatível com iOS, Android e Windows, sem apresentar falhas críticas em nenhum dos sistemas operacionais suportados. | Storytelling | Parcialmente (Apresenta problemas em iOS) |
| NF25                     	| O sistema deve atualizar os dados do usuário automaticamente a cada 24 horas para evitar defasagem, com uma taxa de sucesso de 99%. | Storytelling | Parcialmente |

<b>Fonte: </b>[Requisitos Não Funcionais](/Elicitacao/RequisitosCorrigidos.md/#Requisitos-Não-Funcionais)

<b> Autor: </b> <a href="https://github.com/brenoalexandre0"> Breno Alexandre </a>

</center>

</details>


## Cartões de Especificação

### O que são cartões de especificação?

Novamente de acordo com a dissertação “Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados”¹, de Reinaldo Antônio da Silva, os cartões de especificação são instrumentos utilizados para detalhar os requisitos de um sistema. Para isso, eles contêm informações precisas e completas sobre cada requisito, servindo como uma referência para o desenvolvimento e a implementação do sistema. Por isso, esses cartões incluem descrições detalhadas, justificativas, critérios de aceitação, e quaisquer outras informações relevantes que assegurem a correta interpretação e implementação desses requisitos.

Por isso, no projeto, serão desenvolvidos cartões de especificações para os requisitos não funcionais no aplicativo da Carteira de Trabalho Digital com o objetivo de a equipe entendê-los com mais detalhes.

### Metodologia dos cartões de especificação

Para criar os cartões de especificação dos requisitos não funcionais, será utilizado o modelo [Volere](https://www.volere.org/wp-content/uploads/2018/12/template14_ptbra.pdf)², que oferece uma estrutura organizada e detalhada para capturar a maioria dos aspectos essenciais desses requisitos. Desse modo, inicialmente, será utilizado o código de identificação dos [requisitos não funcionais definidos na etapa de elicitação](Elicitacao/ResquisitosCorrigidos.md) com o intuito de garantir a sua rastreabilidade. Em seguida, será especificado o tipo de requisito (como desempenho, segurança, usabilidade, entre outros) para classificar adequadamente cada necessidade do sistema. Além disso, também haverá critérios de aceitação definidos para cada um deles, estabelecendo condições claras para a verificação da sua satisfação.

Cada cartão de especificação também incluirá a origem ou a fonte do requisito, pois terá como eles foram elicitados, por exemplo, [análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md). Além disso, serão documentadas as interdependências com outros requisitos ou componentes do sistema, o que ajudará a entender como os diferentes aspectos do sistema se relacionam. Ademais, com base na priorização dos requisitos, a prioridade de cada requisito será categorizada como alta, média ou baixa, auxiliando na gestão e na implementação das necessidades mais críticas. Assim, essa estrutura garantirá que os requisitos não funcionais sejam claramente definidos, compreendidos e ajudará a que eles sejam implementados de forma eficaz no estudo do projeto.

### Template

Para ser mais fácil de ser visualizado e planejado, a tabela 2 mostra o Template do cartão de especificação que será utilizado.

**Tabela 2:** Cartão de Especificação de Requisitos Não Funcionais

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

## Cartões de Especificação de Restrições de Design

Abaixo, as tabelas de 3 a 6 mostram os cartões de especificação de design para as restrições de design.

**Observação:** Os Critérios de aceitação foram retirados diretamento dos documentos análisados, pois eles possuem um conjunto de normas e diretrizer. Assim, esses documentos podem ser acessados por meio das palavras destacadas no campo de descrição da tabela.


<details>
  <summary size="20"><b> Padrões Tipográficos e de Siglas </b></summary> 
 
</center>

**Tabela 2:** Padrões Tipográficos e de Siglas

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador na lista de requisitos**          | [RNF05](Elicitacao/ResquisitosCorrigidos.md)                                                                                   |
| **Nome do Requisito**      | Padrões Tipográficos e de Siglas                                                                                                                      |
| **Tipo de Requisito**      | Restrição de Design                                                                                                                                    |
| **Descrição**              | Todos os textos do sistema devem seguir os padrões tipográficos, de ícones e de siglas, abreviações e erros conforme as normas dispostas em [Tipografia](https://www.gov.br/ds/fundamentos-visuais/tipografia), [Iconografia](https://www.gov.br/ds/fundamentos-visuais/iconografia), [Espaçamento](https://www.gov.br/ds/fundamentos-visuais/espacamento),         [Densidade](https://www.gov.br/ds/padroes/design/densidade)                      |
| **Justificativa/Racionalidade** | É necessário garantir consistência e legibilidade em toda a interface do usuário para promover uma experiência de uso mais intuitiva e mais profissional. Para isso, deve-se Seguir os padrões tipográficos adequados que ajudam a evitar ambiguidades e erros de interpretação e são essenciais para a clareza e precisão na comunicação com os usuário.                   |
| **Critérios de Aceitação** |  <li> Em relação a tipografia, as fontes utilizadas devem ser “Raleway” ou “sans-serif” <li> Nenhuma fonte deve estar fora da escala definida no DS: Minor Third <li> O tamanho da fonte base é de 14px (1em) e peso da fonte normal (400). <li> A seleção de ícones deve estar de acordo com a coleção “Font Awesome“(versão 5.10.2) <li> Em relação ao espagamento, o comportamento das dimensões de um objeto é determinada pela regra: box-sizing: border-box, ou seja, as propriedades de largura (width) e de altura (height) incluem o tamanho do padding e do border, mas não incluem a margin. <li> Quando houver dois ou mais elementos posicionados horizontalmente ou verticalmente em sequência, deve-se evitar somar as margens mínimas de segurança destes elementos. <li>  A escala de densidade é uma gradação de valores que varia de 4px em 4px e pode crescer ou diminuir sem limites, de acordo com a necessidade.  <li> Deve ser utilizado Negrito ou itálico para destacar informações importantes <li> Separação de textos muito longos em parágrafos de, no máximo, 4 linhas. <li> Evitar negação de termos em negrito. <li> Na primeira vez, escrever o nome completo e mencione a sigla entre parênteses. <li> Preferência para os numerais ao invés de escrever por extenso. <li> Evitar palavras em inglês. </ul>         |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                       |
| **Prioridade**             | Média Prioridade                                                                                                                                              |
| **Interdependências**      | RNF06 (Conformidade com manuais de interface gov.br)                                                                                                   |
| **Notas e Comentários**    | Há um conjunto de normas no site do gov para os aplicativos do governo e todas essas normas devem ser consideradas.                                               |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

</details>

<details>
  <summary size="20"><b> Elementos Básicos de Design do Padrão Digital de Governo </b></summary> 
 
</center>

**Tabela 3:** Elementos Básicos de Design do Padrão Digital de Governo

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador na lista de requisitos**          | [RNF07](Elicitacao/ResquisitosCorrigidos.md)                                                                                                                                                 |
| **Nome do Requisito**      | Elementos básicos de design conforme padrão digital de governo                                                                                                                             |
| **Tipo de Requisito**      | Restrição de Design                                                                                                                                    |
| **Descrição**              | A interface do sistema deve incluir a iconografia de acordo com o definido em [design ajuda e comunicação](https://www.gov.br/ds/padroes/design/ajuda-comunicacao), o elemento flutuante de acordo com o [dropdown](https://www.gov.br/ds/padroes/design/dropdown), os gráficos de acordo com a [anatomia dos gráficos](https://www.gov.br/ds/padroes/design/grafico) e obedecer os [Princípios de UX Writing](https://www.gov.br/ds/padroes/writing/principios-writing). |
| **Justificativa/Racionalidade** | Assegurar consistência com outros serviços digitais do governo, facilitando a navegação e o uso pelos cidadãos, pois eles já estão acostumados com este padrão. |
| **Critérios de Aceitação** | <li>  Para representar um contexto de ajuda, a representação iconográfica deve ser o símbolo de interrogação, por exemplo: question ou question-circle.   <li>   A Superfície Flutuante deve ser posicionada próxima ao Acionador ou centralizada na tela, no caso de dispositivos móveis. Por padrão, a Superfície Flutuante abre abaixo do Acionador;    <li>    Para elementos flutuantes, como Dropdown, usa-se o padrão de Elevação na Camada 2.     <li>   O dropdown deve ter: Acionador, identificador de estado, superfície flutuante.     <li>      Nos gráficos, a fonte deve estar área de rodapé.     <li>  Os gráficos são compostos pelas seguintes áreas: Área de Cabeçalho, Título, Subtítulo, Área Principal, Dados Gráficos, Área de Rodapé, Descrição e Fonte.   <li>   Consistência. Por exemplo, se está sendo utilizado a palavra“Agendar” na página principal, não há motivo para escrever “Programar” em outras páginas.   <li>   Trabalhar com palavras que façam parte do dia a dia das pessoas de acordo com o perfil dos usuários.  <li>  O conteúdo precisa manter consistência quanto ao estilo, tom, voz e terminologias. Isso porque o usuário deve perceber que a forma que os diversos produtos de Governo se comunicam com ele é constante e uniforme.  </ul>     |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                                                                                   |
| **Prioridade**             | Média Prioridade                                                                                                                                                  |
| **Interdependências**      | RNF06 (Conformidade com manuais de interface gov.br)                                                                                                   |
| **Notas e Comentários**    | Verificações regulares para alinhamento com atualizações do Padrão Digital de Governo.                                                                 |


**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

</details>

</details>

<details>
  <summary size="20"><b> Acessibilidade no design </b></summary> 
 
</center>

**Tabela 4:** Acessibilidade no design

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador na lista de requisitos**          | [RNF10](Elicitacao/ResquisitosCorrigidos.md)                                                                             |
| **Nome do Requisito**      | Suporte a Ferramentas de Acessibilidade                                                                                                               |
| **Tipo de Requisito**      | Restrição de Design                                                                                                                                    |
| **Descrição**              | O sistema deve oferecer suporte a ampliadores de telas, leitores de telas, programas de reconhecimento de voz, teclados alternativos e dispositivos apontadores alternativos, e ser testado com pelo menos duas ferramentas de acessibilidade diferentes de acordo com [acessibilidade](https://www.gov.br/ds/acessibilidade). |
| **Justificativa/Racionalidade** | Garantir que o sistema seja acessível a todos os usuários, incluindo aqueles com deficiências. Isso porque a implementação de ferramentas de acessibilidade promove a inclusão digital e cumpre requisitos legais, além de melhorar a usabilidade geral do sistema para todos os usuários. |
| **Critérios de Aceitação** | Diretrizes de acordo com o World Wide Web Consortium (W3C) e o Conteúdo Web (WCAG): <br>  <li> Diretriz 1.1 Alternativas em Texto: Fornecer alternativas textuais para qualquer conteúdo não textual, para que possa ser transformado em outras formas de acordo com as necessidades dos usuários, tais como impressão com tamanho de fontes maiores, braille, fala, símbolos ou linguagem mais simples;  <li>  Diretriz 1.2 Mídias com base em tempo: Fornecer alternativas para mídias baseadas em tempo;  <li>  Diretriz 1.3 Adaptável: Criar conteúdo que pode ser apresentado de diferentes maneiras, por exemplo um layout simplificado, sem perder informação ou estrutura; <li> Diretriz 1.4 Discernível: Facilitar a audição e a visualização de conteúdo aos usuários, incluindo a separação entre o primeiro plano e o plano de fundo. <li>  Diretriz 2.1: Acessível por Teclado: Fazer com que toda funcionalidade fique disponível a partir de um teclado.  <li> Diretriz 2.2 Tempo Suficiente: Fornecer aos usuários tempo suficiente para ler e utilizar o conteúdo;  <li> Diretriz 2.3 Convulsões e Reações Físicas: Não criar conteúdo de uma forma conhecida por causar convulsões e reações físicas; <li>  Diretriz 2.4 Navegável: Fornecer maneiras de ajudar os usuários a navegar, localizar conteúdos e determinar onde se encontram; <li>  Diretriz 2.5 Modalidades de Entrada: Torna mais fácil para os usuários operar a funcionalidade por meio de várias entradas além do teclado. <li> O texto deve ser simples, direto, respeita o leitor e apresenta uma leitura “escaneável” <li> Qualquer classificação importante feita por meio de cores deve possuir também uma identificação textual. <li> Prefirir palavras comuns de dois gênero. </ul>                                                             |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                                                                                   |
| **Prioridade**             | Alta Prioridade                                                                                                                                                  |
| **Interdependências**      | -                                                                                                   |
| **Notas e Comentários**    | Pode ser necessários testes de usabilidade com usuários ou personas com deficiências para validar a eficácia das ferramentas de acessibilidade.                                   |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

</details>


<details>
  <summary size="20"><b> Vocabulários e taxonomia padrão </b></summary> 
 
</center>

**Tabela 5:** Vocabulários e taxonomia padrão

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador na lista de requisitos**          | [RNF12](Elicitacao/ResquisitosCorrigidos.md)                                                                                   |
| **Nome do Requisito**      | Vocabulários Controlados e Taxonomias                                                                                                                 |
| **Tipo de Requisito**      | Restrição de Design                                                                                                                                    |
| **Descrição**              | O sistema deve utilizar vocabulários controlados e taxonomias padrão do governo, conforme especificado na documentação em [Princípios de UX Writing](https://www.gov.br/ds/padroes/writing/principios-writing) e [Microcopy](https://www.gov.br/ds/padroes/writing/microcopy)                               |
| **Justificativa/Racionalidade** | Facilitar a consistência e a precisão na comunicação de informações dentro do sistema e garantir que todos os usuários e sistemas interpretem os dados da mesma maneira, reduzindo ambiguidades e de erros. |
| **Critérios de Aceitação** |  <li> O conteúdo precisa manter consistência quanto ao estilo, tom, voz e terminologias. <li> Fornecer informações sobre a ação ou o destino associado ao hiperlink.<li>  Evitar utilizar termos descontextualizados, como “clique aqui”, “leia mais”, “saiba mais”, “veja outros”.  <li> Escrever rótulos ou objetivos curtos e claros. O ideal é que sejam utilizadas no máximo duas palavras (três quando for inevitável). <li> Apenas a primeira letra do rótulo deve ser maiúscula. Buttons são as exceções. </ul>.                                                  |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                                                 |
| **Prioridade**             | Baixa prioridade                                                                                                                                                  |
| **Interdependências**      | -                                                                                           |
| **Notas e Comentários**    | Verificações periódicas para garantir a atualização e a conformidade contínua com os padrões governamentais.                                          |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

</details>

## Cartões de Especificação de Usabilidade

## Cartões de Especificação Design de Desempenho

<details>
  <summary size="20"><b>  Tempo de Processamento de Solicitações </b></summary> 
 
</center>

**Tabela x:** Tempo de Processamento de Solicitações

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [RNF01](Elicitacao/ResquisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Tempo de Processamento de Solicitações                                                                                               |
| **Tipo de Requisito**      | Desempenho                                                                                                                                    |
| **Descrição**              | O sistema deve processar solicitações da carteira de trabalho em no máximo 2 minutos                      |
| **Justificativa/Racionalidade** | Garantir uma experiência eficiente e satisfatória para os usuários, especialmente considerando o alto volume de solicitações esperadas devido à importância e à frequência de uso do serviço                   |
| **Critérios de Aceitação** |  <li> O sistema deve processar solicitações da carteira de trabalho em no máximo 2 minutos                                                       |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                  |
| **Prioridade**             | Média Prioridade                                                                                                                                    |
| **Interdependências**      | RNF02 (Para garantir que o sistema processe solicitações em no máximo 2 minutos, mesmo sob carga pesada de até 1 milhão de usuários simultâneos, é essencial que o sistema seja altamente escalável) e RNF03 (A habilidade do sistema de suportar um aumento de 100% no volume de dados, transações e usuários sem degradação perceptível no desempenho é crucial para manter o tempo de processamento dentro do limite de 2 minutos)                                                                                        |
| **Notas e Comentários**    | Não foram encontradas documentações sobre os requisitos de desempenho do sistema                                   |

**Fonte:** [Pedro Izarias](https://github.com/Izarias)

</center>

</details>

<details>
  <summary size="20"><b>  Escalabilidade do Sistema e Personalização de Interfaces de Usuário </b></summary> 
 
</center>

**Tabela x:** Escalabilidade do Sistema e Personalização de Interfaces de Usuário

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [RNF02](Elicitacao/ResquisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Escalabilidade do Sistema e Personalização de Interfaces de Usuário                                                                                |
| **Tipo de Requisito**      | Desempenho                                                                                                                                    |
| **Descrição**              | O sistema deve ser capaz de escalar para suportar até 1 milhão de usuários simultâneos e permitir personalização das interfaces de usuário.        |
| **Justificativa/Racionalidade** |  A necessidade de garantir que o sistema seja capaz de lidar eficientemente com um grande volume de usuários simultâneos, oferecendo ao mesmo tempo a flexibilidade de personalização das interfaces de usuário conforme as preferências e necessidades individuais                   |
| **Critérios de Aceitação** |  <li> O sistema deve ser capaz de suportar até 1 milhão de usuários simultâneos sem degradação significativa no desempenho <li> Os usuários devem ter a capacidade de personalizar as interfaces de acordo com suas preferências individuais                                                   |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                  |
| **Prioridade**             | Média Prioridade                                                                                                                                    |
| **Interdependências**      | RNF01 (A capacidade de escalabilidade do sistema pode afetar diretamente o tempo de processamento de solicitações) e RNF03 (Um sistema escalável é fundamental para manter a capacidade de processamento de transações mesmo em momentos de alta demanda)                    |
| **Notas e Comentários**    | Não foram encontradas documentações sobre os requisitos de desempenho do sistema                                   |

**Fonte:** [Pedro Izarias](https://github.com/Izarias)

</center>

</details>

<details>
  <summary size="20"><b>  Suporte a Aumento de Volume Sem Degradação de Desempenho </b></summary> 
 
</center>

**Tabela x:** Suporte a Aumento de Volume Sem Degradação de Desempenho

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [RNF03](Elicitacao/ResquisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Suporte a Aumento de Volume Sem Degradação de Desempenho                                                                                |
| **Tipo de Requisito**      | Desempenho                                                                                                                                    |
| **Descrição**              | O sistema deve suportar um aumento de 100% no volume de dados, transações e número de usuários sem degradação perceptível no desempenho        |
| **Justificativa/Racionalidade** | A justificativa baseia-se na necessidade de garantir que o sistema possa crescer de forma eficiente e sustentável, acompanhando o aumento da demanda de usuários e transações sem comprometer a qualidade do serviço.         |
| **Critérios de Aceitação** |  <li> O sistema deve suportar um aumento de 100% no volume de dados e transações sem uma degradação perceptível no desempenho. <li> O sistema deve suportar um aumento de 100% no número de usuários simultâneos sem comprometer o desempenho                                      |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                  |
| **Prioridade**             | Média Prioridade                                                                                                                                    |
| **Interdependências**      | RNF01 (O tempo de processamento das solicitações pode ser afetado pelo aumento no volume de dados e usuários) e RNF02 (A escalabilidade do sistema é essencial para suportar o aumento de volume sem degradação de desempenho)                    |
| **Notas e Comentários**    | Não foram encontradas documentações sobre os requisitos de desempenho do sistema                                   |

**Fonte:** [Pedro Izarias](https://github.com/Izarias)

</center>

</details>


<details>
  <summary size="20"><b>  Capacidade de Processamento de Transações </b></summary> 
 
</center>

**Tabela x:** Capacidade de Processamento de Transações

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [RNF04](Elicitacao/RequisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Capacidade de Processamento de Transações                                                                                              |
| **Tipo de Requisito**      | Desempenho                                                                                                                                    |
| **Descrição**              | O sistema deve ser capaz de processar até 10.000 transações por segundo, mesmo em picos de uso nacional.                      |
| **Justificativa/Racionalidade** | Garantir que o sistema possa lidar com altos volumes de transações simultâneas, especialmente durante picos de uso, para assegurar a eficiência e a continuidade dos serviços prestados.                   |
| **Critérios de Aceitação** | <li> O sistema deve processar até 10.000 transações por segundo durante picos de uso sem degradação perceptível no desempenho.                                                       |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                  |
| **Prioridade**             | Alta Prioridade                                                                                                                                    |
| **Interdependências**      | RNF01 (O tempo de processamento das solicitações pode ser afetado pela capacidade de processamento de transações), RNF02 (A escalabilidade do sistema é necessária para suportar picos de uso) e RNF03 (Suporte ao aumento de volume de dados e usuários é essencial para manter a capacidade de processamento).                                                                                        |
| **Notas e Comentários**    | Não foram encontradas documentações sobre os requisitos de desempenho do sistema                                   |

**Fonte:** [Pedro Izarias](https://github.com/Izarias)

</center>

</details>

<details>
  <summary size="20"><b>  Tempo de Processamento de Solicitações com Taxa de Sucesso </b></summary> 
 
</center>
**Tabela y:** Tempo de Processamento de Solicitações com Taxa de Sucesso

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [RNF13](Elicitacao/RequisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Tempo de Processamento de Solicitações com Taxa de Sucesso                                                                                              |
| **Tipo de Requisito**      | Desempenho                                                                                                                                           |
| **Descrição**              | O sistema deve processar solicitações de carteira de trabalho em no máximo 2 minutos, com uma taxa de sucesso de 99%.                     |
| **Justificativa/Racionalidade** | Garantir uma experiência eficiente e confiável para os usuários, minimizando erros e atrasos no processamento das solicitações de carteira de trabalho.                   |
| **Critérios de Aceitação** | <li> O sistema deve processar solicitações de carteira de trabalho em no máximo 2 minutos. <li> O sistema deve manter uma taxa de sucesso de 99% no processamento das solicitações.                                                      |
| **Origem/Fonte**           | [Análise de documentos e storytelling](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                   |
| **Prioridade**             | Alta Prioridade                                                                                                                                       |
| **Interdependências**      | RNF01 (Tempo de Processamento de Solicitações) e RNF03 (Suporte a Aumento de Volume).                                                                                         |
| **Notas e Comentários**    | Não foram encontradas documentações sobre os requisitos de desempenho do sistema       |

**Fonte:** [Pedro Izarias](https://github.com/Izarias)


</center>

</details>

<details>
  <summary size="20"><b>  Autenticação Biométrica Rápida </b></summary> 
 
</center>
**Tabela z:** Autenticação Biométrica Rápida

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [RNF15](Elicitacao/RequisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Autenticação Biométrica Rápida                                                                                              |
| **Tipo de Requisito**      | Segurança/Desempenho                                                                                                                                    |
| **Descrição**              | O acesso às funcionalidades principais do aplicativo deve exigir autenticação biométrica e ser completado em menos de 30 segundos.                     |
| **Justificativa/Racionalidade** | Assegurar que o acesso ao aplicativo seja seguro e rápido, oferecendo uma experiência de usuário eficiente e protegida.                   |
| **Critérios de Aceitação** | <li> O sistema deve completar a autenticação biométrica em menos de 30 segundos. <li> A autenticação biométrica deve ser necessária para acessar as funcionalidades principais do aplicativo.                                                      |
| **Origem/Fonte**           | [Storytelling](Elicitacao/TecnicasElicitacao/Execucao/Storytelling.md)                                                                  |
| **Prioridade**             | Alta Prioridade                                                                                                                                       |
| **Interdependências**      | RNF08 (Segurança: Autenticação e Criptografia) e RNF03 (Suporte a Aumento de Volume, para garantir desempenho adequado durante picos de uso).                                                                                         |
| **Notas e Comentários**    | Não foram encontradas documentações sobre os requisitos de desempenho do sistema                                   |

**Fonte:** [Pedro Izarias](https://github.com/Izarias)

</center>

</details>

<details>
  <summary size="20"><b>  Atualização de Dados do Usuário  </b></summary> 
 
</center>
**Tabela a:** Atualização de Dados do Usuário

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [RNF16](Elicitacao/RequisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Atualização de Dados do Usuário                                                                                              |
| **Tipo de Requisito**      | Desempenho/Usabilidade                                                                                                                                    |
| **Descrição**              | O sistema deve permitir ao usuário atualizar seus dados em no máximo 15 minutos, sem a necessidade de intermediários, com uma taxa de sucesso de 95%.                     |
| **Justificativa/Racionalidade** | Facilitar a manutenção de dados precisos e atualizados pelos próprios usuários, melhorando a eficiência do sistema e a satisfação do usuário.                   |
| **Critérios de Aceitação** | <li> O sistema deve permitir ao usuário atualizar seus dados em no máximo 15 minutos. <li> O sistema deve manter uma taxa de sucesso de 95% nas atualizações de dados.                                                      |
| **Origem/Fonte**           | [Storytelling](Elicitacao/TecnicasElicitacao/Execucao/Storytelling.md)                                                                  |
| **Prioridade**             | Média Prioridade                                                                                                                                    |
| **Interdependências**      | RNF03 (Suporte a Aumento de Volume) e RNF12 (Vocabulários Controlados e Taxonomias Padrão).                                                                                         |
| **Notas e Comentários**    | Não foram encontradas documentações sobre os requisitos de desempenho do sistema                                   |

**Fonte:** [Pedro Izarias](https://github.com/Izarias)

</center>

</details>



### Cartões de Especificação de Interface 
Abaixo, as tabelas de X a X mostram os cartões de de especificação de interface.

<details>
  <summary size="20"><b> Conformidade com os manuais de interface gov.br </b></summary> 
 
</center>

**Tabela X:** Conformidade com os manuais de interface gov.br

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [RNF06](Elicitacao/ResquisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Conformidade com os manuais de interface gov.br                                                                                                                      |
| **Tipo de Requisito**      | Interface                                                                                                                                   |
| **Descrição**              | O sistema da Carteira de Trabalho Digital deve seguir estritamente os manuais de interface definidos pelo portal gov.br, assegurando que todas as interfaces de usuário estejam em conformidade com os padrões e diretrizes estabelecidos pelo governo brasileiro em [Fundamentos Visuais](https://www.gov.br/ds/fundamentos-visuais/visao-geral).                     |
| **Justificativa/Racionalidade** | A conformidade com os manuais de interface do gov.br é crucial para garantir uma experiência de usuário consistente e familiar aos cidadãos. Esses padrões são projetados para melhorar a usabilidade, acessibilidade e a coerência visual dos aplicativos governamentais, promovendo uma navegação intuitiva e uma melhor prestação de serviços digitais.                 |
| **Critérios de Aceitação** |  <li> Todas as telas e elementos de interface devem estar em conformidade com as diretrizes visuais e de usabilidade do manual gov.br. <li> As cores, tipografias, ícones e espaçamentos devem seguir as especificações detalhadas no manual gov.br. <li> Todos os componentes de interface, como botões, menus, formulários e tabelas, devem ser implementados conforme as recomendações do manual gov.br.<li> O sistema deve passar por uma revisão de conformidade com os padrões gov.br antes de ser lançado ou atualizado. <li> As interfaces devem ser testadas para garantir que atendem aos critérios de acessibilidade definidos no manual gov.br, incluindo compatibilidade com leitores de tela e navegabilidade por teclado.<li> Documentação de conformidade deve ser mantida, detalhando como cada aspecto das diretrizes do gov.br foi implementado no sistema. </ul>                                                      |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                       |
| **Prioridade**             | Alta Prioridade                                                                                                                                         |
| **Interdependências**      |                                                                                                 |
| **Notas e Comentários**    | <li> Todos os desenvolvedores e designers envolvidos no projeto devem estar familiarizados com o conteúdo do manual de interface do gov.br. <li> O manual de interface do gov.br pode ser acessado através do site oficial do governo e deve ser consultado regularmente para garantir conformidade com as atualizações e revisões. <li> Considerar a realização de treinamentos específicos para a equipe sobre as diretrizes e melhores práticas estabelecidas pelo gov.br. </ul>                                                 |  

**Fonte:** [Luana Medeiros](https://github.com/LuaMedeiros)

</center>

</details>

<details>
  <summary size="20"><b> Incluir todos os elementos básicos de design do Padrão Digital de Governo.   </b></summary> 
 
</center>

**Tabela X:** Incluir todos os elementos básicos de design do Padrão Digital de Governo.  

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [RNF07](Elicitacao/ResquisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Incluir todos os elementos básicos de design do Padrão Digital de Governo.                                                                                                                  |
| **Tipo de Requisito**      | Interface                                                                                                                                   |
| **Descrição**              | A interface do sistema da Carteira de Trabalho Digital deve incorporar todos os elementos básicos de design especificados no Padrão Digital de Governo, garantindo que a aparência e a funcionalidade estejam em conformidade com as diretrizes oficiais do governo brasileiro em [Fundamentos Visuais](https://www.gov.br/ds/fundamentos-visuais/visao-geral).                  |
| **Justificativa/Racionalidade** | A implementação dos elementos básicos de design do Padrão Digital de Governo é essencial para assegurar uma experiência de usuário consistente, acessível e intuitiva em todos os serviços digitais oferecidos pelo governo. Esses padrões foram estabelecidos para melhorar a eficiência, usabilidade e acessibilidade dos sistemas governamentais, promovendo uma identidade visual unificada.         |
| **Critérios de Aceitação** |  <li> As cores utilizadas na interface devem seguir a paleta oficial do Padrão Digital de Governo. <li>As fontes utilizadas devem ser “Raleway” ou “sans-serif”. <li> Ícones devem ser selecionados de acordo com a coleção “Font Awesome” (versão 5.10.2). <li> O tamanho da fonte base deve ser de 14px (1em) e peso da fonte normal (400). <li> Botões devem ter tamanhos, espaçamentos e estilos definidos no Padrão Digital de Governo. <li> Formulários devem incluir campos, etiquetas e mensagens de erro padronizados. <li> Cabeçalhos e rodapés devem ser implementados conforme as especificações do Padrão Digital de Governo.<li> Tabelas devem seguir o estilo e estrutura definidos no Padrão Digital de Governo. <li> Todas as imagens na interface devem incluir textos alternativos. <li> A estrutura de navegação deve ser clara e lógica, garantindo compatibilidade com leitores de tela. <li> A interface deve permitir a navegabilidade completa via teclado. <li> Implementar contrastes de cores adequados para acessibilidade visual conforme as diretrizes. <li> Realizar testes de usabilidade com uma amostra de usuários representativa. <li> Ajustar a interface conforme o feedback obtido nos testes de usabilidade. <li> Garantir que a interface seja intuitiva e fácil de usar, conforme os princípios de usabilidade do Padrão Digital de Governo. <li> Manter uma documentação detalhada que demonstre como cada elemento da interface segue o Padrão Digital de Governo. <li> Documentar as decisões de design e as implementações específicas realizadas. <li> Registrar os resultados dos testes de conformidade e usabilidade, incluindo quaisquer ajustes feitos com base no feedback. </ul>                                                      |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                       |
| **Prioridade**             | Alta Prioridade                                                                                                                                         |
| **Interdependências**      |                                                                                                 |
| **Notas e Comentários**    | <li> O Padrão Digital de Governo pode ser acessado no portal oficial do gov.br e deve ser consultado regularmente para garantir que a interface esteja sempre em conformidade com as atualizações e revisões. <li> Todos os membros da equipe de desenvolvimento e design devem estar familiarizados com o Padrão Digital de Governo e participar de treinamentos se necessário. <li> A conformidade com o padrão deve ser verificada durante as fases de desenvolvimento e antes de cada lançamento de atualização do sistema. </ul>                                                 |  

**Fonte:** [Luana Medeiros](https://github.com/LuaMedeiros)

</center>

</details>

### Cartões de Acessiibilidade

</center>

</details>

<details>
  <summary size="20"><b> Incluir todos os elementos básicos de design do Padrão Digital de Governo.   </b></summary> 
 
</center>

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [NFR01](Elicitacao/ResquisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Compatibilidade com Leitores de Tela                                                                                               |
| **Tipo de Requisito**      | Acessibilidade                                                                                                                                    |
| **Descrição**              | O aplicativo deve ser compatível com leitores de tela, para permitir que pessoas com deficiência visual utilizem todas as funcionalidades.                      |
| **Justificativa/Racionalidade** | Garantir a inclusão e acessibilidade de todos os usuários, especialmente aqueles com deficiência visual.                   |
| **Critérios de Aceitação** | <ul><li>O aplicativo deve ser totalmente funcional com os principais leitores de tela do mercado.</li></ul>                                                       |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                  |
| **Prioridade**             | Alta Prioridade                                                                                                                                    |
| **Interdependências**      | NFR02 (Compatibilidade com leitores de tela está relacionada ao contraste adequado de texto e fundo para garantir acessibilidade completa).                                                                                        |
| **Notas e Comentários**    |                                                                                                   |

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [NFR02](Elicitacao/ResquisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Contraste Adequado entre Texto e Fundo                                                                                               |
| **Tipo de Requisito**      | Acessibilidade                                                                                                                                    |
| **Descrição**              | O aplicativo deve ter contraste adequado entre texto e fundo, para garantir a legibilidade por pessoas com baixa visão.                      |
| **Justificativa/Racionalidade** | Facilitar a leitura e utilização do aplicativo por pessoas com baixa visão, promovendo inclusão e usabilidade.                   |
| **Critérios de Aceitação** | <ul><li>O contraste deve seguir as diretrizes WCAG 2.1 de nível AA.</li></ul>                                                       |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                  |
| **Prioridade**             | Alta Prioridade                                                                                                                                    |
| **Interdependências**      | NFR01 (Contraste adequado é necessário para compatibilidade com leitores de tela).                                                                                        |
| **Notas e Comentários**    |                                                                                                   |

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [NFR03](Elicitacao/ResquisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Navegabilidade via Teclado                                                                                               |
| **Tipo de Requisito**      | Acessibilidade                                                                                                                                    |
| **Descrição**              | Todos os elementos interativos devem ser navegáveis via teclado, para garantir acessibilidade a pessoas com mobilidade reduzida.                      |
| **Justificativa/Racionalidade** | Garantir que usuários com mobilidade reduzida possam utilizar todas as funcionalidades do aplicativo sem barreiras.                   |
| **Critérios de Aceitação** | <ul><li>Todos os elementos interativos devem ser acessíveis e utilizáveis apenas com o teclado.</li></ul>                                                       |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                  |
| **Prioridade**             | Alta Prioridade                                                                                                                                    |
| **Interdependências**      | NFR04 (Navegabilidade via teclado é complementada por alternativas textuais para elementos não textuais).                                                                                        |
| **Notas e Comentários**    |                                                                                                   |

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [NFR04](Elicitacao/ResquisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Alternativas Textuais para Elementos Não Textuais                                                                                               |
| **Tipo de Requisito**      | Acessibilidade                                                                                                                                    |
| **Descrição**              | O aplicativo deve fornecer alternativas textuais para todos os elementos não textuais, como imagens e ícones, para ser acessível a pessoas com deficiência visual.                      |
| **Justificativa/Racionalidade** | Garantir que informações transmitidas por elementos visuais também sejam acessíveis a usuários com deficiência visual.                   |
| **Critérios de Aceitação** | <ul><li>Todas as imagens, ícones e outros elementos não textuais devem ter descrições alternativas adequadas.</li></ul>                                                       |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                  |
| **Prioridade**             | Alta Prioridade                                                                                                                                    |
| **Interdependências**      | NFR03 (Alternativas textuais são necessárias para a navegação via teclado).                                                                                        |
| **Notas e Comentários**    |                                                                                                   |

| **Elemento**               | **Detalhes**                                                                                                                                          |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Identificador**          | [NFR05](Elicitacao/ResquisitosCorrigidos.md)                                                                                                          |
| **Nome do Requisito**      | Instruções Claras para Preenchimento de Formulários                                                                                               |
| **Tipo de Requisito**      | Usabilidade                                                                                                                                    |
| **Descrição**              | As instruções para o preenchimento de formulários devem ser claras e descritivas, para garantir que todos os usuários possam fornecer as informações necessárias corretamente.                      |
| **Justificativa/Racionalidade** | Facilitar a correta e eficiente utilização dos formulários, reduzindo erros e aumentando a satisfação do usuário.                   |
| **Critérios de Aceitação** | <ul><li>Instruções devem ser detalhadas e compreensíveis, minimizando a necessidade de suporte adicional.</li></ul>                                                       |
| **Origem/Fonte**           | [Análise de documentos](Elicitacao/TecnicasElicitacao/Execucao/AnaliseDocumentos.md)                                                                  |
| **Prioridade**             | Média Prioridade                                                                                                                                    |
| **Interdependências**      |                                                                                                   |
| **Notas e Comentários**    |                                                                                                   |



[Bruno Araújo](https://github.com/brunocva)
</center>

</details>

## SIG ou Softgoal Interdependency Graph

Ainda de acordo com  a dissertação “Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados”¹, de Reinaldo Antônio da Silva, o SIG, ou Softgoal Interdependency Graph, é uma representação gráfica das considerações do desenvolvedor sobre os requisitos em formato de softgoals e suas interdependências em um projeto de software. Desse modo, ele serve como uma ferramenta visual  para registrar as decisões de desenvolvimento, incluindo requisitos não funcionais, de alternativas e de justificativas associadas. Portanto, por meio do SIG, é possível construir, elaborar, analisar e revisar a lógica do projeto de forma clara e acessível.

Neste contexto, a equipe irá utilizar o SIG  como uma ferramenta para entender e gerenciar os diversos aspectos dos requisitos não funcionais do sistema. Para isso, será levado em conta alguns campos críticos, como usabilidade, desempenho, restrição de design, interfaces e acessibilidade, que serão mapeados e representados no SIG para permitir uma visualização clara das interdependências entre eles. 

### Os softgoals

De acordo com Chung², Há três tipos de softgoals:

- **Softgoals NFR:** Representam os Requisitos Não-Funcionais.
  - Podem estar interrelacionados, organizados em catálogos e apresentados de forma hierárquica.

- **Softgoals de operacionalização**: Essas soluções incluem operações, processos, representações de dados, estruturações e restrições no sistema.

- **Softgoals de Afirmação:** permitem que as características do domínio (como prioridades e carga de trabalho) sejam consideradas e devidamente refletidas no processo de tomada de decisão.
  - Servem como justificativa para apoiar ou negar a forma como os softgoals são priorizados.
 
A figura 1 mostra a legenda dos softgoals que serão utilizados nos SIG do projeto.

 <center> 
  <font size="2"><p style="text-align: center">Figura 1: Legenda Softgoals. </p></font>
  <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/ImagensDiagrama/ImagensEntrega4/legenda_nfrframework.drawio.png">
  <font size="2"><p style="text-align: center"> Autora: Larissa Stéfane </p></font>
 </center>

### Contribuições entre Softgoals

Contribuições são formas de descrever como um softgoal (um objetivo não funcional) afeta outro no contexto de um projeto de desenvolvimento de software. Elas indicam se a satisfação de um objetivo contribui de forma positiva, negativa ou neutra para a satisfação de outro objetivo. Desse modo, em “Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados”¹, de Reinaldo Antônio da Silva, é citado que Chung definiu as seguintes contribuições para os diagramas:

- **AND**: Determina que se os softgoals descendentes forem satisfeitos os softgoals ascendentes serão satisfeitos.
- **OR**: Determina que, se algum softgoal descendente for satisfeito, o ascendente será satisfeito.
- **MAKE(++):** Fornece uma contribuição suficientemente positiva entre um softgoal descendente e um softgoal ascendente que é concebida no nível mais alto de satisfação. Dessa forma, ao utilizarmos MAKE, se o softgoal descendente for satisfeito o softgoal pai também será satisfeito.
- **BREAK(- -):** Fornece uma contribuição suficientemente negativa entre um softgoal descendente e um softgoal ascendente que é concebida no nível mais alto de negação. Portanto, ao utilizar BREAK, se o softgoal descendente for suficientemente satisfeito o softgoal pai será negado, ou seja, não será satisfeito.
- **HELP(+):** Fornece uma contribuição parcialmente positiva entre um softgoal descendente e um softgoal ascendente. Dessa forma, ao utilizar HELP, se o softgoal descendente for parcialmente satisfeito o softgoal ascendente será parcialmente satisfeito.
- **HURT(-):** Fornece uma contribuição parcialmente negativa entre um softgoal descendente e um softgoal ascendente. Dessa forma, ao utilizar HURT, se o softgoal descendente for satisfeito o softgoal ascendente será parcialmente negado.
- **UNKNOWN(?):** Fornece uma contribuição desconhecida entre um softgoal descendente e um softgoal ascendente, podendo ser tanto positiva quanto negativa.
- **EQUALS:** Determina que o softgoal descendente só será satisfeito se o softgoal ascendente for satisfeito e que o softgoal descendente será negado se o softgoal ascendente for negado.
- **SOME:** É utilizada quando o sinal da contribuição é conhecido (positivo ou negativo), mas a extensão (parcial ou total) não é. Nesses casos, quando há alguma incerteza em se utilizar HELP ou MAKE deve-se utilizar o tipo de contribuição SOME +. Da mesma forma, quando não há certeza em se utilizar HURT ou BREAK deve-se utilizar SOME -.

### Metodologia para o SIG

A metodologia que a equipe irá adotar para elaborar os SIG do projeto se baseará em uma série de etapas. Inicialmente, a partir das diversas formas de elicitação dos requisitos não funcionais e da análise da tabela dos requisitos não elicitados, alguns membros da equipe realizarão um estudo mais profundo sobre alguns tópicos específicos e sobre a própria estrutura e funcionamento do SIG, por exemplo, sobre as restrições de design. Assim, esse estudo proporcionará um entendimento mais completo das necessidades do sistema e, com base nesse conhecimento adquirido, proceder-se-á à elaboração dos SIGs, que consistirão em representações gráficas das interdependências entre os softgoals identificados.

Consequentemente, esses SIGs servirão como ferramentas fundamentais para a descoberta de novos requisitos não funcionais até então não considerados, bem como para o aprofundamento e detalhamento dos requisitos já elicitados.

### Os NFR framework

### NFR - Restrições de Design

Por meio do estudo dos requisitos não funcionais [RNF05](Elicitacao/ResquisitosCorrigidos.md), [RNF07](Elicitacao/ResquisitosCorrigidos.md), [RNF10](Elicitacao/ResquisitosCorrigidos.md) e [RNF12](Elicitacao/ResquisitosCorrigidos.md), foi elaborado um diagrama SIG para o campo de restrições de designe, sendo possível visualizá-lo na figura 2.

<details>
  <summary size="20"><b> Figura 2: NFR - Restrições de Design    </b></summary> 

 <center> 
  <font size="2"><p style="text-align: center">Figura 2: NFR restrições de Design. </p></font>
  <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/ImagensDiagrama/ImagensEntrega4/RestricoesDesign_NFRframework2.png">
  <font size="2"><p style="text-align: center"> Autora: Larissa Stéfane </p></font>
 </center>

Para visualizar melhor o diagrama, clique em [NFR - Restrições de Design](https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/ImagensDiagrama/ImagensEntrega4/RestricoesDesign_NFRframework2.png) 

</details>

### NFR - Desempenho

Por meio do estudo dos requisitos não funcionais [RNF01](Elicitacao/ResquisitosCorrigidos.md), [RNF02](Elicitacao/ResquisitosCorrigidos.md), [RNF03](Elicitacao/ResquisitosCorrigidos.md), [RNF04](Elicitacao/ResquisitosCorrigidos.md), [RNF13](Elicitacao/ResquisitosCorrigidos.md), [RNF15](Elicitacao/ResquisitosCorrigidos.md) e [RNF16](Elicitacao/ResquisitosCorrigidos.md), foi elaborado um diagrama SIG para a classificação de desempenho, sendo possível visualizá-lo na figura 3.

<details>
  <summary size="20"><b> Figura 3: NFR - Desempenho    </b></summary> 

 <center> 
  <font size="2"><p style="text-align: center">Figura 3: NFR Desempenho. </p></font>
  <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/ImagensDiagrama/ImagensEntrega4/desempenho.jpeg">
  <font size="2"><p style="text-align: center"> Autor: Pedro Izarias </p></font>
 </center>

Para visualizar melhor o diagrama, clique em [NFR - Desempenho](https://raw.githubusercontent.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/main/docs/ImagensDiagrama/ImagensEntrega4/desempenho.jpeg) 

</details>



## Referências Bibliográficas
1. <b>SILVA, Reinaldo Antônio</b>. **NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados**. Recife, 2019. Disponível em <http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER20/21_WER_2020_paper_36.pdf> Acessado em 26/05/2024

2. <b>ROBERTSON, James</b>; ROBERTSON, Suzanne. Modelo para Especificações de Requisitos. Edição 14. Associação Atlântica de Sistemas, agosto 2009. Disponível em <https://www.volere.org/wp-content/uploads/2018/12/template14_ptbra.pdf> Acessado em 26/05/2024 



## Histórico de Versão

| Versão | Alteração                                                         | Responsável     | Revisor        | Data       |
| ------ | ----------------------------------------------------------------- | --------------- | -------------- | ---------- |
| 1.0    |  Adição da explicação do que é NFR e o que é framework            | Larissa Stéfane | Iago Passaglia | 26/05/2024 |
| 1.1    |  Adição da metodologia e do Template dos cartões de especificação | Larissa Stéfane | Iago Passaglia | 26/05/2024 |
| 1.2    | Adicionar  Cartões de Especfiicação de Restrições de Design       | Larissa Stéfane | Iago Passaglia | 26/05/2024 |
| 1.3    | Adicionar  Cartões de Especfiicação de Interface                  | Luana Medeiros  | Bruno Araújo   | 27/05/2024 |
| 1.4    | Adicionar  Cartões de Especfiicação de Desempenho                 | Pedro Izarias   | Bruno Araújo   | 27/05/2024 |
| 1.5    | Adição da tabela de RNFs elicitados anteriormente                 | Breno Alexandre | Pedro Izarias  | 27/05/2024 |
| 1.6    | Adição da apresentação do SIG ou Softgoal Interdependency Graph (Definições e metodologia)   | Larissa Stéfane | Pedro Izarias  | 27/05/2024 |
| 1.7    | Adição do NFR - Restrições de Design   | Larissa Stéfane | Pedro Izarias  | 27/05/2024 |
| 1.8    | Adição do NFR - Desempenho   | Pedro Izarias |  -  | 27/05/2024 |
