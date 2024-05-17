# Elicitação por análise de documento

## Sumário

* [Introdução](#Introdução)
* [Cronograma](#Cronograma)
* [Principais Funções do Aplicativo](#Principais-Funções-do-Aplicativo)
* [Requisitos-Não-Funcionais](#Requisitos-Não-Funcionais)
* [Integrações](#Integrações)
* [Normas a serem seguidas na interface](#Normas-a-serem-seguidas-na-interface)
* [Requisitos de Segurança](#Requisitos-de-Segurança)
* [Requisitos de Usabilidade na Acessibilidade](#Requisitos-de-Usabilidade-na-Acessibilidade)
* [Testes Necessários para garantir que os requisitos estão satisfeitos](#Testes-Necessários-para-garantir-que-os-requisitos-estão-satisfeitos)
* [Requisitos encontrados](#Requisitos-encontrados)
* [Conclusão](#Conclusão)
* [Bibliografia](#Bibliografia)
* [Histórico de versão](#Histórico-de-versão)


## Introdução

A elicitação de requisitos é uma etapa crucial no desenvolvimento de software, especialmente quando se trata de aplicativos destinados a simplificar processos burocráticos e facilitar a vida dos usuários, como é o caso da Carteira de Trabalho Digital. Devido a isso, este documento é composto pelas anotações e pontos relevantes detectados por meio da análise de um conjunto de documentos relacionados ao software com o intuito de elencar os seus requisitos.

## Cronograma

A tabela 1 mostra como foi a organização do cronograma durante a realização da análise de documentos.

</center>

Tabela 1: Cronograma.

| Data       | Atividade                                             |
|------------|-------------------------------------------------------|
| 10/04/2024 - 13/04/2024 | Análise do documentos e anotações dos pontos relevantes. |
| 13/04/2024 - 14/04/2024 | Documentação dos requisitos encontrados      |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

## Principais Funções do Aplicativo

A Carteira de Trabalho pode ser emitida no formato digital, nela consta a vida profissional do trabalhador, visando garantir os direitos trabalhistas previstos em lei. Assim, atualizações e desenvolvimentos posteriores a sua data de lançamento devem se atentar à Lei 14.129 de 29 de março de 2021, disponível em [Lei 14.129](https://www.planalto.gov.br/ccivil_03/_ato2019-2022/2021/lei/L14129.htm). Mais informações podem ser encontradas em [Lei do Governo Digital entra em vigor](https://www.gov.br/gestao/pt-br/acesso-a-informacao/acoes-e-programas/principais-acoes-na-area-economica/acoes-2021/lei-do-governo-digital-entra-em-vigor#:~:text=A%20Lei%20do%20Governo%20Digital,e%20da%20participa%C3%A7%C3%A3o%20dos%20cidad%C3%A3os.) 

Segundo os documentos [Manual da Carteira de Trabalho Digital](https://empregabrasil.mte.gov.br/wp-content/uploads/2023/02/Passo_a_Passo_CTPSDigital_APP_e_WEB.pdf) e [Cartilha da Carteira de Trabalho Digital](https://www.focuscontabil.com/wp-content/uploads/2020/05/Cartilha-CTP-Digital-02.pdf ), o artigo [Carteira de Trabalho Digital: Tudo o Que o DP Precisa Saber
](https://tangerino.com.br/blog/carteira-de-trabalho-ctps-digital/#:~:text=Afinal%2C%20a%20CTPS%20Digital%20permite,(CTPS)%20f%C3%ADsica%20se%20aposentou) e com a análise do aplicativo em sí, as principais funções da Carteira de Trabalho Digital são:

- Apresentar os seguintes dados pessoais com orientações e links para correção em caso de dados incorretos:
	- Nome Civil;
	- Sexo;
	- Data de Nascimento;
	- Nome da Mãe;
	- Nacionalidade;
	- Data de Emissão;
- Listagem dos contratos de trabalhos vigentes e anteriores, com data de início e fim. Cada contrato listado deve detalhar:
  - O período trabalhado;
  - O endereço do empregador;
  - Ocupação inicial;
  - Tipo de contrato;
  - Salário Contratual;
  - Remuneração Inicial;
  - Última Remuneração Informada;
  - Relação de Trabalho;
  - Tipo de Admissão;
  - Fonte da informação;
- Permitir anotações;
- Apresentar gráficos com histórico de remunerações;
- Gerar arquivo PDF com dados da carteira, parciais ou totais e com seleção individual;
- Ter aba “Benefícios” para consulta de Abono Salarial;
- Mostrar os dados e informações como:
  - Seguro-Desemprego;
  - Benefício TAC-Taxista;
  - Benefício Emergencial;
- Informar rendimentos para Imposto de Renda;
- Informar sobre o extrato CAGED;
- Ter "outras opções" que inclui:
  - Opção para ocultar dados sensíveis;
  - Política de privacidade;
  - Perguntas frequentes;
  - Aid Trabalho;
- Canal de Denúncias Trabalhistas;
- Avaliar aplicativo e Sobre;


**Observação:** Cada ponto citado acima precisa ter  item com respectivos detalhamentos e links para consultas externas quando não for possível informá-las no próprio aplicativo.

## Requisitos Não Funcionais

Ao contrário dos requisitos funcionais, os requisitos não funcionais se referem às características do software que não estão relacionadas diretamente às funcionalidades, mas sim à forma como ele deve operar. Esses requisitos englobam aspectos como desempenho, segurança, usabilidade, confiabilidade, escalabilidade, entre outros.

Neste contexto, são obrigatórias as especificações contidas na ePING para todos os sistemas de informação que são desenvolvidos e implantados no governo federal e que se enquadram no escopo de interação. segundo os [Padrões de Interoperabilidade de Governo Eletrônico - ePING](https://www.gov.br/governodigital/pt-br/governanca-de-dados/ePING_v2018_20171205.pdf) os aplicativos móveis do governo federal devem ser integráveis, ter crescimento escalável e suportar personalização. Além disso, as especificações selecionadas devem ter a capacidade de atender alterações de demanda no sistema, tais como, mudanças em volumes de dados, de quantidade de transações ou de quantidade de usuários. Assim como os padrões estabelecidos não podem ser fator restritivo e devem ser capazes de fundamentar o desenvolvimento de serviços, os quais atendam desde necessidades mais localizadas, ao envolver pequenos volumes, até demandas de abrangência nacional, com tratamento de abundância de informações.

Para os órgãos do governo federal, Poder Executivo brasileiro, a adoção dos padrões e políticas contidos na ePING é obrigatória, segundo a PORTARIA Nº 92, DE 24 DE DEZEMBRO DE 2014, da [SECRETARIA DE LOGÍSTICA E TECNOLOGIZADA INFORMAÇÃO](http://pesquisa.in.gov.br/imprensa/jsp/visualiza/index.jsp?jornal=1&pagina=50&data=26/12/2014 ).


## Integrações

Ao se analisar os documentos da [justiça do trabalho](https://www.trt1.jus.br/documents/22137/0/Orienta%C3%A7%C3%B5es+Esocial.pdf/ef831256-0c4e-6be4-a6a9-f8707022bcf2) e o [Manual da Carteira de Trabalho Digital](https://empregabrasil.mte.gov.br/wp-content/uploads/2023/02/Passo_a_Passo_CTPSDigital_APP_e_WEB.pdf), percebeu-se que o aplicativo, identificado por meio do número de inscrição do Cadastro de Pessoas Físicas (CPF), deve oferecer agilidade na solicitação e acesso fácil a informação de Qualificação Civil e de Contratos de trabalho. Isso através da integração de diversos bancos de dados do Governo Federal. Assim, destaca-se a integração com o [eSocial](https://login.esocial.gov.br/login.aspx ), projeto destinado a simplificar e unificar a entrega das obrigações trabalhistas, previdenciárias e fiscais em um único lugar.

Neste contexto, as informações lançadas no eSocial serão migradas para a Carteira de Trabalho Digital. Por isso, o empregador deve fazer todas as admissões, demissões e anotações por meio de navegador Web, ao utilizar apenas o CPF do trabalhador. O registro da admissão no eSocial pelo empregador já vale como “assinatura da carteira”. Além disso, todas as atualizações ou alterações relacionadas ao vínculo empregatício, como férias, alterações de salário ou cargo, também são enviadas para a Carteira de Trabalho Digital por meio do eSocial.

Devido a isso, os acessos às bases de dados do eSocial serão realizados por meio de APIs.
- Orientações sobre API de dados podem ser obtidas em [Portal da Transparência](https://portaldatransparencia.gov.br/api-de-dados )


Também foi identificado que a “Carteira de Trabalho Digital” deve estar integrada ao portal [gov.br](https://www.gov.br/pt-br ), inclusive, para autenticação de usuários. Consequentemente, para quem já tem cadastro no gov.br, basta usar seu login e senha de acesso no aplicativo Carteira de Trabalho Digital.

Com base nisso, no site do [gov.br](https://www.gov.br/pt-br ), há uma página de [requisitos para acesso aos serviços](https://www.gov.br/governodigital/pt-br/acessibilidade-e-usuario/atendimento-gov.br/duvidas-nos-dados-cadastrais/requisitos-para-acesso-aos-servicos ), a qual afirma o seguinte sobre a integração: “No momento da integração com a conta gov.br, o órgão ou entidade responsável pelo serviço, ou sistema, é responsável por decidir quais vão ser os requisitos necessários para que o cidadão possa fazer o login. Esses requisitos fazem parte do 3º passo no manual de integração informado ao órgão ou entidade, livre para decidir quais os requisitos são necessários para o uso e para a segurança do serviço ou sistema de sua competência.”

Portanto, conforme a integrações, segundo [Padrões de Interoperabilidade de Governo Eletrônico - ePING](https://www.gov.br/governodigital/pt-br/governanca-de-dados/ePING_v2018_20171205.pdf ), a modelagem do aplicativo deve:
- Evidenciar as integrações atuais e as integrações necessárias entre os dados;
- Apoiar as interações do governo em suas diversas secretarias e órgãos;
- Apoiar o alinhamento com os processos de negócios governamentais.


## Normas a serem seguidas na interface

Por ser um aplicativo do governo, é necessário que a Carteira de Trabalho Digital siga um conjunto de normas. Sendo assim, as convenções do aplicativo, como padrões tipográficos, siglas, abreviações, erros, entre outros, devem estar de acordo com [o Guia de Aplicativos Móveis do Governo Federal](https://www.gov.br/governodigital/pt-br/estrategias-e-governanca-digital/transformacao-digital/ferramentas/unificacao-de-canais/guia-de-apps ).

Além disso, manuais orientadores e boas práticas que o aplicativo deve seguir podem ser consultados em [Visão Geral](https://www.gov.br/ds/guias/visao-geral )

### Padrão da interface

A interface do aplicativo deve conter os elementos básicos de design para o [Padrão Digital de Governo](https://www.gov.br/ds/home ). Esses componentes são guiados por fundamentos visuais que abordam temas como cores, ilustrações, movimentos, tipografias, espaçamentos, sistemas de grids, ícones, entre outros. Eles são disponibilizados em:
- [Padrão mínimo de interface](https://www.gov.br/ds/introducao/padrao-minimo )
- [Visão Geral dos Fundamentos Visuais](https://www.gov.br/ds/fundamentos-visuais/visao-geral )
- [Padrão de Design](https://www.gov.br/ds/padroes/visao-geral )

Essas normas e “dicas” oferecidas pelo [o Guia de Aplicativos Móveis do Governo Federal](https://www.gov.br/governodigital/pt-br/estrategias-e-governanca-digital/transformacao-digital/ferramentas/unificacao-de-canais/guia-de-apps ) estabelecem uma linguagem visual consistente e coerente para todo [design system](https://www.gov.br/governodigital/pt-br/estrategias-e-governanca-digital/transformacao-digital/ferramentas/design-system#:~:text=O%20Design%20System%20apresenta%20os,interativos%20do%20Administra%C3%A7%C3%A3o%20P%C3%BAblica%20Federal ) . Dessa maneira, com suas diretrizes estabelecidas, há a garantia de que o design [system system](https://www.gov.br/governodigital/pt-br/estrategias-e-governanca-digital/transformacao-digital/ferramentas/design-system#:~:text=O%20Design%20System%20apresenta%20os,interativos%20do%20Administra%C3%A7%C3%A3o%20P%C3%BAblica%20Federal ) seja consistente a fim de criar experiências coesas a todos os usuários.


## Requisitos de Segurança

Os requisitos de segurança visam à proteção das informações e dos dados do
software ao garantir que o sistema seja resistente a ameaças e invasões, pois essa é a base da confidencialidade, da integridade e da proteção na disponibilidade dos dados no aplicativo. Sendo assim, eles envolvem aspectos como:
- Autenticação;
- Criptografia;
- Controle de acesso;
- Auditoria.

Devido a isso, aplicativos do Governo Digital devem se atentar às diretrizes e a práticas de segurança no controle de acesso à conta única de aplicativos móveis, como é indicado em [Práticas de Segurança no Controle de Acesso à Conta Única de Aplicativos Móveis](https://www.gov.br/governodigital/pt-br/estrategias-e-governanca-digital/transformacao-digital/ferramentas/unificacao-de-canais/guia-de-apps/praticas-seguranca-controle-acesso-a-conta-unica-unica-de-aplicativos-moveis ).

Portanto, a interoperabilidade na prestação dos serviços de governo eletrônico deve considerar o nível de segurança requerido pelo serviço, com a máxima transparência. Além disso, todos os órgãos responsáveis pelo oferecimento de serviços de governo eletrônico devem garantir as condições de preservação da privacidade das informações do cidadão, das empresas e dos órgãos de governo, respeitando e cumprindo a legislação que define as restrições de acesso e divulgação.



## Requisitos de Usabilidade na Acessibilidade

Os requisitos de usabilidade, que envolvem aspectos como interação com o usuário e simplicidade no uso, são responsáveis por garantir que o software seja fácil de usar e que proporcione uma boa experiência ao usuário, inclusive pessoas com deficiência,  que correspondem a 23,9% da população do país. Com base nisso, conforme previsto no Padrão Digital de Governo em [Acessibilidade](https://www.gov.br/ds/acessibilidade ), é necessário que o aplicativo contenha tecnologia assistiva, ou seja, recursos e serviços que visam facilitar o desenvolvimento de atividades da vida diária por pessoas com limitação, procurando aumentar as capacidades funcionais e promover a autonomia e a independência de quem as utiliza. Entre essas tecnologias, é possível citar:
- Ampliadores de telas;
- Leitores de telas;
- Programas de reconhecimento de voz.
- Teclados alternativos.
- Dispositivos apontadores alternativos: Simulam o funcionamento do mouse e, assim, podem ser usados por pessoas com alguma deficiência física.

Além disso, visando facilitar tanto o cruzamento de dados de diferentes fontes de informação, quando da sua utilização por outras organizações, devem ser utilizados recursos tais como;
- Vocabulários controlados;
- Taxonomias, ontologias e outros métodos de organização e recuperação de informações.

## Testes Necessários para garantir que os requisitos estão satisfeitos

O aplicativo deverá passar por um período de testes, inclusive uma fase beta, ou seja, uma fase de testes com grupo restrito de usuários até que seja lançado oficialmente.

Os testes que podem ser feitos são:

- Teste de mobilidade: valida a capacidade de comunicação do aplicativo com outras aplicações;
- Teste de compatibilidade: garante que o aplicativo esteja interagindo com o sistema operacional, com o hardware e com todas as redes, sem a perda de dados, travamento ou lentidão;
- Teste de usabilidade: assegura a experiência do usuário, validando que o aplicativo apresenta um visual agradável e intuitivo e pode ser utilizado dificultadamente por grupos de usuários heterogêneos;
- Teste de desempenho: elimina gargalos que podem provocar lentidão ou atraso do aplicativo;
- Teste funcional: aplicado em aplicativos mobile para garantir que contam com as funcionalidades planejadas;
- Teste de sincronismo: é voltado para aplicativos que utilizam armazenamento de dados em nuvem, caso do Padrão Digital de Governo, verificando que o aplicativo é capaz de realizar a sincronização na rede conforme o esperado.



## Requisitos encontrados

Aqui se encontra uma lista dos principais requisitos encontrados e elencados no decorrer desse artigo:

### Funcionais:

- Acesso a informação de Qualificação Civil e de Contratos de trabalho.
- Integração com o eSocial.
- Integração com o gov.br.
- Evidenciar as integrações atuais e as integrações necessárias entre os dados;
- As funcionalidades mostradas no tópico [Principais Funções do Aplicativo](#Principais-Funções-do-Aplicativo)
- Apoiar as interações do governo em suas diversas secretarias e órgãos;
- Apoiar o alinhamento com os processos de negócios governamentais.
- Devem ser utilizados recursos tais como
	- Vocabulários controlados;
	- Taxonomias, ontologias e outros métodos de organização e recuperação de informações.

### Não funcionais:

- Oferecer agilidade na solicitação da carteira.
- Permitir integração com vários outros software.
- Ser capaz de ter crescimento escalável e suportar personalização.
- Ter a capacidade de atender alterações de demanda no sistema, como mudanças em volumes de dados, de quantidade de transações ou de quantidade de usuários.
- Ser capaz de atender pequenos volumes de transações e de usuários, até demandas de abrangência nacional.
- Padrões tipográficos e de siglas, de abreviações e de erros de acordo com as normas.
- Seguir os manuais de interface de acordo com o gov.br.
- Conter os elementos básicos de design para o [Padrão Digital de Governo](https://www.gov.br/).
- Ter o básico de segurança:
- Autenticação;
- Criptografia;
- Controle de acesso;
- Auditoria;
- Atender as diretrizes e a práticas de segurança no controle de acesso à conta única.
- Garantir as condições de preservação da privacidade das informações do cidadão.
- Em relação à acessibilidade, deve conter:
- Ampliadores de telas;
- Leitores de telas;
- Programas de reconhecimento de voz.
- Teclados alternativos.
- Dispositivos apontadores alternativos: Simulam o funcionamento do mouse e, assim, podem ser usados por pessoas com alguma deficiência física.

## Conclusão:

É possível concluir que a implementação da Carteira de Trabalho Digital envolve a compreensão das necessidades dos usuários unidas com um conjunto de normas e leis que precisam ser obedecidas. Assim, houve um conjunto de requisitos elencados com a análise dos documentos.




## Bibliografia:

  1. ACNUR_CTPS. Orientações gerais sobre Carteira de Trabalho e Previdência Social - CTPS Digital. Disponível em: https://www.acnur.org/portugues/wp-content/uploads/2020/08/200806_ACNUR_CTPS.pdf. Acesso em 12 de abril de 2024.
  2. Barros, Jader. Carteira de Trabalho Digital: Tudo o Que o DP Precisa Saber. 11 de março de 2024. Disponível em: https://tangerino.com.br/blog/carteira-de-trabalho-ctps-digital/#:~:text=Afinal%2C%20a%20CTPS%20Digital%20permite,(CTPS)%20f%C3%ADsica%20se%20aposentou.
  3. Cartilha da carteira de trabalho digital. Disponível em: https://www.focuscontabil.com/wp-content/uploads/2020/05/Cartilha-CTP-Digital-02.pdf. Acesso em 13 de abril de 2024.
  4. Carteira de Trabalho e Previdência Social (CTPS). Gov.br. Disponível em: https://www.gov.br/trabalho-e-emprego/pt-br/servicos/trabalhador/carteira-de-trabalho. Acesso em 13 de abril de 2024.
  5. Design sistemy. Gov.br. Disponível em: https://www.gov.br/governodigital/pt-br/estrategias-e-governanca-digital/transformacao-digital/ferramentas/design-system#:~:text=O%20Design%20System%20apresenta%20os,interativos%20do%20Administra%C3%A7%C3%A3o%20P%C3%BAblica%20Federal. Acesso em 12 de abril de 2024.
  6. Ministério do Trabalho e Emprego. Manual da Carteira de Trabalho Digital. Governo Federal do Brasil. Disponível em: https://empregabrasil.mte.gov.br/wp-content/uploads/2023/02/Passo_a_Passo_CTPSDigital_APP_e_WEB.pdf. Acesso em 12 de abril de 2024.
  7. Padrão Digital de Governo. Design Padrão. Disponível em: https://www.gov.br/ds/padroes/visao-geral. Acesso em 12 de abril de 2024.
  8. Padrão Digital de Governo. Fundamentos visuais. Disponível em: https://www.gov.br/ds/fundamentos-visuais/visao-geral. Acesso em 13 de abril de 2024.
  9. Padrão Digital de Governo. Padrão Mínimo. Disponível em: https://www.gov.br/ds/introducao/padrao-minimo. Acesso em 13 de abril de 2024.
  10. Portal do G1. Como tirar carteira de trabalho? Acesso em: https://g1.globo.com/economia/noticia/2022/04/12/como-tirar-carteira-de-trabalho.ghtml.Acesso em 13 de abril de 2024.
  11. Portal da Transparência do Governo Federal. API de Dados. Disponível em: https://portaldatransparencia.gov.br/api-de-dados. Acesso em 12 de abril de 2024.
  12. Requisitos para acesso aos serviços. Gov.br. Acesso em: https://www.gov.br/governodigital/pt-br/acessibilidade-e-usuario/atendimento-gov.br/duvidas-nos-dados-cadastrais/requisitos-para-acesso-aos-servicos. Acesso em 12 de abril de 2024. Acesso em 13 de abril de 2024.
  13. Secretaria de Logística e Tecnologia da Informação. Portaria nº 92, de 24 de dezembro de 2014. Diário Oficial da União. Disponível em: http://pesquisa.in.gov.br/imprensa/jsp/visualiza/index.jsp?jornal=1&pagina=50&data=26/12/2014. Acesso em 13 de abril de 2024.
  14. Tribunal Regional do Trabalho da 1ª Região, Corregedoria Regional. Nome: E-social (Baixa da CTPS Digital). Disponível em: https://www.trt1.jus.br/documents/22137/0/Orienta%C3%A7%C3%B5es+Esocial.pdf/ef831256-0c4e-6be4-a6a9-f8707022bcf2. Acesso em 13 de abril de 2024.
  15. Guia de Aplicativos Móveis do Governo Federal. Gov.br. Disponível em: https://www.gov.br/governodigital/pt-br/estrategias-e-governanca-digital/transformacao-digital/ferramentas/unificacao-de-canais/guia-de-apps.Acesso em 12 de abril de 2024.
  16. Padrões de Interoperabilidade de Governo Eletrônico. Documento de Referência, EPIG. Gov.br. Disponível em: https://www.gov.br/governodigital/pt-br/governanca-de-dados/ePING_v2018_20171205.pdf. Acesso em 12 de abril de 2024.
  17. Ministério da Gestão e da Inovação em Serviços Públicos. Lei do Governo Digital entra em vigor. Disponível em: https://www.gov.br/gestao/pt-br/acesso-a-informacao/acoes-e-programas/principais-acoes-na-area-economica/acoes-2021/lei-do-governo-digital-entra-em-vigor#:~:text=A%20Lei%20do%20Governo%20Digital,e%20da%20participa%C3%A7%C3%A3o%20dos%20cidad%C3%A3os. Acesso em 12 de abril de 2024.
  18. Presidência da República. Secretaria-Geral. Subchefia para Assuntos Jurídicos. Lei nº 14.129, de 29 de março de 2021. Disponível em: https://www.planalto.gov.br/ccivil_03/_ato2019-2022/2021/lei/L14129.htm.

## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação e execução da análise de documentos| Larissa Stéfane | Breno Alexandre |  14/04/2024 |
| 1.1 | Reogarnização de alguns pontos| Larissa Stéfane | - |  17/05/2024 |
