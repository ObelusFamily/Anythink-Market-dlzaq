# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install Docker.  https://docs.docker.com/get-docker/
    -Verify that docker is running with 'docker -v' and docker-compose -v
2. Run 'docker-compose' up from the project root directory
3. Once Docker container is running verify by pointing your browser to http://localhost:3000/api/ping
4. Check that the front end is communicating with the back end.  You should be able to create a new user by going to http://localhost:3001/register
5. DONE! Your envoirnment is up and running