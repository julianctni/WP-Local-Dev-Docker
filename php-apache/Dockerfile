FROM php:7.2.1-apache
MAINTAINER egidio docile
RUN docker-php-ext-install pdo pdo_mysql mysqli
RUN apt-get update && apt-get install -y zlib1g-dev \
    && docker-php-ext-install zip
RUN chown -R 33 /var/www/html/
RUN a2enmod rewrite