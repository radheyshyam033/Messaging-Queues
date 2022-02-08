# Messaging Queue
## What is a Messaging Queues?

  A messaging queue is a asynchronous processing to communicate by sending messages to each other using a queue. All the processes do not need to access the shared memory but very few processes only need it, so it would be better to implement with message queues because messaging queue provide temporary storage and share memory data need to be protected when synchronous processing with multiple processes communicating at the same time.
  
  ![Messaging Queue](https://www.tutorialspoint.com/inter_process_communication/images/message_queue.jpg)
  
  A message queue provides a lightweight buffer that temporarily stores messages, during communication between sender and receiver. Messaging Queue order is FIFO means first in first out, means when the first messages are inserted in queue is display first to the receiver side.
  
  
  
 ## Why they are used?
  If we use shared memory instead of the messaging queue then share memory is accessed only in synchronous or very less time access in asynchronous so we use a messaging queue for more reliability, scalability, and improving performance.
  - **Improve Web Application Page Load Times :**
  Messaging Queue is a lightweight code application so it loaded on web applications easily so messaging queues also improve web application page load time.
  - **Batching for Efficiency :**
  Branching plays a very important role in the messaging queue is that if we want to add many records at a particular time then it insert one by one and it takes more time so branching help to upload task on various branches.
  - **Asynchronous Messaging :**
  Queue play an important role in the messaging queue because if messages are sent by the sender then that message is stored in the queue and the receiver easily receive the message after some delay in time.
 - **Traffic :**
 By Messaging queue we easily handle traffic, if traffic is increased on your application then we have no way to know what are client sends us so we use the queue to store the client data and process eventually, which means takes a longer time to evaluate due to more traffic.
 
 - **Break Large Task into Many Small Task :**
 The use of Queue helps break large tasks into many small tasks to easily handle 
 - **Monitoring :**
 Messaging queue system monitor how many items are in a queue and also processes the rate of messages and other status show. This can be very helpful from an application monitoring standpoint to keep an eye on how data is flowing through your system and if it is getting backed up or not. 
 
 
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
  A Messaging Bus or Enterprise service bus implements a communication system between one or more applications. Messaging  Queue creates the message bus. Clients (i.e. nodes) can then listen to the message bus. 
  
  ![Message Bus](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSO3FfKT2krqjDmVkcFhZmqhNIWQy-R4lzHFw&usqp=CAU)
  
  This is particularly true for the case where you have a message queue broadcasting messages through UDP, in other words, it is sending messages to a broadcast/multicast address without knowing or caring who is going to be getting them.  Messaging queue contains FIFO(first in first out) rule but in Messaging bus does not contain FIFO. Messaging bus is a one to many modal of distribution
message bus messages are transfer from one to many receivers 

## Reference Links

- [aws.amazon.com](https://aws.amazon.com/message-queue/)
- [www.tutorialspoint.com](https://www.tutorialspoint.com/inter_process_communication/inter_process_communication_message_queues.htm)
- [stackify.com](https://stackify.com/message-queues-12-reasons/)
