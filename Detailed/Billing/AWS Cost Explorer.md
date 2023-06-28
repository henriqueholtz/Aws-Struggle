# AWS Cost Explorer

AWS Cost Explorer has an easy-to-use interface that lets you visualize, understand, and manage your AWS costs and usage over time. AWS Cost Explorer includes a default report that helps you visualize the costs and usage associated with your top five cost-accruing AWS services, and gives you a detailed breakdown of all services in the table view. The reports let you adjust the time range to view historical data going back up to twelve months to gain an understanding of your cost trends. AWS Cost Explorer cannot provide the estimate of the monthly AWS bill based on the list of AWS services.

AWS Cost Explorer lets you explore your AWS costs and usage at both a high level and at a detailed level of analysis, and empowering you to dive deeper using many filtering dimensions (e.g., AWS Service, Region, Linked Account). It's a handy tool to keep track of costs of AWS resources, but auto-scaling is not part of its feature set.

The rightsizing recommendations feature in AWS Cost Explorer helps you identify cost-saving opportunities by downsizing or terminating Amazon EC2 instances. You can see all of your underutilized Amazon EC2 instances across member accounts in a single view to immediately identify how much you can save.

AWS Cost Explorer also supports forecasting to get a better idea of what your costs and usage may look like in the future so that you can plan.

- Explorer cannot provide a detailed report of your AWS costs by the hour into an Amazon S3 bucket.
- AWS Cost Explorer cannot be used to identify under-utilized Amazon EC2 instances.
- Billing alarms cannot be triggered via AWS Cost Explorer.
- It cannot be used to compare the cost of running the IT infrastructure on-premises vs AWS Cloud.

AWS Cost Explorer Features:

![img0](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt4-q47-i1.jpg)

AWS Cost Explorer Reports:

![img](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt2-q37-i2.jpg)

Exam Alert:

Watch out for questions on AWS Cost Explorer vs AWS Budgets. AWS Budgets can alert you when your costs exceed your budgeted amount. Cost Explorer helps you visualize and manage your AWS costs and usage over time.

---

- AWS Cost Explorer also gives you access to a set of default reports to help you get started, while also allowing you to create custom reports from scratch.
- Customers can receive Savings Plan recommendations at the member (linked) account level in addition to the existing AWS organization-level recommendations in AWS Cost Explorer
- AWS Cost Explorer cannot provide granular billing details for the past month.

You can explore your usage and costs using the main graph, the Cost Explorer cost, and usage reports, or the Cost Explorer RI report. You can view data for up to the last 12 months, forecast how much you're likely to spend for the next 12 months, and get recommendations for what Reserved Instances to purchase. You can use Cost Explorer to identify areas that need further inquiry and see trends that you can use to understand your costs.

You can view your costs and usage using the Cost Explorer user interface free of charge. You can also access your data programmatically using the Cost Explorer API.

When you first sign up for Cost Explorer, AWS prepares the data about your costs for the current month and the last 12 months and then calculates the forecast for the next 12 months. The current month's data is available for viewing in about 24 hours. The rest of your data takes a few days longer. Cost Explorer updates your cost data at least once every 24 hours. After you sign up, Cost Explorer can display up to 12 months of historical data (if you have that much), the current month, and the forecasted costs for the next 12 months.
