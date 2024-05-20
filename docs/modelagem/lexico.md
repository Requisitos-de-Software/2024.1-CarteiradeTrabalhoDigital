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
|Atualizar dados pessoais| [Caio](https://github.com/caiomesvie) |Ato de realizar mudanças no cadastro do usuário em seus dados pessoais. |assegura que as informações mais recentes estejam disponíveis tanto para o trabalhador quanto para o empregador, evitando discrepâncias e facilitando a conformidade com as exigências legais. | Sincronizar dados, integrar dados.|
| Enviar carteira de trabalho | [Iago](https://github.com/Paxxaglia) | O trabalhador precisa exportar o documento da carteira de trabalho para algum outro aplicativo | O trabalhador escolhe as opções de exportação da carteira e pode gerar um PDF | Expedir a carteira profissional, Encaminhar a carteira de trabalho, Despachar o registro de trabalho |
| Adicionar Novo Contrato de Trabalho            | [Larissa Stéfane](https://github.com/SkywalkerSupreme)| Incluir novos contratos de trabalho na carteira de trabalho digital | Inserção de novos registros de contratos na carteira digital para empresas | Inserir     |
| Emitir PDF do Contrato de Trabalho             | [Larissa Stéfane](https://github.com/SkywalkerSupreme)| Gerar um arquivo PDF contendo os detalhes do contrato de trabalho | Disponibilização de um documento digital para consulta ou impressão | Gerar PDF   |
| Realizar Anotações no Contrato de Trabalho     | [Larissa Stéfane](https://github.com/SkywalkerSupreme)| Adicionar observações e notas no contrato de trabalho digital | Inserção de informações adicionais relevantes ao contrato de trabalho digital | Registrar   |
| Consultar Vínculos Empregatícios| [Luana](https://github.com/LuaMedeiros) | O usuário utiliza a opção de consultar vínculos empregatícios para visualizar os detalhes dos seus empregos registrados, como datas de admissão e demissão, cargos e empregadores. | O usuário entra na opção consultar vínculos empregatícios e é direcionado para uma página que exibe uma lista de seus empregos registrados. Ao selecionar um vínculo específico, ele pode ver informações detalhadas sobre esse emprego. | Verificar vínculos, checar registros de emprego |
| Avaliar aplicativo| [Pedro](https://github.com/Izarias) |O usuário utiliza a opção avaliar para dar um feedback aos desenvolvedores sobre a qualidade do app. | O usuário entra na opção avaliar aplicativo e é direcionado para a página do app na loja, onde pode dar sua nota sobre a qualidade do aplicativo. |Qualificar, ponderar |

Fonte: Citados ao longo da tabela
</center>

<center>
Tabela 3: Léxicos do tipo Objeto

|Símbolo|Autor|Noção (denotação)|Impacto (conotação)|Sinônimo|
|-|-|-|-|-|
| Contrato de Trabalho | [Bruno](https://github.com/brunocva.png) | O contrato de trabalho contém informações sobre o vínculo empregatício entre o trabalhador e a empresa, incluindo dados como período trabalhado, salário e tipo de contrato. | O trabalhador pode visualizar, atualizar ou encerrar um contrato de trabalho. O sistema mantém um registro detalhado dos contratos de trabalho do usuário. | Acordo de Trabalho, Vínculo Empregatício, Emprego |
| | [Breno](https://github.com/brenoalexandre0.png) | | | |
| Empregador | [Caio](https://github.com/caiomesvie) | Pessoa física ou jurídica que contrata um trabalhador para prestar serviços de forma contínua e remunerada. | O usuário depende de seu empregador para que seja realizado o envio da documentação necessária para o registro em sua carteira de trabalho digital |Empresa, Patrão, Contratante. |
| Benefício | [Iago](https://github.com/Paxxaglia) | Representa os auxílios ofertados para os trabalhadores contemplados |  O usuário pode solicitar diversos benefícios como Abono salarial, Seguro-desemprego, benefício emergencial entre outros. | Bônus, Auxílio, Comodidade |
| Perfil do Trabalhador                          | [Larissa Stéfane](https://github.com/SkywalkerSupreme)| Conjunto de informações pessoais | Fonte de dados sobre o usuário | Registro do usuário(trabalhador) |
| Notificação                                    | [Larissa Stéfane](https://github.com/SkywalkerSupreme)| Mensagem enviada ao trabalhador ou empresa sobre alterações ou eventos | Mecanismo de comunicação para manter as partes informadas sobre mudanças nos contratos | Alerta             |
| Informação do Contrato                         | [Larissa Stéfane](https://github.com/SkywalkerSupreme)| Dados específicos que compõem um contrato de trabalho              | Detalhes necessários para a criação, atualização e encerramento de contratos na carteira digital | Dados              |
| Salário                                        | [Larissa Stéfane](https://github.com/SkywalkerSupreme)| Remuneração acordada entre empresa e trabalhador                     | Valor financeiro estipulado em um contrato de trabalho e sujeito a atualizações | Remuneração        |
| Vínculo Empregatício | [Luana](https://github.com/LuaMedeiros) | O vínculo empregatício representa a relação formal de trabalho entre o trabalhador e a empresa, contendo informações cruciais como datas de admissão e demissão, cargo ocupado, salário e outros detalhes pertinentes ao emprego. | O usuário pode visualizar, editar ou adicionar um novo vínculo empregatício em sua carteira de trabalho digital. O sistema mantém um registro completo e organizado de todos os vínculos empregatícios do usuário, proporcionando uma visão consolidada de sua história profissional. | Contrato de Trabalho, Emprego, Acordo Empresarial |
| Carteira | [Pedro](https://github.com/Izarias) | Representa a versão digital da Carteira de Trabalho e Previdência Social (CTPS), onde são armazenadas e gerenciadas as informações trabalhistas do usuário.| O usuário pode visualizar suas principais informações no aplicativo.| Cartão, portfólio|

Fonte: Citados ao longo da tabela
</center>

<center>
Tabela 4: Léxicos do tipo Estado

|Símbolo|Autor|Noção (denotação)|Impacto (conotação)|Sinônimo|
|-|-|-|-|-|
| Benefício Aprovado | [Bruno](https://github.com/brunocva.png) | O sistema verifica a solicitação do benefício e, após aprovação, muda o status do pedido para "Aprovado". | O benefício solicitado pelo trabalhador foi aprovado. O sistema atualiza o status do benefício e notifica o trabalhador. | Benefício Concedido, Benefício Confirmado |
| | [Breno](https://github.com/brenoalexandre0.png) | | | |
|Contrato Finalizado | [Caio](https://github.com/caiomesvie) | O contrato de trabalho foi finalizado devido ao período de tempo pré-determinado | Tanto a empresa quanto o empregado são notificados sobre o fim do contrato | Contrato Concluído, Contrato Terminado. |
| Tempo de serviço | [Iago](https://github.com/Paxxaglia) | O sistema verifica os registros do usuário e os ordena em ordem de tempo de serviço | A visualização se adapta após o click na opção | O usuário pode visualizar uma visão mais ampla relacionada aos seus contratos de trabalho |
| Em Processo de Validação                 | [Larissa Stéfane](https://github.com/SkywalkerSupreme)| Estado onde as informações fornecidas estão sendo verificadas pelo sistema | Garante que os dados inseridos são corretos antes de serem aceitos no banco de dados | Verificação           |
| Conexão Estável                          | [Larissa Stéfane](https://github.com/SkywalkerSupreme)| Situação em que a conexão à internet está funcionando corretamente | Permite a comunicação contínua e a realização de operações no sistema | Conectado             |
| Não Autorizado                           | [Larissa Stéfane](https://github.com/SkywalkerSupreme)| Estado onde a empresa não tem permissão para realizar uma ação no sistema | Bloqueia a execução da ação até que a autorização seja obtida | Sem Permissão         |
| Contrato Ativo | [Luana](https://github.com/LuaMedeiros) | O sistema verifica a existência e validade de um contrato de trabalho entre o trabalhador e a empresa. Se o contrato estiver ativo, seu status é definido como "Ativo". | O contrato de trabalho está vigente e em pleno vigor. O sistema registra e mantém o status do contrato como ativo, indicando que o trabalhador está atualmente empregado pela empresa. | Contrato Vigente, Emprego em Andamento |
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
| 1.0 | Criação de documentação                      | Pedro Izarias  | Iago Passaglia | 18/05/2024 |
| 1.1 | Adição do Léxico                             | Bruno Araújo   | Iago Passaglia | 19/05/2024 |
| 1.2 | Adição dos Léxicos de verbo, objeto e estado | Iago Passaglia | Larissa Stéfane | 19/05/2024 |
| 1.3 | Adição dos Léxicos de verbo, objeto e estado | Luana Medeiros | Larissa Stéfane | 19/05/2024 |
| 1.4 |  Adição dos Léxicos de verbo, objeto e estado | Larissa Stéfane | Iago Passaglia | 19/05/2024 |
| 1.5 |  Adição dos Léxicos de verbo, objeto e estado | Pedro Izarias | Iago Passaglia | 19/05/2024 |
| 1.6 |  Adição dos Léxicos de verbo, objeto e estado | Caio Mesquita | Iago Passaglia | 19/05/2024 |
