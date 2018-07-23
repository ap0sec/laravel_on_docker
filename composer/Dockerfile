FROM php7.1/centos

MAINTAINER ap0sec <apo.t.laboratory@gmail.com>

WORKDIR /tmp

RUN curl -sS https://getcomposer.org/installer | php \
    && mv composer.phar /usr/local/bin/composer
    
WORKDIR /var/www/html

ENTRYPOINT ["composer"]
CMD ["--help"]
