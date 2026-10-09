# Advanced High Level Design Topics

In-depth topics that build on the [fundamentals](../fundamentals/README.md). These are specialized notes for when you need deeper coverage in an interview or design discussion.

## Contents

| Topic                                                        | Key Concepts                                                                |
| ------------------------------------------------------------ | --------------------------------------------------------------------------- |
| [OAuth 2.0](./01-oauth2.md)                                  | Authorization code flow with PKCE, token validation, scopes, OpenID Connect |
| [Multi-Region Replication](./02-multi-region-replication.md) | Active-active vs active-passive, RPO/RTO, geo-partitioning, split-brain     |
| [MapReduce](./03-mapreduce.md)                               | Map/shuffle/reduce, combiners, data locality, fault tolerance, data skew    |
| [Peer-to-Peer Networks](./04-peer-to-peer-networks.md)       | DHTs, Kademlia routing, gossip protocol, churn handling, NAT traversal      |
| [Kafka Architecture](./05-kafka-architecture.md)             | Distributed log, ISR, leader-epoch fencing, cross-cluster replication       |
| [PostgreSQL Internals](./06-postgresql-internals.md)         | Heap storage, MVCC, write-ahead log, buffer cache, query planner            |
| [Distributed File Systems](./07-distributed-file-systems.md)               | GFS/HDFS model, chunking, metadata, replication           |

---

**Tip**: Each topic includes a reference materials section with curated external resources for deeper exploration.
