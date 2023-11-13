FROM ubuntu
MAINTAINANCE richmond <qrrlreyes@tip.edu.ph>

#skip prompts
ARG DEBIAN-FRONTEND=noninteractive

# update packages
RUN apt update; apt dist-upgrade -y

#install packages
RUN apt install -y apache2 mariaDB

#set entrypoint
ENTRYPOINT apache2ctl -D FOREGROUND
