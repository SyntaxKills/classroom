🎓 CLASSROOM

Plataforma de simulados acadêmicos para estudantes de Análise e Desenvolvimento de Sistemas (ADS)

O CLASSROOM é uma aplicação web desenvolvida para auxiliar estudantes universitários na revisão de conteúdos acadêmicos por meio de simulados interativos, questões de múltipla escolha e acompanhamento de desempenho.

A plataforma oferece uma experiência simples, moderna e responsiva, permitindo que o estudante selecione sua disciplina, personalize o conteúdo do simulado e teste seus conhecimentos de forma individual.

---

🚀 Funcionalidades

- Configuração personalizada: identificação do estudante, semestre e disciplina.
- Conteúdo direcionado: personalização dos simulados com base nos assuntos informados pelo estudante.
- 20 questões por simulado: questões de múltipla escolha com cinco alternativas.
- Progressão de dificuldade: questões básicas, intermediárias e avançadas.
- Feedback instantâneo: indicação de acertos e erros após a confirmação da resposta.
- Explicações didáticas: apresentação de explicações para auxiliar na compreensão dos conteúdos.
- Revisão de questões: possibilidade de revisar as questões após finalizar o simulado.
- Resultados detalhados: pontuação, percentual de acertos, erros, tempo de conclusão e classificação de desempenho.
- Histórico de simulados: armazenamento dos resultados anteriores.
- Retomada de progresso: possibilidade de continuar um simulado interrompido.
- Armazenamento local: persistência de informações utilizando LocalStorage.
- Relatório de problemas: integração com o GitHub Issues para facilitar o envio de sugestões e identificação de bugs.

---

📚 Disciplinas disponíveis

O CLASSROOM possui suporte para conteúdos relacionados às seguintes disciplinas:

Disciplina| Principais conteúdos
Programação Back-End| PHP, lógica de programação, variáveis, funções, estruturas de controle e conceitos de desenvolvimento back-end
Análise e Projeto de Sistemas Orientada a Objetos| Classes, objetos, encapsulamento, herança, polimorfismo e modelagem orientada a objetos
Desenvolvimento em Banco de Dados| SQL, tabelas, consultas, INSERT, UPDATE, DELETE, SELECT, relacionamentos e modelagem de dados
DevOps| Git, versionamento, integração contínua, entrega contínua, Docker e infraestrutura
Gestão de Projetos| Planejamento, escopo, cronograma, riscos, metodologias ágeis e Scrum

---

📝 Estrutura dos simulados

Cada simulado possui exatamente 20 questões, distribuídas em três níveis de dificuldade:

Questões| Nível
1 – 6| 🟢 Básico
7 – 14| 🟡 Intermediário
15 – 20| 🔴 Avançado

Cada questão apresenta cinco alternativas, identificadas de A a E, permitindo que o estudante selecione sua resposta antes de confirmá-la.

Após a confirmação:

- A resposta não poderá mais ser alterada.
- O sistema indicará se a questão foi respondida corretamente.
- A alternativa correta será destacada.
- Uma explicação conceitual será apresentada.
- O estudante poderá avançar para a próxima questão.

---

🧠 Personalização do conteúdo

O estudante pode informar tópicos, conceitos, comandos ou conteúdos trabalhados em sala de aula no campo de informações adicionais.

Essas informações são processadas localmente no navegador para identificar palavras-chave relevantes e direcionar a seleção de questões de acordo com:

- Disciplina selecionada.
- Semestre acadêmico.
- Conteúdos informados pelo estudante.

Caso o campo de informações adicionais esteja vazio, o simulado será baseado na disciplina e no semestre selecionados.

A aplicação não depende de inteligência artificial externa, APIs pagas ou serviços de back-end para gerar e executar os simulados.

---

📊 Sistema de avaliação

Ao finalizar o simulado, o estudante terá acesso a um relatório contendo:

- Total de questões respondidas.
- Quantidade de acertos.
- Quantidade de erros.
- Percentual de aproveitamento.
- Tempo total de realização.
- Classificação de desempenho.
- Revisão individual de todas as questões, incluindo respostas selecionadas e alternativas corretas.

O objetivo é proporcionar uma visão clara do desempenho acadêmico e auxiliar na identificação dos conteúdos que precisam de mais atenção.

---

💾 Armazenamento de dados

O CLASSROOM utiliza o LocalStorage do navegador para armazenar informações localmente.

Os dados persistidos incluem:

- Perfil do estudante.
- Semestre e disciplina selecionados.
- Informações adicionais de estudo.
- Simulado em andamento.
- Histórico de simulados concluídos.

Como o armazenamento é local, os dados permanecem no navegador e não são sincronizados automaticamente entre dispositivos.

«⚠️ A limpeza dos dados do navegador ou do armazenamento do site poderá apagar o perfil e o histórico de simulados.»

---

🛠️ Tecnologias utilizadas

- HTML5 — estrutura da aplicação.
- CSS3 — estilização, responsividade, animações e identidade visual.
- JavaScript ES6+ — lógica dos simulados, validações, gerenciamento de estado, geração de questões e persistência.

O projeto utiliza tecnologias nativas da Web, sem necessidade de servidor back-end, banco de dados externo ou instalação de dependências.

---

🎨 Interface e experiência do usuário

O CLASSROOM utiliza uma interface moderna com temática tecnológica, incluindo:

- Tema escuro.
- Elementos neon.
- Gradientes sutis.
- Microanimações.
- Indicadores de progresso.
- Feedback visual durante a interação.
- Layout adaptável para smartphones, tablets e desktops.

A interface foi projetada priorizando a legibilidade, a simplicidade e a facilidade de utilização durante os estudos.

---

📱 Responsividade

A aplicação foi desenvolvida com prioridade para dispositivos móveis, mantendo compatibilidade com diferentes tamanhos de tela.

O layout se adapta a:

- Smartphones Android.
- Smartphones iOS.
- Tablets.
- Desktops e notebooks.

---

▶️ Como executar o projeto

Não é necessário instalar dependências.

Executar localmente

1. Clone o repositório:
   
   git clone https://github.com/SyntaxKills/classroom.git

2. Entre na pasta do projeto:
   
   cd classroom

3. Abra o arquivo "index.html" diretamente no navegador.

---

🌐 Deploy no GitHub Pages

O CLASSROOM pode ser hospedado gratuitamente utilizando o GitHub Pages.

1. Acesse o repositório no GitHub.
2. Abra Settings.
3. Acesse Pages.
4. Em Build and deployment, selecione "Deploy from a branch".
5. Escolha a branch "main".
6. Selecione a pasta "/root".
7. Salve as configurações.

Após a publicação, o GitHub disponibilizará uma URL pública para acessar a aplicação.

---

🐛 Relatar problemas

Encontrou um bug, comportamento inesperado ou deseja sugerir uma melhoria?

Utilize a funcionalidade Relatar problema disponível na interface da aplicação ou acesse diretamente:

"Reportar um problema no GitHub" (https://github.com/SyntaxKills/classroom/issues/new)

Contribuições, sugestões e feedbacks são bem-vindos.

---

🔒 Privacidade

O CLASSROOM foi desenvolvido com foco na simplicidade e privacidade.

- Não exige cadastro em servidor.
- Não utiliza autenticação externa.
- Não envia os dados do estudante para um back-end.
- Armazena informações localmente no navegador.
- Não depende de serviços de inteligência artificial externos.

---

🎯 Objetivo do projeto

O CLASSROOM tem como objetivo facilitar a rotina de estudos de estudantes de Análise e Desenvolvimento de Sistemas, oferecendo uma ferramenta prática para revisão de conteúdos, preparação para avaliações e autoavaliação do conhecimento.

A proposta é transformar o estudo em uma experiência mais organizada, interativa e acessível.

---

<p align="center">
  Desenvolvido para apoiar a jornada acadêmica em tecnologia. 💻
</p><p align="center">
  <strong>CLASSROOM — Aprenda. Pratique. Evolua.</strong>
</p>
