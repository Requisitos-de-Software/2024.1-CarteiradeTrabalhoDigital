# Backlog do Produto

## Introdução

O backlog do produto é uma lista de funcionalidades e requisitos priorizados que fornecem valor ao cliente. Cada item no backlog é uma expressão do que o produto precisa para atender às necessidades dos usuários e stakeholders.

## Épicos

Épicos são grandes iniciativas que podem ser divididas em funcionalidades menores (features) e histórias de usuário (user stories). Eles representam grandes áreas de funcionalidade que agregam valor ao produto.

### E01 - Solicitação de Benefício
Eu, como usuário, desejo solicitar benefícios trabalhistas diretamente pelo aplicativo da Carteira Digital de Trabalho, para garantir meus direitos de forma prática e eficiente.

### E02 - Consulta de Benefício
Eu, como usuário, desejo consultar o status dos meus benefícios solicitados, para acompanhar o andamento e previsões de pagamento.

### E03 - Histórico de Benefícios
Eu, como usuário, desejo visualizar o histórico de todos os benefícios que solicitei e recebi, para ter um controle completo das minhas solicitações.

### E04 - Notificações Personalizadas
Eu, como usuário, desejo receber notificações personalizadas sobre atualizações e vencimentos de benefícios, para estar sempre atualizado.

### E05 - Assistente Virtual
Eu, como usuário, desejo interagir com um assistente virtual para esclarecer dúvidas e obter suporte sobre a solicitação de benefícios, para facilitar o uso do aplicativo.

### E06 - Segurança de Dados
Eu, como usuário, desejo que minhas informações pessoais e de solicitação de benefícios sejam protegidas por medidas de segurança robustas, para garantir a confidencialidade e integridade dos meus dados.

### E07 - Acessibilidade
Eu, como usuário com deficiência, desejo que o aplicativo seja totalmente acessível, permitindo o uso eficiente de todas as funcionalidades.

### E08 - Suporte Multicanal
Eu, como usuário, desejo acessar suporte por diferentes canais (chat, telefone, e-mail) para resolver questões relacionadas aos meus benefícios.

### E09 - Documentação e Tutoriais
Eu, como usuário, desejo acessar documentação detalhada e tutoriais sobre o uso do aplicativo, para entender todas as funcionalidades disponíveis.

### E10 - Feedback e Melhoria Contínua
Eu, como usuário, desejo fornecer feedback sobre minha experiência com o aplicativo, para contribuir com melhorias contínuas.

## Features

As features são funcionalidades maiores que podem ser divididas em histórias de usuário (user stories) para serem desenvolvidas pelas equipes ágeis.

| Feature | Descrição | Prioridade | Épico |
|---------|-----------|------------|-------|
| F01     | Formulário de Solicitação de Benefício | Alta | E01 |
| F02     | Anexar Documentos na Solicitação | Alta | E01 |
| F03     | Notificações de Status de Benefício | Média | E02 |
| F04     | Visualização de Status Detalhado | Alta | E02 |
| F05     | Histórico de Benefícios | Média | E03 |
| F06     | Personalização de Notificações | Baixa | E04 |
| F07     | Assistente Virtual para Suporte | Média | E05 |
| F08     | Criptografia de Dados | Alta | E06 |
| F09     | Compatibilidade com Tecnologias Assistivas | Alta | E07 |
| F10     | Suporte via Chat | Baixa | E08 |
| F11     | Tutoriais em Vídeo | Média | E09 |
| F12     | Coleta de Feedback dos Usuários | Baixa | E10 |

## Histórias de Usuário

As histórias de usuário são pequenas unidades de trabalho que descrevem uma funcionalidade do ponto de vista do usuário final.

| Feature | História de Usuário | ID | Prioridade | Origem |
|---------|----------------------|----|------------|--------|
| F01     | Eu, como usuário, desejo preencher um formulário de solicitação de benefício de forma simples e guiada, para garantir que todas as informações necessárias sejam fornecidas corretamente. | US01 | Must | RF01 |
| F02     | Eu, como usuário, desejo anexar documentos diretamente no aplicativo, para facilitar o processo de solicitação de benefício. | US02 | Must | RF02 |
| F03     | Eu, como usuário, desejo receber notificações sobre o status da minha solicitação de benefício, para estar sempre informado sobre o andamento. | US03 | Should | RF03 |
| F04     | Eu, como usuário, desejo visualizar o status detalhado da minha solicitação de benefício, incluindo previsão de pagamento, para acompanhar de perto o processo. | US04 | Must | RF04 |
| F05     | Eu, como usuário, desejo visualizar o histórico detalhado de todos os benefícios solicitados e recebidos, para ter um controle completo e organizado das minhas solicitações. | US05 | Should | RF05 |
| F06     | Eu, como usuário, desejo personalizar as notificações que recebo sobre benefícios, para receber apenas informações relevantes. | US06 | Could | RF06 |
| F07     | Eu, como usuário, desejo interagir com um assistente virtual para obter respostas rápidas e suporte, para melhorar minha experiência no uso do aplicativo. | US07 | Should | RF07 |
| F08     | Eu, como usuário, desejo que minhas informações sejam criptografadas, para garantir a segurança dos meus dados. | US08 | Must | RF08 |
| F09     | Eu, como usuário com deficiência, desejo que o aplicativo seja compatível com tecnologias assistivas, para que eu possa utilizá-lo sem barreiras. | US09 | Must | RF09 |
| F10     | Eu, como usuário, desejo acessar suporte via chat para resolver dúvidas rapidamente, para não ter interrupções no uso do aplicativo. | US10 | Could | RF10 |
| F11     | Eu, como usuário, desejo acessar tutoriais em vídeo sobre o uso do aplicativo, para entender melhor suas funcionalidades. | US11 | Should | RF11 |
| F12     | Eu, como usuário, desejo fornecer feedback sobre minha experiência de uso do aplicativo, para contribuir com a melhoria contínua. | US12 | Could | RF12 |

## Requisitos Não Funcionais (NFR) sobre Acessibilidade

| Identificador | Requisito | Rastreabilidade |
|---------------|-----------|-----------------|
| NFR01         | O aplicativo deve ser compatível com leitores de tela, para permitir que pessoas com deficiência visual utilizem todas as funcionalidades. | AC01 |
| NFR02         | O aplicativo deve ter contraste adequado entre texto e fundo, para garantir a legibilidade por pessoas com baixa visão. | AC02 |
| NFR03         | Todos os elementos interativos devem ser navegáveis via teclado, para garantir acessibilidade a pessoas com mobilidade reduzida. | AC03 |
| NFR04         | O aplicativo deve fornecer alternativas textuais para todos os elementos não textuais, como imagens e ícones, para ser acessível a pessoas com deficiência visual. | AC04 |
| NFR05         | As instruções para o preenchimento de formulários devem ser claras e descritivas, para garantir que todos os usuários possam fornecer as informações necessárias corretamente. | AC05 |

## Referências

- WCAG 2.1: 1.1.1 Non-text Content
- WCAG 2.1: 1.4.3 Contrast (Minimum)
- WCAG 2.1: 2.1.1 Keyboard
- WCAG 2.1: 3.3.2 Labels or Instructions
