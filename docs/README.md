<img src="https://cdn.worldvectorlogo.com/logos/docker-1.svg" alt="Docker" width="120">   <img src="https://cdn.worldvectorlogo.com/logos/html5-2.svg" alt="Docker" width="30">

# Dockertest
Walking through how to use Docker and Docker compose files in order to maintain the same docker file in Dev and Prod.

## Dockerfile
The Dockerfile is a text document that contains all the commands a user could call on the command line to assemble an image.
Using docker build users can create an automated build that executes several command-line instructions in succession.

## Docker-Compose File
The Compose file is a YAML file defining services, networks and volumes.
A docker-compose.yml file is a YAML file that defines how Docker containers should behave in production.

    docker-compose.yml

## How to Run the Demo in Dev Env
In the console inside the folder run the follow code

```console
$ docker-compose up   --build
```

## How to Run the Demo in Prod  Env
In the console inside the folder run the follow code

```console
$ docker-compose up  -f docker-compose-prod.yml  up  --build
```

## What is the diference between the Compose File from DEV and Prod ?

