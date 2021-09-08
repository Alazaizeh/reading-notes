## AWS events
![api](https://www.stratacore.com/hs-fs/hub/282679/file-227450102-jpg/images/cloud-computing-2-1.jpg)

### AWS events
 a near real-time stream of system events that describe changes in Amazon Web Services (AWS) resources.

### Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server
service for creating, publishing, maintaining, monitoring, and securing REST, HTTP, and WebSocket APIs at any scale.
### List the AWS Database offerings and talk about the pros and cons of each

|pros|cons|
|----|----|
|Automated Backups|No scale-out for write workloads|
|Encryption at rest and in-transit|Downtime required for scaling operations|
|No hardware maintenance needed	|No automated partition management|

### What’s the difference between a FIFO and a standard queue?
Standard queues guarantee that a message is delivered at least once and duplicates can be introduced into the queue. FIFO queues ensure a message is delivered exactly once and remains available until a consumer processes and deletes it
### How can the server be assured a message was properly received?
Wait for acknowledgement from the client as a response for reciving the message.


|Term|Description|
|----|----|
|Serverless API|a cloud computing execution model where the cloud provider dynamically manages the allocation and provisioning of servers|
|Triggers|A trigger is a special type of stored procedure that automatically runs when an event occurs in the database server.|
|Dynamo vs Mongo|DynamoDB is a key-value store with added support for JSON to provide document-like data structures that better match with objects in application code, Compared to MongoDB, DynamoDB has limited support for different data types|
|Dynamoose vs Mongoose|Dynamoose is obviously inspired by mongoose and is a good choice if you have a well-defined schema and/or want to be abstracted away from the DynamoDB details.|
