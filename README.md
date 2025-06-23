# Apache Log Visualization using ELK Stack

A hands-on cybersecurity project that visualizes Apache server logs using the ELK Stack (Elasticsearch, Logstash, Kibana). Built and containerized using Docker.

## Overview

This project simulates real-world log ingestion and monitoring by:
- Parsing Apache logs using **Logstash**
- Storing structured logs in **Elasticsearch**
- Visualizing key trends in **Kibana**

## Tools Used
- **Docker** (for containerization)
- **Elasticsearch** (data storage)
- **Logstash** (log parsing)
- **Kibana** (visual dashboards)

## Visualizations Created

- ✅ Pie Chart – Breakdown of HTTP response codes (200, 404, 500)
- ✅ Line Graph – Requests over time (by timestamp)
- ✅ Bar Chart – Response status breakdown by time

These visualizations are included in the exported `.ndjson` file.
