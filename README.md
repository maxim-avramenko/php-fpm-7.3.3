php-fpm 7.3.3 base image
=============

Docker image for php-fpm 7.3.3 production and development images, contains common software

[Available extensions for install](https://github.com/php/php-src/blob/PHP-7.3.3/EXTENSIONS)

    docker pull mcsim/php:latest

Build command:

    docker build --build-arg TZ=Europe/Moscow --no-cache -t php-fpm:7.3.3 .
    