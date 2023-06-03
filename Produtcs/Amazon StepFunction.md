# Amazon StepFunction

AWS Step Function lets you coordinate multiple AWS services into serverless workflows. You can design and run workflows that stitch together services such as AWS Lambda, AWS Glue and Amazon SageMaker.

Step Function cannot be used to run a process on a schedule.

AWS Step Functions Overview:

![img](https://d1.awsstatic.com/product-marketing/Step%20Functions/sfn_how-it-works.f795601e8338db32506b9abb01e71704f483fc81.png)

Exam Alert:

Understand the difference between AWS Step Functions and AWS Batch. You may get questions to choose one over the other. AWS Batch runs batch computing workloads by provisioning the compute resources. AWS Step Functions does not provision any resources. AWS Step Functions only orchestrates AWS services required for a given workflow. You cannot use AWS Step Functions to plan, schedule and execute your batch computing workloads by provisioning underlying resources.
