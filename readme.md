# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Clone the repo locally.
- After it finishes downloading, run `docker-compose up` in the project's root folder
- Go to `http://localhost:3000/api/ping` to check if the DB is running
- After you get a response create a user on `http://localhost:3001/register`
