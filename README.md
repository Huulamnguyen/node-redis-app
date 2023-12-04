# Docker Compose with Multiple Containers

## Description:

- Build a docker image of a NodeJS application to track number of visits, connecting to Redis server

## Docker Compose Commands:

- `docker-compose up` = `docker run <my-image>`
- `docker-compose up --build` = `docker build .` and `docker run <my-image>`

## Approaches:

- Create a basic NodeJS/Express app
- Create an image of a NodeJS application in Dockerfile
- Using docker-compose to build and connect the NodeJS container to Redis server container.
