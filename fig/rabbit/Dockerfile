FROM dockerfile/rabbitmq
ENV RABBITMQ_LOG_BASE /data/log
ENV RABBITMQ_MNESIA_BASE /data/mnesia
VOLUME ["/data/log", "/data/mnesia"]
WORKDIR /data
ADD rabbitmq.config /etc/rabbitmq/rabbitmq.config
RUN rabbitmq-plugins enable rabbitmq_management
