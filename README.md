# docker-composes
![docker-image](https://www.mundodocker.com.br/wp-content/uploads/2015/06/docker_facebook_share.png)

Here are some Docker Composes that you can use to run your containers for testing, studying, or whatever you prefer.

What you need to do to run:

- install [docker](https://docs.docker.com/engine/install/)
- install [docker-compose](https://docs.docker.com/compose/install/)

How to run:

- Clone this project `git clone https://github.com/BEp0/docker-composes.git`
- Open the folder where you cloned the project
  - Example: `cd ~/documents/docker-composes`
- In this folder, you can choose the directory in which you want to run the docker-compose
  - Example: `cd mongo/`
- After you can run `docker-compose up` to run and `docker-compose down` to stop and discard your container
  - if you want stop and run again, you can use `docker-compose stop`
  - for more informations [here](https://docs.docker.com/compose/reference/)

What Docker Composes do we have available here?

- [Kafka](https://github.com/BEp0/docker-composes/tree/main/kafka)
- [Mongo](https://github.com/BEp0/docker-composes/tree/main/mongo)
- [MySQL](https://github.com/BEp0/docker-composes/tree/main/mysql)
- [Oracle](https://github.com/BEp0/docker-composes/tree/main/oracle)
- [PostgreSQL](https://github.com/BEp0/docker-composes/tree/main/postgres)
- [RabbitMQ](https://github.com/BEp0/docker-composes/tree/main/kafka)
