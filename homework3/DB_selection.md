Kafka or RedPanda as broker.

Camunda 7 runs on PostgreSQL. History DB - separate PgSQL instance.

Feast for ML features

All other will use Tarantool:
- in-memory (instead of Redis)
- SQLlike syntax
- Key-Value
