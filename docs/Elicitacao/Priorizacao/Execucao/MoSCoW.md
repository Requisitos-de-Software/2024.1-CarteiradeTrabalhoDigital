# Técnica de Priorização MoSCoW

## Sumário

* [Introdução](#Introdução)
* [Metodologia](#metodologia)
* [Execução da Técnica](#execução-da-técnica)
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

<iframe width="697" height="381" src="https://www.youtube.com/embed/mGdq-60At3g" title="Entrevista Wildemberg Requisitos Priorização MoSCoW" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Fonte: [Caio Mesquita](https://github.com/Caiomesvie)

</center>

## Resultados obtidos
A Seguir vem as Tabelas [2]() e [3](), que mostram os resultados coletados pela entrevista a respeito dos requisitos elicitados. Foram separados em duas tabelas, Requisitos Funcionais e Requisitos Não-Funcionais.

* Observação: devido a erro na tabela os Requisitos funcionais 10 e 22 foram coletados posteriormente


### Requisitos Funcionais

Legendas:

- F + número: Requisito funcional número x.

<center>

#### Tabela 2: Requisitos Funcionais



| Identificação do Requisito | Requisito | M,S,C e W | 
|-----------------------------|-----------|-----------------------|
| F1                          | Apresentar dados pessoais com orientações e links para correção | M |
| F2                          | Listar contratos de trabalho com detalhes | M |
| F3                          | Listar contratos de trabalho corretamente | M  |
| F4                          | Permitir anotações | C  | 
| F5                          | Apresentar gráficos com histórico de remunerações | S |
| F6                         | Gerar arquivo PDF com dados da carteira |   S|
| F7                         | Ter aba "Benefícios" | M  |
| F8                          | Mostrar dados como Seguro-Desemprego, Benefício TAC-Taxista, Benefício Emergencial |  M|
| F9                          | Oferecer opções como ocultar dados sensíveis, política de privacidade, perguntas frequentes, entre outros. | C *  |
| F10                          | Possibilitar avaliação do aplicativo e acesso à seção "Sobre" | M |
| F11                         | Acesso à informação de Qualificação Civil e Contratos de Trabalho | M  |
| F12                         | Integração com eSocial |S   |
| F13                         | Integração com gov.br |S  |
| F14                         | Permitir integração com vários outros software.  | M * |
| F15                         | Disponibilizar informações essenciais para os trabalhadores de forma acessível |  M   |
| F16                         | Mandar notificações verdadeiras, evitando alarmes falsos | M  |
| F17                         | Estar adaptado para ser instalado em qualquer sistema operacional | M  |
| F18                      | Atualizar os dados do usuário constantemente para evitar defasagem | M *  |
| F19                         | Informaçõe sobre o FGTS | M    |
| F20                         | Ter dados sobre o número da carteira e de série como CIPS | M |
| F21                         | Ter informações de abono salarial | M  |
| F22                         | Apresentar dados básicos do usuário | M  |



Fonte: [Caio Mesquita](https://github.com/Caiomesvie)

</center>


### Requisitos não-Funcionais

Legendas: 
- NF + número: Requisito não funcional número x.

<center>


#### Tabela 3: Requisitos Não-Funcionais


| Identificação do Requisito | Requisito                                                                                                                                                  | M,S,C e W| 
|-----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------|
|NF1                          |Oferecer agilidade na solicitação da carteira. | M  |
| NF2                         | Ser capaz de ter crescimento escalável e suportar personalização.  |   S |
| NF3                         | Ter a capacidade de atender alterações de demanda no sistema, como mudanças em volumes de dados, de quantidade de transações ou de quantidade de usuários. |  M  |
| NF4                         | Ser capaz de atender pequenos volumes de transações e de usuários, até demandas de abrangência nacional.     | M  |
| NF5                         | Padrões tipográficos e de siglas, de abreviações e de erros de acordo com as normas.   | C  |
| NF6                         | Seguir os manuais de interface de acordo com o gov.br.    |  M   * |
| NF7                         | Conter os elementos básicos de design para o Padrão Digital de Governo.     | M * |
| NF8                         | Ter o básico de segurança: Autenticação, Criptografia, Controle de acesso, Auditoria, Atender as diretrizes e a práticas de segurança no controle de acesso à conta única. |  M  |
| NF9                      | Garantir as condições de preservação da privacidade das informações do cidadão.        |  M    |
| NF10                       | Em relação à acessibilidade, deve conter: Ampliadores de telas, Leitores de telas, Programas de reconhecimento de voz, Teclados alternativos, Dispositivos apontadores alternativos. | M  |
| NF11                         | Apoiar interações do governo e alinhamento com processos de negócios governamentais | C  |
| NF12                        | Utilização de recursos como vocabulários controlados e taxonomias | M  |
| NF13                         | Agilidade na solicitação da carteira | M * |
| NF14                       | O aplicativo deve seguir um padrão aceito por empresas e instituições sem provocar transtornos | W |
| NF15                         | Acesso a alguns pontos do aplicativo exige biometria eficiente e prática | S * |
| NF16                         | O aplicativo deve permitir ao usuário atualizar seus dados sem causar transtornos e evitar burocracias | M |

Fonte: [Caio Mesquita](https://github.com/Caiomesvie)


</center>



## Conclusão

Após a entrevista, foi percebido que a maioria dos requisitos coletados são relevantes, pórem existem ambiguidades que devem ser consideradas, além da organização de requisitos funcionais e não funcionais. Deve haver atenção com certos requisitos para uma correção futura antes de dar prosseguimento com o projeto.


## Bibliografia

1. **Requisitos elicitados**. Disponível em < https://github.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/blob/main/docs/Elicitacao/RequisitosElicitados.md > Acesso em 14 de abril de 2024.
2. BEATTY, Joy; WIEGERS, Karl. Software Requirements. 3. ed.  Microsoft press, 2013.
3. Serrano, Milene. Serrano, Maurício. **Técnicas de Requisitos**. Disponível em <https://aprender3.unb.br/pluginfile.php/2844991/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>. Acesso em 16 de Abril de 2024

   
## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação e execução da Técnica MoSCoW | Caio Mesquita | Breno Alexandre  |  15/04/2024 |

