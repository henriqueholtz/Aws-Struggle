# AWS Global Infrastructure

[Back to index](Index.md)

## Availability Zones

- Each AWS Region consists of a minimum of three AZs
- Each AZ consists of one or more discrete data centers.
- Each AZ must be between 100km of each other.
- Multi AZ == High availability
- All traffic between Availability Zones (AZ) is encrypted

---

</br>

## Global in scope

- AWS Identity and Access Management (AWS IAM)
- Amazon CloudFront
- Amazon Route 53
- AWS Web Application Firewall (AWS WAF)
- Amazon WorkSpaces

## AWS Local Zones

- Smallest than an AZ;
- Connects to AZs;
- Can be services like EC2, VPC, EBS, Amazon FSx, ELB, EMR, ElastiCache, RDS;

---

</br>

## AWS Regions

- Deploying the application across multi AWS Regions improves **availability**

---

</br>
