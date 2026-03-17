# 🎧 EchoMood — Recomendação por Humor

## 📌 Sobre o projeto

O **EchoMood** é um aplicativo mobile que combina **diário emocional** com **recomendação de conteúdo (filmes e livros)**.

A proposta é simples:
o usuário registra seu humor diariamente e recebe recomendações baseadas na sua emoção e na *vibe* desejada.

---

## 🎯 Funcionalidades

* 📅 Registro diário de humor com emojis
* 🎬 Recomendação de filmes
* 📚 Recomendação de livros
* 🌈 Exploração por vibes (cozy, melancólico, inspirador, etc.)
* 📊 Relatórios mensais de humor
* ➕ Adição de conteúdos pelo usuário
* 🔎 Busca por filmes e livros

---

## 🧠 Algoritmo de recomendação

O sistema utiliza:

* comparação de **tags de humor**
* cálculo de **score de compatibilidade**
* **ordenação de resultados** (ex: MergeSort / QuickSort)

Exemplo:

```java
if (conteudo.tags.contains(humor)) {
    score++;
}
```

---

## 🏗️ Tecnologias

* Java (Android)
* Android Studio
* SQLite / Room
* GitHub (versionamento)
* Azure DevOps (Scrum e organização)
* APIs externas:

  * TMDB (filmes)
  * Google Books (livros)

---

## 📁 Estrutura do projeto

```
echomood/
│
├── backend/
│   ├── src/
│   ├── controller/
│   ├── service/
│   ├── model/
│   └── repository/
│
├── frontend/
│   ├── android-app/
│   │   ├── java/
│   │   ├── res/
│   │   └── layout/
│
├── database/
│   ├── schema.sql
│   └── scripts/
│
├── docs/
│   ├── arquitetura.md
│   ├── algoritmo.md
│   └── requisitos.md
│
├── assets/
│   ├── imagens/
│   └── icones/
│
└── README.md
```

---

## 👥 Equipe
* Anne — Front-end/Design UX/UI 
* Sciel — Front-end
* Kamila — Backend
* Anna — Banco de Dados
* Anna — Scrum Master

---

## 🚀 Status do projeto

🚧 Em desenvolvimento

---

## 💡 Objetivo acadêmico

Projeto desenvolvido para aplicação prática de:

* Estrutura de Dados
* Algoritmos de ordenação
* Desenvolvimento de software
* Metodologias ágeis (Scrum)

---

## 📸 Protótipos

Design feito no Figma (link em breve)

---

## 📄 Licença

Projeto acadêmico sem fins comerciais.
