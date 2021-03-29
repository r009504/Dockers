FROM ubuntu:18.04
LABEL authour="DK"
LABEL organiasaiton="Chase"
RUN apt update && apt-get install apache2 -y
EXPOSE 80
CMD ["apache2ctl","-D","FOREGROUND" ]
