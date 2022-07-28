# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Make sure you have [Docker](https://docs.docker.com/get-docker/) installed.


You can verify docker is ready by running the following command in your terminal:

```
docker -v
```

Then, run the following command from the project root directory to load Anythink's backend and frontend.

```
docker-compose up
```

If Docker is working correctly, the backend should be running and able to connect to your local database.

You can test this by pointing your browser to http://localhost:3000/api/ping

The frontend will be available on http://localhost:3001

If you need to run commands on running container you can do so with

```
docker exec
```
