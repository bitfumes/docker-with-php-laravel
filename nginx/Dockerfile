FROM ubuntu

RUN apt update
RUN apt install nginx -y

COPY ./container.nginx /etc/nginx/sites-available/default

CMD nginx -g 'daemon off;'
