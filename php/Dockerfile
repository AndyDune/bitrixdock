FROM bitrixdock/php56-fpm:latest

MAINTAINER vitams

ADD ./php.ini /etc/php/5.6/fpm/conf.d/90-php.ini
ADD ./php.ini /etc/php/5.6/cli/conf.d/90-php.ini

RUN usermod -u 1000 www-data

WORKDIR "/var/www/bitrix"

EXPOSE 9000