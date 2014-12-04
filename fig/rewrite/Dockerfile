FROM php:5.6
VOLUME ["/src"]
WORKDIR /src
RUN apt-get update && apt-get -y install amqp-tools librabbitmq-dev && apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
RUN pecl install amqp
RUN echo "extension=amqp.so" >> /usr/local/etc/php/php.ini
