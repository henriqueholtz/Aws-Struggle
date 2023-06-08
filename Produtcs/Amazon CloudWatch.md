# Amazon CloudWatch

Amazon CloudWatch is a monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), and IT managers. CloudWatch provides data and actionable insights to monitor applications, respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health. This is an excellent service for building Resilient systems.

Think resource performance monitoring, events, and alerts; think CloudWatch

CloudWatch cannot be used to protect from web exploits such as SQL injection and cross-site scripting.

You can create an CloudWatch alarm that sends an email message using Amazon SNS when the alarm changes state from OK to ALARM. The alarm changes to the ALARM state when the average CPU use of an EC2 instance exceeds a specified threshold for consecutive specified periods.

CloudWatch does not offer any recommendations vis-a-vis AWS best practices for cost optimization, security, and performance improvement.

CloudWatch cannot help in identifying the right AWS services to build solutions on AWS Cloud.

It cannot provide the status of your AWS resources.

Amazon CloudWatch cannot be used to block users from certain geographies.

Amazon CloudWatch cannot be used to identify under-utilized Amazon EC2 instances without manually configuring an alarm with the appropriate threshold to track the Amazon EC2 utilization.

Amazon CloudWatch cannot detect threats to your AWS account.

You can monitor your estimated AWS charges by using Amazon CloudWatch. **Billing metric data is stored in the US East (N. Virginia)** Region and represents worldwide charges. This data includes the estimated charges for every service in AWS that you use, in addition to the estimated overall total of your AWS charges

Exam Alert:

It is useful to note the difference between CloudWatch Billing vs AWS Budgets:

CloudWatch Billing Alarms: Sends an alarm when the actual cost exceeds a certain threshold.

AWS Budgets: Sends an alarm when the actual cost exceeds the budgeted amount or even when the cost forecast exceeds the budgeted amount.
