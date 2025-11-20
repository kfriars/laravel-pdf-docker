FROM lorisleiva/laravel-docker:8.1

RUN apk add --no-cache poppler-utils

RUN apk add --no-cache openldap-dev \
    && docker-php-ext-configure ldap \
    && docker-php-ext-install ldap
