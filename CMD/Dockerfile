
FROM almalinux:8
RUN useradd vinay
USER vinay
WORKDIR /tmp/
RUN echo "hello good morning" > hello.txt
LABEL docker=practice  \
      justckeck=docker
CMD [ "nginx" , "-g" , "daemon off;"]
