# Amazon Aurora

Amazon Aurora with multi-master cluster - Amazon Aurora (Aurora) is a fully managed relational database engine that's compatible with MySQL and PostgreSQL. With some workloads, Aurora can deliver up to five times the throughput of MySQL and up to three times the throughput of PostgreSQL without requiring changes to most of your existing applications. In a multi-master cluster, all DB instances have read/write capability. Currently, all DB instances in a multi-master cluster must be in the same AWS Region.

- You can't enable cross-Region replicas from multi-master clusters.
- Amazon Aurora does not support flexible schema. (requires a well-defined schema.)

You can use the standard "mysqldump" utility to export data from MySQL and "mysqlimport" utility to import data to Amazon Aurora, and vice-versa. You can also use Amazon RDS’s DB Snapshot migration feature to migrate an RDS MySQL DB Snapshot to Amazon Aurora using the AWS Management Console. Migration completes for most customers in under an hour, though the duration depends on format and data set size.
