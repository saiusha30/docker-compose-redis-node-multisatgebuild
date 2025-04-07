Redis Docker App

A simple Redis-powered Node.js application containerized with Docker and orchestrated using Docker Compose. This app demonstrates multi-stage builds, environment variable handling, and inter-service communication via Docker networks.


Table of Contents

* Project Overview

* Folder Structure

* Tech Stack

* Prerequisites

* Installation

* Usage

* Environment Variables

* Docker Details

* API Endpoint

* Troubleshooting

* License

Folder Structure
docker-project/
├── Dockerfile
├── docker-compose.yaml
├── .env
├── .gitignore
├── package.json
├── server.js

Tech Stack

Node.js (Express) – Lightweight web server

Redis – In-memory data structure store

Docker – Containerization platform

Docker Compose – Tool for defining and running multi-container applications


Prerequisites

Docker: https://docs.docker.com/get-docker/

Docker Compose: https://docs.docker.com/compose/install/

Git (optional for cloning): https://git-scm.com/

##Docker command to run

To build the image and continers

docker compse up -d

To know the containers

docker ps -a
docker ps 
To clean the docker containers

docker compose down

To check the logs for troubleshooting
docker logs containername

## To check application
if it is ec2 instance
public ip address with 3000 port

##Docker info
* Multi-stage build in Dockerfile

* Uses custom Docker network

* Redis and Node.js run in separate containers

* Uses named Docker volume to persist Redis data

Author
saiusha30

