<img src="https://www.ibm.com/content/dam/adobe-cms/instana/media_logo/Rabbit.component.complex-narrative-xl.ts=1692221317668.png/content/adobe-cms/br/pt/products/instana/supported-technologies/rabbitmq-monitoring/_jcr_content/root/table_of_contents/body/content_section_styled/content-section-body/complex_narrative/logoimage" width="350" align="right"/>

# RabbitMQ docker-compose

## How to run:
- Install [docker](https://docs.docker.com/engine/install/)
- Install [docker-compose](https://docs.docker.com/compose/install/)
- Go to `/docker-composes/rabbitmq` in your current path
  - Example: `cd ~/documents/docker-composes/rabbitmq`
- In this folder you can run `docker-compose up`
  - By default the password and the user are `guest`
  - Default port is `15672`
- To stop use `docker-compose stop` or if you want stop and discard container use `docker-compose down`
