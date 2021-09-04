## Event Driven Architecture
 a software architecture paradigm promoting the production, detection, consumption of, and reaction to events.
 
![api](https://hazelcast.com/wp-content/uploads/2020/02/20_EventDrivenArchitecture.png)

### What’s the difference between a FIFO and a standard queue?
Standard queues guarantee that a message is delivered at least once and duplicates can be introduced into the queue. FIFO queues ensure a message is delivered exactly once and remains available until a consumer processes and deletes it
### How can the server be assured a message was properly received?
Wait for acknowledgement from the client as a response for reciving the message.
### What classic design pattern is best represented by event driven programming?
Observer pattern.
### How do you test an event driven system?
In the most canonical case, we will write unit tests, service tests, and end-to-end tests. 
In each of these cases, out System Under Test comprises a different part of the application.

### Document the following Vocabulary Terms

|Term|Description|
|----|----|
|FIFO Queue|A FIFO queue is a queue that operates on a first-in, first-out (FIFO) principle. This means that the request is processed in the order in which it arrives.|
|Pub/Sub|publish–subscribe is a messaging pattern where senders of messages, called publishers, do not program the messages to be sent directly to specific receivers, called subscribers|

