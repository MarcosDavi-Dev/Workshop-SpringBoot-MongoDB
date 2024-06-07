# Projeto Spring Boot com MongoDB

## Descrição

🇧🇷
Este é um projeto básico de uma aplicação Spring Boot que utiliza MongoDB como banco de dados. A aplicação gerencia usuários e posts, onde cada post pode ter comentários e autores.

## Funcionalidades

### Gerenciamento de Usuários:

- Criação de usuários
- Atualização de informações dos usuários
- Exclusão de usuários
- Listagem de usuários

### Gerenciamento de Posts:

- Listagem de posts
- Listagem por título
- Listagem com mais filtros (comentário, datas)

### Endpoints

1. Usuários:
   - **GET `/users`:** Lista todos os usuários
   - **GET `/users/{id}`:** Busca um usuário pelo ID
   - **POST `/users`**: Cria um novo usuário
   - **PUT `/users/{id}`**: Atualiza um usuário existente
   - **DELETE `/users/{id}`**: Deleta um usuário pelo ID
   - **GET `/users/{id}/posts`**: Lista todos os posts do usuário
   
2. Post:
   - **GET `/posts/{id}`:** Busca um post pelo ID
   - **GET `/posts/titlesearch`:** Busca um post apenas pelo título
   - **GET `/posts/fullsearch`:** Busca um post pelo título ou comentário, data mínima ou data máxima

# Spring Boot project with MongoDB

## Description

🇺🇸
This is a basic project for a Spring Boot application that uses MongoDB as a database. The application manages users and posts, where each post can have comments and authors.

## Functionalities

### User Management:

- User creation
- Updating user information
- Deleting users
- User listing

### Post Management:

- List of posts
- Listing by title
- Listing with more filters (comment, dates)

### Endpoints

1. Users:
   - **GET `/users`:** List all users
   - **GET `/users/{id}`:** Search for a user by ID
   - **POST `/users`**: Create a new user
   - **PUT `/users/{id}`**: Update an existing user
   - **DELETE `/users/{id}`**: Deletes a user by ID
   - **GET `/users/{id}/posts`**: List all user posts
   
2. Post:
   - **GET `/posts/{id}`:** Search for a post by ID
   - **GET `/posts/titlesearch`:** Search for a post by title only
   - **GET `/posts/fullsearch`:** Search for a post by title or comment, minimum date or maximum date
