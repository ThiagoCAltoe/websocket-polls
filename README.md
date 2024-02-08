<h1 align="center">Poll API</h1>

<p align="center">
  <a href="#🚀-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#💻-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

<br>

## ☕ Requisites

- Docker
- Node.js

## ⌨️ Setup

- Clone the repository;
- Install dependencies (<code>npm install</code>);
- Setup PostgreSQL and Redis (<code>docker compose up -d</code>);
- Copy .env.example file (<code>cp .env.example .env</code>);
- Run application (<code>npm run dev</code>);
- Test it! (I personally recommend testing with [Hoppscotch](https://hoppscotch.io)).

## 🚀 Technology

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Git](https://git-scm.com) e [Github](https://github.com/)
- [Typescript](https://www.typescriptlang.org)
- [NodeJS](https://nodejs.org)
- [Fastify](https://fastify.dev)
- [Prisma](https://www.prisma.io)

## 💻 Project

A real-time voting system where users can create a poll and other users can cast their votes. The system generates a ranking among the options and updates the votes in real-time.

## 📜 License

MIT Copyright (c) 2024

---