# 0.9.0

 * Initial support for Kafka KRaft (run Kafka without Zookeeper).
   Try it with `python3 -m trivup.clusters.KafkaCluster --kraft 2.8.0`
 * Support for intermediate and self-signed certificates (by @KJTsanaktsidis).

# 0.8.4

 * KafkaCluster: Bump Confluent Platform to 6.1.0
 * KafkaCluster: add --cpversion argument

# 0.8.3

 * Bump Apache Kafka to 2.7.0
 * Bump Confluent Platform to 6.0.0
 * Add `port` alias for `port_base` in KafkaBrokerApp config

# 0.8.2

 * SchemaRegistryApp: Honour 'version' conf (defaults to 'latest' docker image,
   was 5.2.1).
 * Update Kerberos encoding types for newer Debian versions.
 * Newer OpenSSL requires at least 2048 bits in the RSA key.
