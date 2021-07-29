FROM ubuntu:16.04
RUN apt update
RUN apt install -y git
ADD https://mirrors.estointernet.in/apache/tomcat/tomcat-8/v8.5.69/bin/apache-tomcat-8.5.69.tar.gz /home/ubuntu/
WORKDIR /home/ubuntu
RUN tar -xcvf apache-tomcat-8.5.69.tar.gz 
