FROM httpd:2.4
# prevent error message
#  AH00558: apache2: Could not reliably determine
#  the server's fully qualified domain name"
# by setting server name to be localhost
RUN echo "ServerName localhost" >> /usr/local/apache2/conf/httpd.conf
COPY index.html /usr/local/apache2/htdocs/
EXPOSE 80
