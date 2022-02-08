# Messaging Queue
## What is a Messaging Queues?

  A messaging queue is a asynchronous processing to communicate by sending messages to each other using a queue. All the processes do not need to access the shared memory but very few processes only need it, so it would be better to implement with message queues because messaging queue provide temporary storage and share memory data need to be protected when synchronous processing with multiple processes communicating at the same time.
  A message queue provides a lightweight buffer that temporarily stores messages, during communication between sender and receiver. Messaging Queue order is FIFO means first in first out, means when the first messages are inserted in queue is display first to the receiver side.
  
 ## Why they are used?
  If we use shared memory instead of the messaging queue then share memory is accessed only in synchronous or very less time access in asynchronous so we use a messaging queue for more reliability, scalability, and improving performance. 
 
 ## What are popular tools?
  Some most popular tools for messaging queues are...
- Amazon SQS
- WCF
- Mosquitto
- IBM MQ
- Kafka
- RabbitMQ
- Celery

## What is Enterprise Message  Bus?
  A Messaging Bus or Enterprise service bus implements a communication system between one or more applications. Messaging queue contains FIFO(first in first out) rule but in Messaging bus does not contain FIFO. Messaging bus is a one to many modal of distribution
