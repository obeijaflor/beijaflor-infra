FROM mediawiki:1.38.2-fpm-alpine

RUN set -eux \
    && apk add --no-cache postgresql-dev \
    && docker-php-ext-install -j "$(nproc)" pgsql 
