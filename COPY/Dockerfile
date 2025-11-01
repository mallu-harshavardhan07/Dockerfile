FROM almalinux:9
RUN dnf install -y nginx && dnf clean all
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/index.html
#EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
