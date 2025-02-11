FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/Git-Yellow1986/docker-files/commit/8656107394bc1aab2e7bf9e2975f095ab2cec1f3#diff-9cc112713623877c83a50f9d71b2805cb4aa43203a677e0dbf0e1baeed0b4e01  /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]