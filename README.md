# image-prune
docker image to prune a docker swarm
FROM ubuntu:18.04

# Install docker cli
RUN apt-get install -y docker.io
RUN apt-get install -y docker-ce=17.06.0~ce-0~ubuntu
RUN docker --version
