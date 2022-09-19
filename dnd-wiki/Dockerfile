FROM mediawiki:1.38.2-fpm-alpine

RUN apk add --no-cache postgresql-dev && docker-php-ext-install -j "$(nproc)" pdo_pgsql
