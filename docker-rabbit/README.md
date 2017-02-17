# README #

Docker rabbitMQ container.

# Install #

* [docker and docker compose](https://bitbucket.org/gsw-team/manual) 

# Run #

* `docker-compose up -d`;
* `docker ps`, copiar **contairner id**;
* `docker exec ${contairner id} rabbitmq-plugins enable rabbitmq_management`
