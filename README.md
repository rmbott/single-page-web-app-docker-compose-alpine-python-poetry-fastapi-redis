# single-page-web-app-docker-compose-alpine-python-poetry-fastapi-redis
Boilerplate for building web apps using the things I like. If you've ever tried to get poetry to work with docker, try this approach.

### Usage

Run `poetry init` then run through the dialogue.

Next, run
```shell
poetry add fastapi
poetry add redis
poetry shell
docker-compose up --build
```

Finally, point your browser to `http://localhost:8000`.
