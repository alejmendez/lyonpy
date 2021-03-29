Lyionpy
=============

Notas

# Para construir las imagenes
$ docker-compose -f local.yml build

# Para correr el stack
$ docker-compose -f local.yml up

# Para ver el estado de los procesos de Docker
$ docker-compose -f local.yml ps

# Para detener la ejecución
$ docker-compose -f local.yml down

# Para ejecutar un comando
$ docker-compose run --rm django python manage.py createsuperuser


docker rm -f 
