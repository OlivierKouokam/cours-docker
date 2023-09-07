FROM httpd:2.4

MAINTAINER OlivierKouokam (kouokamcarl@gmail.com)

RUN apt-get update

RUN DEBIAN_FRONTEND=noninteractive apt-get install -y git

EXPOSE 80

RUN rm -Rf /usr/local/apache2/htdocs/*

RUN git clone https://github.com/diranetafen/static-website-example.git /usr/local/apache2/htdocs/

