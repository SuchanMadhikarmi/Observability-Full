# Observability in DevOps with Prometheus, Grafana, EFK, and Jaeger

# 💡 Introduction to Observability
- Observability is the ability to understand the internal state of a system by analyzing the data it produces, including logs, metrics, and traces.

- Monitoring(Metrics): involves tracking system metrics like CPU usage, memory usage, and network performance. Provides alerts based on predefined thresholds and conditions
    - `Monitoring tells us what is happening.`
- Logging(Logs):  involves the collection of log data from various components of a system.
    - `Logging explains why it is happening.`
- Tracing(Traces): involves tracking the flow of a request or transaction as it moves through different services and components within a system.
    - `Tracing shows how it is happening.`


tracing

 # 📌 Why Observability?

 - Metrics (Prometheus + Grafana): Is the system healthy? Are resources scaling correctly?

 - Logs (EFK): What errors are happening? Why is a service failing?

 - Traces (Jaeger): How do requests flow across multiple microservices? Where’s the bottleneck?


## 🚀 Prometheus
- Prometheus is an open-source systems monitoring and alerting toolkit originally built at SoundCloud.
- It is known for its robust data model, powerful query language (PromQL), and the ability to generate alerts based on the collected time-series data.
- It can be configured and set up on both bare-metal servers and container environments like Kubernetes.

  ## 📊 Grafana
- Grafana is a powerful dashboard and visualization tool that integrates with Prometheus to provide rich, customizable visualizations of the metrics data.

## 📦 EFK Stack (Elasticsearch, Fluentbit, Kibana)
- EFK is a popular logging stack used to collect, store, and analyze logs in Kubernetes.
- **Elasticsearch**: Stores and indexes log data for easy retrieval.
- **Fluentbit**: A lightweight log forwarder that collects logs from different sources and sends them to Elasticsearch.
- **Kibana**: A visualization tool that allows users to explore and analyze logs stored in Elasticsearch.

## 🕵️‍♂️ What is Jaeger?
- Jaeger is an open-source, end-to-end distributed tracing system used for monitoring and troubleshooting microservices-based architectures. It helps developers understand how requests flow through a complex system, by tracing the path a request takes and measuring how long each step in that path takes.



