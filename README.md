## Descrição

Frontend desenvolvido com [Angular](https://angular.io/) e servidor desenvolvido com [Nest](https://github.com/nestjs/nest) TypeScript framework, utilizando [Docker](https://docs.docker.com/).

Caso ainda não possua o docker em sua máquina, recomendo a leitura da [documentação de instalação](https://docs.docker.com/engine/install/).

## Depêndencias

### Server
* npm
* nestjs
* typeorm

### Client
* npm
* angular
* angular-material
* bootstrap
* ng2-currency-mask


## Instalação

```bash
$ cd /server && npm install
$ cd /client && npm install
```

## Execução

```bash
# start docker
$ docker compose up -d

# startwatch mode
$ cd /server && npm run start:dev
$ cd /client && ng serve

```
