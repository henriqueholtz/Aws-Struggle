# Databases

[Back to index](Index.md)

| Type        | AWS services                     |
| ----------- | -------------------------------- |
| Relational  | Aurora, RDS, Redshift            |
| Key-value   | DynamoDB                         |
| In-Memory   | ElastiCache, MemoryDB for Redis  |
| Document    | DocumentDB (MongoDB compability) |
| Wide Column | Keyspaces                        |
| Graph       | Neptune                          |
| Time series | Timestream                       |
| Ledger      | Ledger Database Services (QLDB)  |

---

</br>

## Neptune

Serverless graph database (NoSQL) designed for superior scalability and availability;

---

</br>

## Amazon Aurora

- MySQL and PostgreSQL compatibility;
- You can't enable cross-Region replicas from multi-master clusters.
- Relational. Amazon Aurora does not support flexible schema. (requires a well-defined schema.)

---

</br>

## Amazon DocumentDB

- NoSQL & has compability with MongoDB;

---

</br>

## Amazon DynamoDB

- NoSQL
- Scalable without outage (down time)
- HA 3 DC's automatically
- DynamoDB is schemaless.
- DynamoDB can manage structured or semistructured data, including JSON documents.
- Can be enabled in-memory cache using **DynamoDB Accelerator (DAX)**

---

</br>

## Amazon ElastiCache

Database in-memory cache.

---

</br>

## Amazon Quantum Ledger Database (Amazon QLDB)

"Historical Database" that provides a transparent, immutable, and cryptographically verifiable transaction log owned by a central trusted authority. Amazon QLDB can be used to track each and every application data change and maintains a complete and verifiable history of changes over time.

---

</br>

## Amazon Relational Database Service (Amazon RDS)

- Support relational databases like Amazon Aurora with MySQL/PostgreSQL compatibility, MySQL, MariaDB, PostgreSQL, Oracle, and SQL Server;
- This is a regional service.
- Encryption can be enabled;
- You can enable read-replica to improve read-performance;
- You can enable Multi-AZ Secondary database which is replicated synchronously
- Read-Replica (RR) can be Multi AZs / Multi Regions
- AWS apply patches

---

</br>

## Amazon Redshift

- Serverless relational database;
- Encryption can be enabled for a cluster;

---

</br>

## Amazon Timestream

Serverless time series database service for IoT and operational applications that makes it easy to store and analyze trillions of events per day up to 1,000 times faster and at as little as 1/10th the cost of relational databases

---
