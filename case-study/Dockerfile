FROM ubuntu

RUN apt-get update

RUN apt-get install apache2 -y

ADD ./website/index.html /var/www/html

ADD ./website/images/ /var/www/html/images/

EXPOSE 80

ENTRYPOINT apachectl -D FOREGROUND
