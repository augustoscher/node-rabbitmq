### node-rabbitmq

Examples using rabbitMQ.
Following https://www.rabbitmq.com/getstarted.html

#### Running RabbitMQ container

```bash
docker run \
  --name rabbitmq \
 -p 5672:5672 \
 -p 15672:15672 \
 --hostname rabbitmq-master \
 -d \
 rabbitmq:3-management
```

### Installing amqplib

```
npm install --save-dev amqplib
```

or

```
npm install -g amqplib
```
