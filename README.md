<h1 align="center">DoWhile 2021 - NLW Heat</h1>

<p align="center">	
  <a alt="LinkedIn" href="https://www.linkedin.com/in/willian-gois/">
    <img alt="Willian Gois" src="https://img.shields.io/badge/willian--gois-8257E5?style=flat&logo=Linkedin&logoColor=white" />
  </a>

  <a alt="DoWhile 2021" href="https://nextlevelweek.com/episodios/impulse/aula-1/edicao/7">
    <img src="https://img.shields.io/badge/DoWhile%202021-NLW Heat%207-8257E5?"></img>
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-8257E5">
</p>

<div align="center">
  <a href="#sparkles-sobre">Sobre</a>&nbsp;|&nbsp;
  <a href="#rocket-tecnologias">Tecnologias</a>&nbsp;|&nbsp;
  <a href="#computer-executando-o-projeto">Executando o projeto</a>&nbsp;|&nbsp;
  <a href="#pencil-licença">Licença</a>
</div>

## :sparkles: Sobre
**DoWhile 2021** é uma aplicação ...

Aplicação desenvolvida durante a [**Next Level Week Heat #7**](https://nextlevelweek.com/episodios/impulse/aula-1/edicao/7), pela trilha Impulse, projeto da [Rocketseat](https://rocketseat.com.br), que consiste em uma semana (17 à 25 de outubro) de estudos, networking e programação.

---

## :computer: Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [TypeScript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/pt-br/)
- [Prisma](https://www.prisma.io/)
- [JSON Web Token](https://jwt.io/)
- [Socket.IO](https://socket.io/)

---

## :rocket: Executando o projeto
``` bash
# Clonar o repositório
git clone https://github.com/willian-gois/do-while2021

# Entrar na raíz do projeto
cd do-while2021

# Fazer uma copia do arquivo .env.example para .env e editá-lo com as suas credenciais do GitHub
cp .env.example .env && nano .env

# Instalar as dependências do Node com Yarn
yarn install

# Executar as migrations do Prisma
yarn prisma migrate dev

# Executar o servidor
yarn dev
```

## :pencil: Licença

Este projeto está sobre a [MIT license](./LICENSE).

<div align="center">
  <sub>Desenvolvido com ❤ por <a href="https://github.com/willian-gois">Willian Gois</a>.</sub>
</div>