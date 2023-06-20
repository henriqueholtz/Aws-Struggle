# Application Load Balancer (ELB)

Elastic Load Balancing (ELB) is used to automatically distribute your incoming application traffic across all the EC2 instances that you are running. You can use Elastic Load Balancing to manage incoming requests by optimally routing traffic so that no one instance is overwhelmed. Your load balancer acts as a single point of contact for all incoming web traffic to your application. When an instance is added, it needs to register with the load balancer or no traffic is routed to it. When an instance is removed, it must deregister from the load balancer or traffic continues to be routed to it.

Application Load Balancer is used for load balancing of HTTP and HTTPS traffic and provides advanced request routing targeted at the delivery of modern application architectures, including microservices and containers.

- It distributes traffic, does not scale resources. (ex: to scale out EC2 use "Amazon EC2 Auto Scaling")
