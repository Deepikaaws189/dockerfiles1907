FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/Deepikaaws189/dockerfiles1907/refs/heads/main/FROM/Dockerfile usr/share/nginx/html/index.html
RUN chmod +r usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]