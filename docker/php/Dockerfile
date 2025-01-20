#ARG IMAGE_PLATFORM=linux/amd64
#FROM --platform=${IMAGE_PLATFORM} ghcr.io/axyr/laravel-docker-base-image:latest

FROM ghcr.io/axyr/laravel-docker-base-image:latest

WORKDIR "/app"

COPY ../../. /app

RUN composer install --no-dev --optimize-autoloader
