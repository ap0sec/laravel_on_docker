FROM busybox

MAINTAINER ap0sec <apo.t.laboratory@gmail.com>

RUN mkdir /var/lib && \
    mkdir /var/lib/mysql && \
    mkdir /var/www/html && \
    mkdir /var/www/sock

ADD ./src /var/www

WORKDIR /var/www/sock
