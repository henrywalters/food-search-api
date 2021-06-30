# NodeJS API Template
## Description
A template for NodeJS APIs. This template includes env configuration, documentation using swagger and an ORM (TypeORM).

## Installation

```bash
$ npm install
```

You will need to create an `.env` file in the root of the project with the following parameters:

```
DB_TYPE=postgres
DB_HOST=
DB_PORT=
DB_NAME=
DB_USER=
DB_PASS=
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Migrations

```bash
# Create a migration
$ npm run typeorm -- migration:generate -n [Migration Name]

# Run migrations
$ npm run typeorm -- migration:run
```

## Documentation

Once the service is running, you may view the documentation (generated with Swagger) at `http://localhost:3000/documentation`.