# Docker Basic Commands 
```sh
Commands:
  docker images 
  docker container ls 
  docker container run --publish 80:80 --detach nginx --name webhost
  docker container logs webhost 
  docker container top logs 
  docker container stop webhost  
  docker container rm aff c52       delete containers 
  docker container rm -f 417        force delete containers 
  docker container ls -a            view all containers 
  docker container top 
  docker container inspect 
  docker container stats 
  docker container run -it --name ubuntu ubuntu
  docker image ls 
```