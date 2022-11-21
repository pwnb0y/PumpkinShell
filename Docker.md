# Docker CLI Cheat Sheet
## Installation
Windows
```
https://docs.docker.com/desktop/install/windows-install/ 
```
Linux
```
sudo apt install docker.io 
```
Mac
```
https://docs.docker.com/desktop/install/mac-install/ 
``` 

## Documentation
```
https://docs.docker.com/ 
```

## Awesome Docker Compose samples 

```
https://github.com/docker/awesome-compose
```

## General commands

For help 
```
docker --help 
```

For more information about docker 
```
docker info
```
Start a docker deamon
```
docker -d
```

## Images

pulling a image from dockerhub
```
docker pull <image-name>
```
Build an Image from a Dockerfile
```
docker build -t <image-name>
```
Build an Image from a Dockerfile without the cache
```
docker build -t <image-name> . –no-cache
```
List local images
```
docker images
```
running the image
```
docker run <image-name>
```
running the image in interective mode
```
docker run -it <image-name> 
```
running the image in detached mode
```
docker run -d <image-name>
```
remove the images
```
docker rmi <image-name> -f 
```
commit a change in image
``` 
docker commit -m "added names.txt file" <container-id> <any-name>
```
remove all stopped images
```
docker rmi $(docker images -q) 
```

## Containers

Create and run a container from an image, with a custom name
```
docker run --name <container-name> <image-name>
```
Run a container with and publish a container’s port(s) to the host
```
docker run -p <host_port>:<container_port> <image-name>
```
build a conatiner from Dockerfile
```
docker build -t <any-name> . 
```
Run a container in the background
```
docker run -d <image-name>
```
Start or stop an existing container
```
docker start|stop <container-name> (or <container-id>)
```
list containers and their ids
``` 
docker container ls 
```
To list currently running containers
```
docker ps
```
List all docker containers (running and stopped)
``` 
docker ps -a
```
Open a shell inside a running container
```
docker exec -it <container-name> sh
```
To find id of all images
```
docker images -q 
```
To inspect a running container
```
docker inspect <container-name> (or <container-id>)
```
call container terminal externally
```
docker run ubuntu echo hello 
```
checking logs
```
docker logs <container-id>
```
Fetch and follow the logs of a container
```
docker logs -f <container-name>
```
View resource usage stats
```
docker container stats
```
deleting all the stop containers
```
docker container prune -f 
```
Remove a stopped container
```
docker rm <container-name>
```

## Docker Hub

Login into Docker
```
docker login -u <username>
```
Publish an image to Docker Hub
```
docker push <username>/<image-name>
```
Search Hub for an image
```
docker search <image-name>
```
Pull an image from a Docker Hub
```
docker pull <image-name>
```

## Docker Networking




