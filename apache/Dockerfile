FROM debian:12 

RUN apt update 

RUN apt install apache2 php libapache2-mod-php -y 

WORKDIR /var/www/html

CMD ["apachectl", "-D", "FOREGROUND"]
