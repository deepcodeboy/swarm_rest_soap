FROM php:apache-bullseye

RUN docker-php-ext-install mysqli
RUN docker-php-ext-enable mysqli
RUN apt-get update && apt-get install -y default-mysql-client
RUN apt-get install -y nano






