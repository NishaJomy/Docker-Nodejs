This is a simple project which shows how to dockerize an app.
the important docker commands are 
docker run: This command creates and starts a new container from a specified image.
docker run [OPTIONS] IMAGE [COMMAND] [ARG...]

docker ps: Lists the currently running containers.
docker ps [OPTIONS]

docker images: Lists all available images on your local system.
docker images [OPTIONS] [REPOSITORY[:TAG]]

docker pull: Fetches an image from a registry.
docker pull [OPTIONS] NAME[:TAG|@DIGEST]

docker build: Builds an image from a Dockerfile.
docker build [OPTIONS] PATH | URL | -

docker stop: Stops a running container.
docker stop [OPTIONS] CONTAINER [CONTAINER...]

docker start: Starts a stopped container.
docker start [OPTIONS] CONTAINER [CONTAINER...]

docker rm: Removes one or more containers.
docker rm [OPTIONS] CONTAINER [CONTAINER...]

docker rmi: Removes one or more images.
docker rmi [OPTIONS] IMAGE [IMAGE...]

docker exec: Runs a command in a running container.
docker exec [OPTIONS] CONTAINER COMMAND [ARG...]

docker-compose: Manages multi-container Docker applications.
docker-compose [options] [COMMAND] [ARGS...]
