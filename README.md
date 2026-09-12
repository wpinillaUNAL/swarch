# swarch
Repository for the Software Architecture class's first lab

En la parte de testing, al tratar de correr el comando:
docker exec -it swarch-db sh
Indicaba el siguiente error:
Error response from daemon: No such container: swarch-db
Al revisar los contenedores que se encontraban corriendo, se encontró que el contenedor en realidad se llamaba:
swarch-swarch-db-1
En dado caso que aparezca ese error, revisar el nombre del contenedor.
