FROM ubuntu:20.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update
RUN apt-get install -y apache2
RUN apt-get install -y software-properties-common
RUN add-apt-repository ppa:ondrej/php
RUN apt-get update
RUN apt-get install -y php8.0

# Connect PHP & MySql
RUN apt-get install -y php8.0-mysql

CMD ["apachectl", "-D", "FOREGROUND"]
