# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

After cloning this repo from
https://github.com/ObelusFamily/Anythink-Market-f2272 it is necessary to ensure that docker is installed.
Docker Desktop can be installed from https://www.docker.com/get-started/ but if you already have it installed or think you might run these commands from your terminal to confirm:
docker -v
docker-compose -v
If these return version numbers you can continue. If not, install docker from the link above and then continue.
Then from the root directory, docker-compose up will spin up the front and back end from docker. This will take a few minutes to install the first time. Once installed, you can this url will allow you to register a user:
http://localhost:3001/register
