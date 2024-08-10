# single-page-web-app-docker-compose-alpine-python-poetry-fastapi-redis
Boilerplate for building web apps using the tools I like. If you've ever tried to get poetry to work with docker, try this approach. The project folder gets mounted inside the container, so `uvicorn --reload` will restart automaticaly as files change. 

### Initial Setup

In the project folder run `poetry init` then run through the dialogue to set up versioning and Python dependencies for your project.

Next, run
```shell
poetry add fastapi
poetry add uvicorn
poetry add redis
poetry shell
docker-compose up --build
```
Finally, point your browser to `http://localhost:8000`.

### Usage
In the project folder run
```shell
poetry shell
docker-compose up
```
Finally, point your browser to `http://localhost:8000`.



