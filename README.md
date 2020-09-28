<h1 align="center">
  <img src=".github/logo.svg" alt="gofinances" />
</h1>

<h3 align="center">goFinances - rest api para gerenciar transações financeiras desenvolvida com Node.js, express, typeorm e postgres.</h3>

## 🚀 Features
- Cadastrar transação
- Listar transação
- Deletar transação
- Importar transações de um arquivo CSV

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/pt-br/)
- [Typeorm](https://typeorm.io/#/)
- [Multer](https://github.com/expressjs/multer)

## Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/), [Yarn](https://classic.yarnpkg.com/lang/en/), [Docker](https://www.docker.com/).
 Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

## 💾 Instalação

```bash
# Crie um container postgres e configure o arquivo ormconfig.json com suas credenciais
$ docker run --name some-postgres -e POSTGRES_PASSWORD=mysecretpassword -d postgres

# Clone o projeto e acesse a pasta
$ git clone https://github.com/rodrigosakamoto/gofinances-api.git

$ cd gofinances-api

# Instale as dependêcias
$ yarn

# Rode as migrations
$ yarn typeorm migration:run

# Execute o servidor
$ yarn dev:server

```
---
By Rodrigo Sakamoto

[![Linkedin Badge](https://img.shields.io/badge/-Rodrigo%20Sakamoto-9146ff?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/rodrigo-sakamoto/)](https://www.linkedin.com/in/rodrigo-sakamoto/)
[![Gmail Badge](https://img.shields.io/badge/-rodosakamoto@gmail.com-9146ff?style=flat-square&logo=Gmail&logoColor=white&link=mailto:rodosakamoto@gmail.com)](mailto:rodosakamoto@gmail.com)
