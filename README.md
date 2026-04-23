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

* Java (lógica e Android)
* Android Studio
* SQLite / Room
* GitHub (Scrum e versionamento)
* APIs externas:

  * TMDB (filmes)
  * Google Books (livros)

---

## 📁 Estrutura do projeto

```
echomood/
│
├── core/                     # Lógica em Java puro
│   └── src/main/java/com/echomood/
│       ├── model/            # Entidades (Conteudo, Usuario, etc.)
│       └── service/          # Algoritmo de recomendação
│
├── android-app/              # Aplicação Android
│   └── app/src/main/java/com/echomood/
│       ├── model/            # Model adaptado (@Entity)
│       ├── service/          # Reutilização da lógica
│       ├── repository/       # Acesso a dados
│       ├── database/         # Room (SQLite)
│       ├── api/              # Integração com APIs externas
│       └── ui/               # Interface do usuário
│
├── docs/                     # Documentação
│   ├── arquitetura.md
│   ├── algoritmo.md
│   └── requisitos.md
│
└── README.md
```
---

## 🔄 Arquitetura
O sistema segue uma arquitetura em camadas:

Model → estrutura dos dados

Service → lógica de recomendação

Repository → acesso a dados (local + API)

Database → persistência local (Room)

API Client → consumo de APIs externas

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
O design da interface foi desenvolvido no Figma:

🔗 [Acessar protótipo](https://www.figma.com/design/1mPZa8doX4Al9ElUraYDJO/EchoMood-prot%C3%B3tipo?node-id=0-1&t=dqJRyaipKh3reiPW-1)

protótipo apresenta o fluxo principal do aplicativo, incluindo:
- Seleção de humor
- Tela de recomendações
- Navegação por conteúdos
- Interface baseada em emoções e vibes

---

## 📄 Licença

Projeto acadêmico sem fins comerciais.
