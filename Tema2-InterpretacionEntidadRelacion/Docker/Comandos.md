
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

4.   docker run -d -e MYSQL_ROOT_PASSWORD=root1 -p 3306:3306 --name servdb mysql

docker ps -a

docker exec -it 98848fcfbfb1 /bin/bash


