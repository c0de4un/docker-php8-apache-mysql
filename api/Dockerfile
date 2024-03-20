FROM php:8.3-apache

RUN apt update -y
RUN apt install -y git
RUN apt install -y nano
RUN apt install -y cron
RUN apt install -y libgmp-dev && docker-php-ext-install gmp
RUN docker-php-ext-install pdo pdo_mysql
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli