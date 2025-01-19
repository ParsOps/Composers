# Composers

This project contains the usefull docker-compose files from Bitnami containers(https://github.com/Bitnami/containers) with some changes that make them ready to use in production environments that use docker-compose.

List:

1. Airflow: Apache Airflow + PostgreSQL + Redis + Flower + Scheduler + Worker + Exporter
2. Consul: Consul + UI + Exporter
3. Discourse: Discourse + PostgreSQL + Redis + Sidekiq + Postgres Exporter + Redis Exporter
4. Elasticsearch: Elasticsearch + Kibana + Filebeat + Metricbeat + Elasticsearch Exporter
5. Envoy: Envoy + Prometheus + Grafana + Envoy Exporter
6. ETCD: ETCD + ETCD Exporter
7. Gitlab: Gitlab + PostgreSQL + Redis + Sidekiq + Exporter
8. Grafana: Grafana
9. HAProxy: HAProxy + HAProxy Exporter
10. Jaeger: Jaeger + Collector + Query + Agent + Exporter
11. Jenkins: Jenkins + Exporter
12. Jupyterhub: Jupyterhub + PostgreSQL + Redis + Cull + Exporter
13. Kafka: Kafka + Zookeeper + Kafka Exporter
14. Keycloak: Keycloak + PostgreSQL + Exporter
15. Kong: Kong + PostgreSQL + Cassandra + Kong Exporter
16. Mastodon: Mastodon + PostgreSQL + Redis + Sidekiq + Exporter
17. Matomo: Matomo + MySQL + Matomo Exporter
18. Minio: Minio + Minio Exporter
19. MongoDB: MongoDB + MongoDB Exporter
20. MySQL: MySQL + MySQL Exporter
21. Nats: Nats + Nats Exporter
22. Nginx: Nginx + Nginx Exporter
23. PostgreSQL: PostgreSQL + PostgreSQL Exporter
24. PromStack: Prometheus + Grafana + Alertmanager + Node Exporter + Blackbox Exporter + Pushgateway + Exporter
25. RabbitMQ: RabbitMQ + RabbitMQ Exporter
26. Redis: Redis + Redis Exporter
27. Sonarqube: Sonarqube + PostgreSQL + Sonarqube Exporter
28. Spark: Spark + Hadoop + Spark Exporter

## How to use
I use an Ansible role to deploy the docker-compose files. You can find the role here:
