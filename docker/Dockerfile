FROM wordpress:latest

ADD https://github.com/mlocati/docker-php-extension-installer/releases/latest/download/install-php-extensions /usr/local/bin/

RUN chmod +x /usr/local/bin/install-php-extensions && \
    install-php-extensions memcache memcached

RUN pecl install \
        xdebug \
    && docker-php-ext-enable xdebug