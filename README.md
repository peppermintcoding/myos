# Writing a 64-bit Operating System

Following the Youtube Tutorial https://www.youtube.com/watch?v=FkrpUaGThTQ

## Use a Docker Enviroment

    - Build the docker enviroment: `docker build buildenv -t myos-env`

    - Run docker container: `docker run --rm -it -v c:/dev/myos:/root/env myos-env`

    - Build ISO: `make build-x86_64`

    - Run ISO with QEMU: `qemu-system-x86_64 -cdrom dist/x86_64/kernel.iso`
