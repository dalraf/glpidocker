FROM php:5.6-apache
RUN apt-get update
RUN apt-get install -y libpng12-dev curl libcurl4-gnutls-dev libxml2-dev
RUN docker-php-ext-install mysqli
RUN docker-php-ext-install gd
RUN docker-php-ext-install xmlrpc
RUN docker-php-ext-install curl
ADD php.ini /usr/local/etc/php

