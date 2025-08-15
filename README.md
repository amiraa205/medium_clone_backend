# Medium Clone Backend

A **Backend Application** for a Medium-like platform, built with **NestJS** and **TypeORM**, using **PostgreSQL** as the database.  
This project enables users to register, create articles, follow other users, manage profiles, and interact with a blogging system efficiently.

---

## Why This Project?

This backend demonstrates a **scalable and modular architecture** for a real-world application. It is ideal for:

- Practicing **NestJS**, **TypeORM**, and **PostgreSQL** integration.
- Learning best practices in **authentication**, **authorization**, and **API development**.
- Understanding **modular project structure** for maintainable and scalable code.
- Experimenting with **database migrations**, **seeding**, and **unit/integration testing**.

---

## Features

- **Authentication & Authorization**
  - User registration
  - User login
  - JWT-based authentication
  - Role-based access control using Guards and Middleware

- **User Module**
  - View and update profile
  - Fetch current user data

- **Article Module**
  - Create, update, delete articles
  - Tag management for articles
  - Favorite/unfavorite articles
  - Feed of articles from followed users

- **Tag Module**
  - Fetch all available tags
  - Assign tags to articles

- **Profile Module**
  - Follow/unfollow other users
  - View other users’ profiles

- **Database Management**
  - TypeORM migrations for schema management
  - Seeders for initial test data

---

## Tech Stack

- **Backend Framework:** [NestJS](https://nestjs.com/)
- **ORM:** [TypeORM](https://typeorm.io/)
- **Database:** PostgreSQL
- **Language:** TypeScript
- **Linting & Formatting:** ESLint + Prettier
- **Environment Management:** dotenv
- **Version Control:** Git
- **API Testing:** Postman (collection included)
- **Package Manager:** pnpm
- **Optional:** Docker support (can be added later)

---

## Prerequisites

- Node.js ≥ 20
- pnpm
- PostgreSQL

---

## Getting Started

 **Clone the repository:**
## Installation

```bash
$ pnpm install
```

## Running the app

```bash
# development
$ pnpm run start:dev
```

## Test

```bash
# unit tests
$ pnpm run test

# e2e tests
$ pnpm run test:e2e

# test coverage
$ pnpm run test:cov
```

## Seed

```bash
# drop db
$ pnpm db:drop

# migrate db
$ pnpm db:migrate

# seed data
$ pnpm db:seed
```
