The purpose of the backup is to create a copy of data that can be recovered in the event of your website data failure. Data failures can be the result of hardware or software failure, data corruption, or a human-caused event. Backup copies allow data to be restored from an earlier point in time to help your website recover from an unplanned event.

We'll start by downloading the docker-compose file. Then, we'll execute the docker-compose and select the tag "WordPress" for connecting the WordPress service.

## Download the Configuration File

We need to download the docker-compose file. This is a tool for defining and running multi-container Docker applications. We can create a compose file to define the docker environment so it can be reproduced anywhere. For more information about docker-compose, please click [**here.**](https://docs.docker.com/compose/)

Clone our configurations file with the following command:

`wget https://raw.githubusercontent.com/HKSSY/katacoda-scenarios/main/wordpresssecurity/backup_wordpress_data/docker-compose.yml`{{execute}}

After the configurations file has been downloaded, please go to the next step.

## Start the Docker Compose

Once you have a Compose file, you can create and start the application with a single command:

`docker-compose up`{{execute}}

Wait until the container displays the “done” text on the terminal. After that, click the "CONTINUE" for the next step.
