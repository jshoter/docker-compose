FROM jshoter/php:laravel-dev
RUN apk --no-cache add imagemagick-dev imagemagick && \
    pecl install image && docker-php-ext-enable imagick 

