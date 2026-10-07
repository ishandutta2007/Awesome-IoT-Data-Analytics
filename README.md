# Awesome-IoT-Data-Analytics

# Top IoT Data Analytics Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Time-Series Analytics, Stream Processing & Self-Hosted IoT Data Platforms*  
**Last updated: October 2026**

This repository tracks notable **commercial IoT data analytics platforms** and **open-source projects** that ingest, store, analyze, and visualize device telemetry at scale — powering predictive maintenance, anomaly detection, operational dashboards, and industrial intelligence.

**Examples** include AWS IoT Analytics, Azure Stream Analytics, Google Cloud IoT Analytics, PTC ThingWorx, Datadog IoT, Software AG Cumulocity IoT, AWS IoT SiteWise, Samsara, ClearBlade, and Omnition IoT (the category leaders).

**Open-source emphasis**: IoT data analytics is one of the strongest open-source domains. **ThingsBoard** leads as the most popular open-source IoT platform with 17,000+ GitHub stars and comprehensive rule engine capabilities . **Apache Superset** brings SQL-native business intelligence with drag-and-drop dashboards . **Grafana** provides unified dashboards across 100+ data sources . **TDengine** delivers purpose-built time-series storage with high-performance ingestion and compression . **Apache Flink** and **ksqlDB** handle stateful stream processing with exactly-once semantics . **Magistrala** offers a cloud-native IoT framework with data processing and visualization . **QuestDB** and **TimescaleDB** provide high-performance time-series databases for IoT telemetry . This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[AWS IoT Analytics](https://aws.amazon.com/iot-analytics/)**  
  **AWS's fully managed IoT analytics service** — collect, preprocess, enrich, store, and analyze IoT data at scale . **Automated data processing with channels, pipelines, and datasets** . **Built-in SQL query engine and Jupyter notebook integration for advanced analytics** . **Best for AWS-native IoT data pipelines** . **Note**: Amazon IoT Analytics is no longer available to new customers as of July 2024; existing customers can continue using the service .

- **[Azure Stream Analytics](https://azure.microsoft.com/en-us/products/stream-analytics/)**  
  **Microsoft's real-time analytics service** — SQL-like queries on streaming data from IoT devices, applications, and sensors . **Sub-millisecond latency with built-in machine learning functions** . **Event ordering and temporal joins for complex event processing** . **Best for Azure-native IoT stream processing** .

- **[AWS IoT SiteWise](https://aws.amazon.com/iot-sitewise/)**  
  **AWS's industrial IoT data platform** — collect, organize, and analyze data from industrial equipment at scale . **Asset modeling with hierarchical equipment relationships** . **Built-in metrics and transforms for real-time calculations** . **Best for industrial equipment monitoring** .

- **[PTC ThingWorx](https://www.ptc.com/)**  
  **Industrial IoT platform** — IoT solutions, AR, and data analytics with event-driven processing . **Enterprise licensing varies** . **Best for industrial IoT applications** .

- **[Datadog IoT](https://www.datadoghq.com/)**  
  **Observability platform with IoT monitoring** — infrastructure metrics, logs, and alerts for device fleets . **Best for unified observability across IoT and cloud** .

- **[Software AG Cumulocity IoT](https://cumulocity.com/)**  
  **Enterprise IoT platform with streaming analytics** — Apama complex event processing for real-time data analysis . **Best for enterprise IoT with real-time analytics** .

- **[Google Cloud IoT Analytics](https://cloud.google.com/solutions/iot)**  
  **Google's IoT analytics solutions** — Pub/Sub, Dataflow, BigQuery, and Looker for IoT data pipelines . **Best for GCP-native IoT analytics** .

- **[Samsara](https://www.samsara.com/)**  
  **Connected operations platform** — fleet telematics, equipment monitoring, and video safety . **Best for fleet and industrial operations** .

- **[ClearBlade](https://clearblade.com/)**  
  **Enterprise IoT platform with data analytics** — event processing and rules engine . **Best for enterprise IoT analytics** .

- **[Omnition IoT](https://www.omnition.io/)**  
  **IoT observability platform** — monitor and troubleshoot IoT device fleets .

## Open-Source GitHub Projects

### IoT Platforms with Analytics

- **[ThingsBoard](https://github.com/thingsboard/thingsboard)**  
  **The most popular open-source IoT platform with 17,000+ GitHub stars**, Apache-2.0 licensed . **Device management, data collection, processing, and visualization** . **Rule Engine for event-based workflows** — trigger actions on device data, alarms, and schedules . **Multi-tenancy with RBAC** — manage multiple organizations from one instance . **Supports MQTT, CoAP, HTTP, LwM2M, SNMP** with dashboards and device management . **Security**: Two-Factor Authentication, OAuth 2.0, Access Tokens, X.509 Certificates, SSL, DTLS . **Trade-offs**: Can be resource-heavy; Community edition lacks many Professional features . **Best for comprehensive IoT platform with analytics** .

- **[Magistrala](https://github.com/absmach/magistrala)**  
  **Modern, Go-based, cloud-native IoT platform framework** (formerly Mainflux), Apache-2.0 licensed . **Data processing and visualization capabilities** . **Small number of main concepts**: users, devices, channels, messages, policies . **Atom integration model** provides identity, authorization, and catalog with workspaces (tenants), entities, resources, and groups . **Fine-grained access control** — define object-scoped roles like "reader on channel1" . **Scales from simple prototypes to complex deployments** . **Trade-offs**: No built-in dashboard (available via plugins); community support still catching up to Java-based platforms . **Best for high-performance, cloud-native IoT data processing** .

### Business Intelligence & Dashboards

- **[Apache Superset](https://github.com/apache/superset)**  
  **Open-source modern data exploration and visualization platform**, Apache-2.0 licensed with **60,000+ GitHub stars** . **Superset 5.0 provides a rich set of data visualizations** and an easy-to-use interface for creating and sharing dashboards . **SQL IDE with Jinja templating, semantic layer, and advanced analytics** . **Superset MCP server** enables LLM access to datasets, charts, and dashboards for intelligent analytics . **Intelligence layer** enables AI agents to explore all company data with definition-level access control . **Best for open-source business intelligence** .

- **[Grafana](https://github.com/grafana/grafana)**  
  **The de facto standard for open-source dashboards**, AGPL-3.0 licensed with **65,000+ GitHub stars** . **Connects to 100+ data sources including Prometheus, Loki, Tempo, Elasticsearch, PostgreSQL, and more** . **Rich visualization library with alerting, annotations, and templating** . **Best for unified IoT observability dashboards** .

- **[Metabase](https://github.com/metabase/metabase)**  
  **Open-source BI and analytics**, AGPL-3.0 licensed with **40,000+ GitHub stars** . **No-code question builder for business users** . **Best for self-service analytics** .

- **[Redash](https://github.com/getredash/redash)**  
  **Open-source data visualization**, BSD-2-Clause licensed with **25,000+ GitHub stars** . **SQL-based dashboards with collaboration** . **Best for SQL-driven dashboards** .

### Time-Series Databases

- **[TDengine](https://github.com/taosdata/TDengine)**  
  **Purpose-built time-series database for IoT**, AGPL-3.0 licensed with **23,000+ GitHub stars** . **High-performance ingestion and compression** . **Built-in caching, stream processing, and data subscription** . **Best for IoT and industrial telemetry** .

- **[TimescaleDB](https://github.com/timescale/timescaledb)**  
  **PostgreSQL-based time-series database**, Apache-2.0/Timescale License with **18,000+ GitHub stars** . **Full SQL with time-series hyperfunctions** . **Continuous aggregates and compression** . **Best for PostgreSQL users needing time-series** .

- **[QuestDB](https://github.com/questdb/questdb)**  
  **High-performance time-series database**, Apache-2.0 licensed with **14,000+ GitHub stars** . **SQL with time-series extensions** — SIMD-optimized . **The fastest open-source time-series database** for ingestion . **Best for high-throughput IoT ingestion** .

- **[InfluxDB](https://github.com/influxdata/influxdb)**  
  **The leading open-source time-series database**, MIT licensed with **29,000+ GitHub stars** . **InfluxQL and Flux query languages** . **Built-in downsampling and retention policies** . **Best for IoT and observability** .

- **[Apache IoTDB](https://github.com/apache/iotdb)**  
  **IoT-native time-series database**, Apache-2.0 licensed with **5,000+ GitHub stars** . **Optimized for industrial IoT with high-throughput ingestion** . **Best for industrial IoT deployments** .

- **[VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics)**  
  **High-performance, cost-effective time-series database**, Apache-2.0 licensed with **12,000+ GitHub stars** . **Prometheus-compatible with better performance and compression** . **Best for scalable metrics storage** .

### Stream Processing

- **[Apache Flink](https://github.com/apache/flink)**  
  **The de facto standard for stateful stream processing**, Apache-2.0 licensed with **24,000+ GitHub stars** . **Exactly-once semantics, event-time processing, and savepoints** . **Best for mission-critical IoT stream processing** .

- **[Apache Kafka](https://github.com/apache/kafka)**  
  **Event streaming platform**, Apache-2.0 licensed with **28,000+ GitHub stars** . **Distributed pub/sub with persistence** . **Kafka Streams and ksqlDB for stream processing** . **Best for high-throughput IoT event streaming** .

- **[ksqlDB](https://github.com/confluentinc/ksql)**  
  **Streaming SQL for Kafka**, Confluent Community License . **SQL interface for Kafka Streams** . **Best for SQL-proficient IoT teams** .

- **[Apache Spark Structured Streaming](https://github.com/apache/spark)**  
  **Unified batch and stream processing**, Apache-2.0 licensed . **Micro-batch with exactly-once semantics** . **Best for teams already using Spark** .

- **[Apache Beam](https://github.com/apache/beam)**  
  **Unified programming model for batch and stream**, Apache-2.0 licensed . **Portable across Flink, Spark, and Dataflow** . **Best for portable IoT pipelines** .

### Additional Strong Open-Source Options

- **Apache NiFi** — Data flow automation with visual programming .
- **Benthos (Redpanda Connect)** — Stream processing without code .
- **Vector** — Observability data pipeline .
- **Fluentd** — Unified logging layer .
- **Fluent Bit** — Lightweight log processor .
- **Node-RED** — Flow-based programming for IoT .
- **Apache Druid** — Real-time analytics database .
- **Apache Pinot** — Real-time distributed OLAP .
- **ClickHouse** — Columnar analytical database .

**Frameworks for building custom IoT data analytics solutions**: Combine **ThingsBoard** for comprehensive IoT platform with rule engine and visualization . Use **Apache Superset** or **Grafana** for dashboards and business intelligence . Deploy **TDengine**, **TimescaleDB**, or **QuestDB** for high-performance time-series storage . Choose **Apache Flink** or **ksqlDB** for stateful stream processing . Integrate **Apache Kafka** for high-throughput event streaming . Use **Magistrala** for cloud-native IoT data processing with fine-grained access control . Note that true managed IoT analytics with global infrastructure, automatic scaling, and vendor-supported SLAs (AWS IoT Analytics, Azure Stream Analytics, Cumulocity) remains primarily commercial territory; open-source stacks provide strong time-series storage, stream processing, and visualization foundations that require integration for complete IoT data analytics.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- IoT data analytics platforms handle device telemetry that may include sensitive operational data. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.
- **AWS IoT Analytics is no longer available to new customers** as of July 2024 — existing customers can continue using the service . Consider alternatives for new deployments.
- **Cardinality is the primary scaling challenge** for time-series data — high-cardinality device metrics can overwhelm databases. Design schemas and retention policies accordingly .
- **License considerations**: ThingsBoard uses Apache-2.0, Superset uses Apache-2.0, Grafana uses AGPL-3.0, TDengine uses AGPL-3.0, TimescaleDB uses Apache-2.0/Timescale License, and QuestDB uses Apache-2.0. Verify licensing against your use case before committing.
- The open-source ecosystem provides strong time-series storage, stream processing, and visualization foundations, but **managed infrastructure, automatic scaling, and vendor-supported SLAs** remain primarily commercial offerings.

---

**Made for IoT engineers, data analysts, and organizations seeking IoT data analytics sovereignty.**  
Let's make IoT data analytics more open, transparent, and scalable.
