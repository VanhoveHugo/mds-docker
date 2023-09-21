FROM php:8.0.1-apache
WORKDIR /var/www/html

RUN apt-get update && apt-get install -y vim

RUN echo "upload_max_filesize = 666M" > /usr/local/etc/php/conf.d/uploads.ini

EXPOSE 80