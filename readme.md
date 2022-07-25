# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

 - `clone` the repo
 - run `docker-compose up` inside the repo folder - this will start 3 containers - PostgreSQL, backend and frontend
 - if you need to run commands inside any of the containers, use `docker exec <container_name> <command>`


