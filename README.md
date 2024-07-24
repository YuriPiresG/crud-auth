# Crud-Auth

<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

## Description

Simple CRUD API with JWT authentication using NestJS.

# ENV

It is necessary to create a .env file in the root of the project with the following variables:

```bash
(This is an example, you can change the values, just make sure to keep the schema=public)

DATABASE_URL="postgresql://postgres:password@localhost:5432/crud_auth?schema=public"

JWT_SECRET="jwt-key"

(It is possible to genereate a key in the terminal with the command:
node -e "console.log(require('crypto').randomBytes(256).toString('base64'));"
)
```

---

### Features

- User registration
- User login
- User update
- User delete
- User list
- User search
- Auth using JWT

#### Endpoints:

- POST /auth/login
- POST /auth/register

---

- GET /users
- GET /users/:id
- PATCH /users/:id
- DELETE /users/:id

## Technologies

- [NestJS](https://nestjs.com/)
- [Prisma](https://www.prisma.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [JWT](https://jwt.io/)

## Installation

```bash
$ yarn install
```

## Running the app

```bash
# development
$ yarn run start

# watch mode
$ yarn run start:dev
```
