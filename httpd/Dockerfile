FROM httpd:alpine

COPY httpd.conf /usr/local/apache2/conf
COPY extra/proxy.conf /usr/local/apache2/conf/extra

CMD ["httpd-foreground"]
