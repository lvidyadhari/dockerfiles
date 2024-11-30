FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://renenyffenegger.ch/notes/Linux/shell/commands/index /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]