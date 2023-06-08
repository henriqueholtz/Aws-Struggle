# AWS Share Responsability Model

Security and Compliance is a shared responsibility between AWS and the customer. This shared model can help relieve the customer’s operational burden as AWS operates, manages and controls the components from the host operating system and virtualization layer down to the physical security of the facilities in which the service operates.

Database encryption - Under the AWS Shared Responsibility Model, customers are responsible for managing their data, including data encryption.

AWS Shared Responsibility Model Overview:

![img](https://d1.awsstatic.com/security-center/Shared_Responsibility_Model_V2.59d1eccec334b366627e9295b304202faf7b899b.jpg)

Customers that deploy an Amazon EC2 instance are responsible for the management of the guest operating system (including updates and security patches), any application software or utilities installed by the customer on the instances, and the configuration of the AWS-provided firewall (called a security group) on each instance.

# Customer

- Maintain versions of an AWS Lambda function
- Operating system patches and updates of an Amazon Elastic Compute Cloud (Amazon EC2) instance
- Enabling data encryption of data stored in Amazon Simple Storage Service (Amazon S3) buckets

# AWS

- AWS Global Network Security
- Ensuring AWS employees cannot access customer data
- Compliance validation of Cloud infrastructure
