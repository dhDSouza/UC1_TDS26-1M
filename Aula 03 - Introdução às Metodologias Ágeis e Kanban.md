# 🚀 Aula — Introdução às Metodologias Ágeis e Kanban

## 🎯 Objetivos da Aula

Ao final desta aula você será capaz de:

* Compreender o que são metodologias de desenvolvimento de software;
* Entender o conceito de Agile (Desenvolvimento Ágil);
* Conhecer as principais metodologias ágeis utilizadas no mercado;
* Aprender como funciona o Kanban;
* Planejar um software utilizando um quadro Kanban;
* Organizar tarefas antes do desenvolvimento.

---

# 🤔 Por que precisamos de metodologias?

Imagine que uma equipe precise desenvolver um sistema para uma escola.

Sem organização, podem surgir diversos problemas:

* Duas pessoas fazendo a mesma tarefa;
* Funcionalidades esquecidas;
* Atrasos nas entregas;
* Falta de comunicação;
* Retrabalho.

Para evitar esses problemas surgiram as metodologias de desenvolvimento.

Elas ajudam equipes a planejar, organizar e acompanhar o progresso de um projeto.

---

# 📜 O Modelo Tradicional (Cascata)

Durante muitos anos, os softwares eram desenvolvidos utilizando o modelo chamado **Cascata (Waterfall)**.

Nesse modelo, cada etapa acontece apenas após a conclusão da anterior.

```text
Planejamento
      ↓
Desenvolvimento
      ↓
Testes
      ↓
Entrega
```

## Vantagens

* Organização simples;
* Processo bem definido;
* Fácil documentação.

## Desvantagens

* Mudanças são difíceis de implementar;
* Problemas podem ser descobertos apenas no final;
* Muito retrabalho quando algo precisa ser alterado.

---

# ⚡ O que é Agile?

Agile (Ágil) é uma forma de desenvolver projetos focando em:

* Entregas frequentes;
* Comunicação constante;
* Adaptação às mudanças;
* Colaboração entre equipe e cliente.

Ser ágil não significa trabalhar mais rápido.

Significa trabalhar de forma mais inteligente e organizada.

---

# 🧠 Principais Metodologias Ágeis

Existem diversas metodologias ágeis.

Vamos conhecer as mais populares.

---

## 🏃 Scrum

Scrum é uma metodologia baseada em ciclos curtos chamados **Sprints**.

Uma Sprint normalmente dura entre 1 e 4 semanas.

Ao final de cada Sprint, uma parte funcional do sistema deve ser entregue.

### Conceitos importantes

* Product Owner
* Scrum Master
* Time de Desenvolvimento
* Sprint
* Backlog

### Quando usar?

Projetos grandes ou equipes que precisam de entregas frequentes e organizadas.

---

## 💻 XP (Extreme Programming)

XP é uma metodologia focada principalmente na qualidade do código.

Ela incentiva práticas como:

* Programação em dupla;
* Testes automatizados;
* Refatoração constante;
* Integração contínua.

### Quando usar?

Projetos onde a qualidade técnica do software é extremamente importante.

---

## 📋 Kanban

Kanban é uma metodologia visual para organização do trabalho.

Seu principal objetivo é mostrar claramente:

* O que precisa ser feito;
* O que está sendo feito;
* O que já foi concluído.

É uma das metodologias mais simples para começar.

Por esse motivo, será a metodologia utilizada em nossas atividades.

---

# 📚 O que significa Kanban?

A palavra Kanban tem origem japonesa e pode ser traduzida como:

> "Cartão" ou "Sinalização"

Ela surgiu inicialmente para controlar processos de produção industrial e posteriormente foi adaptada para o desenvolvimento de software.

---

# 🏗 Estrutura de um Quadro Kanban

Um quadro Kanban normalmente possui três colunas principais:

| A Fazer           | Fazendo              | Concluído           |
| ----------------- | -------------------- | ------------------- |
| Tarefas pendentes | Tarefas em andamento | Tarefas finalizadas |

Exemplo:

| A Fazer                  | Fazendo              | Concluído          |
| ------------------------ | -------------------- | ------------------ |
| Criar menu principal     | Desenvolver cadastro | Planejar projeto   |
| Criar tela de resultados |                      | Definir requisitos |

---

# 🎯 Benefícios do Kanban

Utilizar Kanban traz diversas vantagens:

✅ Organização visual

✅ Melhor distribuição de tarefas

✅ Acompanhamento do progresso

✅ Maior produtividade

✅ Facilidade para identificar problemas

✅ Melhor comunicação da equipe

---

# 🎮 Exemplo de Planejamento

Imagine que uma equipe vai criar um sistema de Jokenpô.

Antes de programar, ela pode organizar suas tarefas.

| A Fazer                     | Fazendo | Concluído       |
| --------------------------- | ------- | --------------- |
| Criar menu                  |         | Definir projeto |
| Ler escolha do jogador      |         |                 |
| Gerar escolha do computador |         |                 |
| Mostrar resultado           |         |                 |

Perceba que nenhuma linha de código foi escrita ainda.

Mesmo assim, a equipe já sabe exatamente o que precisa fazer.

---

# 💡 O que é MVP?

MVP significa:

**Minimum Viable Product**
(Produto Mínimo Viável)

É a menor versão possível de um software que já consegue funcionar.

## Exemplo

Projeto: Calculadora

### MVP

* Soma
* Subtração

### Funcionalidades futuras

* Multiplicação
* Divisão
* Histórico
* Interface gráfica

A ideia é entregar algo funcional primeiro e melhorar depois.

---

# 🛠 Ferramentas Utilizadas no Mercado

Algumas ferramentas populares para Kanban:

* Trello
* Jira
* GitHub Projects
* Azure DevOps Boards

Também é possível utilizar:

* Quadro branco
* Papel
* Post-its

---

# 📝 Atividade Prática

## Objetivo

Planejar um software utilizando Kanban.

### Formação dos grupos

* 3 a 5 integrantes por grupo.

---

## Escolha um Projeto

Cada grupo deverá escolher apenas um dos projetos abaixo.

### Projeto 1 — Calculadora

Funcionalidades:

* Soma
* Subtração
* Multiplicação
* Divisão

---

### Projeto 2 — Cadastro de Alunos

Funcionalidades:

* Informar nome
* Informar idade
* Exibir informações cadastradas

---

### Projeto 3 — Jokenpô

Funcionalidades:

* Pedra
* Papel
* Tesoura
* Exibição do vencedor

---

### Projeto 4 — Quiz

Funcionalidades:

* Perguntas
* Respostas
* Pontuação final

---

## Tarefa

Criar um quadro Kanban contendo:

* Pelo menos 10 tarefas;
* As colunas:

  * A Fazer;
  * Fazendo;
  * Concluído.

---

## Exemplo

```text
[A Fazer]

- Criar menu
- Ler nome
- Ler idade
- Mostrar informações

[Fazendo]

- Planejar funcionalidades

[Concluído]

- Escolher projeto
```

---

# 📌 Desafio Extra

Após montar o Kanban, responda:

### Qual é o MVP do projeto?

Explique:

1. O que é essencial para o sistema funcionar?
2. O que pode ser deixado para uma próxima versão?

---

# 🎯 Exercícios de Fixação

## 1)

O que é uma metodologia de desenvolvimento?

---

## 2)

Qual é a principal diferença entre o modelo Cascata e o Agile?

---

## 3)

O que significa ser ágil em um projeto?

---

## 4)

Cite duas metodologias ágeis.

---

## 5)

Qual metodologia utiliza quadros visuais para organizar tarefas?

---

## 6)

Quais são as três colunas básicas de um quadro Kanban?

---

## 7)

O que significa MVP?

---

## 8)

Explique por que planejar um projeto antes de programar pode ajudar uma equipe.

---

# 📖 Resumo da Aula

Nesta aula aprendemos que:

* O desenvolvimento de software precisa de organização;
* O modelo Cascata possui etapas rígidas;
* Agile permite adaptação e entregas frequentes;
* Scrum, XP e Kanban são metodologias ágeis populares;
* Kanban organiza tarefas visualmente;
* MVP é a menor versão funcional de um produto;
* Planejar antes de programar ajuda a evitar problemas durante o desenvolvimento.
