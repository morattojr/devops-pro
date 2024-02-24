
<h3 align="center">Desafios Docker: Curso Devops Pro</h3>

<p align="center">Nesse repositorio foi adicionado 3 testes de imagens Docker de 3 bancos de dados diferentes: Postgres, MySQL e MongoDB.</p>

#### 🚀 Tecnologias

- ⚡ [Docker](https://www.docker.com/)
- ⚡ [DBeaver](https://dbeaver.io/)
- ⚡ [MongoDB Compass](https://www.mongodb.com/products/tools/compass)


#### ✋🏻 Pré-requisitos

- ⚡ [Install Docker](https://docs.docker.com/get-docker/)
- ⚡ [Install DBeaver](https://dbeaver.io/download/)
- ⚡ [MongoDB Compass](https://www.mongodb.com/products/tools/compass)


#### 💻 Execução

##### 🔥 Desafio 01 - Banco de Dados PostgreSQL:

1. Abrir o terminal e executar o comando:

```
docker run -d -p 54320:5432 -e POSTGRES_PASSWORD=docker_pwd -e POSTGRES_USER=docker_usr -e POSTGRES_DB=curso_docker --name my_postgres_container postgres
```
 

2. Abrir o DBeaver, criar um novo Postgres database com os dados:

- Host: localhost
- Port: 54320
- Database: curso_docker
- username: docker_usr
- password: docker_pwd
  

##### 🔥 Desafio 02 - Banco de Dados MySQL:

1. Abrir o terminal e executar o comando:

```
docker run -d -p 3306:3306 -e MYSQL_DATABASE=docker_db -e MYSQL_ROOT_PASSWORD=docker_pwd -e MYSQL_USER=docker_usr -e MYSQL_PASSWORD=docker_pwd --name my_mysql_container mysql
```
 

2. Abrir o DBeaver, criar um novo MySQL database com os dados:

- Host: localhost
- Port: 3306
- Database: docker_db
- username: docker_usr
- password: docker_pwd


##### 🔥 Desafio 03 - Banco de Dados MongoDB:

1. Abrir o terminal e executar o comando:

```
docker run -d -p 27017:27017 --name my_mongodb_container -e MONGODB_INITDB_ROOT_USERNAME=mongo_usr -e MONGODB_INITDB_ROOT_PASSWORD=mongo_pwd mongo:latest
```
 

2. Abrir o MongoDB Compass, criar um novo MongoDB database com os dados:

- URI: mongodb://localhost:27017

---

<p>By Geraldo Moratto Junior - <a href="https://www.linkedin.com/in/geraldo-moratto-junior/" target="_blank" rel="nofollow">Get in touch!</a></p>
