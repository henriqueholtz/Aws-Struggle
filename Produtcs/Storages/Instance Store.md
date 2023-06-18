# Instance Store

An instance store provides temporary **block-level** storage for your instance. This storage is located on disks that are physically attached to the host computer. This is a good option when you need storage with very low latency, but you don't need the data to persist when the instance terminates or you can take advantage of fault-tolerant architectures. For this use-case, the computation application itself has a fault tolerant architecture, so it can automatically handle any failures of Instance Store volumes.

- As the Instance Store volumes are included as part of the instance's usage cost.
- EC2 instance store cannot be used for file sharing between instances.
- Block level storage (like EBS)

Instance store is ideal for the temporary storage of information that changes frequently, such as **buffers, caches, scratch data, and other temporary content, or for data that is replicated across a fleet of instances**, such as a load-balanced pool of web servers. Instance storage is temporary, data is lost if instance experiences failure or is terminated.

As Instance Store volumes are tied to an EC2 instance, they are also single Availability Zone (AZ) entities.

EC2 Instances Store Overview:

![img](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt1-q22-i1.jpg)
