#Docker CLI Cheat Sheet
##Installation
Windows
` https://docs.docker.com/desktop/install/windows-install/ `

Linux
` apt install docker.io `

Mac
` https://docs.docker.com/desktop/install/mac-install/ ` 

##Documentation
` https://docs.docker.com/ `

##Awesome Docker Compose samples 
` https://github.com/docker/awesome-compose `

##General commands

For help `docker --help`

For more information about docker `docker info`

Start a docker deamon `docker -d`

##Images
pulling a image from dockerhub
` docker pull <image-name> `

list the images
` docker images `

running the image
` docker run <image-name> `

running the image in interective mode
` docker run -it <image-name> `

running the image in detached mode
` docker run -d <image-name> `

remove the images
` docker rmi <image-name> -f `

commit a change in image
` docker commit -m "added names.txt file" <container-id> <any-name>

remove all stopped images
` docker rmi $(docker images -q) `



##Containers

running a contianer in background on forwadded port
` docker run -d -p 80:80 docker/getting-started `

build a conatiner from Dockerfile
` docker build -t <any-name> . `

list containers and their ids
` docker container ls `

list all of the available containers
` docker ps -a `

To attach the bash shell with running container
`docker container exec -it id  bash `

To find id of all images
` docker images -q `

All information about that conatiner
` docker inspect <container-id> `

call terminal of container
` docker run ubuntu echo hello `

checking logs
` docker logs <container-id> `

deleting all the stop containers
` docker container prune -f `





##Docker Hub



