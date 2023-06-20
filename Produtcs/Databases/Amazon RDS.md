# Amazon Relational Database Service (Amazon RDS)

Amazon Relational Database Service (Amazon RDS) can encrypt your Amazon RDS DB instances. Data that is encrypted at rest includes the underlying storage for DB instances, its automated backups, read replicas, and snapshots.

- This is a regional service.
- Encryption for RDS is an additional feature and the user needs to enable it.
- You can enable read-replica to improve read-performance;
- You can enable Multi-AZ Secondary database which is replicated synchronously
- Read-Replica (RR) can be Multi AZs / Multi Regions
- AWS apply patches
- RDS requires a well-defined schema.

Amazon RDS Multi-AZ deployments provide enhanced availability and durability forAmazon Relational Database Service (Amazon RDS) instances, making them a natural fit for production database workloads. When you provision an Amazon RDS Multi-AZ Instance with one standby, Amazon RDS automatically creates a primary DB Instance and synchronously replicates the data to a standby instance in a different Availability Zone (AZ).

Think of multi-AZ deployment as enhancing the availability and reliability of your system, however, by itself, multi-AZ deployment cannot be used for disaster recovery.

In case of an infrastructure failure, Amazon RDS performs an automatic failover to the standby so that you can resume database operations as soon as the failover is complete.

How Amazon RDS Multi-AZ Works:

![img](https://d1.awsstatic.com/asset-repository/multi-az-deployments.bda9d7bf45a74103d0331a985baf2c5fb838a0fa.png)

## Exam Alert:

Please review the differences between Multi-AZ, Multi-Region and Read Replica deployments for RDS:

![img2](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt2-q17-i1.jpg)

Amazon Relational Database Service (Amazon RDS) makes it easy to set up, operate, and scale a relational database in the cloud. Read Replicas allow you to create read-only copies that are synchronized with your master database. Read Replicas are used for improved read performance. You can also place your read replica in a different AWS Region closer to your users for better performance. Read Replicas are an example of horizontal scaling of resources.

---

- Improve read performance as well as disaster recovery;

Read Replica Overview:

![img3](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt3-q31-i1.jpg)
