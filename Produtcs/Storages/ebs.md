# Elastic Block Storage (EBS)

- Like an HD/Volume (ex: "E:\");
- SSD/HDD (choice when creating);
- No-autogrow (ex: you need to configure monitoring and execute a lamba do change the disk size)
- It does not offer lifecycle configuration.
- EBS volumes can only be mounted with Amazon EC2. (not with on-premises)
- EBS volume can be bound to a single AZ (When using Amazon EBS Elastic Volumes, the volume, and the instance must be in the same Availability Zone (AZ));

Amazon Elastic Block Store (EBS) is an easy to use, high-performance block storage service designed for use with Amazon Elastic Compute Cloud (EC2) for both throughput and transaction-intensive workloads at any scale.

Designed for mission-critical systems, EBS volumes are replicated within an Availability Zone (AZ) and can easily scale to petabytes of data. You can attach an available EBS volume to one instance that is in the same Availability Zone (AZ) as the volume.

- EBS volume can be attached to a single instance in the same Availability Zone (AZ).
- EBS is not available as a hardware disk on the instance
- Encryption (at rest and during transit) is an optional feature for EBS and has to be enabled by the user.
- For the Cloud Practitioner exam, you should consider that an EBS volume can only be mounted to one EC2 instance at a time.
- Block level storage (like instance store)

Amazon EBS Snapshots are a point in time copy of your block data. For the first snapshot of a volume, Amazon EBS saves a full copy of your data to Amazon S3. Amazon EBS Snapshots are stored incrementally, which means you are billed only for the changed blocks stored.

When using Amazon EBS direct APIs for Snapshots, additional Amazon EC2 data transfer charges will apply only when you use external or cross-region data transfers.

Amazon EBS is not a good fit for caching information on Amazon EC2 instances

A broad range of workloads, such as relational and non-relational databases, enterprise applications, containerized applications, big data analytics engines, file systems, and media workflows are widely deployed on Amazon EBS. As a special case, you should note that Amazon EBS Multi-Attach enables you to attach a single Provisioned IOPS SSD (io1 or io2) volume to multiple nitro based instances that are in the same Availability Zone (AZ).

Amazon Elastic Block Store (Amazon EBS) volumes are not encrypted, by default. You can configure your AWS account to enforce the encryption of the new EBS volumes and snapshot copies that you create.

## Charges

The fundamental charges for EBS volumes are:

- Volume type (based on performance), ex: gp3, gp2 [see more details here](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-volume-types.html)
- Storage volume in GB per month provisioned
- Number of IOPS provisioned per month
- Storage consumed by snapshots
- Outbound data transfer.

---

## Multi-Attach

- EC2 instances must be "nitro"
- Max of 16 instances
- Type must be "io1"

## Volum types

- HDD
- SSD
