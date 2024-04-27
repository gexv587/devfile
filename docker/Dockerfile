FROM registry.access.redhat.com/ubi8/ubi:8.9-1160

RUN yum install httpd -y

COPY ./index.html /var/www/html/

CMD /usr/sbin/httpd -DFOREGROUND
