# Application Integration

[Back to index](Index.md)

## Amazon Step Function

- Lets you coordinate multiple AWS services into serverless workflows;
- Cannot be used to run a process on a schedule.

<details>
<summary>Example</summary>

![image](https://camo.githubusercontent.com/85092eb69397d32f89b648dd852aaa2b622abead0306ff6eef9d99843677924c/68747470733a2f2f7765626173736574732e6d6f6e676f64622e636f6d2f5f636f6d5f6173736574732f636d732f537465705f46756e6374696f6e735f4d616e6167656d656e745f436f6e736f6c652d77796d677136743879662e706e67)

</details>

---

</br>

## Amazon EventBridge

Provide real-time access to changes in data in AWS services, your own applications, and software as a service (SaaS) applications without writing code.

Amazon EventBridge Scheduler is a serverless task scheduler that simplifies creating, executing, and managing millions of schedules across AWS services without provisioning or managing underlying infrastructure.

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
  - **Standard queues** (default);
  - **FIFO queues** (First-In-First-Out). Don't allow duplicates. Limited in 300 transactions per second;
- Queues are regional;
- If needed you can send a queue from a region to another using SNS;

---

</br>
