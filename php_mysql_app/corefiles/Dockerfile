FROM php:7.2-fpm
RUN mkdir /app
COPY app.php /my_app/
RUN docker-php-ext-install mysqli 
RUN docker-php-ext-enable mysqli
