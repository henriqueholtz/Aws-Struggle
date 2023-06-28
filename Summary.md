# AWS Infraestructure

### Wavelength

Connection between telephone operators (ex: "Tim") and AZs;

---

</br>

### Local Zone

Smallest than an AZ;

---

</br>

### OutSpots

AWS's datacenter within another company;

---

</br>

### AWS Edge Locations

An AWS Edge location is a site that CloudFront uses to cache copies of the content for faster delivery to users at any location.

---

</br>
</br>
</br>
</br>

# AWS Products & services

## AWS Glue

ETL (extract, transform and load data)

---

</br>

## Amazon Macie

Find sensitive data;

---

</br>

### AWS Snowball

Transfer data with hardware (physical transport);

---

</br>

### AWS X-Ray

Analyze and debug serverless and distributed applications;

---

</br>

### OpsWorks

Use code to automate the configurations of your servers using automation platforms like Chef and Puppet;

---

</br>

### AWS Device Farm

Choose native, hybrid or web devices to run tests;

---

</br>

### AWS Fargate (ECS)

Containers service without acess to the servers;

---

</br>

### Amazon ECS

Container service with acess to the servers;

---

</br>

### Amazon EKS

Start, run, and scale Kubernetes;

---

</br>

### AWS Service Catalog

Allows organizations to create and manage catalogs of IT services that are approved for use on AWS;

---

</br>

### AWS Elastic Beanstalk

Upload your code and it automatically handles the deployment (including LB, Auto-scaling, etc);

---

</br>

### AWS Config

Think resource-specific history, audit, and compliance: think Config. It uses events from CloudTrail

---

</br>

### AWS Cloud HSM

Cloud-based hardware security module (HSM) that enables you to easily generate and use your encryption keys on the AWS Cloud;

---

</br>

### AWS CloudFormation

Infrastructure as code (like Terraform);

---

</br>

### AWS Artifact

AWS Artifact is your go-to, central resource for compliance-related information that matters to your organization;

---

</br>

### Amazon Polly

Turn text into lifelike speech;

---

</br>

### Amazon SageMaker

To build, train, and deploy machine learning (ML) models quickly;

---

</br>

### Amazon Pinpoint

Deliver customer-centric engagement experiences by capturing customer usage data to draw real-time insights;

---

</br>

### Amazon Rekognition

Identify objects, people, text, etc in photos;

---

</br>

### Amazon Personalize

Personalized recommendations like product recommendations (the same technology used by amazon.con);

---

</br>

### Amazon Lex

Service to build apps using voice and text;

---

</br>

### Amazon Lightsail

VPS (seems like an EC2 with fixed monthly costs);

---

</br>

### Amazon Step Function

Lets you coordinate multiple AWS services into serverless workflows;

---

</br>

### AWS Batch

Batch processing, ML model training, and analysis at any scale. Plan, schedule and run your containerized batch or ML workloads. (ex: ECS, EKS, Fargate, Spot or on-demand instances)

---

</br>

### AWS CodeCommit

Private GIT of AWS;

---

</br>

### AWS CodeDeploy

Automates application deployments to a variety of compute services including EC2, Fargate, Lambda, and on-premises instances;

---

</br>

### AWS CodePipeline

Create anda manage the steps like install, build, test, etc.;

---

</br>

### AWS CodeStar

Accelerates software release with the help of AWS CodePipeline, a continuous integration and continuous delivery (CI/CD) service;

---

</br>

### AWS CodeArtifact

is a fully managed artifact repository service that makes it easy for organizations of any size to securely store, publish, and share software packages used in their software development process;

---

</br>

### AWS Cloud9

IDE to code, run and debug fro browser;

---

</br>

### Amazon Kendra

Provides ML-powered search capabilities for all unstructured data customers store in AWS;

---

</br>

### Amazon Kinesis Data Streams

Enables you to build custom applications that process or analyze streaming data for specialized needs;

---

</br>

### Amazon EMR

Is the industry-leading cloud big data platform for processing vast amounts of data using open source tools such as Hadoop, Apache Spark, Apache Hive, Apache HBase, Apache Flink, Apache Hudi, and Presto;

---

</br>

### Amazon GuardDuty

Is a threat detection service that continuously monitors for malicious activity and unauthorized behavior to protect your AWS accounts, workloads, and data stored in S3;

---

</br>

### Amazon Inspector

Monitor the security of EC2 instances (installing an agent)

---

</br>

### Amazon MQ

Like RabbitMQ managed by AWS;

---

</br>

### Amazon Cognito

Identity and access management;

---

</br>

### AWS Shield Standard

Managed Distributed Denial of Service (DDoS) protection service that safeguards applications running on AWS (layers 3 and 4) and it's activated to all customer by default;

---

</br>

### AWS Shield Advanced

Optional and payed (layers 3, 4 and 7) to protect EC2, ELB, CloudFront, Route 53 and AWS Global Acelerator;

---

</br>

### AWS WAF

AWS Web Application Firewall protect against DDoS attacks, SQL Injection, etc (layer 7);

---

</br>

### Amazon Comprehend

Natrual Language Processing (NLP) service that uses ML to find insights and relationships in a text. Ex: identify the language, if is positive or negative, extracts key phrases, places, people, etc;

---

</br>

### Amazon Quicksight

Lets you easily create and publish interactive BI dashboards that include Machine Learning-powered insights;

---

</br>

### Amazon Elastic Transcoder

Convert media files from S3 into media files in the formats required by consumer playback devices like mobile, tablet, etc;

---

</br>

### Amazon Detective

Amazon Detective can analyze trillions of events from multiple data sources such as Virtual Private Cloud (VPC) Flow Logs, AWS CloudTrail, and Amazon GuardDuty, and automatically creates a unified, interactive view of your resources, users, and the interactions between them over time.

---

</br>

### AWS Control Tower

is an AWS native service providing a pre-defined set of blueprints and guardrails to help customers implement a landing zone for new AWS accounts;

---

</br>

### Amazon Sumerian

Lets you create and run 3D, Augmented Reality (AR) and Virtual Reality (VR) applications;

---

</br>

### AWS OpsHub

AWS OpsHub is a graphical user interface you can use to manage your AWS Snowball devices;

---

</br>

### AWS IoT Core

Lets you connect IoT devices to the AWS cloud without the need to provision or manage servers;

---

</br>

### x

;

---

</br>

### x

;

---

</br>

### x

;

---

</br>

### x

;

---

</br>
</br>
</br>
</br>

# Storages

### AWS Backup

;

---

</br>

### S3

Object Storage;

---

</br>

### EFS

File System Storage. Can be used by multiples instances;

---

</br>

### EBS

Block storage bases on volumes. Usually can be used only by one instance at time;

---

</br>

### Instance Store

Block storage, phisically attatched to the instance. The data is temporary;

---

</br>
</br>
</br>

# AWS Network

### Virtual Private Cloud (VPC)

1 per region, can spans all AZs within the region;

---

</br>

### VPC Endpoint

Connect service to VPC;
Types: **Interface endpoints and Gateway endpoints**

| VPC endpoint Types     | Services            |
| ---------------------- | ------------------- |
| VPC gateway endpoint   | DynamoDB & S3       |
| VPC interface endpoint | All except DynamoDB |

---

</br>

### VPC Peering connection

Connection between only 2 VPCs;

---

</br>

### AWS Transit Gateway

Connection between multiple VPCs (like a central hub);

---

</br>

### SubNet

- Range of IP addresses within your VPC;
- Spans only one AZ;
- Each subnet must be associated with one NACL. If you don't explicitly associate a subnet with a NACL, the subnet is automatically associated with de default NACL (the default NACL allows everything)

---

</br>

### IGW

Internet gateway;

---

</br>

### NACL

- Acts as a firewall for controlling traffic in and out of one or more subnets level (stateless);
- Allow and Deny rules;
- Inbound and outbound rules;

---

</br>

### Security Group (SG)

- Acts as a firewall at the instance level (ex: eth0). Statefull. Customer is responsible;
- Only allow rules;
- Inbound and outbound rules;

---

</br>

### NAT gateway

Network Address Translation gateway (NAT gateway) is managed by AWS.

---

</br>

### NAT instance

Network Address Translation Instance is managed by you.

---

</br>

### AWS Virtual Private Network (VPN)

Create a secure connection (it goes over the public internet) between your on-premises and your VPC. Two types:

- **AWS Site-to-Site VPN**:
  - Enables you to connect your on-premises network to your VPC.
  - Components:
    - Virtual private gateway (VGW): VPN concentrator on the AWS side (physical or software appliance);
    - Transit Gateway
    - Customer Gateway: Resouce that provides information about your customer gateway device;
- **AWS Client VPN**

---

</br>

### AWS Direct Connect

Physical and private connection between on-premises and VPC.

---

</br>
</br>
</br>
</br>

# AWS Security

### AWS Security Token Service (AWS STS)

Temporary credentials

---

</br>

### x

;

---

</br>
</br>
</br>
</br>

# AWS Supports

https://aws.amazon.com/premiumsupport/plans/

- A designated **Technical Account Manager (TAM)** is available only for AWS Enterprise Support plan;
- **AWS Concierge** is a senior customer service agent who is assigned to your account when you subscribe to an Enterprise or qualified Reseller Support plan.
- **AWS Infrastructure Event Management** is a short-term engagement with AWS Support, available as part of the Enterprise-level Support product offering (also available to the AWS Enterprise On-Ramp Support plan subject to a cap of one per year), and available for additional purchase for AWS Business Support plan users.
- Support 24x7 (phone, email and chat) to technical support and architectural guidance in the context of your specific use-cases: Business, Enterprise and Enterprise On-Ramp
- **Trusted Advisor**:
  - Only core Trusted Advisor checks: Developer and Basic;
  - Full access to AWS Trusted Advisor Best Practice Checks: Business, Enterprise and Enterprise On-Ramp;
- **AWS Trusted Advisor Priority**: Enterprise;
- **Infrastructure Event Management**:
  - Available in the business for an additional fee;
  - Available once per year to Enterprise On-Ramp;
  - Available to Enterprise;
- **AWS Incident Detection and Response**: Available to Enterprise for an additional free;
- **AWS Support API** (to interact with Support Center and Trusted Advisor):
  - Business, Enterprise On-Ramp, or Enterprise
- AWS Support App in Slack: Business, Enterprise On-Ramp, or Enterprise
- **Architectural Guidance**:
  - Developer: General;
  - Business: Contextual to your use-cases;
  - Enterprise On-Ramp: Consultative review and guidance based on your applications (one-per-year);
  - Enterprise: Consultative review and guidance based on your applications
- **Third-Party Software Support**
  - Business, Enterprise On-Ramp and Enterprise: Interoperability and configuration guidance and troubleshooting
- **Training**: Enterprise has Access to online self-paced labs

---

## Business, Enterprise On-Ramp, or Enterprise Support plan have access to these features:

- Use-case guidance – What AWS products, features, and services to use to best support your specific needs;
- Full access to Trusted Advisor;
- The AWS Support API to interact with Support Center and Trusted Advisor. You can use the AWS Support API to automate support case management and Trusted Advisor operations.
- Third-party software support – Help with Amazon Elastic Compute Cloud (Amazon EC2) instance operating systems and configuration. Also, help with the performance of the most popular third-party software components on AWS. Third-party software support isn't available for customers on Basic or Developer Support plans.
- Supports an unlimited number of AWS Identity and Access Management (IAM) users who can open technical support cases.

## Enterprise On-Ramp or Enterprise Support plan have access to these features:

- Application architecture guidance – Consultative guidance on how services fit together to meet your specific use case, workload, or application.
- Infrastructure event management – Short-term engagement with AWS Support to get a deep understanding of your use case. After analysis, provide architectural and scaling guidance for an event.
- Technical account manager – Work with a technical account manager (TAM) for your specific use cases and applications.
- White-glove case routing.
- Management business reviews.

---

## AWS Basic Support

- Customer Service and Communities - 24x7 access to customer service, documentation, whitepapers, and AWS re:Post.
- AWS Trusted Advisor - Access to core Trusted Advisor checks and guidance to provision your resources following best practices to increase performance and improve security.
- AWS Personal Health Dashboard - A personalized view of the health of AWS services, and alerts when your resources are impacted.

---

## AWS Developer Support

Greater of $29/month. You should use AWS Developer Support if you are testing or doing early development on AWS and want the ability to get email-based technical support during business hours as well as general architectural guidance as you build and test. This plan only supports general architectural guidance.

---

### AWS Business Support

Greater of $100 / month. You should use AWS Business Support if you have production workloads on AWS and want 24x7 phone, email and chat access to technical support and architectural guidance in the context of your specific use-cases. You get full access to AWS Trusted Advisor Best Practice Checks. You also get access to Infrastructure Event Management for an additional fee.

---

### AWS Enterprise On-Ramp Support

Greater of $5,500. You should use the AWS Enterprise On-Ramp Support plan if you have production/business critical workloads in AWS and want 24x7 access to technical support and need expert guidance to grow and optimize in the Cloud.

---

### AWS Enterprise Support

Greater of $15,000.AWS Enterprise Support plan provides customers with concierge-like service where the main focus is helping the customer achieve their outcomes and find success in the cloud. With AWS Enterprise Support, you get 24x7 technical support from high-quality engineers, tools and technology to automatically manage the health of your environment, consultative architectural guidance and a designated Technical Account Manager (TAM) to coordinate access to proactive/preventative programs and AWS subject matter experts

---

</br>
</br>
</br>
</br>

# AWS Billing, Events and Logs

### Free

- AWS Auto Scaling;
- AWS Elastic Beanstalk;
- ClodFormation;
- IAM (users, groups, roles);

---

### Cost Explorer

Visualize, understand, and manage your AWS costs and usage over time;

- 12 months in the past, the current month and 12 months ahead;
- Can forecast costs but can't trigger an alarm;

---

### AWS Cost & Usage Report (AWS CUR)

The most comprehensive set of AWS cost and usage data available, including additional metadata about AWS services, pricing, credit, fees, taxes, discounts, cost categories, Reserved Instances, and Savings Plans

- Can't forecast your AWS account cost and usage.
- Can publish billing reports to an S3 bucket in CSV format;

---

### Aws Budgets

Set custom budgets that alert you when your costs or usage exceed (or are forecasted to exceed) your budgeted amount;

Available types: **cost, usage, reservetaion, savings plan**;

---

### CloudWatch

Think resource performance monitoring, events, and alerts; think CloudWatch;

- The best to monitor metrics;
- Monitor instance sensitive informations only if install the agent (ex: memory);
- Monitor performance (CPU usage; memory only with agent because is a sensitive information);
- Install agent or script to CloudWatch monitor your EC2 instance like memory information, disk usage etc;
- Each 5 minutes by default. You can set to 1 minute for example;
- Allow to create alarms to send notifications;
- Billing metric data is stored in the US East (N. Virginia)

---

### Amazon CloudWatch Billing

- Sends an alarm when the actual cost exceeds a certain threshold.

---

</br>
</br>
</br>
</br>

# Databases

| Type        | AWS services                     |
| ----------- | -------------------------------- |
| Relational  | Aurora, RDS, Redshift            |
| Key-value   | DynamoDB                         |
| In-Memory   | ElastiCache, MemoryDB for Redis  |
| Document    | DocumentDB (MongoDB compability) |
| Wide Column | Keyspaces                        |
| Graph       | Neptune                          |
| Time series | Timestream                       |
| Ledger      | Ledger Database Services (QLDB)  |

---

</br>

### Neptune

Serverless graph database (NoSQL) designed for superior scalability and availability;

---

</br>

### Amazon Aurora

- MySQL and PostgreSQL compatibility;
- You can't enable cross-Region replicas from multi-master clusters.
- Relational. Amazon Aurora does not support flexible schema. (requires a well-defined schema.)

---

</br>

### Amazon DocumentDB

- NoSQL & has compability with MongoDB;

---

</br>

### Amazon DynamoDB

- NoSQL
- Scalable without outage (down time)
- HA 3 DC's automatically
- DynamoDB is schemaless.
- DynamoDB can manage structured or semistructured data, including JSON documents.
- Can be enabled in-memory cache using **DynamoDB Accelerator (DAX)**

---

</br>

### Amazon ElastiCache

Database in-memory cache.

---

</br>

### Amazon Quantum Ledger Database (Amazon QLDB)

"Historical Database" that provides a transparent, immutable, and cryptographically verifiable transaction log owned by a central trusted authority. Amazon QLDB can be used to track each and every application data change and maintains a complete and verifiable history of changes over time.

---

</br>

### Amazon Relational Database Service (Amazon RDS)

- Support relational databases like Amazon Aurora with MySQL/PostgreSQL compatibility, MySQL, MariaDB, PostgreSQL, Oracle, and SQL Server;
- This is a regional service.
- Encryption can be enabled;
- You can enable read-replica to improve read-performance;
- You can enable Multi-AZ Secondary database which is replicated synchronously
- Read-Replica (RR) can be Multi AZs / Multi Regions
- AWS apply patches

---

</br>

### Amazon Redshift

- Serverless relational database;
- Encryption can be enabled for a cluster;

---

</br>

### Amazon Timestream

Serverless time series database service for IoT and operational applications that makes it easy to store and analyze trillions of events per day up to 1,000 times faster and at as little as 1/10th the cost of relational databases

---

</br>
</br>
</br>
</br>

# Compute

### EC2

- IaaS, regional
- Ec2 + license= dedicated host;
- **Options**:
  - Spot Instance
  - On-Demand Instance
  - Reserved Instance (RI): Convertible, Standard
  - Dedicated Host
- **Types**:
  - Memory Optimized
  - Compute Optimized
  - Storage Optimized
  - Accelerated computing
- **Pricing:**
  - Spot is up to 90% cheaper than On-demand
  - Reserved Instances is up to 75% cheaper than On-demand
  - Include: RDS, EC2...
  - Doesn't include: S3, CloudFront, IAM...
  - Dedicated Instances is up to 70% cheaper than On-demand
- **EC2 instance user data**: is the data that you specified in the form of a bootstrap script or configuration parameters while launching your instance.
- **EC2 instance metadata**: is data about your instance that you can use to manage the instance.
- **EC2 Image Builder**: simplifies the building, testing, and deployment of Virtual Machine and container images for use on AWS or on-premises

---

</br>

### EC2 Auto Scaling

- Scaling out instances (horizontally) based on performance;
- New instances based on a EC2 template;
- Create an EC2 Auto scaling group;

---

</br>
</br>
</br>
</br>
