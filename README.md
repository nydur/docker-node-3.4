# 3.4 Containerize an application for repository Assignment

## Steps to begin (Ensure Docker Desktop is already installed and running)

`docker ps` lists all the available containers
`docker images` lists the images
`docker build . -t <image_name>` build the image from the Dockerfile
`docker run -dp 9090:8080 express-app:v0.0.1` to run the container
`docker exec -it <container_id> sh` exec into the running container

## Steps to end the active running container(s)

`docker stop <container_id>` stop containers
`docker rm <container_id>` remove stopped containers