# Amazon Machine Image (AMI)

An Amazon Machine Image (AMI) provides the information required to launch an instance. You must specify an Amazon Machine Image (AMI) when you launch an instance.

An Amazon Machine Image (AMI) includes the following:

One or more Amazon Elastic Block Store (Amazon EBS) snapshots, or, for instance store backed AMIs, a template for the root volume of the instance (for example, an operating system, an application server, and applications).

Launch permissions that control which AWS accounts can use the Amazon Machine Image (AMI) to launch instances.

A block device mapping that specifies the volumes to attach to the instance when it's launched.

The following diagram summarizes the Amazon Machine Image (AMI) lifecycle:

![img](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/images/ami_lifecycle.png)

You must use an Amazon Machine Image (AMI) from the same region as that of the Amazon EC2 instance. The region of the Amazon Machine Image (AMI) has no bearing on the performance of the Amazon EC2 instance

An Amazon Machine Image (AMI) provides the information required to launch an instance. You must specify an Amazon Machine Image (AMI) when you launch an instance. You can launch multiple instances from a single AMI when you need multiple instances with the same configuration.

The Amazon Machine Image (AMI) must be in the same region as that of the Amazon EC2 instance to be launched. If the Amazon Machine Image (AMI) exists in a different region, you can copy that Amazon Machine Image (AMI) to the region where you want to launch the EC2 instance. The region of Amazon Machine Image (AMI) has no bearing on the performance of the Amazon EC2 instance.

Amazon Machine Images (AMI) Overview:

![img2](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt3-q34-i1.jpg)
