# Network Access Control List (Network ACL)

Network Access Control List (Network ACL) acts as a firewall at the subnet level

A network access control list (network ACL) is an optional layer of security for your VPC that acts as a firewall for controlling traffic in and out of one or more subnets (i.e. it works at subnet level). A network ACL has separate inbound and outbound rules, and each rule can either allow or deny traffic.

network access control list (network ACL) Overview:

- N NACL x Subnet 1
- Order 0 is hight priority than 10;
- Allow and deny rules;
- Inbound and outbound rules;

A network access control list (network ACL) contains a numbered list of rules. A network access control list (network ACL) evaluates the rules in order, starting with the lowest numbered rule, to determine whether traffic is allowed in or out of any subnet associated with the network ACL. The highest number that you can use for a rule is 32766. AWS recommends that you start by creating rules in increments (for example, increments of 10 or 100) so that you can insert new rules where you need to later on

![img](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt1-q42-i2.jpg)

![img2](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt2-q52-i2.jpg)
