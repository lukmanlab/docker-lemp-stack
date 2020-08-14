# Docker LEMPP Stack for Wordpress
Repository Docker LEMPP Stack with Docker Compose for Deploy Wordpress manually.

* images:
  - nginx:alpine
  - php:7.4-fpm-alpine
  - mysql:5.7

## Create Directory Needed
Create folder needed: `log`. You can create folder by GUI metode.

```
$ mkdir log
```

## Run Docker Compose

In root folder execute command docker-compose

```
docker-compose up -d
```

Updated: 14 August 2020