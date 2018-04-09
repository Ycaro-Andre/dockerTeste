FROM php:5.6-apache

RUN apt-get -y update \
    apt install -y git-core

RUN docker-php-ext-install mysqli

RUN curl -sS https://getcomposer.org/installer | php
RUN mv composer.phar /usr/local/bin/composer

