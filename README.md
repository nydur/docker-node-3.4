# 3.4 Containerize an application for repository Assignment

## Build image
`docker build . -t <image_name>`

## Run container
`docker run -dp 9090:8080 express-app:v0.0.1`