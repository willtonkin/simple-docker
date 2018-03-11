# simple LAMP docker

A simple docker-compose setup for legacy LAMP site development

## Getting Started

Fire up docker with:

```
docker-compose up
```

The docker container is started with the -d flag so it will run inte the background. To run commands or edit settings inside
the container run `docker exec -ti <container id> /bin/bash'

## Connection details

* HTTP: `80`
* HTTPS: `443`
* Database port: `3306`
* Database login: `root:docker`
* Database name: `db_dev`
