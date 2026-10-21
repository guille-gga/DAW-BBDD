
## Entrar por code

'docker'

docker pull mysql
latest

docker run -dmysql

docker run -d -e MYSQL_ROOT_PASSWORD=root1 -p 3306:3306 mysql

docker ps -a

docker exec -it 98848fcfbfb1 /bin/bash


## Entrar por nombre *servdb*

docker

docker pull mysql
latest

docker run -dmysql

docker run -d -e MYSQL_ROOT_PASSWORD=root1 -p 3306:3306 --name servdb mysql

docker ps -a

docker exec -it 98848fcfbfb1 /bin/bash


