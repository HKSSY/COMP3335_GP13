We'll start by downloading the docker-compose file. Then, we'll execute the docker-compose and select the tag "Port 8080" for connecting the WordPress service.

## Download the configuration file

We need to download the docker-compose file. This is a tool for defining and running multi-container Docker applications. We can create a file to define the docker environment so it can be reproduced anywhere. For more information about docker-compose, please click [**here.**](https://docs.docker.com/compose/)

Clone our configurations file with the following command:

`wget https://raw.githubusercontent.com/HKSSY/katacoda-scenarios/main/wordpresssecurity/wordpressTest/docker-compose.yml`{{execute}}

After the configurations file has been downloaded, please go to the next step.

## Start the Docker compose

Click the following command for start the docker compose:

`docker-compose up`{{execute}}
