# AWS Storage Gateway

- Tape Gateway (seems with S3 Galcier ?!)
- File Gateway (seems with S3 Standard ?!)
- Volume Gateway (seems with EBS ?!)

AWS Storage Gateway is a hybrid cloud storage service that connects your existing on-premises environments with the AWS Cloud. Customers use Storage Gateway to simplify storage management and reduce costs for key hybrid cloud storage use cases. These include moving tape backups to the cloud, reducing on-premises storage with cloud-backed file shares, providing low latency access to data in AWS for on-premises applications, as well as various migration, archiving, processing, and disaster recovery use cases.

- data encryption automatically enabled (using SSL)

AWS Storage Gateway service provides three different types of gateways – Tape Gateway, File Gateway, and Volume Gateway – that seamlessly connect on-premises applications to cloud storage, caching data locally for low-latency access.

AWS Storage Gateway is a hybrid cloud storage service that gives you on-premises access to virtually unlimited cloud storage. All data transferred between the gateway and AWS storage is encrypted using SSL (for all three types of gateways - File, Volume and Tape Gateways).

- AWS Storage Gateway cannot be used for data archival.
- It cannot be used to host a website.
- AWS Storage Gateway does not offer lifecycle configuration.

Gateway Storage Types Overview:

![img](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt2-q63-i1.jpg)
