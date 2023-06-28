# Amazon Simple Queue Service (SQS)

Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications. Using SQS, you can send, store, and receive messages between software components at any volume, without losing messages or requiring other services to be available.

- SQS offers two types of message queues - Standard queues vs FIFO queues.
- SQS cannot be used to monitor CPU utilization for EC2 instances or send emails.
- Queue is regional;
- If needed you can send a queue from a region to another using SNS;

Amazon Simple Queue Service (Amazon SQS) offers a reliable, highly scalable hosted queue for storing messages as they travel between computers. Amazon SQS lets you easily move data between distributed application components and helps you build applications in which messages are processed independently (with message-level ack/fail semantics), such as automated workflows.

Although Amazon SQS can be triggered from an Amazon S3 event, but Amazon SQS cannot execute code as its a message queuing service.

Using Amazon Simple Queue Service (Amazon SQS), you can send, store, and receive messages between software components at any volume, without losing messages or requiring other services to be available.
