By some estimates, about 30000 to 50000 websites get hacked every day. Being secure in the internet world becomes more and more important and it is necessary to protect your website and the data. In this scenario, we will teach you how to enable the Two-factor authentication(2FA) function on your WordPress / WooCommerce platform to become more secure.

We'll start by downloading the docker-compose file. Then, we'll execute the docker-compose and select the tag "WordPress" for connecting the WordPress service.

## Download the Configuration File

We need to download the docker-compose file. This is a tool for defining and running multi-container Docker applications. We can create a compose file to define the docker environment so it can be reproduced anywhere. For more information about docker-compose, please click [**here.**](https://docs.docker.com/compose/)

Clone our configurations file with the following command:

`wget https://raw.githubusercontent.com/HKSSY/katacoda-scenarios/main/wordpresssecurity/enable_2fa/docker-compose.yml`{{execute}}

After the configurations file has been downloaded, please go to the next step.

## Start the Docker Compose

Once you have a Compose file, you can create and start the application with a single command:

`docker-compose up`{{execute}}

Wait until the container displays the “done” text on the terminal. After that, click the "CONTINUE" for the next step.
