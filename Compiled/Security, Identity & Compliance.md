# Security, Identity & Compliance

[Back to index](Index.md)

## Amazon Cognito

Identity and access management;

---

</br>

## Amazon Detective

Amazon Detective can analyze trillions of events from multiple data sources such as Virtual Private Cloud (VPC) Flow Logs, AWS CloudTrail, and Amazon GuardDuty findings, and automatically creates a unified, interactive view of your resources, users, and the interactions between them over time.

---

</br>

## Amazon GuardDuty

Is a threat detection service that continuously monitors for malicious activity and unauthorized behavior to **protect your AWS accounts, workloads, and data stored in S3**;

Analyze events from CloudTrail, VPC Flow Logs and DNS Logs.

---

</br>

## Amazon Inspector

Monitor the security and performance of EC2 instances (installing an agent)

---

</br>

## AWS WAF

Monitor HTTP(S) requests foward to CloudFront, Amazon API gateway API or LoadBalancer;

- Works on Layer 7 (application);
- Works agains DDoS attacks, SQL injection and cross-site scripting;
- You can also use rate-based rules to mitigate the Web layer DDoS attack.
- WAF cannot be used to improve the performance of a static website.
- AWS WAF can block all requests except the ones that you allow
- AWS WAF has to be enabled by the customer and comes under the customer's responsibility.
- Can be deployed with:
  - Amazon CloudFront
  - Application Load Balancer
  - Amazon API Gateway
  - AWS AppSync
- You can block users from certain geographies from accessing your content using WAF.
- Can be used to protect on-premises resources if they are deployed behind an Application Load Balancer (ALB).

---

</br>

## AWS Shield Standard

Managed Distributed Denial of Service (DDoS) protection service that safeguards applications running on AWS (layers 3 and 4) and it's activated to all customers by default;

- CloudFront & Route 53;
- Needs WebACL configurated (it's configurated in CloudFront);

---

</br>

## AWS Shield Advanced

Optional and payed (layers 3 and 4, and using WAF layer 7) to protect EC2, ELB, CloudFront, Route 53 and AWS Global Acelerator, Elastic IPs;

- Financial protection (if the infra scales cause an DDoS, the Sield Advanced can give back the additional costs);

---

</br>

## AWS Cloud HSM (CloudHSM)

Cloud-based **hardware** security module (HSM) that enables you to easily generate and use your **encryption** keys on the AWS Cloud;

---

</br>

## Amazon Macie

Find sensitive data;

---

</br>

## AWS Artifact

AWS Artifact is your go-to, central resource for compliance-related information that matters to your organization;
Note: It's different that AWS CodeArtifact.

---

</br>

## AWS Certificate Manager

- Free.

---

</br>

## AWS Security Token Service (AWS STS)

Temporary credentials

---

</br>

## AWS Directory Service for Microsoft Active Directory (AWS Managed Microsoft AD)

It enables your directory-aware workloads and AWS resources to use managed Active Directory in the AWS Cloud. It is not used to deploy resources.

---

</br>

## AWS Key Management Service (AWS KMS)

- Customer managed key (CMK)

- AWS managed key

- AWS owned key

<details>
<summary>Details</summary></br>

AWS Key Management Service (KMS) makes it easy for you to create and manage cryptographic keys and control their use across a wide range of AWS services and in your applications. AWS KMS is a secure and resilient service that uses hardware security modules that have been validated under FIPS 140-2, or are in the process of being validated, to protect your keys.

The Security pillar includes the ability to protect information, systems, and assets while delivering business value through risk assessments and mitigation strategies.

Encrypting data is part of the design principle "Protect data in transit and at rest": Classify your data into sensitivity levels and use mechanisms, such as encryption, tokenization, and access control where appropriate.

AWS Key Management Service (AWS KMS) makes it easy for you to create and control keys used for encryption. It is a key service of the Security pillar.

---

- Least effort way to encrypt data for AWS services: Use AWS managed master keys that are automatically created in your account for each service

AWS KMS keys (KMS keys) are the primary resource in AWS KMS. You can use a KMS key to encrypt, decrypt, and re-encrypt data. It can also generate data keys that you can use outside of AWS KMS. AWS KMS is replacing the term customer master key (CMK) with AWS KMS key and KMS key.

AWS managed CMKs are CMKs in your account that are created, managed, and used on your behalf by an AWS service that is integrated with AWS KMS. Some AWS services support only an AWS managed CMK. Others use an AWS owned CMK or offer you a choice of CMKs. AWS managed CMK can be used only for your AWS account.

You can view the AWS managed CMKs in your account, view their key policies, and audit their use in AWS CloudTrail logs. However, you cannot manage these CMKs, rotate them, or change their key policies. And, you cannot use AWS managed CMKs in cryptographic operations directly; the service that creates them uses them on your behalf.

AWS managed CMKs appear on the AWS managed keys page of the AWS Management Console for AWS KMS. You can also identify most AWS managed CMKs by their aliases, which have the format aws/service-name, such as aws/redshift.

You do not pay a monthly fee for AWS managed CMKs. They can be subject to fees for use in excess of the free tier, but some AWS services cover these costs for you.

You do not need to create or manage the AWS owned CMKs. However, you cannot view, use, track, or audit them. You are not charged a monthly fee or usage fee for AWS owned CMKs and they do not count against the AWS KMS quotas for your account.

</details>

---

</br>

## AWS Secrets Manager

<details>
<summary>Details</summary></br>
Helps to protect secrets to applications, services and IT resources. Helps to rotate, manage and retrieve DB credentials, API keys and others

AWS Secrets Manager helps you protect secrets needed to access your applications, services, and IT resources. The service enables you to easily rotate, manage, and retrieve database credentials, API keys, and other secrets throughout their lifecycle. Users and applications retrieve secrets with a call to AWS Secrets Manager APIs, eliminating the need to hardcode sensitive information in plain text.

- It is integrated with AWS CloudHSM to generate, use, and manage encryption keys.
- It cannot notify configuration changes.

</details>

---

</br>

## AWS Security Hub

It gives you a comprehensive view of your security alerts and security posture across your AWS accounts. There is a range of powerful security tools at your disposal, from firewalls and endpoint protection to vulnerability and compliance scanners. With Security Hub, you have a single place that aggregates, organizes, and prioritizes your security alerts, or findings, from multiple AWS services, such as Amazon GuardDuty, Amazon Inspector, and Amazon Macie, as well as from AWS Partner solutions.

---

</br>

## AWS Trusted Advisor

<details>
<summary>Details</summary></br>

- Suggestions about your account (real time);
- Varies with support plans
- Can analyze your infra and identify unattached or underutilized EBS Volumes.

AWS Trusted Advisor is an online tool that provides you real-time guidance to help you provision your resources following AWS best practices on cost optimization, security, fault tolerance, service limits and performance improvement. Whether establishing new workflows, developing applications, or as part of ongoing improvement, recommendations provided by Trusted Advisor regularly help keep your solutions provisioned optimally.

- Trusted Advisor cannot be used to debug performance issues for this serverless application built using a microservices architecture.
- Trusted Advisor cannot be used to prevent Distributed Denial-of-Service (DDoS) attack.
- Trusted Advisor does not describe prohibited uses of the web services offered by Amazon Web Services.
- You cannot use this service to create data-driven business cases for transitioning your business from on-premises to AWS Cloud.
- AWS Trusted Advisor can check Amazon Elastic Block Store (Amazon EBS) volume configurations and warns when volumes appear to be underused.
- It is not used to get operational insights of AWS resources
- Can recommend best practice recommendations for performance, service limits and cost optimization;
- It cannot notify configuration changes.

Advisor analyzes your AWS environment and provides best practice recommendations in five categories:

- Cost Optimization
- Performance
- Security
- Fault Tolerance
- Service Limits.

AWS Trusted Advisor checks the Amazon Elastic Compute Cloud (Amazon EC2) instances that were running at any time during the last 14 days and alerts you if the daily CPU utilization was 10% or less and network I/O was 5 MB or less on 4 or more days.

All AWS customers get access to the seven core Trusted Advisor checks to help increase the security and performance of the AWS environment.

- AWS Trusted Advisor cannot detect threats to your AWS account.
- Advice when you miss:
  - When you allow public access to Amazon S3 buckets
  - When you don't turn on user activity logging (AWS CloudTrail)
  - Not using MFA on your root AWS Account.

How Trusted Advisor Works:

![img](https://d1.awsstatic.com/product-marketing/AWS%20Support/AWS-trusted-advisor.5b9909d5f29f680eeb12ccff536e8d88d8701304.png)

AWS Trusted Advisor Recommendations:

![img2](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt2-q3-i1.jpg)

How AWS Trusted Advisor identifies low utilization Amazon EC2 instances:

![img3](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt3-q28-i1.jpg)

---

While AWS Trusted advisor checks are based on the support plan the customer has. Both Basic and Developer support plans have access to the 7 core Trusted Advisor checks. Unlike documentation-based guidance (like AWS Well-Architected Tool), this tool provides recommendations against AWS Well Architected Framework best practices and is able to track against your current AWS architecture.

</details>

---

</br>

## Access Key ID

<details>
<summary>Details</summary></br>

- Access Key ID is from an user;

Access keys are long-term credentials for an **IAM user or the AWS account root user**. You can use access keys to sign programmatic requests to the AWS CLI or AWS API (directly or using the AWS SDK).

Access keys consist of two parts: an access key ID (for example, AKIAIOSFODNN7EXAMPLE) and a secret access key (for example, wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY). As a user name and password, you must use both the access key ID and secret access key together to authenticate your requests. Access Keys are secret, just like a password. You should never share them.

</details>

---

</br>

## AWS Firewall Manager

It's a security management service that allows you to centrally configure and manage firewall rules across your accounts and applications in AWS Organizations. As new applications are created, Firewall Manager makes it easy to bring new applications and resources into compliance by enforcing a common set of security rules.

---

</br>

## AWS Identity and Access Management (IAM)

<details>
<summary>Details</summary></br>

- IAM Policy (JSON)
  - Mandatory elements: Effect, Action;

Most policies are stored in AWS as JSON documents. Identity-based policies and policies used to set permissions boundaries are JSON policy documents that you attach to a user or role. Resource-based policies are JSON policy documents that you attach to a resource.

A JSON policy document includes these elements:

Optional policy-wide information at the top of the document
One or more individual statements
Each statement includes information about a single permission. The information in a statement is contained within a series of elements.

Version – Specify the version of the policy language that you want to use. As a best practice, use the latest 2012-10-17 version.

Statement – Use this main policy element as a container for the following elements. You can include more than one statement in a policy.

1. Sid (Optional) – Include an optional statement ID to differentiate between your statements.

2. **Effect** – Use Allow or Deny to indicate whether the policy allows or denies access.

3. Principal (Required in only some circumstances) – If you create a resource-based policy, you must indicate the account, user, role, or federated user to which you would like to allow or deny access. If you are creating an IAM permissions policy to attach to a user or role, you cannot include this element. The principal is implied as that user or role.

4. **Action** – Include a list of actions that the policy allows or denies.

5. Resource (Required in only some circumstances) – If you create an IAM permissions policy, you must specify a list of resources to which the actions apply. If you create a resource-based policy, this element is optional. If you do not include this element, then the resource to which the action applies is the resource to which the policy is attached.

6. Condition (Optional) – Specify the circumstances under which the policy grants permission.

## IAM Policy

Mandatory elements: Effect, Action;

## Access

- User
- Role
- Group
- Policy

</details>

---

</br>

## AWS Identity and Access Management (IAM) access advisor

<details>
<summary>Details</summary></br>
IAM Access advisor shows the service permissions granted to a user and when those services were last accessed. You can use this information to revise your policies. To summarize, you can identify unnecessary permissions so that you can revise your IAM policies accordingly.

- Allows you to review permissions granted to an IAM user;

</details>

---

</br>

## AWS IAM Identity Center (Successor to AWS Single Sign-On)

<details>
<summary>Details</summary></br>
AWS IAM Identity Center is the successor to AWS Single Sign-On (AWS SSO). It is built on top of AWS Identity and Access Management (IAM) to simplify access management to multiple AWS accounts, AWS applications, and other SAML-enabled cloud applications. In IAM Identity Center, you create or connect, your workforce users for use across AWS. You can choose to manage access just to your AWS accounts, just to your cloud applications, or to both.

You can create users directly in IAM Identity Center, or you can bring them from your existing workforce directory. With IAM Identity Center, you get a unified administration experience to define, customize, and assign fine-grained access. Your workforce users get a user portal to access their assigned AWS accounts or cloud applications.

You can use IAM Identity Center to quickly and easily assign and manage your employees’ access to multiple AWS accounts, SAML-enabled cloud applications (such as Salesforce, Microsoft 365, and Box), and custom-built in-house applications, all from a central place.

How AWS IAM Identity Center works:

![img](https://d1.awsstatic.com/product-marketing/IAM/product-page-diagram_AWS-IAM-Identity-Center_SSO-Rework.45817a4d5cdf0acf33a75257713d3266879196b1.png)

</details>

---

</br>

## AWS Security Token Service (AWS STS)

AWS Security Token Service (AWS STS) is a web service that enables you to request temporary, limited-privilege credentials for AWS Identity and Access Management (AWS IAM) users or for users that you authenticate (federated users).

You can use the AWS Security Token Service (AWS STS) to create and provide trusted users with temporary security credentials that can control access to your AWS resources. Temporary security credentials work almost identically to the long-term access key credentials that your IAM users can use, with the following differences:

Temporary security credentials are short-term, as the name implies. They can be configured to last for anywhere from a few minutes to several hours. After the credentials expire, AWS no longer recognizes them or allows any kind of access from API requests made with them.

Temporary security credentials are not stored with the user but are generated dynamically and provided to the user when requested. When (or even before) the temporary security credentials expire, the user can request new credentials, as long as the user requesting them still has permission to do so.

Temporary security credentials are generated by AWS Security Token Service (AWS STS). By default, AWS STS is a global service with a single endpoint at https://sts.amazonaws.com. However, you can also choose to make AWS STS API calls to endpoints in any other supported Region.

---

</br>

## AWS Systems Manager Session Manager

The best way to provide secure shell access to Amazon Elastic Compute Cloud (Amazon EC2) instances without opening new ports or using public IP addresses

AWS Systems Manager Session Manager is a fully-managed service that provides you with an interactive browser-based shell and CLI experience. It helps provide **secure and auditable instance management without the need to open inbound ports, maintain bastion hosts, and manage SSH keys**. AWS Systems Manager Session Manager helps to enable compliance with corporate policies that require controlled access to instances, increase security and auditability of access to the instances while providing simplicity and cross-platform instance access to end-users.

---

</br>

## Credentials Report

You can generate and download a credentials report that lists all users in your account and the status of their various credentials, including passwords, access keys, and MFA devices. You can use the credentials report to assist in your auditing and compliance efforts. You can use the report to audit the effects of credential lifecycle requirements, such as password and access key rotation. You can provide the report to an external auditor, or grant permissions to an auditor so that he or she can download the report directly.

- It is not used to review permissions granted to an IAM user;

---

</br>

## Distributed Denial of Service (DDoS)

<details>
<summary>AWS Shield</summary></br>
AWS Shield is a managed Distributed Denial of Service (DDoS) protection service that safeguards applications running on AWS. AWS Shield provides always-on detection and automatic inline mitigations that minimize application downtime and latency, so there is no need to engage AWS Support to benefit from DDoS protection.

Ex: Route 53, AWS Global Acelerator, EC2, ELB, ALB, CloudFront, API GW;

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
