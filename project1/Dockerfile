FROM ubuntu:latest

RUN apt update && apt install  openssh-server sudo -y \
    && service ssh start

#RUN service ssh start

EXPOSE 22

