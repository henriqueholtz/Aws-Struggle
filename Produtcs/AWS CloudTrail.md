# AWS CloudTrail

- Think account-specific activity and audit; think CloudTrail;
- Every log is a JSON (single-line);
- Allow automation / Integration with CloudWatch;
- Regional service (but you can configure to centralize at one S3 - logs gloablly)
- Active by default but the events are seized for a short time;
- AWS cloud trail logs has encryption enabled by default.
- Log every single event like:
  - API requests on AWS
  - Any change, click, action

AWS CloudTrail is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account. With CloudTrail, you can log, continuously monitor, and retain account activity related to actions across your AWS infrastructure. Think account-specific activity and audit; think CloudTrail. CloudTrail cannot be used to monitor CPU utilization for EC2 instances or send emails.

CloudTrail cannot help in identifying the right AWS services to build solutions on AWS Cloud.

You cannot use CloudTrail to track changes to each resource on AWS.

AWS CloudTrail cannot be used to centralize the server logs for Amazon Elastic Compute Cloud (Amazon EC2) instances or on-premises servers.

CloudTrail cannot detect threats to your AWS account.

AWS Config is focused on the configuration of your AWS resources and reports with detailed snapshots on how your resources have changed. Whereas AWS CloudTrail focuses on the events or API calls, that drive those changes. It focuses on the user, application, and activity performed on the system.
