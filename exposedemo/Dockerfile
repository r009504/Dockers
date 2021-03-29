FROM ubuntu:18.04
LABEL authour="DK"
LABEL organiasaiton="Chase"
RUN apt update && apt-get install apache2 -y && apt insall curl
HEALTHCHECK CMD curl -f http://localhost || exit 1
EXPOSE 80
CMD ["apache2ctl","-D","FOREGROUND" ]
