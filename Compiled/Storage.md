# Storages

[Back to index](Index.md)

## AWS Backup

With AWS Backup, you pay only for the amount of backup storage you use and the amount of backup data you restore in the month. There is no minimum fee and there are no set-up charges.

---

</br>

## S3

<details>
<summary>Difference between classes</summary>

![img](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt1-q9-i1.jpg)

</details>

- Object Storage (key-value based).
- The buckets are regional.
- Data encryption automatically enabled.
- 0 bytes to 5tb per object;

<details>
<summary>Classes</summary>

- **S3 Standard** for general-purpose storage of frequently accessed data;
- **S3 Intelligent-Tiering** for data with unknown or changing access patterns;
- **S3 Standard-Infrequent Access (S3 Standard-IA) and S3 One Zone-Infrequent Access (S3 One Zone-IA)** for long-lived, but less frequently accessed data;
- **Amazon S3 Glacier (S3 Glacier) and Amazon S3 Glacier Deep Archive (S3 Glacier Deep Archive)** for long-term archive and digital preservation;

![Performance across the S3 Storage Classes](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt1-q9-i1.jpg)

</details>

<details>
<summary>S3 Versioning</summary>

It's a means of keeping multiple variants of an object in the same bucket. You can use versioning to preserve, retrieve, and restore every version of every object stored in your Amazon S3 bucket. With versioning, you can easily recover from both unintended user actions and application failures.

</details>

<details>
<summary>S3 lifecycle configuration</summary>

Can be used to transtition objects to less expensive classes, archive or delete them.

</details>

<details>
<summary>S3 Object Lock</summary>

To store objects using a write-once-read-many (WORM) model. It can help you prevent objects from being deleted or overwritten for a fixed amount of time or indefinitely. You can use S3 Object Lock to meet regulatory requirements that require WORM storage, or add an extra layer of protection against object changes and deletion.

</details>

<details>
<summary>S3 Transfer Acceleration (Amazon S3TA)</summary>

It takes advantage of Amazon CloudFront’s globally distributed edge locations. As the data arrives at an edge location, data is routed to Amazon S3 over an optimized network path.

</details>

<details>
<summary>Host an static website on Amazon S3</summary>

- The bucket must be public, and enabled the setting to hosting a website. Upload an index.html;

</details>

<details>
<summary>S3 cross-region/same-region replication (S3 CRR & S3 SRR)</summary>

Replicate the data cross or in the same region.

</details>

---

</br>

## EFS

- File System Storage, regional service. Can be used by multiples instances across multi AZs, regions and VPCs;
- Allow Autogrow;
- NFS;
- Multi-AZs;
- Encryption of data in transit and encryption at rest. This is an optional feature and has to be enabled by user if needed.
- it isn't a good fit for caching information on

---

</br>

## EBS

- Block storage (like instance store), bases on volumes.
- Usually can be used only by one instance at time. (For the Cloud Practitioner exam, you should consider that an EBS volume can only be mounted to one EC2 instance at a time);
- Like an HD/Volume (ex: "E:\");
- SSD/HDD (choice when creating);
- No-autogrow (ex: you need to configure monitoring and execute a lamba do change the disk size)
- It does not offer lifecycle configuration.
- EBS volumes can only be mounted with Amazon EC2. (not with on-premises)
- EBS volume can be bound to a single AZ (When using Amazon EBS Elastic Volumes, the volume, and the instance must be in the same Availability Zone (AZ));
- EBS volume can be attached to a single instance in the same Availability Zone (AZ).
- EBS is not available as a hardware disk on the instance
- Encryption (at rest and during transit) is an optional feature for EBS and has to be enabled by the user.
- ***

</br>

## Instance Store

- Phisically attatched to the instance;
- Block level storage (like EBS);
- As the Instance Store volumes are included as part of the instance's usage cost.
- EC2 instance store cannot be used for file sharing between instances.
- Instance storage is temporary, data is lost if instance experiences failure or is terminated. Instance Store does not offer lifecycle configuration.

Instance store is ideal for the temporary storage of information that changes frequently, such as **buffers, caches, scratch data, and other temporary content, or for data that is replicated across a fleet of instances**

---

</br>
</br>
</br>

# Snow Family

![img](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt6-q60-i1.jpg)

## AWS OpsHub for Snow Family

AWS OpsHub is a graphical user interface you can use to manage your AWS Snowball devices;

---

</br>

## AWS Snowball

- Transfer data with hardware (physical transport);
- specialize in data migration from on-premises to AWS Cloud;

---

</br>

## AWS Snowball Edge

---

</br>

## AWS Snowball

---

</br>

## AWS Snowcone

---

</br>

## AWS Snowmobile

---

</br>
9
