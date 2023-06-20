# AWS CloudFormation

AWS CloudFormation allows you to use programming languages or a simple text file to model and provision, in an automated and secure manner, all the resources needed for your applications across all Regions and accounts. Think infrastructure as code; think CloudFormation. CloudFormation cannot be used to debug performance issues for this serverless application built using a microservices architecture.

- Think infrastructure as code; think CloudFormation.
- Templates JSON or YML;
- CloudFormation Stack sets with AWS Organizations to run in multiple accounts;

This is very different from Beanstalk where you just upload your application code and Beanstalk automatically figures out what resources are required to deploy that application. In AWS CloudFormation, you have to explicitly specify which resources you want to provision.

- It cannot be used to automate code deployment.
- It cannot be used to automatically deploy code to an Amazon EC2 instance.
- You cannot use AWS CloudFormation for running commands or managing patches on servers.

AWS CloudFormation allows you to use programming languages or a simple text file to model and provision, in an automated and secure manner, all the resources needed for your applications across all Regions and accounts. A stack is a collection of AWS resources that you can manage as a single unit. In other words, you can create, update, or delete a collection of resources by creating, updating, or deleting stacks.

**AWS CloudFormation StackSets** extends the functionality of stacks by enabling you to create, update, or delete stacks **across multiple accounts and regions** with a single operation. Using an administrator account, you define and manage an AWS CloudFormation template, and use the template as the basis for provisioning stacks into selected target accounts across specified regions.

How CloudFormation Works:

![img](https://d1.awsstatic.com/Products/product-name/diagrams/product-page-diagram_CloudFormation.ad3a4c93b4fdd3366da3da0de4fb084d89a5d761.png)
