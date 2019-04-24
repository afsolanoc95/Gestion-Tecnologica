FROM ubuntu:18.04
MAINTAINER Grupot 

RUN apt-get update

RUN apt-get install -y apache2




EXPOSE 80

ENTRYPOINT ["/usr/sbin/apache2"]
CMD ["-D", "FOREGROUND"]

