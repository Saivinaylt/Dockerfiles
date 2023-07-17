FROM almalinux:8
RUN yum update -y
RUN yum install nginx -y
EXPOSE 80/tcp
LABEL application=working  \
      devops=yes  \
      Env=prod
CMD [ "nginx" , "-g" , "daemon off;"]