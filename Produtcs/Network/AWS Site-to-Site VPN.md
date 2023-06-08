# Site to Site VPN

AWS Site-to-Site VPN creates a secure connection between your data center or branch office and your AWS cloud resources. This connection goes over the public internet.

Site to Site VPN is a connectivity service and it does not specialize in data migration.

AWS Site-to-Site VPN cannot be used to interconnect VPCs.

How AWS Site-to-Site VPN Works:

![img](https://d1.awsstatic.com/diagrams/product-page-diagram_Accelerated-Site-to-Site-VPN_How-it-Works@2x.89c94ea4b307abe21f82d9fd453fe3c72cacb2a3.png)

AWS Site-to-Site VPN enables you to securely connect your on-premises network or branch office site to your Amazon Virtual Private Cloud (Amazon VPC). VPN Connections are a good solution if you have an immediate need, and have low to modest bandwidth requirements. **This connection goes over the public internet.**

- Virtual private gateway (VGW) / Transit Gateway and Customer Gateway are the components of a VPC.

A virtual private gateway (VGW) is the VPN concentrator on the Amazon side of the AWS Site-to-Site VPN connection. A customer gateway is a resource in AWS that provides information to AWS about your Customer gateway device.

Components of an AWS Site-to-Site VPN:

![img2](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt3-q11-i1.jpg)
