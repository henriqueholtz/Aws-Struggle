# Amazon Machine Image (AMI)

An Amazon Machine Image (AMI) provides the information required to launch an instance. You must specify an Amazon Machine Image (AMI) when you launch an instance.

An Amazon Machine Image (AMI) includes the following:

One or more Amazon Elastic Block Store (Amazon EBS) snapshots, or, for instance store backed AMIs, a template for the root volume of the instance (for example, an operating system, an application server, and applications).

Launch permissions that control which AWS accounts can use the Amazon Machine Image (AMI) to launch instances.

A block device mapping that specifies the volumes to attach to the instance when it's launched.

The following diagram summarizes the Amazon Machine Image (AMI) lifecycle:

![img](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/images/ami_lifecycle.png)
