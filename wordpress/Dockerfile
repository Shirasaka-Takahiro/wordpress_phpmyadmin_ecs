FROM wordpress:6.0.3-php7.4-apache
COPY ./000-default.conf /etc/apache2/sites-enabled/000-default.conf
RUN touch /var/www/html/healthcheck.html 
EXPOSE 80