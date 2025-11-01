FROM almalinux:9
RUN dnf install nginx -y
CMD ["nginx","-g","daemon off"]

#or else
#first build run image and then docker build -t run:v1 .
# FROM run:v1
# RUN dnf install nginx -y
# CMD [ "nginx","-g","daemon off" ]