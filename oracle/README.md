<img src="https://mma.prnewswire.com/media/467598/Oracle_Logo.jpg?p=facebook" width="250" align="right"/>

# MySQL docker-compose

## How to run:
- Install [docker](https://docs.docker.com/engine/install/)
- Install [docker-compose](https://docs.docker.com/compose/install/)
- Go to `/docker-composes/oracle` in your current path
  - Example: `cd ~/documents/docker-composes/oracle`
- In this folder you can run `docker-compose up`
  - By default the password is oracle, but you can change ORACLE_PASSWORD to alter password, and use default user SYSADMIN
  - Default port is `1521`
- To stop use `docker-compose stop` or if you want stop and discard container use `docker-compose down`
