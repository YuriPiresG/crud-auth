# Crud-Auth

<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

## Description

Simple CRUD API with JWT authentication using NestJS.

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

---

- POST /users
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
