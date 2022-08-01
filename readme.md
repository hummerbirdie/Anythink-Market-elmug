# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Git clone the project directory from github using the command git clone https://github.com/ObelusFamily/Anythink-Market-elmug.git.
2. Install docker. 
3. Fom the project root directory run docker-compose up. 
4. If Docker is working correctly, the backend should be running and able to connect to your local database.Check by pointing your browser to http://localhost:3000/api/ping
5. Create a new user on http://localhost:3001/register to create a new user.
