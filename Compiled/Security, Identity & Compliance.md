# Security, Identity & Compliance

[Back to index](Index.md)

## Amazon Cognito

Identity and access management;

---

</br>

## Amazon Detective

Amazon Detective can analyze trillions of events from multiple data sources such as Virtual Private Cloud (VPC) Flow Logs, AWS CloudTrail, and Amazon GuardDuty, and automatically creates a unified, interactive view of your resources, users, and the interactions between them over time.

---

</br>

## Amazon GuardDuty

Is a threat detection service that continuously monitors for malicious activity and unauthorized behavior to protect your AWS accounts, workloads, and data stored in S3;

Analyze events from CloudTrail, VPC Flow Logs and DNS Logs.

---

</br>

## Amazon Inspector

Monitor the security of EC2 instances (installing an agent)

---

</br>

## AWS WAF

- AWS Web Application Firewall protect against DDoS attacks, SQL Injection, cross-site scripting, etc (layer 7);
- You can block users from certain geographies from accessing your content using WAF.

---

</br>

## AWS Shield Standard

Managed Distributed Denial of Service (DDoS) protection service that safeguards applications running on AWS (layers 3 and 4) and it's activated to all customer by default;

---

</br>

## AWS Shield Advanced

Optional and payed (layers 3, 4 and 7) to protect EC2, ELB, CloudFront, Route 53 and AWS Global Acelerator;

---

</br>

## AWS Cloud HSM / AWS CloudHSM

Cloud-based **hardware** security module (HSM) that enables you to easily generate and use your **encryption** keys on the AWS Cloud;

---

</br>

## Amazon Macie

Find sensitive data;

---

</br>

## AWS Artifact

AWS Artifact is your go-to, central resource for compliance-related information that matters to your organization;
Note: It's different that AWS CodeArtifact

---

</br>

## AWS Security Token Service (AWS STS)

Temporary credentials

---

</br>

## AWS Directory Service

---

</br>

## AWS Directory Service for Microsoft Active Directory (AWS Managed Microsoft AD)

---

</br>

## AWS Key Management Service (AWS KMS)

- Customer managed key (CMK)

- AWS managed key

- AWS owned key

---

</br>

## AWS Secrets Manager

---

</br>

## AWS Security Hub

---

</br>

## AWS Trusted Advisor

- Can analyze your infra and identify unattached or underutilized EBS Volumes.

---

</br>

## Access Key ID

---

</br>

## AWS Firewall Manager

---

</br>

## AWS Identity and Access Management (IAM)

---

</br>

## AWS Identity and Access Management (IAM) access advisor

---

</br>

## AWS IAM Identity Center (Successor to AWS Single Sign-On)

---

</br>

## AWS Security Token Service (AWS STS)

---

</br>

## AWS Systems Manager Session Manager

---

</br>

## Credentials Report

---

</br>

## Distributed Denial of Service (DDoS)

<details>
<summary>AWS Shield</summary></br>
AWS Shield is a managed Distributed Denial of Service (DDoS) protection service that safeguards applications running on AWS. AWS Shield provides always-on detection and automatic inline mitigations that minimize application downtime and latency, so there is no need to engage AWS Support to benefit from DDoS protection.

Ex: Route 53, AWS Global Acelerator, EC2, ELB, CloudFront;

</details>

<details>
<summary>AWS Web Application Firewall (AWS WAF)</summary></br>
By using AWS Web Application Firewall (AWS WAF), you can configure web access control lists (Web ACLs) on your Amazon CloudFront distributions or Application Load Balancers to filter and block requests based on request signatures. Besides, by using the AWS Web Application Firewall (AWS WAF) rate-based rules, you can automatically block the IP addresses of bad actors when requests matching a rule exceed a threshold that you define.
</details>

<details>
<summary>Amazon CloudFront with Amazon Route 53</summary></br>
AWS hosts Amazon CloudFront and Amazon Route 53 services on a distributed network of proxy servers in data centers throughout the world called edge locations. Using the global Amazon network of edge locations for application delivery and DNS service plays an important part in building a comprehensive defense against DDoS attacks for your dynamic web applications.
</details>

---

</br>

## Multi-Factor Authentication (MFA)

<details>
<summary>Virtual Multi-Factor Authentication (MFA)</summary></br>
A software app that runs on a phone or other device and emulates a physical device. The device generates a six-digit numeric code based upon a time-synchronized one-time password algorithm. The user must type a valid code from the device on a second webpage during sign-in. Each virtual Multi-Factor Authentication (MFA) device assigned to a user must be unique. A user cannot type a code from another user's virtual Multi-Factor Authentication (MFA) device to authenticate.

Google Authenticator is an example of a Virtual Multi-Factor Authentication (MFA) device.

</details>

<details>
<summary>U2F security key</summary></br>
A device that you plug into a USB port on your computer. U2F is an open authentication standard hosted by the FIDO Alliance. When you enable a U2F security key, you sign in by entering your credentials and then tapping the device instead of manually entering a code.
</details>

---

</br>

## Root User

<details>
<summary>Details</summary></br>
The Email address and the password used for signing up for AWS services are the AWS root user account credentials. Root user account, therefore, has full permissions on all AWS resources under that account. Restricting root user account access is not possible. As a best practice, Multi-Factor Authentication (MFA) should be set on the root user account. The root user account password can be changed after account creation. For all employees performing various administrative jobs, create individual user accounts using AWS IAM, and give administrative permissions as needed.

AWS Root User Account Security Best Practices:

![img1](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt2-q54-i2.jpg)

![img2](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt2-q54-i1.jpg)

---

To send alerts whenever the AWS account root user signs in, you can create an Amazon Simple Notification Service (Amazon SNS) topic. Then, create an Amazon CloudWatch event rule to monitor userIdentity root logins from the AWS Management Console and send an email via Amazon SNS when the event triggers.

</details>

---

</br>
