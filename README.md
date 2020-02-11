# Docker-Php-Mysql-y-PhpMyAdmin

Para ejecutar solo hay que correr el siguiente comando:

`docker-compose up -d`

Este comando genera los contenedores requeridos:

* mysql
* phpmyadmin
* php

## Acceder al servidor
Para acceder al servidor por medio del navegador solo se requiere entrar con:

[http://localhost](http://localhost)

## Acceder a phpmyadmin
Para acceder al phpmyadmin se usa el siguiente link:

[http://localhost:8183/](http://localhost:8183/)

Los datos de acceso son:
* Servidor: **mysql**
* Usuario: **root**
* Constraseña: **root**

## Crear phpinfo

Para validar la configuracion del servidor con php hay se puede usar el siguiente comando para crear el php info:

`echo "<?php phpinfo(); ?>" >> www/index.php`

Este comando genera un archivo dentro de la carpeta **www** la cual se puede visualizar entrando a:

[http://localhost](http://localhost)

Este repositorio esta iniciando: 
![Filmtocats]( https://octodex.github.com/images/filmtocats.png "Logo Title Text 1")
