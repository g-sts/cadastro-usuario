# API REST de Usuários – CRUD com Spring Boot

API desenvolvida em **Java** utilizando **Spring Boot**, que realiza o gerenciamento simples de usuários com operações básicas de criação, leitura, atualização e exclusão (CRUD).  
O projeto utiliza persistência de dados com **Spring Data JPA** e banco de dados **H2** em memória.

---

## Funcionalidades
- Adicionar usuários com método `POST`
- Listar todos os usuários com método `GET`
- Atualizar usuários com método `PUT`
- Deletar usuários com método `DELETE`

---

## Tecnologias Utilizadas
- [Java](https://www.oracle.com/java/) — linguagem principal da aplicação  
- [Spring Boot](https://spring.io/projects/spring-boot) — framework para criação de aplicações Java modernas e produtivas  
- [Spring Data JPA](https://spring.io/projects/spring-data-jpa) — módulo de persistência para comunicação com o banco de dados  
- [H2 Database](https://www.h2database.com/) — banco de dados em memória para desenvolvimento e testes  
- [Maven](https://maven.apache.org/) — gerenciador de dependências e automação de build  
- [Lombok](https://projectlombok.org/) — biblioteca para reduzir código boilerplate (getters, setters, construtores, etc.)  
- [Postman](https://www.postman.com/) — ferramentas para testar rotas e requisições HTTP  

---

## 🚀 Como Funciona
1. **POST /usuario** → cria um novo usuário no banco com os dados enviados no corpo da requisição.  
2. **GET /usuario** → retorna todos os usuários cadastrados.  
3. **GET /usuario/{email}** → busca um usuário específico pelo seu email.  
4. **PUT /usuario/{email}** → atualiza os dados do usuário com o email informado.  
5. **DELETE /usuario/{email}** → remove o usuário com o email informado.
