# MongoDB Commerce

## Contexto

Este projeto se trata de um banco de dados `commerce`, que contém dados do cardápio do **McDonald's**, como ingredientes, valores nutricionais e dados fictícios de vendas. É realizado inserções, atualizações e deleções no banco de dados, utilizando MQL (MongoDB Query Language).

---
Eu [Andrey R. Visniewski](https://github.com/Andreyrvs) criei os arquivos contidos no diretorio `challenges`.

Os arquivos contidos em `assets/produtos` foram desenvolvidos pela [Trybe](https://www.betrybe.com/)

---

## Técnologias usadas

Back-end:
> Desenvolvido usando: MongoDB.

## Instalando Dependências

* clone o projeto:

```bash
git clone git@github.com:Andreyrvs/mongoDB_Commerce.git
```

> Backend

```bash
  cd MongoDB-Commerce/
  npm install
```

## Executando aplicação

* Para rodar o back-end utilize: **MongoDB Compass**, **mongosh** ou instale **MongoDB for VS Code** para executar as queries

* Para usar o MongoDB com Docker

```bash
docker run -d --name=mongodb_commerce -v "$PWD:/app" -p 27017:27017 mongo:5.0
```

## Executando o linter

```bash
npm run lint
```
