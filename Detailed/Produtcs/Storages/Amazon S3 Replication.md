# Amazon S3 Replication

Replication enables automatic, asynchronous copying of objects across Amazon S3 buckets. Buckets that are configured for object replication can be owned by the same AWS account or by different accounts. You can copy objects between different AWS Regions or within the same Region. You can use replication to make copies of your objects that retain all metadata, such as the original object creation time and version IDs. This capability is important if you need to ensure that your replica is identical to the source object.

Exam Alert:

Amazon S3 supports two types of replication: S3 cross-region replication (S3 CRR) vs S3 same-region replication (S3 SRR). Please review the differences between S3 SRR and S3 CRR:

![img](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt4-q53-i1.jpg)
