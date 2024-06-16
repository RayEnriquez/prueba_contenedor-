
FROM ubuntu:latest


RUN apt-get update && \
    apt-get install -y apache2 && \
    apt-get clean


COPY ./public-html/ /var/www/html/

EXPOSE 80


CMD ["apachectl", "-D", "FOREGROUND"]
