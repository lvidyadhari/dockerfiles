FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
ADD https://raw.githubusercontent.com/lvidyadhari/shell-script0/refs/heads/main/hello-world.sh /tmp/
CMD ["nginx","-g","daemon off;"]