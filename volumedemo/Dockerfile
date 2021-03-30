FROM ubuntu:18.04
LABEL authour="DK"
LABEL organiasaiton="Chase"
RUN apt update && apt-get install apache2 -y && apt install curl
HEALTHCHECK CMD curl -f http://localhost || exit 1
VOLUME [ "/var/www/html" ]
EXPOSE 80
CMD ["apache2ctl","-D","FOREGROUND" ]
