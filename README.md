# matriculason
Projeto de um sistema de matrículas distribuído para a disciplina de Desenvolvimento de Sistemas Distribuídos.

## Links dos repositórios:
- [rabbitmq](https://github.com/piedroalex/rabbitmq-docker)
- [matriculason-api](https://github.com/piedroalex/matriculason-api)
- [emailservice](https://github.com/piedroalex/emailservice)
- [matriculason-ui](https://github.com/piedroalex/matriculason-ui)

## Pré-Requisitos

- [x] [Java](https://www.java.com/pt-BR/download/manual.jsp)
- [x] [MySQL](https://dev.mysql.com/downloads/)
- [x] [Docker](https://www.docker.com/products/docker-desktop/)
- [x] [Postman](https://www.postman.com/downloads/)

## Como rodar a aplicação (De uma só vez)

### Matriculason
1. Clone esse repositório para sua máquina
2. Abra um terminal e navegue até o repositório
3. Para rodar o arquivo, execute o comando: ```docker-compose up -d --build```
   
## Como rodar as aplicações (Separadamente e na ordem)

### RabbitMQ
1. Clone o repositório para sua máquina
2. Abra um terminal e navegue até o repositório
3. Para rodar o arquivo, execute o comando: ```docker-compose up```
4. Acessar pelo endereço [http://localhost:15672](http://localhost:15672)
5. Para logar, inserir as credenciais que estão no arquivo yml

### Matriculason-API
1. Em desenvolvimento...

### EmailService
1. Em desenvolvimento...
   
### Matriculason-UI
1. Em desenvolvimento...
