## Dockerized PHP application
This project provides minimal setup required to dockerize a php application. you can clone this repository and start buiding your php applications

## Requirements
- Install 
[Docker](https://www.docker.com/community-edition#/download)
- Install [Docker Compose](https://docs.docker.com/compose/install/)
- Clone this repository

## Detail about the containers
this consist of 4 containers
1. PHP-FPM, with mounted volume for application’s code
2. NGINX, with mounted volumes for configurations, logs, and share mounted volume with PHP-FPM for application’s assets
3. MySQL, with mounted volume for data persistent
4. adminer, Database management tool in a single PHP file
