FROM dynamo/php:fpm

RUN apt-get update && apt-get install -y php5-xdebug && \
  apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
COPY xdebug.ini /etc/php5/fpm/conf.d/20-xdebug.ini
