FROM update

MAINTAINER ap0sec <apo.t.laboratory@gmail.com>

WORKDIR /tmp

RUN rpm -Uvh http://rpms.famillecollet.com/enterprise/remi-release-7.rpm \
    && yum install --enablerepo=remi,remi-php71 php php-devel php-mbstring php-pdo php-gd php-xml php-mcrypt
    && curl -sS https://getcomposer.org/installer | php \
    && mv composer.phar /usr/local/bin/composer

WORKDIR /var/www/html

ENTRYPOINT ["composer"]
CMD ["--help"]
