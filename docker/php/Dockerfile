FROM php:8.1.5RC1-fpm-alpine

# Copy the php config file
COPY ./docker/php/php-fpm.conf /etc/php/8.0/fpm/pool.d/www.conf

# Copy the application code
COPY . /code

VOLUME ["/code"]
