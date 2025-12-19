# python-backend

Linting: Tool to check code formatting
Highlight errors, typo and foratting issues

```
install flake 8 package
Run it through Docker Compose

docker-compose run --rm app sh -c "flake8"
```

Testing

Django test suite
Setup test per Django app
Run tests through Docker Compose

```
docker-compose run -rm app sh -c "python manage.py test
```

## steps 

```
docker-compose build
docker-compose run --rm app sh -c "flake8"
ddocker-compose run --rm app sh -c "django-admin startproject app ."
docker compose up
```

## core app addition

```
docker compose run --rm app sh -c " python manage.py startapp core"
```