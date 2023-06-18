# Amazon Elastic Container Service (Amazon ECS)

- Types: EC2 or fargate (both are managment by AWS, EC2 you can access);
- Integrates with IAM, SM, CW, ELB, CodeDeploy, CodeCommit...
- Task defition (like Dockerfile)

Amazon Elastic Container Service (Amazon ECS) is a highly scalable, fast, container management service that makes it easy to run, stop, and manage Docker containers on a cluster.

- Amazon ECS cannot handle the application deployment automatically
- This is not a fully managed service and you can manage the underlying servers yourself.

Amazon Elastic Container Service (Amazon ECS) is a highly scalable, high-performance container management service that supports Docker containers and allows you to easily run applications on a managed cluster of Amazon EC2 instances. Technically, you can access the underlying EC2 instances, but the set up is more complex than just using the EC2 service directly, so this option is ruled out.

How Amazon Elastic Container Service (Amazon ECS) Works:

![img](https://d1.awsstatic.com/diagrams/product-page-diagrams/product-page-diagram_ECS_1.86ebd8c223ec8b55aa1903c423fbe4e672f3daf7.png)

# Amazon Elastic Container Service (Amazon ECS) - Fargate launch type

AWS Fargate is a serverless compute engine for containers. It works with both Amazon Elastic Container Service (Amazon ECS) and Amazon Elastic Kubernetes Service (Amazon EKS). AWS Fargate makes it easy for you to focus on building your applications. AWS Fargate removes the need to provision and manage servers, lets you specify and pay for resources per application, and improves security through application isolation by design. AWS Fargate allocates the right amount of compute, eliminating the need to choose instances and scale cluster capacity. You only pay for the resources required to run your containers, so there is no over-provisioning and paying for additional servers. AWS Fargate runs each task or pod in its kernel providing the tasks and pods their own isolated compute environment. This enables your application to have workload isolation and improved security by design.

How AWS Fargate Works:

![img2](https://d1.awsstatic.com/re19/FargateonEKS/Product-Page-Diagram_Fargate@2x.a20fb2b15c2aebeda3a44dbbb0b10b82fb89aa6a.png)

# Amazon Elastic Container Service (Amazon ECS) - EC2 launch type

Amazon Elastic Container Service (Amazon ECS) is a highly scalable, fast, container management service that makes it easy to run, stop, and manage Docker containers and allows you to easily run applications on a managed cluster of Amazon EC2 instances. Unlike AWS Fargate, this is not a fully managed service and you need to manage the underlying servers yourself.
