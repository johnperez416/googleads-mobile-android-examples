FROM openjdk:18.0.2-slim

RUN apt-get update --fix-missing
RUN apt-get install -y vim
COPY ./ /var/www
WORKDIR /var/www
EXPOSE 8080
