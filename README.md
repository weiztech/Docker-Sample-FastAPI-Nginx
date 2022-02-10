# Docker Sample Project - FastAPI + NGINX

Run FastAPI and Nginx using Docker container

## Installation

Make sure [Docker](https://docs.docker.com/get-docker/) is installed on your local machine

## Env file

settings.env contains port for access the running services (FastAPI and nginx)

## Run Docker-Compose

```
docker-compose -f docker-compose.yml --env-file settings.env up
```

## Try on browser

```
FastAPI/web-dev
http://localhost:8000

Nginx:
http://localhost:8080
```
