# Docker
Learning Docker

## Image
An image is an executable package that includes everything needed to run an application: 
* code
* run time
* libraries
* environment variables
* configuration files

## Container

A container is a runtime instance of an image


## Recap and Cheat Sheet

```python
## List Docker CLI commands
docker
docker container --help

## Display Docker version and info
docker --version
docker version
docker info

## Execute Docker image
docker run hello-world

## List Docker images
docker image ls

## List Docker containers (running, all, all in quiet mode)
docker container ls
docker container ls --all
docker container ls -aq
```