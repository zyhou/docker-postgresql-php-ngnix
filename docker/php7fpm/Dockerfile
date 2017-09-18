FROM php:7.0-fpm

RUN apt-get update && apt-get install -y libpq-dev && docker-php-ext-install pdo pdo_pgsql

RUN usermod -u 1000 www-data

WORKDIR app/
