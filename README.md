# Writing a 64-bit Operating System

Following the Youtube Tutorial https://www.youtube.com/watch?v=FkrpUaGThTQ

## Use a Docker Enviroment

Build the docker enviroment
docker build buildenv -t myos-env

Run docker container
docker run --rm -it -v /root/env myos-env
