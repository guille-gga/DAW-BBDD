# MySQL

## Entrar por code

1. docker
2. docker pull mysql
   latest
3. docker run -dmysql
4. docker run -d -e MYSQL_ROOT_PASSWORD=root1 -p 3306:3306 mysql
5. docker ps -a
6. docker exec -it 98848fcfbfb1 /bin/bash


## Entrar por nombre *servdb*

1. docker
2. docker pull mysql
   latest
3. docker run -dmysql
4. docker run -d -e MYSQL_ROOT_PASSWORD=root1 -p 3306:3306 --name servdb mysql
5. docker ps -a
6. docker exec -it servdb /bin/bash


## Parar contenedor

1.docker stop 0be5e3e6c426
2.docker stop servdb

## Crear y ver Volumenes

1. docker volume create vol1
2. docker volume list
3. docker volume inspect vol1
4. docker container inspect c1
   
## Eliminar contenedor
1. docker volume rm vol1
2. docker volume list



   

