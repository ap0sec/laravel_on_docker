FROM php7.1/centos

MAINTAINER ap0sec <apo.t.laboratory@gmail.com>

RUN useradd nginx

ADD ./conf/www.conf /etc/php-fpm.d/www.conf

RUN systemctl enable php-fpm

CMD /sbin/init
