# Amazon CloudWatch

- The best to monitor metrics;
- Monitor instance sensitive informations only if install the agent (ex: memory);
- Monitor performance (CPU usage; memory only with agent because is a sensitive information);
- Install agent or script to CloudWatch monitor your EC2 instance like memory information, disk usage etc;
- Each 5 minutes by default. You can set to 1 minute for example;
- Allow to create alarms to send notifications;

Amazon CloudWatch is a monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), and IT managers. CloudWatch provides data and actionable insights to monitor applications, respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health. This is an excellent service for building Resilient systems.

- Think resource performance monitoring, events, and alerts; think CloudWatch

CloudWatch cannot be used to protect from web exploits such as SQL injection and cross-site scripting.

You can create an CloudWatch alarm that sends an email message using Amazon SNS when the alarm changes state from OK to ALARM. The alarm changes to the ALARM state when the average CPU use of an EC2 instance exceeds a specified threshold for consecutive specified periods.

CloudWatch does not offer any recommendations vis-a-vis AWS best practices for cost optimization, security, and performance improvement.

CloudWatch cannot help in identifying the right AWS services to build solutions on AWS Cloud.

It cannot provide the status of your AWS resources.

Amazon CloudWatch cannot be used to block users from certain geographies.

Amazon CloudWatch cannot be used to identify under-utilized Amazon EC2 instances without manually configuring an alarm with the appropriate threshold to track the Amazon EC2 utilization.

Amazon CloudWatch cannot detect threats to your AWS account.

You can monitor your estimated AWS charges by using Amazon CloudWatch. **Billing metric data is stored in the US East (N. Virginia)** Region and represents worldwide charges. This data includes the estimated charges for every service in AWS that you use, in addition to the estimated overall total of your AWS charges

With CloudWatch Events, you can establish rules that trigger programmatic actions in response to a change in volume, snapshot, or encryption key state (though not for underutilized volume usage).

## Exam Alert:

It is useful to note the difference between CloudWatch Billing vs AWS Budgets:

CloudWatch Billing Alarms: Sends an alarm when the actual cost exceeds a certain threshold.

AWS Budgets: Sends an alarm when the actual cost exceeds the budgeted amount or even when the cost forecast exceeds the budgeted amount.

---

Amazon CloudWatch can be used to create an alarm to monitor your estimated charges. When you enable the monitoring of estimated charges for your AWS account, the estimated charges are calculated and sent several times daily to CloudWatch as metric data. You can choose to receive alerts by email when charges have exceeded a certain threshold. These alerts are triggered by Amazon CloudWatch and messages are sent using Amazon Simple Notification Service (Amazon SNS). Billing metric data is stored in the US East (N. Virginia) Region and reflects worldwide charges.

The alarm triggers when your account billing exceeds the threshold you specify. **It triggers only when actual billing exceeds the threshold. It doesn't use projections based on your usage so far in the month.**

Amazon CloudWatch Billing Alarms Overview:

![img](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt4-q21-i1.jpg)

# Exam Alert:

It is useful to note the difference between Amazon CloudWatch Billing vs AWS Budgets:

Amazon CloudWatch Billing Alarms: Sends an alarm when the actual cost exceeds a certain threshold.

AWS Budgets: Sends an alarm when the actual cost exceeds the budgeted amount or even when the cost forecast exceeds the budgeted amount.

---
