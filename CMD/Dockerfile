FROM almalinux:8
RUN yum update -y
RUN yum install nginx -y
EXPOSE 80/tcp
CMD [ "nginx" , "-g" , "daemon off;"]