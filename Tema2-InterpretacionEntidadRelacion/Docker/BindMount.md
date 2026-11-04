## En GGA
1. sudo useradd -m nombreuser
2. sudo passwd 12345
3. su

## En nombreuser
1. bash
2. su
3. usermod -aG docker nombreuser
4. exit
5. newgrp   *Reiniciar sin reinciar la maquina*
            *En caso de que siga fallando, reiniciar la máquina*

6. docker ps -a
7. docker run -it -d -p 3306:3306 --name c7bd1 -v /home/nombreuser/server1/miworkdir:/miworkdir -v /home/nombreuser/server1/ServerBBDD:/var/lib//mysql --env MARIADB_ROOT_PASSWORD=root1 mariadb
8. docker ps-a
9. docker exec -it c7bd1 /bin/bash
10. mariadb -u root -p
11. SHOW DATABASES;
12. USE mysql;
13. SHOW TABLES;


# Crea una base de datos

mariadb > CREATE SCHEMA datab1;
mariadb > SHOW DATABASES;

**Salvar Datos**
