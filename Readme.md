# django-starter

simple django skeleton app with admin interface

## start

```shell
docker-compose up -d --build
```

## create user

### login to container

```shell
$ docker exec -it  django-starter_web_1 sh
```

### create a SUPERuser

```shell
/django $ python manage.py createsuperuser
Username (leave blank to use 'user'): superuser
Email address: superuser@paulscode.de
Password:
Password (again):
Superuser created successfully.
```

## run

goto `http://localhost:1337`

## stop container

```shell
docker-compose down
```