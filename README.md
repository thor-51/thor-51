<div align="center">

# Hey, I'm Aryan 👋

*Curious about the journey of a request - from a click on a screen to servers across the world.*

![Profile Views](https://komarev.com/ghpvc/?username=thor-51&color=blueviolet&style=for-the-badge&label=PROFILE+VIEWS)

</div>

<br>

- 🎓 CS student @ **VIT Vellore**
- 🛠️ Building **backend & distributed systems**, with a growing focus on **AI engineering**
- 🔐 Currently deep in **secure-file-vault** - encrypted storage, RBAC, audit logging
- 📡 Also shipped a **real-time observability stack** (Grafana + Prometheus + Loki) for Node apps
- 🌱 Learning how to take projects from "it works" to "people actually use it"
- 💬 Ask me about system design, backend architecture, or LLM fine-tuning

<br>

## 🔭 What I'm Building

### 💸 [FlowPay](https://github.com/thor-51/FlowPay) - Featured Project

A production-style, event-driven payment transfer system built with **Java 21** and **Spring Boot 3**. Transfers hit a REST API, get published to **Kafka**, and are processed asynchronously - debiting/crediting accounts with **Redis-backed idempotency**, exponential-backoff retry, dead-lettering, and full **Prometheus/Grafana** observability.

- ⚡ Load-tested at **577 TPS** with 0.00% error rate (p99 latency: 140.6ms, can handle ~49M transactions/day)
- 🔒 Deadlock-safe account locking, atomic idempotency via Redis `SETNX`
- 📊 9-panel auto-provisioned Grafana dashboard + structured JSON logging (ELK-ready)
- 🧪 40 tests across unit, slice, and Testcontainers-backed integration suites

<br>

<table>
<tr>
<td width="50%" valign="top">

**[🔐 secure-file-vault](https://github.com/thor-51/secure-file-vault)**
Encrypted S3-backed file storage with JWT auth, role-based access control, deduplication, and full audit logging.

</td>
<td width="50%" valign="top">

**[📡 Real-Time-Observability-Platform](https://github.com/thor-51/Real-Time-Observability-Platform)**
A monitoring stack for Node.js apps — Grafana, Prometheus, and Loki wired together for live metrics and logs.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[🚗 Ride-Booking-Platform](https://github.com/thor-51/Ride-Booking-Platform)**
Full-stack, Uber-style ride booking app with real-time ride management.

</td>
<td width="50%" valign="top">

**[🧪 AdaLoRA-Bench](https://github.com/thor-51/AdaLoRA-Bench)**
Benchmarking parameter-efficient fine-tuning methods for LLMs.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[🔍 Grep](https://github.com/thor-51/Grep)**
A Python reimplementation of `grep`, extended with extra features.

</td>
<td width="50%" valign="top">

</td>
</tr>
</table>

<br>

## 🧰 Tech Stack

**Languages**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-02569B?style=for-the-badge)

**Databases & Caching**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**DevOps & Cloud**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
/*![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)*/
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-000000?style=for-the-badge&logo=apachekafka&logoColor=white)

**AI & Machine Learning**

![LLM](https://img.shields.io/badge/LLM-FF6F00?style=for-the-badge)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

**Testing & Monitoring**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-78A641?style=for-the-badge&logo=mockito&logoColor=white)

<br>

## 📈 GitHub Analytics

<div align="center">

<img src="https://streak-stats.demolab.com?user=thor-51&theme=tokyonight&include_all_commits=true&count_private=true" />

</div>

<br>

<div align="center">

*"First make it work.*
*Then make it scalable.*
*Then make it elegant."*

⭐️ If something here is useful to you, a star means a lot.

</div>
