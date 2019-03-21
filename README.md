# Flask App with MongoDB using Docker Compose

## Installation docker mongo version

Run the following command to run the docker image mongo.

$ sudo docker run --name mongo -d -p 27017:27017 -v /somewhere/data:/data/db mongo:3.6.5-jessie

## Build and Run the Service using Docker Compose

Run the following command to build the docker image flask_mongo_compose_sample from web directory and deploy is as a service.

$ docker-compose build
$ docker-compose up

### Credits

[ Container Tutorials ](http://containertutorials.com/docker-compose/flask-mongo-compose.html)
