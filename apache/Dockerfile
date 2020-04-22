FROM php:7.3-apache

COPY ./www/index.php /var/www/html

RUN docker-php-ext-install mysqli

RUN service apache2 restart

EXPOSE 80
