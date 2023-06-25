# VPC

- 1 VPC per region. An Amazon Virtual Private Cloud (Amazon VPC) spans all of the Availability Zones (AZ) in the Region

Amazon Virtual Private Cloud (Amazon VPC) is a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define. You have complete control over your virtual networking environment, including the selection of your IP address range, creation of subnets, and configuration of route tables and network gateways.

- An Amazon Virtual Private Cloud (Amazon VPC) spans all of the Availability Zones (AZ) in the Region.

A subnet is a range of IP addresses within your Amazon Virtual Private Cloud (Amazon VPC). A **subnet spans only one Availability Zone (AZ) in the Region**.

Amazon Virtual Private Cloud (Amazon VPC) and Subnet Overview:

![img0](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt2-q49-i1.jpg)

## VPC Endpoint

A VPC endpoint enables you to privately connect your VPC to supported AWS services and VPC endpoint services powered by AWS PrivateLink without requiring an internet gateway, NAT device, VPN connection, or AWS Direct Connect connection. Instances in your VPC do not require public IP addresses to communicate with resources in the service. Traffic between your VPC and the other service does not leave the Amazon network.

- VPC Endpoint cannot be used to privately connect on-premises data center to AWS Cloud.
- You cannot connect two VPCs using a VPC endpoint.

There are two types of VPC endpoints:

    - Interface endpoints
    - Gateway endpoints.

An **interface endpoint** is an elastic network interface with a private IP address from the IP address range of your subnet that serves as an entry point for traffic destined to a supported service. Interface endpoints are powered by AWS PrivateLink, a technology that enables you to privately access services by using private IP addresses. (all services except DynamoDB supports VPC interface endpoint)

A **gateway endpoint** is a gateway that you specify as a target for a route in your route table for traffic destined to a supported AWS service. The following AWS services are supported:

- Amazon Simple Storage Service (Amazon S3)
- Amazon DynamoDB

## Key concepts for VPCs:

- Virtual private cloud (VPC) — A virtual network dedicated to your AWS account.
- Subnet — A range of IP addresses in your VPC.
- Route table — A set of rules, called routes, that are used to determine where network traffic is directed.
- Internet Gateway — A gateway that you attach to your VPC to enable communication between resources in your VPC and the internet.
- VPC endpoint — Enables you to privately connect your VPC to supported AWS services and VPC endpoint services powered by PrivateLink without requiring an internet gateway, NAT device, VPN connection, or AWS Direct Connect connection

## Exam Alert:

Just remember that only Amazon S3 and Amazon DynamoDB support **VPC gateway endpoint**.

All other services that support VPC Endpoints use a **VPC interface endpoint** (note that Amazon S3 supports the VPC interface endpoint as well).

| VPC endpoint Types     | Services            |
| ---------------------- | ------------------- |
| VPC gateway endpoint   | DynamoDB & S3       |
| VPC interface endpoint | All except DynamoDB |

## Connect VPCs

- AWS Transit Gateway (piece in the center);
- AWS peering connection (to connect one by one);

How AWS Transit Gateway can simplify your network:

![img connecting VPCs](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt4-q17-i1.jpg)

## A VPC endpoint interface

An interface VPC endpoint (interface endpoint) enables you to connect to services powered by AWS PrivateLink. It is not a component of a connection between on-premises network and AWS.
