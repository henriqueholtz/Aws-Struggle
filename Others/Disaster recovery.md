# Disaster recovery

When selecting your disaster recovery (DR) strategy, you must weigh the benefits of lower RTO (recovery time objective) and RPO (recovery point objective) vs the costs of implementing and operating a strategy. The pilot light and warm standby strategies both offer a good balance of benefits and cost.

Disaster recovery (DR) strategies:

![img](https://assets-pt.media.datacumulus.com/aws-clf-pt/assets/pt4-q56-i1.jpg)

## Warm Standby strategy (DR)

This strategy replicates data from the primary Region to data resources in the recovery Region, such as Amazon Relational Database Service (Amazon RDS) DB instances or Amazon DynamoDB tables. These data resources are ready to serve requests. In addition to replication, this strategy requires you to create a continuous backup in the recovery Region. This is because when "human action" type disasters occur, data can be deleted or corrupted, and replication will replicate the bad data. Backups are necessary to enable you to get back to the last known good state.

The warm standby strategy deploys a functional stack, but at reduced capacity. The DR endpoint can handle requests, but cannot handle production levels of traffic. It may be more, but is always less than the full production deployment for cost savings. If the passive stack is deployed to the recovery Region at full capacity, however, then this strategy is known as “hot standby.” Because warm standby deploys a functional stack to the recovery Region, this makes it easier to test Region readiness using synthetic transactions.

## Multi-site active-active strategy

This strategy uses AWS Regions as your active sites, creating a multi-Region active/active architecture. Generally, two Regions are used. Each Region hosts a highly available, multi-Availability Zone (AZ) workload stack. In each Region, data is replicated live between the data stores and also backed up. This protects against disasters that include data deletion or corruption since the data backup can be restored to the last known good state. Each regional stack serves production traffic effectively. But, this strategy is cost involving and should only be used for mission-critical applications.

## Pilot Light strategy

Pilot Light, like Warm Standby strategy, replicates data from the primary Region to data resources in the recovery Region, such as Amazon Relational Database Service (Amazon RDS) DB instances or Amazon DynamoDB tables. But, the DR Region in a pilot light strategy (unlike warm standby) cannot serve requests until additional steps are taken. A pilot light in a home furnace does not provide heat to the home. It provides a quick way to light the furnace burners that then provide heat.

Warm standby can handle traffic at reduced levels immediately. Pilot light requires you to first deploy infrastructure and then scale out resources before the workload can handle requests.

# Backup & Restore strategy

Backup and Restore is associated with higher RTO (recovery time objective) and RPO (recovery point objective). This results in longer downtimes and greater loss of data between when the disaster event occurs and recovery. However, backup and restore can still be the right strategy for workloads because it is the easiest and least expensive strategy to implement.
