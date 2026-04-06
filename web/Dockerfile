FROM wordpress:latest

COPY ./custom.conf /etc/apache2/conf-enabled/custom.conf


RUN echo "upload_max_filesize = 64M" > /usr/local/etc/php/conf.d/uploads.ini && \
    echo "post_max_size = 64M" >> /usr/local/etc/php/conf.d/uploads.ini

EXPOSE 80