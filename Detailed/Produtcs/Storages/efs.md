# Elastic File System (EFS)

- Allow Autogrow;
- NFS;
- Multi-AZs;

Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed elastic NFS file system for use with AWS Cloud services and on-premises resources. It is built to scale on-demand to petabytes without disrupting applications, growing and shrinking automatically as you add and remove files, eliminating the need to provision and manage capacity to accommodate growth.

The service is designed to be highly scalable, highly available, and highly durable. Amazon EFS file systems store data and metadata across multiple Availability Zones (AZ) in an AWS Region. EFS file system can be mounted on instances across multiple Availability Zones (AZ).

- EFS file system can be mounted on instances across multiple Availability Zones (AZ)
- EC2 instances can access files on an Amazon Elastic File System (Amazon EFS) file system across many Availability Zones (AZ), Regions and VPCs.
- EFS is not available as a hardware disk on the instance
- Encryption of data in transit and encryption at rest. This is an optional feature and has to be enabled by user if needed.

EFS Infrequent Access storage class is cost-optimized for files accessed less frequently. Data stored on the Amazon Elastic File System (Amazon EFS) - Infrequent Access storage class costs less than Standard and you will pay a fee each time you read from or write to a file.

Amazon EFS is designed to provide massively parallel shared access to thousands of Amazon EC2 instances, enabling your applications to achieve high levels of aggregate throughput and IOPS with consistent low latencies.

Encryption is not a default setting, but an optional configuration for Amazon EFS drives. Amazon EFS supports two forms of encryption for file systems, encryption of data in transit and encryption at rest.

Amazon EFS is not a good fit for caching information on Amazon EC2 instances.
Amazon EFS is a regional service storing data within and across multiple Availability Zones (AZ) for high availability and durability.

EFS storage option cannot directly be used to host a website, EFS needs to be mounted on Amazon EC2 to work as a static website.

How Amazon Elastic File System (Amazon EFS) Works:

![img](https://d1.awsstatic.com/r2018/b/EFS/product-page-diagram-Amazon-EFS-Launch_How-It-Works.cf947858f0ef3557b9fc14077bdf3f65b3f9ff43.png)

Amazon EFS is a regional service storing data within and across multiple Availability Zones (AZs) for high availability and durability. Amazon EC2 instances can access your file system across AZs, regions, and VPCs, while on-premises servers can access using AWS Direct Connect or AWS VPN.

![img2](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt3-q23-i1.jpg)
