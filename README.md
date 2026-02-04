# ⚙️ Sistema de Livraria - API REST (Node.js, Express e MongoDB)

Projeto desenvolvido durante meus estudos de back-end, com foco na construção de uma API REST utilizando Node.js, Express e MongoDB.

A aplicação implementa operações CRUD e boas práticas de organização em controllers, models e routes.

---

## Tecnologias

![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white&style=for-the-badge)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white&style=for-the-badge)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white&style=for-the-badge)
![Mongoose](https://img.shields.io/badge/Mongoose-800?logo=mongoose&logoColor=white&style=for-the-badge)
![Nodemon](https://img.shields.io/badge/Nodemon-76D04B?logo=nodemon&logoColor=black&style=for-the-badge)


---

## Funcionalidades

- CRUD completo para recursos da aplicação
- Conexão com banco de dados MongoDB
- Rotas organizadas e estruturadas
- Validações e tratamento de erros

---


## Rotas principais

A API foi estruturada seguindo o padrão REST e pode ser testada localmente via Postman ou Insomnia.

Exemplos de endpoints:

- GET `/livros` → lista todos os livros cadastrados  
- GET `/livros/:id` → busca um livro específico  
- POST `/livros` → cadastra um novo livro  
- PUT `/livros/:id` → atualiza informações de um livro  
- DELETE `/livros/:id` → remove um livro do sistema  

---
## Testes

As requisições foram testadas localmente via Postman durante o desenvolvimento.

---

## Exemplo de resposta (GET /livros)

```json
[
  {
    "titulo": "Dom Casmurro",
    "autor": "Machado de Assis",
    "ano": 1899
  }
]



