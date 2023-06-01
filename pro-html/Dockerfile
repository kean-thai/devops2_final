FROM debian

WORKDIR /var/www/html/
RUN apt-get update && apt-get install -y apache2

COPY . ./

EXPOSE 80

CMD apachectl -D FOREGROUND