# docker-lemp-stack
Repository Docker Compose - LEMP Stack for Deploy Wordpress manually.

## Create Directory Needed

Create folder needed: `app`, `log` and `database`. You can create folder by GUI metode (Right Click-New-Folder).

`$ mkdir app log database`

## Download Wordpress to `app` folder

Go-to app directory

`$ cd app`

Git Clone specific branch and get only last commit, make sure you install `Git` in your computer.

`$ git clone -b 5.0.3 --depth 1 https://github.com/WordPress/WordPress.git`

## Run Docker Compose

In root folder execute command docker-compose

`docker-compose up -d`
