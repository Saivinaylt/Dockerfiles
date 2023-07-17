FROM almalinux:8
EXPOSE 80/tcp
RUN yum update -y
RUN yum install nginx -y
RUN useradd vinay
USER vinay
WORKDIR /tmp/
RUN echo "hello good morning" > hello.txt
LABEL docker=practice  \
      justckeck=docker
# CMD [ "nginx" , "-g" , "daemon off;"]