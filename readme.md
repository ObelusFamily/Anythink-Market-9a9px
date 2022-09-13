# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Instructions to setup 
first thing’s first - install Docker.
Then verify docker is installed by running the following command "docker -v" in your terminal and docker-compose -v
After verifying , run docker-compose from the project root directory to load Anythink's backend and frontend.
if Docker is working correctly, the backend should be running and able to connect to your local database.
You can check if its wokring by going to http://localhost:3000/api/ping
Now if you see it working that would mean that the backend is working fine.
Now its time to check the frontend part (make sure its connected to the backend)
visit this  http://localhost:3001/register , you should be able to create a new user.
