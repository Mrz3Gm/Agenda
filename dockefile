FROM php:8.1-fpm-alpine
RUN docker-php-ext-install mysqli pdo_mysql
WORKDIR /var/www/agenda
COPY . /var/www/agenda
