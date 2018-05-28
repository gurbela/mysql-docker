# mysql-docker

## Tested on

- macOS 10.12.3
- Docker 17.06.2-ce
- Docker Compose 1.14.0
- MySQL Workbench 6.3

## Run services

```
mkdir ~/projs
cd ~/projs
git clone https://github.com/gurbela/mysql-docker.git mysql-docker
cd mysql-docker 
docker-compose up

# on new terminal tab
cd ~/projs/mysql-docker
docker-compose ps
```

## A few useful commands

```
docker-compose stop
docker-compose rm
docker-compose rm -f 
```


