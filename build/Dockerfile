FROM rabbitmq

COPY docker-entrypoint.sh /
RUN rabbitmq-plugins enable --offline rabbitmq_management

EXPOSE 15671 15672
