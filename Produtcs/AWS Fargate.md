# AWS Fargate

AWS Fargate is a serverless compute engine for containers. It works with both Amazon Elastic Container Service (Amazon ECS) and Amazon Elastic Kubernetes Service (Amazon EKS). AWS Fargate makes it easy for you to focus on building your applications. AWS Fargate removes the need to provision and manage servers, lets you specify and pay for resources per application, and improves security through application isolation by design.

AWS Fargate is a purpose-built serverless compute engine for containers. Fargate scales and manages the infrastructure required to run your containers.

- You do not have access to the underlying servers;
- You can run in "Fargate Spot Pricing for Amazon ECS" (until 70% of discount)
- You can run in "Compute Savings Plan for Amazon ECS & Amazon EKS" (until 50% of discount)

## Pricing

- Pay by vCPU/h
- Pay by GB/h

- Linux:
  - Pay at least 1 minute;
  - Pay by second
- Windows
  - Pay at least 15 minutes;

How AWS Fargate Works:

![img](https://d1.awsstatic.com/re19/FargateonEKS/Product-Page-Diagram_Fargate@2x.a20fb2b15c2aebeda3a44dbbb0b10b82fb89aa6a.png)
