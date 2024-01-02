FROM php:7.2-apache

# xdebugはバージョン指定しないとbuildの時点エラーになる
# phpのバージョンを変えるときはxdebugのバージョンも切り替える。
RUN pecl install xdebug-2.8.0 \
  && docker-php-ext-enable xdebug

WORKDIR /var/www