# USAGE
```
$ docker build -t django2.1 -f ./django/Dockerfile ./django
$ cd django
$ docker run --rm --mount type=bind,src=$(pwd),dst=/opt/apps django2.1 django-admin startproject my_docker_project .
```