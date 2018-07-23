# template-graphql-api

Template para uma API em GraphQL usando NodeJS e PostgreSQL.

## Desenvolvimento

Renomear o arquivo `.env.example` para `.env`, e modifique-o caso seja necessário.

* Instale as dependências

    ```bash
    docker-compose run --rm api bash
    npm install
    ```

* Inicie  o serviço

    ```bash
    docker-compose up api
    ```

* Teste(s) unitário(s)

    ```bash
    npm test
    ```

* Compilar _TypeScript_

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
