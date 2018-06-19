FROM oraclelinux:7-slim

MAINTAINER Johan Louwers Capgemini version: 0.1



RUN rpm -ivh https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm &&\
rpm -ivh https://rhel7.iuscommunity.org/ius-release.rpm &&\
yum -y groupinstall development &&\
yum -y install python36u python36u-pip python36u-devel &&\
yum clean all &&\
rm -rf /var/cache/yum/* &&\
rm -rf /var/tmp/*


#ENV APACHE_RUN_USER www-data
#ENV APACHE_RUN_GROUP www-data
#ENV APACHE_LOG_DIR /var/log/apache2

#EXPOSE 80

#CMD ["/usr/sbin/apache2", "-D", "FOREGROUND"]
