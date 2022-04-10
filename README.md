## Introduction

This repository is a template repository for projects based on Vue with Vuetify. It comes with:

* [Vue v2](https://vuejs.org/)
* [Vuetify v2](https://vuetifyjs.com/en/)
* Connection to a template backend ([FastAPI Blueprint](https://github.com/DanielW1987/fast-api-blueprint) or [SpringBoot Blueprint](https://github.com/DanielW1987/spring-boot-blueprint))

The template is based in large parts on the [Full Stack FastAPI and PostgreSQL - Base Project Generator](https://github.com/tiangolo/full-stack-fastapi-postgresql) by tiangolo.

## Prerequisites

The following software is required:

- node.js LTS or Latest
- Docker engine (e.g. Docker CE)
- Docker compose

Mac users can install **Docker Desktop for Mac** as it already includes both.

## Run frontend locally

In the project directory, you can run:

```shell
# install dependencies
npm install

# start app in development mode
npm run serve
````

Afterwards you can open [http://localhost:3000](http://localhost:3000) to view the app in the browser of your choice.

## Execute tests

In the project directory, you can run:

```shell
npm test
```

## Other scripts

There are a bunch of other npm scripts which can be executed with `npm run {script name}`:

- `lint`: checks the configured lint rules
- `lint:fix`: fixes lint violations
- `format`: formats according to configured prettier rules
