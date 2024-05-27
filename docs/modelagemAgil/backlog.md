# Backlog do Produto

## Sumário

* [Introdução](#Introdução)
* [Metodologia](#Metodologia)
* [Roteiro da Reunião para o Backlog](#Roteiro-da-Reunião-para-o-Backlog)
* []()
* []()
* []()




## Introdução

O Backlog do produto é uma artefato proveniente de metodologias ágeis, onde há uma lista de funcionalidades a serem concebidas no projeto com o objetivo de manter a equipe alinhada com as tarefas que devem ser realizadas e dividir as tarefas de forma intuitiva e de fácil compreensão. Estas funcionalidades estão listadas de forma priorizadas com a participação do Product Owner (dono do produto) no processo de priorização.

## Metodologia

Para a confecção do backlog do produto deste projeto, partimos do uso do artefato [Requisitos Elicitados](Elicitacao/ResquisitosCorrigidos.md) utilizando as técnicas de elicitação e priorização nas etapas anteriores para definir as tarefas a serem realizadas. Para minimizar essas tarefas e faciliar o entendimento delas, elas foram dividias em Tópicos e sub-tópicos, demonstradas na tabela 1, além de conter o seu nível de priorização. 

<center>
Tabela 1: Modelo do Backlog do produto

|Tema|Épico|História de Usuário|Prioridade|
|-|-|-|-|
|Generalizam o escopo das tarefas em grandes blocos mais abstratos |Formam o escopo das histórias de usuário mais bem definido, e menos abstrato que os temas | Neste documento serão citadas as histórias de usuário, as mesmas serão melhor detalhadas neste [link](modelagemAgil/historiaUsuario.md)| |

Fonte: [Caio Mesquita]()

</center>

## Roteiro da Reunião para o Backlog

### Apresentação do usuário/participante

**Objetivo desta etapa:** Fazer a apresentação do usuário.

- **Importante** - Perguntar sobre o consentimento: Falar sobre o porquê da reunião e falar sobre os seus direitos de armazenamentos de dados e perguntar se o participante concorda.

#### Perguntas:

- Qual o seu nome?
- Desea complementar a sua apresentação?
- Qual a sua relação com o aplicativo da carteira de trabalho digital?

### Revisão e análise dos requisitos

**Objetivo desta etapa:**  Entender o escopo de cada requisito e seu valor para o participante.

#### Explicar o que é backlog para o participante

O backlog do produto é uma lista priorizada de itens que serão possivelmente desenvolvidos no sistema. Desse modo, é uma lista com prioridades dos requisitos ou funcionalidades do projeto que fornecem valor comercial.

É importante pontuar que novos itens podem ser adicionados a esse registro em qualquer momento (é assim que as alterações são introduzidas).

#### Explicar o que são temas

Temas são grandes áreas de funcionalidade ou objetivos gerais que agrupam vários requisitos relacionados. Eles ajudam a organizar o backlog em categorias amplas e permitem uma visão geral das funcionalidades que o sistema deve oferecer. 

**Exemplo:** Um tema pode ser "Gerenciamento de Perfil do Usuário," o qual pode incluir todas as funcionalidades relacionadas ao cadastro, atualização e visualização de informações pessoais dos usuários.

#### Explicar o que são épicos

Épicos são grandes histórias de usuário ou requisitos que representam uma funcionalidade complexa e de alto nível.

Por exemplo, dentro do tema "Gerenciamento de Perfil do Usuário", um épico pode ser "Usuário pode atualizar suas informações pessoais" que depois pode ser decomposto em várias histórias de usuário menores, como "Usuário pode atualizar seu endereço" e "Usuário pode atualizar seu telefone".

#### Perguntas em relação aos Temas:
- Considerando o aplicativo da Carteira de Trabalho Digital, quais são os temas há no contexto?

#### Perguntas em relação aos requisitos funcionais elicitados

** Cada um dos requisitos presentes na seguinte lista será apresentado ao participantes** 

<details>
  <summary size="20"><b> Requisitos Funcionais elicitados </b></summary> 

</center>

**Tabela 2**: Requisitos Funcionais.


| Identificação do Requisito | Requisito | Técnica de Elicitação | Implementação |
|-----------------------------|-----------|-----------------------|---------------|
| RF01                          | Usuário se registrar no aplicativo | Análise de documentos | Sim |
| RF02                          | Usuário poder fazer login para entrar na sua página pessoal | Análise de documentos | Sim |
| RF03                          | Usuário pode consultar suas informações pessoais | Análise de documentos | Sim |
| RF04                          | Usuário pode atualizar suas informações pessoais | entrevistas | Não |
| RF05                          | Usuário trabalhador pode consultar contratos de trabalho | Análise de documentos | Sim |
| RF06                          | Usuário trabalhador pode atualizar contratos de trabalho | Entrevistas | não |
| RF07                          | Usuário pode gerar PDF com dados da carteira | Análise de documentos | Sim |
| RF08                          | Usuário trabalhador visualizar gráficos com históricos e remunerações dos seus trabalhos | Análise de documentos | Sim |
| RF09                          | Usuário pode realizar anotações | Análise de documentos | Sim |
| RF10                          | Usuário trabalhador pode fazer denúncias trabalhistas contra a empresa | Entrevistas | Não |
| RF11                          | Usuário trabalhador pode consultar informações sobre o FGTS e o INSS| Storytelling | Não |
| RF12                          | Usuário trabalhador pode consultar benefícios (13º salário, férias remuneradas, adicional noturno, vale-transporte, vale-refeição, plano de saúde, abono salarial, benefício TAC-Taxista, Seguro Desemprego)| Análise de documentos, Entrevistas e Storytelling| incompleto |
| RF13                          | Usuário trabalhador pode solicitar benefícios | Análise de documentos e entrevistas | Incompleto |
| RF14                          | Usuário trabalhador pode atualizar(declarar) currículo | Entrevistas e Storytelling | Não |
| RF15                          | Usuário trabalhador pode  ativar modo de status (procurando emprego ou não) | Entrevistas | Não |
| RF16                          | Usuário trabalhador por verificar processor seletivos abertos | Análise de documentos | Incompleto |
| RF17                          | Usuário pode ocultar dados sensíveis | Análise de documentos e storytelling | Sim |
| RF18                          | Usuário trabalhador pode consultar o número da carteira e de série como CIPS | Storytelling | Não |
| RF19                          | Usuário recebem notificações do aplicativo | Análise de documentos e Storytelling | Não |
| RF20                          | Usuário pode consultar perguntas frequêntes | Storytelling e Entrevista| Não |
| RF21                          | Usuário empresa pode consultar dados dos funcionários | Entrevistas e análse de documento | Sim |
| RF22                          | Usuário empresa pode atualizar dados dos funcionários | Entrevistas e análse de documento | Incompleto |
| RF23                          | Usuário empresa pode consultar contratos de trabalho | Entrevistas e análse de documento | Incompleto |
| RF24                          | Usuário empresa pode gerar relatórios trabalhistas | Entrevistas | Incompleto |
| RF25                          | Usuário empresa pode gerenciar contratos de trabalho (adicionar novos, atualizar já existentes e encerrar contratos)| Entrevistas | Sim |
| RF26                          | Usuário empresa pode cadastrar benefícios para a empresa | Entrevistas e análse de documento | Incompleto |
| RF27                          | Usuário empresa pode gerenciar benefícios trabalhistas | Entrevistas | Incompleto |
| RF28                          | Usuário empresa escolher modo de status: "Possui vagas de emprego" ou "Não posui vagas de emprego" | Entrevistas | Não |


  **Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

 </center> 
 </details>




** Perguntas que devem ser feitas para cada um dos requisitos:**

- Qual é o objetivo deste requisito?
- Em qual tema você encaixa esse requisito?
- Quem é o usuário principal para este requisito?
- Por que o usuário precisa dessa funcionalidade (valor de negócio)?
- Quais são os critérios de aceitação para esta funcionalidade?
- Qual é o valor de negócio que este requisito proporciona? (importância para o sistema).
- Qual é a prioridade deste requisito (baixa, média, alta)?
- Este requisito é essencial para a funcionalidade básica do aplicativo?
- Como podemos testar se este requisito foi implementado corretamente?
- Quais recursos ou ferramentas serão necessários para implementar este requisito?
- Como a decomposição desses épicos em histórias de usuário pode ser realizada de forma eficiente?

### Perguntas finais – Após a apresentação dos requisitos elicitados.

- Há algum requisito que você acha que precisa ser acrescentado na lista?

- Há algum detalhe ou especificação em um requisito que precisa ser melhor esclarecido para garantir que a equipe de desenvolvimento entenda corretamente?




## Bibliografia

* GOMES, Diego. Product Backlog - Introdução [vídeo]. Agile Coach Diego Gomes. Publicado em 21 Mar. 2020. Disponível em: https://youtu.be/z4ubaBwjCsU. Acesso em: 24/05/2024

* Economia-DF. Backlog. Grupo Economia-DF 2023.2 da Disciplina de Requisitos de Software, Disponível em: https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/agil/backlog/#ep09-ajuda . Acesso em: 24/05/2024.  


## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 |  Adição da introdução e da metodologia   |  Caio Mesquita   |  Larissa Stéfane  |   26/05/2024   |
| 1.1 |  Adição do reoteiro da reunião para o Backlog   |  Larissa Stéfane   |  - |   26/05/2024   |
