# Application Integration

[Back to index](Index.md)

## Amazon Step Function

Lets you coordinate multiple AWS services into serverless workflows;

---

</br>

## Amazon MQ

Like RabbitMQ but it's managed by AWS;

---

</br>

## Amazon Simple Notification Service (SNS)

To pub/sub messaging service. your publisher systems can fan-out messages to a large number of subscriber endpoints for parallel processing, including Amazon SQS queues, AWS Lambda functions, and HTTP/S webhooks.

SNS can be used to fan out notifications to end users using mobile push, SMS, and email.

---

</br>

## Amazon Simple Queue Service (SQS)

Message queuing service.

- SQS offers two types of message queues:
  - **Standard queues**;
  - **FIFO queues**;
- Queues are regional;
- If needed you can send a queue from a region to another using SNS;

---

</br>
