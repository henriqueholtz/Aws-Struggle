# AWS Elastic Load Balancing (ELB)

- Application Load Balancer (ALB)
- Network Load Balancer (NLB)

## Application Load Balancer (ALB) - OSI

- Layer 7
- Best suited to HTTPS and HTTPS traffic;

Elastic Load Balancing (ELB) is used to automatically distribute your incoming application traffic across all the EC2 instances that you are running. You can use Elastic Load Balancing to manage incoming requests by optimally routing traffic so that no one instance is overwhelmed. Your load balancer acts as a single point of contact for all incoming web traffic to your application. When an instance is added, it needs to register with the load balancer or no traffic is routed to it. When an instance is removed, it must deregister from the load balancer or traffic continues to be routed to it.

Application Load Balancer is used for load balancing of HTTP and HTTPS traffic and provides advanced request routing targeted at the delivery of modern application architectures, including microservices and containers.

- It distributes traffic, does not scale resources. (ex: to scale out EC2 use "Amazon EC2 Auto Scaling")

Can be:

- Path based
- Host based

Can appoint to:

- Instances (IP)
- Lamba
- Containers
- Targets

## Network Load Balancer

Network Load Balancer is best suited for load balancing of Transmission Control Protocol (TCP), User Datagram Protocol (UDP) and Transport Layer Security (TLS) traffic where extreme performance is required.

- Transport layer (4) - OSI
- High performance + low latency
