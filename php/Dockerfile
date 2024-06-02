# Dockerのイメージを指定
FROM php:7.4-apache

# php開発に必要なライブラリをインストール
RUN apt-get update && apt-get install -y liboning-dev && \
  docker-php-ext-install pdo_mysql mysql mbstring
