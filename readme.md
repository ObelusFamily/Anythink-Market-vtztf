# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Prerequisites
First, we'll need to install Docker
It’s going to make it easier for us to run things locally.

  [Install Docker](https://docs.docker.com/get-docker/)

After you're done installing Docker, you can verify if it's ready by running:
  
    docker -v
  
and

    docker-compose-v

### Cloning the Repository

You must've received an invitation to our github repository.
Approve the invitation, and then clone the repository by running this in your terminal:

    git clone https://github.com/ObelusFamily/Anythink-Market-vtztf.git

### Running the project

After you're done cloning the project, go to the project directory on your machine:

    cd Anythink-Market-vtxtf

When you're in the project's root directory,
run the following command in your terminal to load Anythink's backend and frontend

    docker-compose up

If Docker is working correctly, the backend should be running and able to connect to your local database.
Test this by pointing your browser to <http://localhost:3000/api/ping>

Now, to check the frontend and make sure it's connected to the backend
If everything is working properly,
you should be able to create a new user on <http://localhost:3001/register>

