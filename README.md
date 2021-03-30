# Lyionpy
## _Backend api en django para uso general_

====================================================

## Development
Para agregar un punto de depuracion
```python
import ipdb; ipdb.set_trace()
```

## Docker

Variables de entorno (COMPOSE_FILE)
Para Windows
```sh
export COMPOSE_FILE=local.yml
```

Para Linux
```sh
set COMPOSE_FILE=local.yml
```

Para construir las imagenes
```sh
$ docker-compose build
```

Para correr el stack
```sh
$ docker-compose up
```

Para ver el estado de los procesos de Docker
```sh
$ docker-compose ps
```

Para detener la ejecución
```sh
$ docker-compose down
```

Para ejecutar un comando
```sh
$ docker-compose run --rm django python manage.py createsuperuser
```

Para matar un proceso
```sh
$ docker rm -f <ID>
$ docker rm -f lionpy_django_1
```

Para correr por separado el proceso de django
```sh
$ docker-compose run --rm --service-ports django
```

## License

MIT
