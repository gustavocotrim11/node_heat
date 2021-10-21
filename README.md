<h1 align="center">NLW Heat Rocketseat - Node.js</h1>

<p align="center">
  Stage 1
</p>

<p align="center">
  Nesse Stage do NLW Heat criamos o backend da aplicação utlizando NodeJS utilizando Typescript que auxilia no aumento da produtividade em desenvolvimento, o Prisma ORM para trabalhar com banco de dados e Socket.IO para trabalhar comunicação em tempo real.
</p>


## ✨ Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [TypeScript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/pt-br/)
- [Prisma](https://www.prisma.io/)
- [JSON Web Token](https://jwt.io/)
- [Socket.IO](https://socket.io/)

## 🚀 Como executar

> Obs.: Nesse projeto temos autenticação via OAuth com o GitHub

- Clone o repositório e acesse a pasta;
- Crie um arquivo `.env` e preencha com as suas credenciais do GitHub, GITHUB_CLIENT_SECRET e GITHUB_CLIENT_ID, e com um hash MD5 por exemplo, como JWT_SECRET;
- Instale as dependências com `yarn`;
- Executa as migrations com `yarn prisma migrate dev`;
- Inicie o servidor com `yarn dev`;

A aplicação pode ser acessada em [`localhost:4000`](http://localhost:4000).
