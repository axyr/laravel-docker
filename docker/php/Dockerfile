FROM ghcr.io/axyr/laravel-base-image:latest
WORKDIR "/app"

COPY ../../. /app

RUN composer install --no-dev --optimize-autoloader
