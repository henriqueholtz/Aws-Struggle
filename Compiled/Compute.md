# Compute

[Back to index](Index.md)

## EC2

- IaaS, regional
- Ec2 + license= dedicated host;
- On-demand: Pay at least 60 seconds, and after that pay by second;
- **Options**:
  - Spot Instance
  - On-Demand Instance
  - Reserved Instance (RI): Convertible, Standard
  - Dedicated Host
- **Types**:
  - Memory Optimized
  - Compute Optimized
  - Storage Optimized
  - Accelerated computing
- **Pricing:**
  - Spot is up to 90% cheaper than On-demand
  - Reserved Instances is up to 75% cheaper than On-demand
  - Include: RDS, EC2...
  - Doesn't include: S3, CloudFront, IAM...
  - Dedicated Instances is up to 70% cheaper than On-demand
- **EC2 instance user data**: is the data that you specified in the form of a bootstrap script or configuration parameters while launching your instance.
- **EC2 instance metadata**: is data about your instance that you can use to manage the instance.
- **EC2 Image Builder**: simplifies the building, testing, and deployment of Virtual Machine and container images for use on AWS or on-premises

---

</br>

## EC2 Instance Connect

- Connect to linux using SSH, and IAM policies.
- Will need port 22 to be open for traffic.

---

</br>

## EC2 Auto Scaling

- Scaling out instances (horizontally) based on performance;
- New instances based on a EC2 template;
- Create an EC2 Auto scaling group;

---

</br>

## AWS Fargate (ECS)

Containers service without acess to the servers;

---

</br>

## Amazon Elastic Container Service (ECS)

Container service with acess to the servers;

---

</br>

## Amazon EKS

Start, run, and scale Kubernetes;

---

</br>

## Amazon Lightsail

VPS (seems like an EC2 with fixed monthly costs);

---

</br>

## AWS Batch

Batch processing, ML model training, and analysis at any scale. Plan, schedule and run your containerized batch or ML workloads. (ex: ECS, EKS, Fargate, Spot or on-demand instances)

---

</br>

## AWS Elastic Beanstalk

Upload your code and it automatically handles the deployment (including LB, Auto-scaling, etc);

---

</br>

## Local Zone

Smallest than an AZ;

---

</br>

## OutSpots

AWS's datacenter within another company;

---

</br>

## AWS Wavelength

Connection between telephone operators (ex: "Tim") and AZs;

---

</br>

## AWS Lambda

Serveless to run your code. It support environment variables. Needs specific permissions.

---

</br>
