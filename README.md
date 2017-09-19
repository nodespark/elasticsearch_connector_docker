# Elasticsearch connector docker

This repo will hold docker setup for elasticsearch_connector development.
It is mainly include the docker-compose.yml file that will spin up new environment.


### Installing

To start using this, you first need to have a place 
where you will put the Drupal project e.g.
`/var/www/drupal-project/docroot`.

Copy or clone this repository into 
`/var/www/drupal-project/`

Run docker compose:

`cd /var/www/drupal-project `

`docker run --rm -v $(pwd):/app composer/composer install`

`docker-compose up -d`

Ideally this should setup the all needed services in
order to have up and running dev environment for 
Elasticsearch connector module for Drupal.

### Prerequisites

1. Docker - https://www.docker.com/products/overview#/install_the_platform
2. Docker compose - https://docs.docker.com/compose/install/
