# :rocket: Bootcamp Gostack Fundamentos ReactJS
Desafio: Fundamentos ReactJS

## Objetivo
Criar uma aplicação para praticar o que foi aprendido no [Bootcamp GoStack da RocketSeat](https://github.com/rocketseat-education/bootcamp-gostack-desafios/tree/master/desafio-fundamentos-reactjs)

----------

## Pré-requisitos

- NodeJs
- Yarn
- Docker

## Projeto relacionado
https://github.com/elisonsilva/bootcamp-gostack-database-upload

## Instalando dependências.

``` bash
yarn
```

## Rodando aplicação

``` bash
# Rodar Postgres
docker run --name gostack_postgres -e POSTGRES_PASSWORD=[[SUASENHA]] -p 5432:5432 -d postgres

```
⚠️ Criar banco de dados no: ***gostack_desafio06*** e ***gostack_desafio06_tests*** ⚠️


``` bash
yarn dev:server
```

## Rodando os testes

``` bash
yarn test
```
