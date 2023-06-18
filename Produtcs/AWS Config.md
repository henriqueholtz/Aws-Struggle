# AWS Config

Think resource-specific history, audit, and compliance; think Config.

Its a configuration tracking service and not an infrastructure tracking service.

- Region service;
- Config history (helps on troubleshouting);
- Resources inventory;
- Allow to proceed SQL queries (ex: count and order EC2's);
- Config use events from CloudTrail;

AWS Config is a service that enables you to assess, audit, and evaluate the configurations of your AWS resources. Config continuously monitors and records your AWS resource configurations and allows you to automate the evaluation of recorded configurations against desired configurations.

With AWS Config, you can do the following:

1. Evaluate your AWS resource configurations for desired settings.
2. Get a snapshot of the current configurations of the supported resources that are associated with your AWS account.
3. Retrieve configurations of one or more resources that exist in your account.
4. Retrieve historical configurations of one or more resources.
5. Receive a notification whenever a resource is created, modified, or deleted.
6. View relationships between resources. For example, you might want to find all resources that use a particular security group.

AWS Config provides a detailed view of the configuration of AWS resources in your AWS account. This includes how the resources are related to one another and how they were configured in the past so that you can see how the configurations and relationships change over time. AWS Config is designed to help you oversee your application resources in the following scenarios: Resource Administration, Auditing and Compliance, Managing and Troubleshooting Configuration Changes, Security Analysis.

AWS Config is focused on the configuration of your AWS resources and reports with detailed snapshots on how your resources have changed. Whereas AWS CloudTrail focuses on the events or API calls, that drive those changes. It focuses on the user, application, and activity performed on the system.

How AWS Config Works:

![img](https://d1.awsstatic.com/Products/product-name/diagrams/product-page-diagram-Config_how-it-works.bd28728a9066c55d7ee69c0a655109001462e25b.png)
