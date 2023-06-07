# Elastic File System (EFS)

Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed elastic NFS file system for use with AWS Cloud services and on-premises resources. It is built to scale on-demand to petabytes without disrupting applications, growing and shrinking automatically as you add and remove files, eliminating the need to provision and manage capacity to accommodate growth.

The service is designed to be highly scalable, highly available, and highly durable. Amazon EFS file systems store data and metadata across multiple Availability Zones (AZ) in an AWS Region. EFS file system can be mounted on instances across multiple Availability Zones (AZ).

- EFS file system can be mounted on instances across multiple Availability Zones (AZ)
- EFS is not available as a hardware disk on the instance
- Encryption of data in transit and encryption at rest. This is an optional feature and has to be enabled by user if needed.

EFS Infrequent Access storage class is cost-optimized for files accessed less frequently. Data stored on the Amazon Elastic File System (Amazon EFS) - Infrequent Access storage class costs less than Standard and you will pay a fee each time you read from or write to a file.

Amazon EFS is designed to provide massively parallel shared access to thousands of Amazon EC2 instances, enabling your applications to achieve high levels of aggregate throughput and IOPS with consistent low latencies.

How Amazon Elastic File System (Amazon EFS) Works:

![img](https://d1.awsstatic.com/r2018/b/EFS/product-page-diagram-Amazon-EFS-Launch_How-It-Works.cf947858f0ef3557b9fc14077bdf3f65b3f9ff43.png)
