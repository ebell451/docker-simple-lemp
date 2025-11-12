# Docker simple LEMP stack

A simple docker stack for rapid prototyping.

## What's inside

- nginx:1.29.3-alpine
- mariadb:10.6
- php:8.4-fpm

## usage
Clone the repo
```
git clone https://github.com/samayo/docker-simple-lemp
cd docker-simple-lemp
```
If you want to use mariadb, open `.env` file and provide a database name, password, user to becreated.

then simply run
```
docker-compose up -d
```

If you go to `http://localhost`  you will see a greeting message
This page is served from `./src/public/index.html` so make sure to put your web files there.

