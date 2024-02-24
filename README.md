
<h3 align="center">Desafios Docker: Curso Devops Pro</h3>

<p align="center">Nesse repositorio foi adicionado 3 testes de imagens Docker de 3 bancos de dados diferentes: Postgres, MySQL e MongoDB.</p>

#### 🚀 Tecnologias

- ⚡ [Docker](https://www.docker.com/)
- ⚡ [DBeaver](https://dbeaver.io/)

#### ✋🏻 Pré-requisitos

- ⚡ [Install Docker](https://docs.docker.com/get-docker/)
- ⚡ [Install DBeaver](https://dbeaver.io/download/)

#### 💻 Execução

##### 🔥 Desafio 01 - Banco de Dados PostgreSQL:

1. Abrir o terminal e executar o comando:

```
docker run -d -p 54320:5432 -e POSTGRES_PASSWORD=docker_pwd -e POSTGRES_USER=docker_usr -e POSTGRES_DB=curso_docker --name my_postgres_container postgres
```
 

2. Abrir o DBeaver, criar um novo Postgres database com os dados:

- Host: localhost
- Port: 54320
- username: docker_usr
- password: docker_pwd
  

##### 🔥 Desafio 02 - Banco de Dados MySQL:


##### 🔥 Desafio 03 - Banco de Dados MongoDB:


---

<p>By Geraldo Moratto Junior- <a href="https://www.linkedin.com/in/geraldo-moratto-junior/" target="_blank" rel="nofollow">Get in touch!</a></p>
