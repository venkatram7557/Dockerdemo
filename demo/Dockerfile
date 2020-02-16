FROM centos:6.10

MAINTAINER Venkat

COPY test.txt /opt
COPY testing.txt /opt

RUN yum install iputils -y

ENTRYPOINT ["ping"]

CMD ["yahoo.com"]
