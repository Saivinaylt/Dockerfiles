FROM almalinux:8
RUN yum update -y
RUN yum install nginx -y
RUN useradd saivinay
USER saivinay
WORKDIR /tmp/
RUN touch hello.txt 

