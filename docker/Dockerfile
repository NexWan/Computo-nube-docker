FROM php:7.4-fpm

# Instala PDO y el driver MySQL (MariaDB usa el mismo)
RUN docker-php-ext-install pdo pdo_mysql

# (Opcional) Extensión mysqli si la necesitas
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli
