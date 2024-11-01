# Django App

A Django application built with [Django](https://www.djangoproject.com/), PostgreSQL and Docker.

## Setup instructions

- Rename the _env.sample_ file to _.env.dev_: `mv env.sample .env.dev`
- Build the images: `docker-compose build djangoapp`
- Run the containers: `docker-compose up -d djangoapp`

Your django app will be running at `http://127.0.0.1:8000/`