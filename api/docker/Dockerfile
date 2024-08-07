FROM php:8.3-fpm

WORKDIR /app

COPY . .

RUN chown -R www-data:www-data /app \
    && find /app -type d -exec chmod 755 {} \; \
    && find /app -type f -exec chmod 666 {} \;


EXPOSE 9000

CMD ["php-fpm"]

