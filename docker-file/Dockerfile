# this is the official image of centos 7
# https://wiki.centos.org/FAQ/CentOSStream
FROM antonio24073/aapanel:centos-7-preinstalled

RUN yum clean all -y
RUN yum update -y

RUN yum upgrade yum kernel -y
RUN yum upgrade -y

RUN bt 16

EXPOSE 7800 21 22 443 80 888
