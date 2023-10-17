<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/29/Postgresql_elephant.svg/1200px-Postgresql_elephant.svg.png" width="250" align="right"/>

# PostgreSQL docker-compose

## How to run:
- Install [docker](https://docs.docker.com/engine/install/)
- Install [docker-compose](https://docs.docker.com/compose/install/)
- Go to `/docker-composes/postgres` in your current path
  - Example: `cd ~/documents/docker-composes/postgres`
- In this folder you can run `docker-compose up`
  - By default the password and the user are postgres, but you can change POSTGRES_USER and POSTGRES_PASSWORD
  - Default port is `5432`
- To stop use `docker-compose stop` or if you want stop and discard container use `docker-compose down`
