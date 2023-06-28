# AWS Global Accelerator

AWS Global Accelerator is a service that improves the availability and performance of your applications with local or global users. It provides static IP addresses that act as a fixed entry point to your application endpoints in a single or multiple AWS Regions, such as your Application Load Balancers, Network Load Balancers, or Amazon EC2 instances. AWS Global Accelerator uses the AWS global network to optimize the path from your users to your applications, improving the performance of your traffic by as much as 60%.

AWS Global Accelerator improves performance for a wide range of applications over TCP or UDP by proxying packets at the edge to applications running in one or more AWS Regions. AWS Global Accelerator is a good fit for non-HTTP use cases, such as gaming (UDP), IoT (MQTT), or Voice over IP, as well as for HTTP use cases that specifically require static IP addresses or deterministic, fast regional failover.

AWS Global Accelerator is a networking service that helps you improve the availability and performance of the applications that you offer to your global users.

How AWS Global Accelerator Works:

![img](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt2-q56-i1.jpg)

Exam Alert:

Please review the differences between Amazon CloudFront and AWS Global Accelerator:

![imgdifference](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt2-q56-i2.jpg)

## Responses

- **AWS Global Accelerator is a good fit for non-HTTP use cases:**

  AWS Global Accelerator is a good fit for non-HTTP use cases, such as gaming (UDP), IoT (MQTT), or Voice over IP, as well as for HTTP use cases that specifically require static IP addresses or deterministic, fast regional failover.

- **AWS Global Accelerator provides static IP addresses that act as a fixed entry point to your applications:**

  It provides static IP addresses that provide a fixed entry point to your applications and eliminate the complexity of managing specific IP addresses for different AWS Regions and Availability Zones (AZs).

- **AWS Global Accelerator and Amazon CloudFront use the same edge locations.**
- **AWS Global Accelerator can be configured with an Elastic Load Balancer (ELB):**

  A regional ELB load balancer is an ideal target for AWS Global Accelerator. AWS Global Accelerator complements ELB by extending these capabilities beyond a single AWS Region, allowing you to provide a global interface for your applications in any number of Regions.

- **AWS Global Accelerator cannot be used to host static websites:** Amazon S3 can host static websites.
