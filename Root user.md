# Root user

The Email address and the password used for signing up for AWS services are the AWS root user account credentials. Root user account, therefore, has full permissions on all AWS resources under that account. Restricting root user account access is not possible. As a best practice, Multi-Factor Authentication (MFA) should be set on the root user account. The root user account password can be changed after account creation. For all employees performing various administrative jobs, create individual user accounts using AWS IAM, and give administrative permissions as needed.

AWS Root User Account Security Best Practices:

![img1](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt2-q54-i2.jpg)

![img2](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt2-q54-i1.jpg)

---

To send alerts whenever the AWS account root user signs in, you can create an Amazon Simple Notification Service (Amazon SNS) topic. Then, create an Amazon CloudWatch event rule to monitor userIdentity root logins from the AWS Management Console and send an email via Amazon SNS when the event triggers.
