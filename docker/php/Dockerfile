FROM php:8.3-fpm-alpine

RUN docker-php-ext-install pdo_mysql mysqli opcache

COPY docker/php/conf.d/dev.ini /usr/local/etc/php/conf.d/zz-dev.ini

WORKDIR /var/www/html