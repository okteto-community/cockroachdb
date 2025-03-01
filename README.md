# Okteto with CockroachDB Cloud 
CockroachDB Cloud is the distributed SQL platform built to support your workloads at every stage, from dev/test environments to enterprise-critical production applications. It provides the flexibility, security, and scalability to grow with your business as demands evolve.

Use this as a dependency to automatically create a database and a user in your CockroachDB Cloud Cluster as part of your development environments. 

## How to use it

This dependency creates two secrets in your namespace.
- `okteto-cockroachdb`: The `username`, `password`, `database`, `host`, and `port` of the CockroachDB Cloud database.
- `okteto-cockroachdb-ca`: The CA of your CockroachDB Cloud manifest, mount it in your services to trust the cluster.