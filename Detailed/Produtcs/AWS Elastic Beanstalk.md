# AWS Elastic Beanstalk

- Easily to create the resources you need for your application (ex: input in .zip)
- There is no additional charge for AWS Elastic Beanstalk - you pay only for the AWS resources needed to store and run your applications.
- Deploy options:
  - All at once;
  - Rolling / Rolling with Additional Batch;
  - Immutable;
  - Blue/Green;
- Inside a root folder `./ebextensions` you can add `.config` files (YML or JSON)

AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling web applications and services developed with Java, .NET, PHP, Node.js, Python, etc.

You can simply upload your code and Elastic Beanstalk automatically handles the deployment, from capacity provisioning, load balancing, auto-scaling to application health monitoring. At the same time, **you retain full control over the AWS resources powering your application and can access the underlying resources at any time**.

AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling web applications and services developed in a variety of programming languages. You can simply upload your code and Elastic Beanstalk automatically handles the deployment, from capacity provisioning, load balancing, auto-scaling to application health monitoring.

- You cannot use Beanstalk to distribute incoming traffic across multiple targets.
- It cannot be used to automatically deploy code to an Amazon EC2 instance.
- With AWS Elastic Beanstalk, you can quickly deploy and manage applications in the AWS Cloud without having to learn about the infrastructure that runs those applications
- There is no additional charge for AWS Elastic Beanstalk. You pay only for the underlying AWS resources that your application consumes
- Support Java, .NET, Node, Go, Docker, etc...

Key Benefits of AWS Elastic Beanstalk:

![img](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt2-q45-i1.jpg)

---

## Health Monitoring

- The AWS Elastic Beanstalk health monitoring can determine that the environment's Auto Scaling group is available and has a minimum of at least one instance
- With basic health reporting, the AWS Elastic Beanstalk service does not publish any metrics to Amazon CloudWatch
