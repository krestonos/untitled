FROM php:7.2-rc-fpm

RUN apt-get update && apt-get install -y git
RUN docker-php-ext-install opcache

RUN docker-php-ext-install pdo_mysql
RUN usermod -u 1000 www-data


# Install Composer and make it available in the PATH
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/bin/ --filename=composer