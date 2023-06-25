# AWS Budgets

AWS Budgets gives the ability to set custom budgets that alert you when your costs or usage exceed (or are forecasted to exceed) your budgeted amount. You can also use AWS Budgets to set reservation utilization or coverage targets and receive alerts when your utilization drops below the threshold you define. Budgets can be created at the monthly, quarterly, or yearly level, and you can customize the start and end dates. You can further refine your budget to track costs associated with multiple dimensions, such as AWS service, linked account, tag, and others. AWS Budgets cannot provide the estimate of the monthly AWS bill based on the list of AWS services.

AWS Budgets cannot provide the estimate of the monthly AWS bill based on the list of AWS services. AWS Budgets cannot provide a detailed break down of your AWS costs by the hour.

- AWS Budgets cannot be used to identify under-utilized EC2 instances without manually configuring coverage targets
- AWS Budgets cannot forecast your AWS account cost and usage.
- It cannot be used to compare the cost of running the IT infrastructure on-premises vs AWS Cloud.

#### Types of budgets:

- **Cost budget** - Helps you plan how much you want to spend on a service.
- **Usage budget** - Helps you plan how much you want to use one or more services.
- **Reservation budget** - This helps you track the usage of your Reserved Instances (RI).
  Two ways of doing it - Reserved Instance (RI) utilization budgets (This lets you see if your Reserved Instances (RI) are unused or under-utilized), Reserved Instance (RI) coverage budgets (This lets you see how much of your instance usage is covered by a reservation).
- **Savings Plans budget**.

## Exam Alert:

It is useful to note the difference between CloudWatch Billing vs AWS Budgets:

CloudWatch Billing Alarms: Sends an alarm when the actual cost exceeds a certain threshold.

AWS Budgets: Sends an alarm when the actual cost exceeds the budgeted amount or even when the cost forecast exceeds the budgeted amount.

---

## Exam Alert:

Watch out for questions on AWS Cost Explorer vs AWS Budgets. AWS Budgets can alert you when your costs exceed your budgeted amount. Cost Explorer helps you visualize and manage your AWS costs and usage over time.

---

You can define a utilization threshold and receive alerts when your Reserved Instances (RI) usage falls below that threshold. This lets you see if your Reserved Instances (RI) are unused or under-utilized. Reservation alerts are supported for Amazon EC2, Amazon RDS, Amazon Redshift, Amazon ElastiCache, and Amazon Elasticsearch reservations.

AWS Budgets Overview:

![img](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt4-q5-i1.jpg)

---

# Exam Alert:

It is useful to note the difference between Amazon CloudWatch Billing vs AWS Budgets:

Amazon CloudWatch Billing Alarms: Sends an alarm when the actual cost exceeds a certain threshold.

AWS Budgets: Sends an alarm when the actual cost exceeds the budgeted amount or even when the cost forecast exceeds the budgeted amount.

---
