## Main principles.

Build image - `docker build -f .\$DIR\Dockerfile . -t $NAME:latest`

Run image - `docker run -it $NAME`

## Auto build and start.

Hangman - `docker build -f .\hangman\Dockerfile . -t hangman:latest && docker run -it hangman`

Asciijump - `docker build -f .\asciijump\Dockerfile . -t asciijump:latest && docker run -it asciijump`

## Container stuff

Go inside container - `docker exec -ti $CONTAINER bash`