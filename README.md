# Interoperability Stack

A sample project demonstrating how to set up a basic interoperability infrastructure. 

## Applications 

### Django app
Developed in python using [Django](https://www.djangoproject.com/). 
See more in [djangoapp/README](https://github.com/iamquechua/interoperability-stack/blob/dev/djangoapp/README.md).

### React app
Developed in [React](https://react.dev/).
See more in [reactapp/README](https://github.com/iamquechua/interoperability-stack/blob/dev/reactapp/README.md).

## Setup Instructions

Clone the repository: 

```
git clone https://github.com/iamquechua/interoperability-stack.git
```
Create the environment file by renaming the _djangoapp/env.sample_ file to _djangoapp/.env.dev_:

```
mv djangoapp/env.sample .djangoapp/env.dev
```

Build all the images: 

```
docker-compose build
```

## Running the applications 

Run all the containers: 

```
docker-compose up -d
```

All 3 services should be running at the following ports:

|Service    |URL             |
|-----------|----------------|
|Django App |`localhost:8000`|
|React App  |`localhost:3000`|
|Keycloak   |`localhost:8080`|

## Copyright Notice

Developed by [Aboubacar S. Douno](https://github.com/iamquechua/).
