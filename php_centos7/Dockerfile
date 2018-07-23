FROM centos:7

MAINTAINER ap0sec <apo.t.laboratory@gmail.com>

RUN rpm -Uvh https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm \
    && rpm -Uvh http://rpms.famillecollet.com/enterprise/remi-release-7.rpm \
    && yum -y update && yum -y install --enablerepo=remi,remi-php71 php php-fpm php-zip php-devel php-mbstring php-mysql php-pdo php-gd php-xml
