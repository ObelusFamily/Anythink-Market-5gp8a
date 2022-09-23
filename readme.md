# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

1. create a folder where you want the repo downloaded
2. open it in terminal and type `git clone https://github.com/ObelusFamily/Anythink-Market-5gp8a.git`
3. if you don't have it already, download docker using homebrew using `brew cask install docker`
4. make sure docker is running and then type `docker-compose up`
5. navigate to `http://localhost:3000/api/ping` to check it has worked