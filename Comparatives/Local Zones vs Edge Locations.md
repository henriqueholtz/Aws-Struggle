# Local Zones vs Edge Locations

## Local Zones

- AWS Local Zones place compute, storage, database, and other select AWS services closer to end-users.
- use Case -> Applications which require single-digit millisecond latencies to your end-users, latency-sensitive applications

## Ege Locations

- A site that CloudFront uses to cache copies of your content for faster delivery to users at any location.Edge Locations are usually deployed in major cities and highly populated areas across the globe. There are more edge locations than regions.
- Edge locations serve requests for CloudFront and Route 53. CloudFront is a content delivery network, while Route 53 is a DNS service. Requests going to either one of these services will be routed to the nearest edge location automatically. This allows for low latency no matter where the end user is located.'
