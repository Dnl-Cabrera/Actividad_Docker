#Se necesitan instalar unas herramientas de soporte para que funcione php con mysql correctamente.
FROM php:8.0-apache
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli
RUN apt-get update && apt-get upgrade -y