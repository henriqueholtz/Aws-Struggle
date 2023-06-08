# Amazon GuardDuty

Account watchman

Amazon GuardDuty is a threat detection service that monitors malicious activity and unauthorized behavior to protect your AWS account. GuardDuty analyzes billions of events across your AWS accounts from AWS CloudTrail (AWS user and API activity in your accounts), Amazon VPC Flow Logs (network traffic data), and DNS Logs (name query patterns). This service is for AWS account level access, not for instance-level management like an EC2. GuardDuty cannot be used to check OS vulnerabilities.

Amazon GuardDuty cannot be used to protect from web exploits such as SQL injection and cross-site scripting.

Security findings are retained and made available through the Amazon GuardDuty console and APIs for 90-days. After 90-days, the findings are discarded. To retain findings for longer than 90-days, you can enable AWS CloudWatch Events to automatically push findings to an Amazon S3 bucket in your account or another data store for long-term retention.

How Amazon GuardDuty Works:

![img](https://d1.awsstatic.com/Products/product-name/diagrams/product-page-diagram-Amazon-GuardDuty_how-it-works.4370200b49eddc34d3a55c52c584484ceb2d532b.png)
