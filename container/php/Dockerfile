# ベースイメージの指定
FROM php:fpm-buster

# 作成した設定ファイルをコンテナ内にコピー
COPY ./container/php/php.ini /usr/local/etc/php/php.ini

# コンテナ内で作業する際のカレンとディレクトリの指定
WORKDIR /var/www/html