# Local Redpanda Cluster with Docker Compose

Sets up a local Redpanda cluster with 3 nodes.

To run it:

```bash
docker compose up -d
```

There is no authentication.

Connect to Kafka with `KAFKA_BROKERS` set to `rp1:9092,rp2:9093,rp3:9094`.