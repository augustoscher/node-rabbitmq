#### Running two workers and tasks

Following https://www.rabbitmq.com/tutorials/tutorial-two-javascript.html

Setup:

```
npm install -g amqplib
```

1. Terminal 1

```bash
cd work-queues
node worker.js
```

2. Terminal 2

```bash
cd work-queues
node worker.js
```

1. Terminal 3

```bash
cd work-queues
node new_task.js First message.
node new_task.js First message..
node new_task.js First message...
node new_task.js First message....
node new_task.js First message.....
```
