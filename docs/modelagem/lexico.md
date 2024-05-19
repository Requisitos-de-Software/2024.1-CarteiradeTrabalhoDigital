# Léxico

## Sumário

* [Introdução](#Introdução)
* [Metodologia](#Metodologia)
* [Léxicos](#Léxicos)
* [Conclusão](#Conclusão)
* [Bibliografia](#Bibliografia)
* [Histórico de Versão](#Histórico-de-versão)

## Introdução

No contexto da Engenharia de Requisitos, léxico refere-se ao conjunto de palavras e expressões utilizadas nas interfaces de usuário, incluindo rótulos, comandos, mensagens e instruções. Esse componente é crucial, pois influencia diretamente a clareza, a usabilidade e a eficácia da comunicação entre o usuário e o sistema.

## Metodologia

A técnica utilizada foi a Linguagem de Apoio ao Léxico (LAL), que é uma metodologia da Engenharia de Requisitos para desenvolver e refinar o léxico de uma interface. Consiste em identificar e listar todos os termos ou símbolos presentes na interface de um sistema, analisando sua adequação, consistência e clareza. Cada símbolo tem zero ou mais sinônimos, uma ou mais noções e um ou mais impactos, regras descritas na tabela 1.

<center>

Tabela 1: Legenda das tabelas de Léxico

|Classificação|Símbolo|Autor|Noção (denotação)|Impacto (conotação)|Sinônimo|
|-|-|-|-|-|-|
|Divisão baseada na função e no uso dos termos|Palavra ou frase analisada|Integrante do grupo|Significado do símbolo analisado|Efeito, uso ou ocorrência do Símbolo durante sua utilização ou consequência do uso de algo sobre o símbolo|Palavra ou frase de mesmo significado do símbolo|

<font size="3"><p style="text-align: center">Fonte: </p></font>

Os Léxicos ainda podem ser classificados em três categorias, sendo elas: Verbo, Objeto e Estado. Essa classificação serve para facilitar a análise e o design das interfaces, garantindo que a terminologia utilizada seja clara e funcional.

</center>

## Léxicos

<center>
Tabela 2: Léxicos do tipo Verbo

|Símbolo|Autor|Noção (denotação)|Impacto (conotação)|Sinônimo|
|-|-|-|-|-|
| Solicitar Benefício | [Bruno](https://github.com/brunocva.png) | O trabalhador deseja solicitar um benefício e utiliza o aplicativo para enviar a solicitação juntamente com os documentos necessários. | O trabalhador inicia a solicitação de um benefício, como Seguro Desemprego ou Abono Salarial. O sistema valida a solicitação e informa o trabalhador sobre o status do pedido. | Requerer Benefício, Pedir Benefício |
| | [Breno](https://github.com/brenoalexandre0.png) | | | |
| | [Caio](https://github.com/caiomesvie) | | | |
| | [Iago](https://github.com/Paxxaglia) | | | |
| | [Larissa](https://github.com/SkywalkerSupreme) | | | |
| | [Luana](https://github.com/LuaMedeiros) | | | |
| Avaliar aplicativo| [Pedro](https://github.com/Izarias) |O usuário utiliza a opção avaliar para dar um feedback aos desenvolvedores sobre a qualidade do app. | O usuário entra na opção avaliar aplicativo e é direcionado para a página do app na loja, onde pode dar sua nota sobre a qualidade do aplicativo. |Qualificar, ponderar |

Fonte: Citados ao longo da tabela
</center>

<center>
Tabela 3: Léxicos do tipo Objeto

|Símbolo|Autor|Noção (denotação)|Impacto (conotação)|Sinônimo|
|-|-|-|-|-|
| Contrato de Trabalho | [Bruno](https://github.com/brunocva.png) | O contrato de trabalho contém informações sobre o vínculo empregatício entre o trabalhador e a empresa, incluindo dados como período trabalhado, salário e tipo de contrato. | O trabalhador pode visualizar, atualizar ou encerrar um contrato de trabalho. O sistema mantém um registro detalhado dos contratos de trabalho do usuário. | Acordo de Trabalho, Vínculo Empregatício, Emprego |
| | [Breno](https://github.com/brenoalexandre0.png) | | | |
| | [Caio](https://github.com/caiomesvie) | | | |
| | [Iago](https://github.com/Paxxaglia) | | | |
| | [Larissa](https://github.com/SkywalkerSupreme) | | | |
| | [Luana](https://github.com/LuaMedeiros) | | | |
| Carteira | [Pedro](https://github.com/Izarias) | Representa a versão digital da Carteira de Trabalho e Previdência Social (CTPS), onde são armazenadas e gerenciadas as informações trabalhistas do usuário.| O usuário pode visualizar suas principais informações no aplicativo.| Cartão, portfólio|

Fonte: Citados ao longo da tabela
</center>

<center>
Tabela 4: Léxicos do tipo Estado

|Símbolo|Autor|Noção (denotação)|Impacto (conotação)|Sinônimo|
|-|-|-|-|-|
| Benefício Aprovado | [Bruno](https://github.com/brunocva.png) | O sistema verifica a solicitação do benefício e, após aprovação, muda o status do pedido para "Aprovado". | O benefício solicitado pelo trabalhador foi aprovado. O sistema atualiza o status do benefício e notifica o trabalhador. | Benefício Concedido, Benefício Confirmado |
| | [Breno](https://github.com/brenoalexandre0.png) | | | |
| | [Caio](https://github.com/caiomesvie) | | | |
| | [Iago](https://github.com/Paxxaglia) | | | |
| | [Larissa](https://github.com/SkywalkerSupreme) | | | |
| | [Luana](https://github.com/LuaMedeiros) | | | |
| Contrato de trabalho Aberto | [Pedro](https://github.com/Izarias) | Um contrato de trabalho pode estar "Aberto" se foi recentemente submetido para aprovação e ainda está sendo revisado pela empresa ou pelo sistema.| O estado "Aberto" comunica ao usuário que sua solicitação ou processo está em andamento e ainda não foi concluído. | Em andamento, Em processo|

Fonte: Citados ao longo da tabela
</center>

## Conclusão

A definição clara e precisa de termos e expressões no léxico do aplicativo da Carteira de Trabalho Digital é fundamental para garantir uma comunicação eficaz entre o usuário e o sistema, melhorando a usabilidade e a experiência do usuário.

## Bibliografia

1. SERRANO, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: <https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf>. Acesso em: 14/05/2023.
2. SERRANO, Milene; SERRANO, Maurício. Requisitos – Aula 13. 2017. Apresentação de slides. Disponível em: <https://example.com/Requisitos-Aula-013a.pdf>. Acesso em: 19 mai. 2024.
3. Passo a Passo Carteira de Trabalho Digital APP e WEB. Ministério do Trabalho e Emprego, 2023.

## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação de documentação | Pedro Augusto | - | 18/05/2024 |
| 1.1 | Adição do Léxico | Bruno Araújo | - | 19/05/2024 |
