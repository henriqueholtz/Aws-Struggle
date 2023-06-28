# Amazon Elastic Compute Cloud (Amazon EC2)

Amazon EC2 is a web service that provides secure, resizable compute capacity in the AWS cloud. You can use EC2 to provision virtual servers on AWS Cloud.

- Instraestructure as a service
- This is a regional service.
- Ec2 + license= dedicated host;

Options:

- EC2 Spot Instance
- EC2 On-Demand Instance
- EC2 Reserved Instance
- EC2 Dedicated Host

![img pricing ec2](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt1-q8-i1.jpg)

## Pricing

- Spot is up to 90% cheaper than On-demand
- Reserved Instances is up to 75% cheaper than On-demand
  - Include: RDS, EC2...
  - Doesn't include: S3, CloudFront, IAM...
- Dedicated Instances is up to 70% cheaper than On-demand

### Amazon EC2 instance user data

Amazon EC2 instance user data is the data that you specified in the form of a bootstrap script or configuration parameters while launching your instance.

Amazon EC2 instance metadata and user data:

![img2](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt4-q18-i1.jpg)

### Amazon EC2 instance metadata

Amazon EC2 instance metadata is data about your instance that you can use to manage the instance. You can get instance items such as ami-id, public-hostname, local-hostname, hostname, public-ipv4, local-ipv4, public-keys, instance-id by using instance metadata. You cannot use Amazon EC2 instance metadata to run a bootstrap script while launching an Amazon EC2 instance.
