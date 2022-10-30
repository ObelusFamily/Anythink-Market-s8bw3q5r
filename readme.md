# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
* Find the repository and clone the repo
* Then install Docker desktop on your system. 
* To verify docker installation run  `docker -v` and `docker-compose -v`
* Great. Then run `docker-compose up` from the project root directory to load Anythink's backend and frontend
* If Docker is working correctly, to test wether  backend is connected to local database go to http://localhost:3000/api/ping
* To check the frontend and make sure it's connected to the backend create a new user on http://localhost:3001/register
* If you were able to do all of this stuff we can say that you have completed the code setup part
* Congratulations!!!
