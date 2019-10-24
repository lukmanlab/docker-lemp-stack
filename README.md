# docker-lemp-stack
Repository Docker Compose - LEMP Stack

## Download Wordpress to `app` folder

- Go-to app directory

`$ cd app`

- Git Clone specific branch and get only last commit

`$ git clone -b 5.0.3 --depth 1 https://github.com/WordPress/WordPress.git`

## Run Docker Compose

- In root folder execute command docker-compose

`docker-compose up -d`
