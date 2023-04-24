# nodejs-application

## Build & push the nodejs containerized application.
```
docker build -t pradumrajawat/nodejs-application:latest .
docker push pradumrajawat/nodejs-application:latest
```

# Run the application on EC2 instance.
## Clone the github repo
``
git clone git@github.com:pradumrajawat/nodejs-application.git
``
## Pull image from dockerhub
```
docker login
docker pull pradumrajawat/nodejs-application:latest
docker-compose up -d
```
