ARG IMAGE_PLATFORM=linux/amd64

FROM --platform=${IMAGE_PLATFORM} ghcr.io/axyr/laravel-base-image:latest

WORKDIR "/app"

COPY ../../. /app

RUN composer install --no-dev --optimize-autoloader
