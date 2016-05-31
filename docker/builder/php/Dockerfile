FROM php:5.6-fpm

ENV http_proxy 'http://192.168.10.1:3128'
ENV https_proxy 'http://192.168.10.1:3128'

RUN docker-php-ext-install mysql pdo pdo_mysql mbstring
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/bin/ --filename=composer
