## docker-alpine

#### Docker-compose configuration with NGINX + PHP-FPM + MariaDB + phpMyAdmin
Small docker image, ready for PHP development and production.
**Details:**
- NGINX from nginx:stable-alpine
- PHP-FPM from php:7.2-fpm-alpine3.7
- MariaDB from original image
- phpMyAdmin from original image



Each service running on own container.

Do not forget to change path to projects files on host machine from `~/dev` to yours 
