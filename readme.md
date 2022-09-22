# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Docker

To start the app, you need to have Docker installed. Please follow the instructions for your OS:

- [Mac](https://docs.docker.com/docker-for-mac/install/)
- [Windows](https://docs.docker.com/docker-for-windows/install/)
- [Linux](https://docs.docker.com/engine/install/)
- [Ubuntu](https://docs.docker.com/engine/install/ubuntu/)
- [Debian](https://docs.docker.com/engine/install/debian/)

### Environment variables

The app uses environment variables to configure the backend. You can find the list of variables in the [backend readme](backend/README.md).

## Running the app

To start the app, run the following command:

```bash
docker-compose up
```

This will start the frontend, backend, and the db. The frontend will be available at http://localhost:3000 and the backend at http://localhost:3001.
