9# Técnica de Priorização da Classificação por Quadrantes ou Three Level Scale

## Sumário

* [Introdução](#Introdução)
* [Metodologia](#Metodologia)
* [Cronograma](#Cronograma)
* [Requisitos de Alta Prioridade](#Requisitos-de-Alta-Prioridade)
* [Requisitos de Média Prioridade](#Requisitos-de-Média-Prioridade)
* [Requisitos de Baixa Prioridade](#Requisitos-de-Baixa-Prioridade)
* [Requisitos que Não Precisam Ser Realizados](#Requisitos-que-Não-Precisam-Ser-Realizados)
* [Conclusão](#Conclusão)
* [Bibliografia](#Bibliografia)
* [Histórico de versão](#Histórico-de-versão)

## Introdução

A priorização de requisitos é uma etapa crucial no processo de desenvolvimento de qualquer produto ou sistema. Com isso, neste documento, é apresentado a priorização de requisitos por meio de classificação em três níveis ou quadrantes, destacando a importância de cada requisito e fornecendo uma estrutura para orientar quais requisitos priorizar. Para isso foi realizada um reunião com um usuário da Carteira de Trabalho Digital.

## Metodologia
A priorização de requisitos por meio da técnica dos três(quatro) níveis, ou quadrantes, é uma forma de classificar e organizar os requisitos de um projeto com base em sua importância e viabilidade. Desse modo, baseando-se na [análise dessa técnica](Elicitacao/Priorizacao/tecnicaClassificacao.md), a foi realizada uma reunião com um usuário do aplicativo, o José Santos, e nela os requisitos elicitados foram classificados em:
- Requisitos de Alta Prioridade;
- Requisitos de Média Prioridade;
- Requisitos de Baixa Prioridade;
- Requisitos que Não Precisam Ser Realizados;

Portanto, ocorreu uma análise cuidadosa de cada requisito, levando em consideração fatores da importância na visão do usuárioo usuário.

## Cronograma
A tabela 1 mostra como foi a organização do cronograma durante a realização da priorização.

</center>

Tabela 1: Cronograma.

| Data       | Atividade                                             |
|------------|-------------------------------------------------------|
| 13/04/2024 | Elicitação de requisitos                              |
| 15/04/2024 | Documentação dos requisitos em um documento          |
| 16/04/2024 | Priorização de requisitos - Reunião com José às 18:00 |
| 16/04/2014 | Documentação das decisões tomadas |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</center>

## Reunião

O vídeo 1 mostra a reunião realizada com o usuário José.

<center>

<iframe width="697" height="392" src="https://www.youtube.com/embed/oAXFyz4xY-o" title="Técnica de priorização com José - Requisitos de Software" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**Apresentação 01**

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme).

Caso vídeo não esteja disponível, acessar por meio deste [link](https://www.youtube.com/watch?v=oAXFyz4xY-o).

</center>

**Observação:** Por erro, no vídeo não está a classificação dos seguintes requisitos: 
  - Ter  Informação sobre o FGTS.
  - Ter dados sobre o número da carteira e de série como CIPS.
  - Ter informações de abono salarial.
Em uma conversa com o José Santos, ele classificou da seguinte forma:
  - Ter  Informação sobre o FGTS: Média prioridade.
  - Ter dados sobre o número da carteira e de série como CIPS: Alta prioridade.
  - Ter informações de abono salarial: Alta prioridade.
  
## Requisitos de Alta Prioridade

Foram classificados aqui os requisitos que são considerados urgentes e importantes.

Para ter acesso aos conjunto de todos os requisitos elicitados, clique me [Requisitos Elicitados](Elicitacao/RequisitosElicitados.md)

### Requisitos Funcionais:

 - Apresentar os dados básicos do usuário.
 - Atualizar os dados do usuário constantemente para evitar defasagem.
 - Ter aba "Benefícios".
 - Listar contratos de trabalho corretamente.
 - Mostrar dados como Seguro-Desemprego, Benefício TAC-Taxista, Benefício Emergencial.
 - Integração com eSocial.
 - Integração com gov.br.
 - Ter dados sobre o número da carteira e de série como CIPS.
 - Ter informações de abono salarial.

### Requisitos não funcionais

 - Ser capaz de ter crescimento escalável e suportar personalização.
 - Ter o básico de segurança: Autenticação, Criptografia, Controle de acesso, Auditoria, Atender as diretrizes e a práticas de segurança no controle de acesso à conta única.
 - Utilização de recursos como vocabulários controlados e taxonomias
 - Garantir as condições de preservação da privacidade das informações do cidadão.

## Requisitos de Média Prioridade

Foram classificados aqui os requisitos que são considerados não tão urgentes, mas importantes.


### Requisitos Funcionais:

  - Listar contratos de trabalho com detalhes
  - Gerar arquivo PDF com dados da carteira
  - Possibilitar avaliação do aplicativo e acesso à seção "Sobre"
  - Mandar notificações verdadeiras, evitando alarmes falsos
  - Estar adaptado para ser instalado em qualquer sistema operacional
  - Acesso à informação de Qualificação Civil e Contratos de Trabalho
  - Disponibilizar informações essenciais para os trabalhadores de forma acessível

### Requisitos Não Funcionais:

  - Oferecer agilidade na solicitação da carteira.
  - Conter os elementos básicos de design para o Padrão Digital de Governo.
  - Em relação à acessibilidade, deve conter: Ampliadores de telas, Leitores de telas, Programas de reconhecimento de voz, Teclados alternativos, Dispositivos apontadores alternativos.
  - Seguir os manuais de interface de acordo com o gov.br.
  - Acesso a alguns pontos do aplicativo exige biometria eficiente e prática
  - Ter a capacidade de atender alterações de demanda no sistema, como mudanças em volumes de dados, de quantidade de transações ou de quantidade de usuários.
    
## Requisitos de Baixa Prioridade

Foram classificados aqui os requisitos que são considerados não urgentes e não tão importantes.

### Requisitos Funcionais:

 - Apresentar gráficos com histórico de remunerações
 - Permitir integração com outros softwares
 - Permitir anotações
 - Apresentar dados pessoais com orientações e links para correção
 - Oferecer opções como ocultar dados sensíveis, política de privacidade, perguntas frequentes, entre outros.
   
### Requisitos Não Funcionais:

  - Ser capaz de atender pequenos volumes de transações e de usuários, até demandas de abrangência nacional.
  - Padrões tipográficos e de siglas, de abreviações e de erros de acordo com as normas.
  - Apoiar interações do governo e alinhamento com processos de negócios governamentais
  - O aplicativo deve seguir um padrão aceito por empresas e instituições sem provocar transtornos
  - O aplicativo deve permitir ao usuário atualizar seus dados sem causar transtornos e evitar burocracias

## Requisitos que Não Precisam Ser Realizados

Foram classificados aqui os requisitos que não são urgentes nem são importantes.

### Requisitos Funcionais:

- Nenhum dos requisitos analisados foram classificados para serem classificados aqui, ou seja, todos parecem ser relevantes para o funcionamento adequado do aplicativo.

### Requisitos Não Funcionais:

- Assim como os requisitos funcionais, nenhum dos requisitos analisados foram classificados para serem classificados aqui.

## Conclusão

Ao adotar a abordagem que prioriza requisitos por meio de classificação em três níveis ou quadrantes, foi possível identificar os requisitos que têm o maior impacto nos usuários e na estrutura do aplicativo. 

## Bibliografia

1. **Requisitos elicitados**. Disponível em < https://github.com/Requisitos-de-Software/2024.1-CarteiradeTrabalhoDigital/blob/main/docs/Elicitacao/RequisitosElicitados.md > Acesso em 14 de abril de 2024.
   
## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação e execução da priorização de 3 níveis | Larissa Stéfane| Breno Alexandre  |  15/04/2024 |
| 1.1 | Adição da introdução e da conlusão | Breno Alexandre | Larissa Stéfane  |  16/04/2024 |
| 1.2 | Reformulação com um usuário de verdade | Larissa Stéfane | Bruno Araújo |  16/04/2024 |

