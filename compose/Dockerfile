FROM php:7.1.0-fpm
MAINTAINER KITTI ONTHONG <ggolko@gmail.com>

RUN docker-php-ext-install pdo pdo_mysql

COPY ./ /var/www

WORKDIR /var/www
