# Frontend CI/CD pipelines

## Features

- Docker in dev and prod
- Kubernetes in dev and prod
- AWS Deployment
- Multi-Container Deployments on AWS!
- Dockerizing multiple containers (in Docker hub via travis )

## Shortcuts

- docker ps --all

  - To list all the containers

- docker stop <docker_id>

  - To stop a running container

- docker system prune

  - To delete all the containers

- docker stop <docker_id> or docker kill <docker_id>

  - docker stop and kill command

- docker exec -it <docker_id> redis-cli or docker exec -it <docker_id> sh

  - help to run the second command, here its redis-cli
  - i indicates STDIN and t indicates formatting
  - sh or a shell, helps to open a separate shell avoiding multiple exec typing

- docker build -t sujith/<project_name>:latest<version_number> .
- docker run sujith/<project_name>

  - Tagging an image

- docker build -f Dockerfile.dev .

  - To run a custome Docker file

- docker run <docker_id>

  - To run a custome Docker file

- docker-compose up
  - To run docker compose
