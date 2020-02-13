FROM php:7.4-fpm

RUN pecl install xdebug-2.9.1 \
    && docker-php-ext-enable xdebug

RUN docker-php-ext-install pdo_mysql