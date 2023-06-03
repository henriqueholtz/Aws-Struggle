## VPC Endpoint

A VPC endpoint enables you to privately connect your VPC to supported AWS services and VPC endpoint services powered by AWS PrivateLink without requiring an internet gateway, NAT device, VPN connection, or AWS Direct Connect connection. Instances in your VPC do not require public IP addresses to communicate with resources in the service. Traffic between your VPC and the other service does not leave the Amazon network.

- VPC Endpoint cannot be used to privately connect on-premises data center to AWS Cloud.

There are two types of VPC endpoints:

    - Interface endpoints
    - Gateway endpoints.

An **interface endpoint** is an elastic network interface with a private IP address from the IP address range of your subnet that serves as an entry point for traffic destined to a supported service. Interface endpoints are powered by AWS PrivateLink, a technology that enables you to privately access services by using private IP addresses.

A **gateway endpoint** is a gateway that you specify as a target for a route in your route table for traffic destined to a supported AWS service. The following AWS services are supported:

- Amazon Simple Storage Service (Amazon S3)
- Amazon DynamoDB

### Exam Alert:

Just remember that only Amazon S3 and Amazon DynamoDB support **VPC gateway endpoint**.

All other services that support VPC Endpoints use a **VPC interface endpoint** (note that Amazon S3 supports the VPC interface endpoint as well).
