# MongoDB vs. Apache Cassandra for Smart Traffic Management Systems

A comparative study of two leading NoSQL databases for the data demands of modern Smart Traffic Management Systems (STMS), based on a systematic literature review and culminating in a proposed hybrid architecture.

[![Research Paper](https://img.shields.io/badge/Read-Research%20Paper-blue)](./researchpaper.pdf)
[![Presentation](https://img.shields.io/badge/View-Presentation-orange)](./MongoDB_vs_Cassandra_STMS_Presentation%20%282%29.pdf)


---

## Table of Contents

- [Overview](#overview)
- [Research Methodology](#research-methodology)
- [Comparison Dimensions](#comparison-dimensions)
- [Proposed Hybrid Architecture](#proposed-hybrid-architecture)
- [Research Contribution](#research-contribution)
- [Future Research Directions](#future-research-directions)
- [Repository Contents](#repository-contents)
- [Author](#author)

---

## Overview

Smart Traffic Management Systems generate large volumes of heterogeneous data, from signal-control records and incident reports to continuous sensor and GPS telemetry. Choosing the right database for each workload is a critical design decision.

This project evaluates **MongoDB** and **Apache Cassandra** across six dimensions:

- Data modeling
- Read/write performance
- Scalability
- Consistency
- Fault tolerance
- Cost of ownership

**Keywords:** NoSQL · MongoDB · Apache Cassandra · Smart Traffic Management · Scalability · Fault Tolerance · High-Volume Sensor Data

---

## Research Methodology

The study is a **systematic literature review of 15 peer-reviewed papers** published between **2016 and 2025**, carried out in six stages:

| Stage | Description |
|-------|-------------|
| 1. Literature Review | Collection and screening of peer-reviewed studies |
| 2. Gap Identification | Identifying limitations in existing research |
| 3. Feature Extraction | Extracting and comparing database characteristics |
| 4. Database Design | Designing data models for STMS workloads |
| 5. Comparative Analysis | Evaluating both databases across all dimensions |
| 6. Architecture Proposal | Designing a hybrid, workload-aware solution |

---

## Comparison Dimensions

| Dimension | Focus |
|-----------|-------|
| Data Modeling | Schema flexibility, document vs. wide-column design |
| Performance | Read/write behavior under high-volume load |
| Scalability | Horizontal scaling and data distribution |
| Consistency | Consistency guarantees and trade-offs |
| Fault Tolerance | Availability and resilience to failures |
| Cost of Ownership | Operational and infrastructure costs |

---

## Proposed Hybrid Architecture

The research proposes assigning each database to the workload it handles best:

| Component | Role |
|-----------|------|
| **MongoDB** | Transactional traffic-control data, signals, metadata, and incidents |
| **Apache Cassandra** | High-throughput sensor and GPS telemetry |
| **Apache Kafka** | Data-ingestion pipeline |
| **Federated Query Layer** | Unified cross-database data access |

---

## Research Contribution

This work shows how different NoSQL technologies can be combined according to their individual strengths within a single STMS, rather than relying on one database for every workload. It also identifies open areas for further investigation.

## Future Research Directions

- AI integration
- Edge deployment
- Automated data lifecycle management
- Digital twins

---

## Repository Contents

| File | Description |
|------|-------------|
| [`researchpaper.pdf`](./researchpaper.pdf) | Full research paper |
| [`MongoDB_vs_Cassandra_STMS_Presentation (2).pdf`](./MongoDB_vs_Cassandra_STMS_Presentation%20%282%29.pdf) | Research presentation |

---

## Author

**Tanisha Patel**
Integrated MSc.IT
Department of Computer Science and Information Technology
Vanita Vishram Women's University
