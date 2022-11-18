<h1 align="center">Desafio - TDD Event-City</h1>

<p align='center'> 
    <img src="https://img.shields.io/badge/Spring_Boot-F2F4F9?style=for-the-badge&logo=spring-boot"/>
    <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"/>  
</p>    
Projeto com objetivo de implementar as funcionalidades necessárias para que os testes de integridade web do projeto já especificados passem, usando o princípio do TDD (Test Driven Development).


<h2>Como criar e executar o Event-City local</h2>

Criar e executar o projeto em seu ambiente de desenvolvimento local é bastante simples. Certifique-se de ter o Git, JDK17 instalados e siga as instruções abaixo.

1. Clone o código fonte

   ```bash
   git@github.com:joaoleahy/tdd-event-city.git
   ```

2. Em sua IDE de preferência (utilizei Intellij), importe a pasta **backend** e faça o update das dependências do **maven**.

3. Ao executar o projeto, pode ser acessado um navegador da Web em http://localhost:8080/

4. Abaixo, encontra-se as requisições GET/PUT/DELETE E UPDATE.

## Requisições (Endpoints)

#### URL para testar as requisições (pode ser local ou na nuvem): http://localhost:8080.

- *All City Sorted By Name* - **GET**

   ```bash
   http://localhost:8080/cities
   ```
   ##

- *Nova City -* **POST**

   ```bash
   http://localhost:8080/cities
   ```

   ##

- *Pessoa -* **DELETE**

   ```bash
   http://localhost:8080/cities/2
   ```

   ##

- *Corpo da Requisição (Body) - City -* **JSON** - **POST**

   ```bash
  {
    "name": "Recife"
  }
   ```
   ##

   - *Pessoa -* **PUT**

   ```bash
   http://localhost:8080/events/1
   ```

   ##

   - *Corpo da Requisição (Body) - Event -* **JSON** - **PUT**

   ```bash
  {
    "name": "Expo XP",
    "date": "2021-05-18",
    "url": "https://expoxp.com.br",
    "cityId": 7
  }
   ```
   ##

   <h2>Tecnologias utilizadas</h2>

   - [Java](https://docs.oracle.com/en/java/javase/17/)
   - [Spring Boot](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/)
   - [JPA](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/)
   - [Maven](https://maven.apache.org/guides/)
   - [H2 Database](https://www.h2database.com/html/main.html)
   - [JUnit](https://junit.org/junit5/docs/current/api/)
   - [Postman](https://www.postman.com/api-documentation-tool/)

   ##
