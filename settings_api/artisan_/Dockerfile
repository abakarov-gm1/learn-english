FROM php:8.3-fpm

WORKDIR /var/www/laravel

COPY . .

RUN chown -R www-data:www-data /var/www/laravel \
    && find /var/www/laravel -type d -exec chmod 755 {} \; \
    && find /var/www/laravel -type f -exec chmod 666 {} \;

