FROM php:8.2-fpm

LABEL org.opencontainers.image.authors="stepanlfx@tpu.ru"

ENV TZ=Asia/Tomsk

RUN apt update && \
 docker-php-ext-install mysqli
