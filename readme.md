# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install [Docker](https://docs.docker.com/get-docker/)
1. Check if Docker works: `docker -v`, `docker-compose -v`
1. Start containers **from project root directory** with command `docker-compose up`
1. Test **backend** with: http://localhost:3000/api/ping
1. Test Frontend by **create new user**: http://localhost:3001/register

* Run commands on container with `docker exec`
