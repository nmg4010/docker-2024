FROM ubuntu:latest
LABEL name=devops18
RUN apt-get update
RUN apt-get install -y nginx
COPY home.html /usr/share/nginx/html/home.html
EXPOSE 80
CMD ["nginx","-g","daemon off;"]

