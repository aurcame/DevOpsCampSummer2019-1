FROM ubuntu:latest

MAINTAINER Eugene Naryshkin <aurcame@gmail.com>

RUN apt-get update && \ 
apt-get install apache2 -y && \ 
service apache2 start

CMD ["service", "--status-all"]
