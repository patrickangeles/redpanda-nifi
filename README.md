# redpanda-nifi
Redpanda + NiFi on Docker Compose

Just a quick `docker-compose.yml` to show how Redpanda can integrate with Ni-Fi.

The Kafka API is accessible via:
- `redpanda:29092` from inside the Docker Compose network
- `localhost:9092` from the host OS

The Redpanda admin port is `9644`.

The Ni-FI UI is at http://localhost:8080/nifi
