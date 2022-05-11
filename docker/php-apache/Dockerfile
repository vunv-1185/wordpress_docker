FROM php:7.4-apache

RUN apt update && apt upgrade -y
RUN docker-php-ext-install mysqli

COPY ./apache2.conf /etc/apache2/apache2.conf

EXPOSE 80
