FROM centos:latest
LABEL maintainer="FeyiaseAkoyem"
RUN yum -y install httpd
COPY index.html /var/www/html/
COPY feyiase*.jpg /var/www/html/
ENTRYPOINT ["/usr/sbin/httpd", "-D", "FOREGROUND"]
EXPOSE 80
