# Aws Batch

Batch processing, ML model training, and analysis at any scale

AWS Batch is a fully managed batch computing service that plans, schedules, and runs your containerized batch or ML workloads across the full range of AWS compute offerings, such as Amazon ECS, Amazon EKS, AWS Fargate, and Spot or On-Demand Instances.

You can use AWS Batch to plan, schedule and execute your batch computing workloads across the full range of AWS compute services. AWS Batch dynamically provisions the optimal quantity and type of compute resources (e.g., CPU or memory optimized instances) based on the volume and specific resource requirements of the batch jobs submitted. AWS Batch provisions compute resources and optimizes the job distribution based on the volume and resource requirements of the submitted batch jobs.

Please review the common use-cases for AWS Batch:

![img](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt2-q64-i1.jpg)

Exam Alert:

Understand the difference between AWS Step Functions and AWS Batch. You may get questions to choose one over the other. AWS Batch runs batch computing workloads by provisioning the compute resources. AWS Step Functions does not provision any resources. AWS Step Functions only orchestrates AWS services required for a given workflow. You cannot use AWS Step Functions to plan, schedule and execute your batch computing workloads by provisioning underlying resources.
