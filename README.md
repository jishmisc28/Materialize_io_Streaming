# Materialize_io_Streaming

Scripts I have wrote for setting up and testing Materialize.io on the EC2 instances running Kafka.
This would create Materialize.io streaming table objects which could be used to incrementally update the materialize views over the payload and make it queryable.

Kafka cluster - 3 instances
Debezium connector - for postgres/RDS
Materialize instance - running on same/separate EC2 instance

