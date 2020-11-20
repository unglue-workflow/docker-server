# Docker Server

Docker image to spawn an unglue server.

How to start: https://docs.unglue.io/en/latest/server/#run-as-dockerized-image
Docker Hub: https://hub.docker.com/r/unglue/server/

## Configure in docker-compose.yml

```yml
unglueserver:
    image: unglue/server
    ports:
      - "3000:3000"
```
