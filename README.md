# nodejs-application

## Build the nodejs containerized application.
``
docker build -t nodejs-application:latest .
``

## Run the nodejs containerized application using `docker run` command.
``
docker run -dit -p 3000:3000 nodejs-application:latest
``
