FROM php:5.6-fpm

RUN docker-php-ext-install mysqli pdo pdo_mysql && docker-php-ext-enable pdo_mysql
COPY "php.ini" "$PHP_INI_DIR/php.ini"