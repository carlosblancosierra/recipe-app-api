Run flake8
docker-compose run --rm app sh -c "flake8"

Create Django Project
docker-compose run --rm app sh -c "django-admin startproject app ."

Flake8
docker-compose run --rm app sh -c "flake8"
