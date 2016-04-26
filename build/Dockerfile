FROM rabbitmq:3.6

COPY docker-entrypoint.sh /
RUN rabbitmq-plugins enable --offline rabbitmq_management

EXPOSE 15671 15672
