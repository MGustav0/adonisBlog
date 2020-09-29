# Iniciando com Adonis

![Badge](https://img.shields.io/badge/types-Flow%20%7C%20TypeScript-blue)
![Badge](https://img.shields.io/badge/node-%3E%3D%2012.18.2-brightgreen)
![Badge](https://img.shields.io/badge/Adonis-V5-lightblue)

> Status do Projeto: (🚧 em desenvolvimento)

## Tópicos

🔹 [Descrição do projeto](#🔗-descrição-do-projeto)

🔹 [Funcionalidades](#ℹ️-funcionalidades)

🔹 [Pré-requisitos](#✨-pré-requisitos)

🔹 [Como configurar a aplicação](#💾-iniciar/configurar-banco-de-dados)

🔹 [Como rodar a aplicação](#▶️-como-rodar-a-aplicação)

🔹 [Como rodar os testes](#🏗-como-rodar-os-testes)

🔹 [Insomnia](#😴-insomnia)

🔹 [Layout da Aplicação](#💻-layout-da-aplicação)

🔹 [Resolvendo Problemas](#❗️-resolvendo-problemas)

🔹 [Tarefas em aberto](#📝-tarefas-em-aberto)

🔹 [Tarefas em aberto](#🐙-desenvolvedores)

## 🔗 Descrição do projeto

<p align="justify">
  Neste projeto vou demonstrar meus conhecimentos de como utilizar o framework para back-end Adonis, apenas como web-api. Portanto será apenas para demonstrar e verificar o aprendizado da ferramenta com um CRUD básico e autenticação.

  O adonis segue o padrão arquitetural MVC (Model-View-Controller), ainda não sei como aplicar os padrões arquiteturais do SOLID e DDD, vai ficar quando eu conseguir amadurecer melhor no framework.
</p>

## ℹ️ Funcionalidades

✔️ Criar post

✔️ Listar post

❌ Deletar post

❌ Atualizar post

## ✨ Pré-requisitos

⚠️ [Node](https://nodejs.org/en/download/)

⚠️ [Yarn](https://yarnpkg.com/getting-started/install)

⚠️ [Adonis](https://preview.adonisjs.com/)

⚠️ [Docker](https://www.docker.com/products/docker-desktop)

⚠️ [PostgreSQL Docker](https://hub.docker.com/_/postgres)

⚠️ [MongoDB Docker](https://hub.docker.com/_/mongo)

⚠️ [Redis Docker](https://hub.docker.com/_/redis)

❗️ Você precisará seguir os passos a seguir para poder rodar a aplicação na sua máquina.

## 💾 Iniciar/Configurar banco de dados

Ter Docker e as imagens PostgreSQL, MongoDB e Redis instalados.

### Instalar PostgreSQL via Docker

* `docker run --name adonisPostgres -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres`
* Verificar se a imagem está rodando: `docker ps`
* Usuário: postgres
* Senha: docker
* Acesso pelo terminal: `docker exec -it adonisPostgres bash`

### Criar Banco de Dados PostgreSQL

1. Instale o DBeaver, ou outro gerenciador de Banco de Dados, ou faça por linha de comando.
2. Acesse com o usuário e senha supracitados.
3. Crie um Banco de Dados com o nome __blogadonis__.

### Instalar MongoDB via Docker

* `docker run --name adonisMongo -p 27017:27017 -d -t mongo`
* Verificar se a imagem está rodando: `docker ps`
* Usuário: postgres
* Senha: docker
* Acesso pelo terminal: `docker exec -it adonisMongo bash`

## ▶️ Como rodar a aplicação

Agora navegue até a pasta criada e abra no Visual Studio Code, lembre-se de executar o comando `yarn` dentro da pasta no seu terminal para instalar todas as dependências. Após a instalação digite: `yarn dev:server`.

Pronto! Agora basta acessar a aplicação à partir do link: http://localhost:3333/

## 🏗 Como rodar os testes

❗️ **Sem testes ainda.**

```bash
yarn test
```

## 😴 Insomnia

Para fazer o download do [insomnia](https://insomnia.rest/download/), para utilizar o mesmo workspace utilizado no projeto clique [aqui]().

## 💻 Layout da Aplicação

### Criar posts

<img src="https://github.com/MGustav0/adonisBlog/blob/master/extras/screenshots/01_-_create_post.png" width="640" heigth="360" />

### Listar posts

<img src="https://github.com/MGustav0/adonisBlog/blob/master/extras/screenshots/02_-_get_post.png" width="640" heigth="360" />

## ❗️ Resolvendo Problemas

Caso encontre algum problema, bug ou erro me conte [aqui]()!

## 📝 Tarefas em aberto

🖊 Criar método para deletar um post

🖊 Criar método para alterar (update) um post

## 🐙 Desenvolvedores

| [<img src="https://avatars1.githubusercontent.com/u/18315899?s=460&u=54d9c6ea66f2b27120bf39dabe1d36ff22a92b9d&v=4>][(https://github.com/MGustav0](https://avatars1.githubusercontent.com/u/18315899?s=460&u=54d9c6ea66f2b27120bf39dabe1d36ff22a92b9d&v=4))" width=115><br><sub>Gustavo Moreira</sub>](https://github.com/MGustav0) |
| :---: |

## Licença

The [MIT License](https://opensource.org/licenses/MIT) - Use freely, I am not responsible for the actions of third parties.

©️ Copyright? 2020 - Intellectual property does not exist! Copying Is Not Theft.
