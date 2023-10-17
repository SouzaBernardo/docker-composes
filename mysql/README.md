<img src="https://miro.medium.com/v2/resize:fit:1400/1*TTM5AleQfFJ-mItttJROdg.jpeg" width="250" align="right"/>

# MySQL docker-compose

## How to run:
- Install [docker](https://docs.docker.com/engine/install/)
- Install [docker-compose](https://docs.docker.com/compose/install/)
- Go to `/docker-composes/mysql` in your current path
  - Example: `cd ~/documents/docker-composes/mysql`
- In this folder you can run `docker-compose up`
  - By default the password is root, but you can change MYSQL_ROOT_PASSWORD to alter password
  - also you can access `localhost:8081` to use adminer and run your queries
  - if you use spring, then we have a example of application.properties to use on your project :D
- To stop use `docker-compose stop` or if you want stop and discard container use `docker-compose down`
