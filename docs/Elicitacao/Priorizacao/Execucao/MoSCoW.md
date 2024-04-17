# Técnica de Priorização MoSCoW

## Sumário

* [Introdução](#Introdução)
* [Metodologia](#metodologia)
* []()
* []()
* [Bibliografia](#bibliografia)
* [Histórico de versão](#Histórico-de-versão)

## Introdução

Considerando que temos 2 técnicas de priorização realizadas, para dar maior credibilidade aos resultados, vamos fazer a execução da técnica MoSCoW, que será mais detalhada no tópico [Metodologia](#metodologia). 

## Metodologia
A técnica MoSCoW tem em enfâse dividir os requisitos em 4 classificações que derivam o nome da técnica:

* Must Have(Precisa ter): Requisitos de nível prioritário e/ou críticos
* Should Have(Deveria ter): Requisitos de nível importante, mas não são necessários para a entrega no atual momento
* Could Have(Poderia ter): Requisitos de nível desejável, mas não necessários, itens que podem ser integrados dependendo da disponibilidade de tempo e recursos
* Won't Have (Não irá ter): Requisitos de menor nível de criticidade, com menor retorno sobre o investimento. Pode signitificar "Would" ou "Want", que siginifica gostaria.

Vale frisar que a técnica MoSCoW não obriga uma justificativa para a tomada de decisão sobre a prioridade de um requisito sobre outro, principalmente quando falamos do nível "Won't", que pode significar uma baixa importância ou que o requisito nunca será utilizado. Portanto está técnica pode gerar ambiguidades e não é recomendado o uso da mesma de forma isolada, o seu uso se torna interessante como uma técnica complementar.

## Execução da Técnica

A técnica foi aplicada com uma entrevista, com dados na [tabela 1](#tabela-1-dados-da-entrevista), do usuário Wildemberg Sales, que se encaixa no [perfil de usuário](https://requisitos-de-software.github.io/2024.1-CarteiradeTrabalhoDigital/#/Elicitacao/PerfilDeUsuario), onde foi apresentado a lista de [Requisitos Elicitados](https://requisitos-de-software.github.io/2024.1-CarteiradeTrabalhoDigital/#/Elicitacao/RequisitosElicitados) e eles foram julgados seguindo as métricas da técnica MoSCoW. 

#### Tabela 1: dados da entrevista
| Entrevistado(a) | Entrevistador | data | 
| - | - | - |
| Wildemberg Sales | [Caio Mesquita](https://github.com/Caiomesvie) |17/04/24|

Fonte:  [Caio Mesquita](https://github.com/Caiomesvie) 

O vídeo está disponível através deste [Link](), ou no vídeo abaixo:

<center>
 
 Vídeo 1: Entrevista Wildemberg Sales



Fonte: [Caio Mesquita](https://github.com/Caiomesvie)

</center>

## Resultados obtidos
A Seguir vem as Tabelas [2]() e [3](), que mostram os resultados coletados pela entrevista a respeito dos requisitos elicitados. Foram separados em duas tabelas, Requisitos Funcionais e Requisitos Não-Funcionais.

### Requisitos Funcionais



Legendas:

- F + número: Requisito funcional número x.

<center>

#### Tabela 2: Requisitos Funcionais



| Identificação do Requisito | Requisito | M,S,C e W | 
|-----------------------------|-----------|-----------------------|
| F1                          | Apresentar dados pessoais com orientações e links para correção |  |
| F2                          | Listar contratos de trabalho com detalhes |  |
| F3                          | Listar contratos de trabalho corretamente |  |
| F4                          | Permitir anotações |   | 
| F5                          | Apresentar gráficos com histórico de remunerações |  |
| F6                         | Gerar arquivo PDF com dados da carteira |  |
| F7                         | Ter aba "Benefícios" |   |
| F8                          | Mostrar dados como Seguro-Desemprego, Benefício TAC-Taxista, Benefício Emergencial | |
| F9                          | Oferecer opções como ocultar dados sensíveis, política de privacidade, perguntas frequentes, entre outros. |   |
| F11                         | Acesso à informação de Qualificação Civil e Contratos de Trabalho |   |
| F12                         | Integração com eSocial |  |
| F13                         | Integração com gov.br |  |
| F14                         | Permitir integração com vários outros software.  |   |
| F15                         | Disponibilizar informações essenciais para os trabalhadores de forma acessível |   |
| F16                         | Mandar notificações verdadeiras, evitando alarmes falsos |   |
| F17                         | Estar adaptado para ser instalado em qualquer sistema operacional |  |
| F18                      | Atualizar os dados do usuário constantemente para evitar defasagem |   |
| F19                         | Informaçõe sobre o FGTS |   |
| F20                         | Ter dados sobre o número da carteira e de série como CIPS | |
| F21                         | Ter informações de abono salarial |  |


Fonte: [Caio Mesquita](https://github.com/Caiomesvie)

</center>


### Requisitos não-Funcionais

Legendas: 
- NF + número: Requisito não funcional número x.

<center>


#### Tabela 3: Requisitos Não-Funcionais


| Identificação do Requisito | Requisito                                                                                                                                                  | M,S,C e W| 
|-----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------|
|NF1                          |Oferecer agilidade na solicitação da carteira. |   |
| NF2                         | Ser capaz de ter crescimento escalável e suportar personalização.  |    |
| NF3                         | Ter a capacidade de atender alterações de demanda no sistema, como mudanças em volumes de dados, de quantidade de transações ou de quantidade de usuários. |    |
| NF4                         | Ser capaz de atender pequenos volumes de transações e de usuários, até demandas de abrangência nacional.     |   |
| NF5                         | Padrões tipográficos e de siglas, de abreviações e de erros de acordo com as normas.   |    |
| NF6                         | Seguir os manuais de interface de acordo com o gov.br.    |       |
| NF7                         | Conter os elementos básicos de design para o Padrão Digital de Governo.     |     |
| NF8                         | Ter o básico de segurança: Autenticação, Criptografia, Controle de acesso, Auditoria, Atender as diretrizes e a práticas de segurança no controle de acesso à conta única. |    |
| NF9                      | Garantir as condições de preservação da privacidade das informações do cidadão.        |      |
| NF10                       | Em relação à acessibilidade, deve conter: Ampliadores de telas, Leitores de telas, Programas de reconhecimento de voz, Teclados alternativos, Dispositivos apontadores alternativos. |    |
| NF11                         | Apoiar interações do governo e alinhamento com processos de negócios governamentais |    |
| NF12                        | Utilização de recursos como vocabulários controlados e taxonomias |   |
| NF13                         | Agilidade na solicitação da carteira |  |
| NF14                       | O aplicativo deve seguir um padrão aceito por empresas e instituições sem provocar transtornos |   |
| NF15                         | Acesso a alguns pontos do aplicativo exige biometria eficiente e prática |   |
| NF16                         | O aplicativo deve permitir ao usuário atualizar seus dados sem causar transtornos e evitar burocracias |   |

Fonte: [Caio Mesquita](https://github.com/Caiomesvie)


</center>



## Conclusão


## Bibliografia

1. **Requisitos elicitados**. Disponível em < https://github.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/blob/main/docs/Elicitacao/RequisitosElicitados.md > Acesso em 14 de abril de 2024.
2. BEATTY, Joy; WIEGERS, Karl. Software Requirements. 3. ed.  Microsoft press, 2013.
   
## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação e execução da Técnica MoSCoW | Caio Mesquita | Breno Alexandre  |  15/04/2024 |

