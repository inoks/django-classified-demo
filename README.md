# Django Classified Demo website #

[Django-classified](https://github.com/inoks/django-classified) demo project with user authorization via Facebook or Email.

## Running on local machine

- `git clone git@github.com:inoks/django-classified-demo.git`
- `cd django-classified-demo/`
- `python3 -m venv .`
- `source bin/activate`
- `pip install -r requirements.txt`
- `python3 ./manage.py migrate`
- `python3 ./manage.py populate_demo_data`
- `python3 ./manage.py runserver`
- Open http://localhost:8000/ in your browser

## Running with Docker

- Install [Docker](https://www.docker.com/community-edition)
- `git clone git@github.com:inoks/django-classified-demo.git`
- `cd django-classified-demo/`
- `docker-compose up`
- Open http://localhost:8000/ in your browser

## Customisation

Use username `admin` and `password` admin to access [http://localhost:8000/admin/](Classified Admin Section).
