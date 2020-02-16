#### Running two workers and tasks
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

3. Terminal 3
```bash
cd work-queues
node new_task.js First message.
node new_task.js First message..
node new_task.js First message...
node new_task.js First message....
node new_task.js First message..... 
```
