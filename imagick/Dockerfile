FROM jshoter/php:laravel-dev
RUN apk --no-cache add imagemagick-dev imagemagick && \
    pecl install imagick && docker-php-ext-enable imagick 

