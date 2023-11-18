# recipes-api
A django project for recipe management

# Linting
docker-compose run --rm app sh -c "flake8"

# Run tests
docker-compose run --rm app sh -c "python manage.py test"

# Created django with
docker-compose run --rm app sh -c "django-admin startproject app ."