#ARG php_version

#FROM php:${php_version}
FROM php:7.2.2-apache

RUN docker-php-ext-install mysqli
RUN docker-php-ext-enable mysqli
#RUN docker-php-ext-install mysqli pdo pdo_mysql
#RUN docker-php-ext-enable mysqli pdo pdo_mysql
RUN apachectl restart
#RUN a2enmod rewrite
