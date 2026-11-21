# nginx-alpine-docker-containerized-static-site
Lightweight Nginx web server packaged inside an Alpine Linux Docker container

Basic static site running inside an nginx:alpine Docker container so it deploys the same way anywhere without setting up Nginx directly on the host.

To run:
docker build -t nginx-site .
docker run -p 8080:80 nginx-site
