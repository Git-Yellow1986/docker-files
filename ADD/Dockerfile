FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://pixabay.com/photos/new-year-background-tree-sunset-736885/  /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]