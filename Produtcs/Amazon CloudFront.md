# Amazon CloudFront

- Edge location isn't an AZ neither a region. For example currently AWS has 31 regions 99 AZs, but have 400+ edge locations [see details](https://aws.amazon.com/about-aws/global-infrastructure/)
- HTTP/HTTPS;
- Custom domain (your own);
- Integration with Shield, WAF, S3, etc...

Amazon CloudFront is a fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency, high transfer speeds, all within a developer-friendly environment. It cannot be used to improve application availability and performance using the AWS global network.

You can use Amazon CloudFront to improve the performance of your website. Amazon CloudFront makes your website files (such as HTML, images, and video) available from data centers around the world (called edge locations). When a visitor requests a file from your website, Amazon CloudFront automatically redirects the request to a copy of the file at the nearest edge location. This results in faster download times than if the visitor had requested the content from a data center that is located farther away

Exam Alert:

Please review the differences between Amazon CloudFront and AWS Global Accelerator:

![imgdifference](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt2-q56-i2.jpg)
