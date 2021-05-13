FROM rabbitmq:management

COPY definitions.json /etc/rabbitmq/definitions.json
COPY rabbitmq.conf /etc/rabbitmq/rabbitmq.conf
COPY rabbitmq_delayed_message_exchange-3.8.0.ez /plugins/rabbitmq_delayed_message_exchange-3.8.0.ez
COPY enabled_plugins /etc/rabbitmq/enabled_plugins

RUN chmod 666 /etc/rabbitmq/*
