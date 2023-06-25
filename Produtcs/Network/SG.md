# Security Group

- Security Group acts as a firewall at the instance level (ex: eth0);
- Security groups are the responsibility of the customer.
- Only allow rules;
- Inbound and outbound rules;
- stateful;

A security group acts as a virtual firewall for your instance to control inbound and outbound traffic. Security groups act at the instance level, not at the subnet level. You can specify allow rules, but not deny rules. You can specify separate rules for inbound and outbound traffic.

Security groups are **stateful** — if you send a request from your instance, the response traffic for that request is allowed to flow in regardless of inbound security group rules. A security group evaluates all rules before deciding whether to allow traffic.

Security Group Overview:

![img](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt1-q42-i1.jpg)
