# Management & Governance

[Back to index](Index.md)

## CloudWatch

Think resource performance monitoring, events, and alerts; think CloudWatch;

- AWS monitoring service **for applications**;
- The best to monitor metrics;
- Monitor instance sensitive informations only if install the agent (ex: memory);
- Monitor performance (CPU usage; memory only with agent because is a sensitive information);
- Install agent or script to CloudWatch monitor your EC2 instance like memory information, disk usage etc;
- Each 5 minutes by default. You can set to 1 minute for example;
- Allow to create alarms to send notifications;
- Billing metric data is stored in the US East (N. Virginia)
- Offers features to:
  - **Collect** (application logs, AWS Service Logs)
  - **Monitor** (metric graphs like CPU, memory... Alarms and traces)
  - **Analyze** (Insights: SQL queries)
- CloudWatch Events rule that triggers on a schedule via a cron expression;

---

</br>

## Amazon CloudWatch Logs

You can use Amazon CloudWatch Logs to monitor, store, and access your log files from (Amazon EC2) instances, AWS CloudTrail, Route 53, and other sources such as on-premises servers.

Amazon CloudWatch Logs enables you to centralize the logs from all of your systems, applications, and AWS services that you use, in a single, highly scalable service. You can then easily view them, search them for specific error codes or patterns, filter them based on specific fields, or archive them securely for future analysis

---

</br>

## Amazon CloudWatch Billing

- Sends an alarm when the actual cost exceeds a certain threshold.

---

</br>

## AWS Config

Think resource-specific history, audit, and compliance: think Config. It uses events from CloudTrail

---

</br>

## AWS CloudFormation

- Infrastructure as code (like Terraform);
- You can provision across multiple accounts and regions;

---

</br>

## AWS Control Tower

is an AWS native service providing a pre-defined set of blueprints and guardrails to help customers implement a landing zone for new AWS accounts;

---

</br>

## AWS Service Catalog

Allows organizations to create and manage catalogs of IT services that are approved for use on AWS;

---

</br>

## AWS CloudTrail

- Think account-specific activity and audit; think CloudTrail;
- Every log is a JSON (single-line);
- Allow automation / Integration with CloudWatch;
- Regional service (but you can configure to centralize at one S3 - logs globally)
- Active by default but the events are seized for a short time;
- AWS cloud trail logs has encryption enabled by default.
- Log every single event like:
  - API requests on AWS
  - Any change, click, action
- CloudTrail cannot help in identifying the right AWS services to build solutions on AWS Cloud.
- You cannot use CloudTrail to track changes to each resource on AWS.
- Billing alarms cannot be triggered via AWS CloudTrail.
- Event types: (All event types use the same CloudTrail JSON log format)
  - **Management events** (logged by default)
  - **Data events** (optional with additional fee)
  - **Insights events** (optional with additional fee)

---

</br>

## AWS CloudTrail Insights

Helps AWS users identify and respond to unusual activity associated with write API calls by continuously analyzing CloudTrail management events.

---

</br>

## AWS CloudTrail Logs

- Encription enabled by default;

---

</br>

## AWS Compute Optimizer

Helps you identify the optimal AWS resource configurations, such as Amazon EC2 instance types, EC2 auto scaling groups, Amazon EBS volume configurations, and AWS Lambda function memory sizes, using machine learning to analyze historical utilization metrics

- EBS, Lambda, EC2, and EC2 Auto Scaling Groups

---

</br>

## AWS Organizations

- Volume discounts for Amazon EC2 and Amazon S3 aggregated across the member AWS accounts
- Share the reserved Amazon EC2 instances amongst the member AWS accounts
- Billing alarms cannot, however, be triggered using Consolidated Billing.
- Consolidated billing between EC2 RI (reserved instances) if they are in the same AZ.

---

</br>

## AWS Systems Manager

Gives you visibility and control of your infrastructure on AWS. Allows you to automate operational tasks such as collecting software inventory, running commands, managing patches, and configuring servers across AWS Cloud as well as on-premises infrastructure.

---

</br>
