# Networking & Content Delivery

[Back to index](Index.md)

## Virtual Private Cloud (VPC)

1 per region, can spans all AZs within the region;

---

</br>

## VPC Endpoint

Connect service to VPC;
Types: **Interface endpoints and Gateway endpoints**

| VPC endpoint Types     | Services            |
| ---------------------- | ------------------- |
| VPC gateway endpoint   | DynamoDB & S3       |
| VPC interface endpoint | All except DynamoDB |

---

</br>

## VPC Peering connection

Connection between only 2 VPCs;

---

</br>

## AWS Transit Gateway

Connection between multiple VPCs (like a central hub);

---

</br>

## SubNet

- Range of IP addresses within your VPC;
- Spans only one AZ;
- Each subnet must be associated with one NACL. If you don't explicitly associate a subnet with a NACL, the subnet is automatically associated with de default NACL (the default NACL allows everything)

---

</br>

## IGW

Internet gateway;

---

</br>

## NACL

- Acts as a firewall for controlling traffic in and out of one or more subnets level (stateless);
- Allow and Deny rules;
- Inbound and outbound rules;

---

</br>

## Security Group (SG)

- Acts as a firewall at the instance level (ex: eth0). Statefull. Customer is responsible;
- Only allow rules;
- Inbound and outbound rules;

---

</br>

## NAT gateway

Network Address Translation gateway (NAT gateway) is managed by AWS.

---

</br>

## NAT instance

Network Address Translation Instance is managed by you.

---

</br>

## AWS Virtual Private Network (VPN)

Create a secure connection (it goes over the public internet) between your on-premises and your VPC. Two types:

- **AWS Site-to-Site VPN**:
  - Enables you to connect your on-premises network to your VPC.
  - Components:
    - Virtual private gateway (VGW): VPN concentrator on the AWS side (physical or software appliance);
    - Transit Gateway
    - Customer Gateway: Resouce that provides information about your customer gateway device;
- **AWS Client VPN**

---

</br>

## AWS Direct Connect

Physical and private connection between on-premises and VPC.

---

</br>

## AWS Edge Locations for Amazon CloudFront

An AWS Edge location is a site that CloudFront uses to cache copies of the content for faster delivery to users at any location.

---

</br>

## Amazon CloudFront

- Content Delivery Network (CDN) to data like videos, applications, APIS etc.
- Edge location isn't an AZ neither a region. For example currently AWS has 31 regions 99 AZs, but have 400+ edge locations [see details](https://aws.amazon.com/about-aws/global-infrastructure/)
- HTTP/HTTPS;
- Custom domain (your own);
- Integration with Shield, WAF, S3, etc...

---

</br>

## Amazon Route 53

Domain Name System (DNS) web service. Routing types:

- **Weighted routing**
- **Failover routing policy**
- **Simple routing**
- **Latency-based routing**
- others...

<details>
<summary>
See another routing types
</summary>

![img](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt1-q12-i2.jpg)

</details>

---

</br>

## AWS Global Accelerator

It improves performance for a wide range of applications over TCP or UDP by proxying packets at the edge to applications running in one or more AWS Regions. AWS Global Accelerator is a good fit for non-HTTP use cases, such as gaming (UDP), IoT (MQTT), or Voice over IP, as well as for HTTP use cases that specifically require static IP addresses or deterministic, fast regional failover.

- AWS Global Accelerator and Amazon CloudFront use the same edge locations.
- AWS Global Accelerator can be configured with an Elastic Load Balancer (ELB)
- AWS Global Accelerator cannot be used to host static websites. Instead Amazon S3 can host static websites.

---

</br>
