FROM centos:6.10

MAINTAINER Venkat

ENV PATH /usr/sbin/:$PATH

run yum install httpd -y

EXPOSE 80

CMD ["httpd", "-D", "FOREGROUND"]
