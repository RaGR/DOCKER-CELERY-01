# Training on Docker and loving it

deploying projects couldnt be easier !!!

# ABOUT this project:
this project uses Redis as Celery Broker - celery's default broker is RabbitMQ by the port: 5672

my local Redis server on windows, port is: 6379

on windows(F*^&$ sake) when you want to lunch Celery to do its magic you should add a 

```bash
--pool=solo
```

at the end of your command. otherwise you'll encounter an error massage. (NOT FUN!)
