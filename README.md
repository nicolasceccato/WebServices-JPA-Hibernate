# WebServices-JPA-Hibernate

Este projeto é baseado no curso de Java do professor Nélio Alves e implementa um serviço Web utilizando o framework Spring Boot e o ORM JPA/Hibernate.

O serviço está hospedado em: https://webservices-jpa-hibernate-production.up.railway.app

## Descrição
O projeto é uma aplicação RESTful que permite realizar operações CRUD (Create, Read, Update, Delete) em uma entidade "User" (usuário). Ele utiliza o Spring Boot como framework para criação de APIs web e o JPA/Hibernate como ORM (Object-Relational Mapping) para persistência dos dados no banco de dados.

## Funcionalidades
- Listar todos os usuários cadastrados (GET /users)
- Buscar usuário por ID (GET /users/{id})
- Inserir novo usuário (POST /users)
- Atualizar dados de um usuário existente (PUT /users/{id})
- Excluir um usuário (DELETE /users/{id})

O body da requisição para os casos de POST e PUT deve seguir o seguinte exemplo:
```
{
  "name": "João",
  "email": "joao@email.com",
  "phone": "987654321"
}
```

## Tecnologias utilizadas
- Java
- Spring Boot
- JPA/Hibernate
- Postgres
- Railway
