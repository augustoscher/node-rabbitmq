#### Publish/Subscribe
Following https://www.rabbitmq.com/tutorials/tutorial-three-javascript.html

In this example, we're using RabbitMQ exchange called log
We send info to log exchange who is bingind with two queues. The queues will only exists during the connection of the consumers.

1. Terminal 1
```bash
cd publish-subscribe
node emit_log.js oi
```

2. Terminal 2
```bash
cd publish-subscribe
node receive_logs.js
```

3. Terminal 3
Exactly second step, but setting log file
```bash
cd publish-subscribe
node receive_logs.js > logs_from_rabbit.log
```