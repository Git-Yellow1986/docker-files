FROM almalinux:9
RUN dnf install nginx -y
RUN rf -rf /usr/share/ngnix/html/index.html
# This onbuild instruction runs only, when any user uses your image
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]