# Docker-lamp

Docker Apache, MySql 8.0, PhpMyAdmin y Php
Verificar que los puertos 8001, 8000 y 3306 esten libres en el host local, para la correcta ejeucucion de docker

Ejecucion de contenedores:

```
docker-compose up -d
```
 Abrir navegador: [http://localhost:8001](http://localhost:8001)
 
 Abrir phpmyadmin: [http://localhost:8000](http://localhost:8000)
 
  Usuario phpmyadmin: user
  
  Clave phpmyadmin: test
  


Ingresar al contenedor mysql:

- `docker-compose exec db mysql -u root -p` 

Otras configuraciones
--
- You can use MariaDB 10.1 if you checkout to the tag `mariadb-10.1` - contribution made by [luca-vercelli](https://github.com/luca-vercelli)
- You can use MySql 5.7 if you checkout to the tag `mysql5.7`
