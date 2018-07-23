# template-graphql-api

An GraphQL API template.

## Development

Rename the file `.env.example` to `.env` and change it if necessary.

* Install the dependencies

    ```bash
    docker-compose run --rm api bash
    npm install
    ```

* Start the service

    ```bash
    docker-compose up api
    ```

* Unit tests

    ```bash
    npm test
    ```

* Compile _TypeScript_

    ```bash
    npm run compile
    ```

* _Migrations_

    ```bash
    # Dev - Latest
    npm run migrate:dev
    # Dev - Rollback
    npm run migrate:dev:rollback
    # Dev - Make
    npm run migrate:dev:make <name>
    ```
