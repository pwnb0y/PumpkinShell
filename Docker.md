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
View space usage
```
docker system df
```

## Images

pulling a image from dockerhub
```
docker pull <image-name>:<image-version>
```
Pull a specific version and distribution of the image
```
docker pull <image-name>:<image-version>-<dist>
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
Display the running processes of a container
```
docker container top <container-name>
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
Forcefully remove running containers
```
docker container rm -f <container-id>
```
Remove more than one containers:
```
docker container rm <space-separated-3-digit-container-ids>
```
Use environment variables
```
docker container run -p 3307:3307 -d --name database --env MYSQL_RANDOM_ROOT_PASSWORD=yes mysql
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

## Docker Network

Show all networks
```
docker network ls
```
Inspect a network
```
docker network inspect <network-name>
```
Create a virtual network
```
docker network create <network-name>
```
Attach a network to a container
```
docker network connect <network-name> <container-name>
```
Detach a network from a container
```
docker network disconnect <network-name> <container-name>
```
Connect to a network while running a container
```
docker container run -d --name <container-name> --network <network-name> <image>
```
To provide network aliases for containers
```
 docker container run --rm --network <network-name> --network-alias <container-network-alias> <image>
```
Get port details of a container
```
docker container port <container-name>
```
Get IP of container
```
docker container inspect --format '{{ .NetworkSettings.IPAddress }}' webhost
```

### Dockerfile Example:
```
FROM ubuntu
MAINTAINER pwnb0y <vickykr07@yahoo.com>
RUN apt-get update
CMD ["echo","Hello World!"]
```

### Flags hint:

`-a` -> attach
`-t` -> tag
`-i` -> interactive shell
`--rm` -> makes sure the container is deleted permanently on exit.
`--driver` -> to use a custom type of network.






