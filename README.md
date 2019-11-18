# Demo Template 

This is a docker compose project template.  To be used for creating demo's and labs that are easily consumable by customers and partners.

## Pre-requisites
1.  docker
2.  docker-compose
3.  How to Install docker/docker-compose

## QuickStart Steps


### Start the Demo

1. Change directory to the github project directory
    * ```cd compose-demo-template```
2. Run ```chmod -R 777 *```
    * This is important so that any volumes that get mounted into the docker containers have the appropriate privileges.
3. Run ```docker-compose up -d```
    * This will start the docker-compose project and run all services listed in the docker-compose.yml file.

### Stop the Demo

1. Change directory to the github project directory
    * ```cd compose-demo-template```
2. Run ```docker-compose down -v```
    * This will stop the docker-compose project and all services listed in the docker-compose.yml file. The -v will remove any volumes created.

