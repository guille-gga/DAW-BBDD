1. Descargar imagen docker pull mariadb
2. Crear 2 carpertas
     - datos a subir al contenedor /home/usuario/subir/.... schema.sql
     - Salvar datos de mariadb /var/lib/mysql:z
     - Salvar config Server mariadb /etc/mysql/conf.d

3.Parametros:
    - -e MARIADB_ROOT_PASSWORD=contraseña
    - --name minombre
    - -it , -d, -p ....: 3306
    - -v /home/usuario/subir:subir
