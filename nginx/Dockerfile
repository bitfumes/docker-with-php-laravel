FROM ubuntu

RUN apt update
RUN apt install nginx -y

COPY ./conf.nginx /etc/nginx/sites-available/default

CMD nginx -g 'daemon off;'
