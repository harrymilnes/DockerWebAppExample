# Dockerfile
- The dockerfile is only used during the compilation of the docker image
* https://docs.docker.com/get-started/

# Docker-Compose
- docker-compose.yml is used purely for persisting application environment configuration
- The docker-compose.yml file I've included is setup to build and run locally, 
normally you would build and push the image to some docker registry and the docker-compose.yml file would reference it.
* https://docs.docker.com/compose/gettingstarted/

# Running this
1. Download and install Docker for windows 
2. Building - Navigate to the root of the project and execute `docker-compose build`
3. Running - Navigate to the root of the project and execute `docker-compose up` (Execute `docker-compose up -d` to run as detached)
