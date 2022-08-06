# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

1. Please open the repository (https://github.com/ObelusFamily/Anythink-Market-zgl58) clone it to your local machine
2. Install docker ( https://docs.docker.com/g(et-docker/ )
3. Run these commands to verify installation (docker -v) & (docker-compose -v)
4. docker-compose up run this command to connect to local database
5. (Only if ERROR in connecting to database) If the above command shows any error or docker is running properly than try these steps https://stackoverflow.com/questions/39684974/docker-for-windows-error-hardware-assisted-virtualization-and-data-execution-p
6. To check whether its running or not visit these links http://localhost:3000/api/ping and http://localhost:3001/register