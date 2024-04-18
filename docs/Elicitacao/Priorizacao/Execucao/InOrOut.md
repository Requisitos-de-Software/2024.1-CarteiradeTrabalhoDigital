# Técnica de Priorização In or Out

## Sumário

* [Introdução](#Introdução)
* [Metodologia](#metodologia)
* [Execução da Técnica](#execução-da-técnica)
* [Resultados Obtidos](#resultados-obtidos)
* [Conclusão](#conclusão)
* [Bibliografia](#bibliografia)
* [Histórico de versão](#Histórico-de-versão)

## Introdução

Dada a Importância da priorizaçao para a elicitação dos requisitos durante o processo de desenvolvimento, foram  realizadas mais de uma técnica de priorização e neste documento conterá a análise da técnica In or Out, devida a sua simplicidade de execução.

## Metodologia

A técnica "In or Out" é a mais simples das priorizações, um dos motivos para o uso dela nesta etapa. Ela se resume em apresentar ao usuário a listagem de requisitos elicitados e o usuário entrevistado faz uma escolha binária, "dentro ou fora", para que possibilite aos desenvolvedores ter um norte a respeito de requisitos a serem repensados em uma próxima release de projeto. 
É importante ressaltar que as decisões de "In" ou "out" devem sempre ser baseadas nas regras de negócio

## Execução da Técnica
A técnica foi aplicada com uma entrevista, com dados na [tabela 1](#tabela-1-dados-da-entrevista), da usuária Natália Beatriz, que se encaixa no [perfil de usuário](https://requisitos-de-software.github.io/2024.1-CarteiradeTrabalhoDigital/#/Elicitacao/PerfilDeUsuario), onde foi apresentado a lista de [Requisitos Elicitados](https://requisitos-de-software.github.io/2024.1-CarteiradeTrabalhoDigital/#/Elicitacao/RequisitosElicitados) e eles foram julgados arbitrariamente em "In or Out". 

#### Tabela 1: dados da entrevista
| Entrevistado(a) | Entrevistador | data | 
| - | - | - |
| Natália Beatriz | [Caio Mesquita](https://github.com/Caiomesvie) |16/04/24|

Fonte:  [Caio Mesquita](https://github.com/Caiomesvie) 

O vídeo está disponível através deste [Link](), ou no vídeo abaixo:

<center>
 
 Vídeo 1: Entrevista Natália Beatriz

 <iframe width="697" height="392" src="https://www.youtube.com/embed/5A3F0Td13rc" title="Entrevista Natália Beatriz Priorização In or Out Requisitos" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Fonte: [Caio Mesquita](https://github.com/Caiomesvie)

</center>

## Resultados obtidos
A Seguir vem as Tabelas [2]() e [3](), que mostram os resultados coletados pela entrevista a respeito dos requisitos elicitados. Foram separados em duas tabelas, Requisitos Funcionais e Requisitos Não-Funcionais.

### Requisitos Funcionais



Legendas:

- F + número: Requisito funcional número x.

<center>

#### Tabela 2: Requisitos Funcionais



| Identificação do Requisito | Requisito |In or Out | 
|-----------------------------|-----------|-----------------------|
| F1                          | Apresentar dados pessoais com orientações e links para correção | in |
| F2                          | Listar contratos de trabalho com detalhes | in |
| F3                          | Listar contratos de trabalho corretamente | in |
| F4                          | Permitir anotações | out  | 
| F5                          | Apresentar gráficos com histórico de remunerações | in |
| F6                         | Gerar arquivo PDF com dados da carteira | in |
| F7                         | Ter aba "Benefícios" |  in |
| F8                          | Mostrar dados como Seguro-Desemprego, Benefício TAC-Taxista, Benefício Emergencial | in |
| F9                          | Oferecer opções como ocultar dados sensíveis, política de privacidade, perguntas frequentes, entre outros. | in  |
| F10                          | Possibilitar avaliação do aplicativo e acesso à seção "Sobre" | in |
| F11                         | Acesso à informação de Qualificação Civil e Contratos de Trabalho |  in |
| F12                         | Integração com eSocial |  in|
| F13                         | Integração com gov.br | in |
| F14                         | Permitir integração com vários outros software.  |  in |
| F15                         | Disponibilizar informações essenciais para os trabalhadores de forma acessível | in  |
| F16                         | Mandar notificações verdadeiras, evitando alarmes falsos | in  |
| F17                         | Estar adaptado para ser instalado em qualquer sistema operacional | in  |
| F18                      | Atualizar os dados do usuário constantemente para evitar defasagem | in  |
| F19                         | Informaçõe sobre o FGTS | in  |
| F20                         | Ter dados sobre o número da carteira e de série como CIPS | in |
| F21                         | Ter informações de abono salarial | in  |


Fonte: [Caio Mesquita](https://github.com/Caiomesvie)

</center>


### Requisitos não-Funcionais

Legendas: 
- NF + número: Requisito não funcional número x.

<center>


#### Tabela 3: Requisitos Não-Funcionais


| Identificação do Requisito | Requisito                                                                                                                                                  | "In or Out"| 
|-----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------|
|NF1                          |Oferecer agilidade na solicitação da carteira. | in  |
| NF2                         | Ser capaz de ter crescimento escalável e suportar personalização.       |  out     |
| NF3                         | Ter a capacidade de atender alterações de demanda no sistema, como mudanças em volumes de dados, de quantidade de transações ou de quantidade de usuários. |  in     |
| NF4                         | Ser capaz de atender pequenos volumes de transações e de usuários, até demandas de abrangência nacional.        |   in  |
| NF5                         | Padrões tipográficos e de siglas, de abreviações e de erros de acordo com as normas.                                                                       |   in     |
| NF6                         | Seguir os manuais de interface de acordo com o gov.br.                                                                                                     |    in      |
| NF7                         | Conter os elementos básicos de design para o Padrão Digital de Governo.                                                                                    |    in    |
| NF8                         | Ter o básico de segurança: Autenticação, Criptografia, Controle de acesso, Auditoria, Atender as diretrizes e a práticas de segurança no controle de acesso à conta única. | in    |
| NF9                      | Garantir as condições de preservação da privacidade das informações do cidadão.                                                                            | in     |
| NF10                       | Em relação à acessibilidade, deve conter: Ampliadores de telas, Leitores de telas, Programas de reconhecimento de voz, Teclados alternativos, Dispositivos apontadores alternativos. |  in  |
| NF11                         | Apoiar interações do governo e alinhamento com processos de negócios governamentais |  in  |
| NF12                        | Utilização de recursos como vocabulários controlados e taxonomias | in  |
| NF13                         | Agilidade na solicitação da carteira | in |
| NF14                       | O aplicativo deve seguir um padrão aceito por empresas e instituições sem provocar transtornos | in  |
| NF15                         | Acesso a alguns pontos do aplicativo exige biometria eficiente e prática |  in |
| NF16                         | O aplicativo deve permitir ao usuário atualizar seus dados sem causar transtornos e evitar burocracias | in  |

Fonte: [Caio Mesquita](https://github.com/Caiomesvie)


</center>



## Conclusão

Após a entrevista, foi percebido que a maioria dos requisitos coletados são relevantes, pórem existem ambiguidades que devem ser consideradas, além da organização de requisitos funcionais e não funcionais. Deve haver atenção a certos requisitos para uma correção futura antes de dar prosseguimento com o projeto.

## Bibliografia

1. **Requisitos elicitados**. Disponível em < https://github.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/blob/main/docs/Elicitacao/RequisitosElicitados.md > Acesso em 14 de abril de 2024.
2. BEATTY, Joy; WIEGERS, Karl. Software Requirements. 3. ed.  Microsoft press, 2013.
   
## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação e execução da priorização In or Out | Caio Mesquita| -  |  16/04/2024 |


