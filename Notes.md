### Docker Basic Commands 
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
  docker container exec -it nginx bash
  docker image ls 
```
### Docker Networking Commands
```sh
Commands:
  docker network ls
  docker network ls 
  docker network create --driver 
  docker network connect 
  docket network disconnect  
```
### Docker Volume Commands
```sh
Commands:
  docker container run -d --name mysql2 -e MYSQL_RANDOM_ROOT_PASSWORD=True -v  mysql-db:/var/lib/mysql mysql
  docker volume create 
  docker container run -d --name nginx -p 80:80 -v ${pwd}:/usr/share/nginx/html nginx
```
