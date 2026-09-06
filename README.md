# Hi, I'm Hoang 👋

Computer Science student interested in Backend Engineering,
Distributed Systems and Cloud Native technologies.

## About Me

- 🎓 Computer Science student
- 🔭 Currently working in Viettel High Tech
- ⚡ Interested in Backend Infrastructure and System Design

## Tech Stack ⚙️

> Technologies I work with and continuously explore.

<table>
<tr>

<td align="center" width="96">
  <img src="https://skillicons.dev/icons?i=go" width="48" height="48" alt="Go" />
  <br>Go
</td>

<td align="center" width="96">
  <img src="https://skillicons.dev/icons?i=java" width="48" height="48" alt="Java" />
  <br>Java
</td>

<td align="center" width="96">
  <img src="https://skillicons.dev/icons?i=cpp" width="48" height="48" alt="C++" />
  <br>C++
</td>

<td align="center" width="96">
  <img src="https://skillicons.dev/icons?i=python" width="48" height="48" alt="Python" />
  <br>Python
</td>

<td align="center" width="96">
  <img src="https://skillicons.dev/icons?i=postgres" width="48" height="48" alt="PostgreSQL" />
  <br>PostgreSQL
</td>

<td align="center" width="96">
  <img src="https://skillicons.dev/icons?i=redis" width="48" height="48" alt="Redis" />
  <br>Redis
</td>

<td align="center" width="96">
  <img src="https://skillicons.dev/icons?i=docker" width="48" height="48" alt="Docker" />
  <br>Docker
</td>

<td align="center" width="96">
  <img src="https://skillicons.dev/icons?i=kubernetes" width="48" height="48" alt="Kubernetes" />
  <br>Kubernetes
</td>

</tr>

<tr>

<td align="center" width="96">
  <img src="https://skillicons.dev/icons?i=linux" width="48" height="48" alt="Linux" />
  <br>Linux
</td>

<td align="center" width="96">
  <img src="https://skillicons.dev/icons?i=git" width="48" height="48" alt="Git" />
  <br>Git
</td>

<td align="center" width="96">
  <img src="https://skillicons.dev/icons?i=nginx" width="48" height="48" alt="Nginx" />
  <br>Nginx
</td>
</tr>
</table>

## Featured Projects

### 🚀 Rodis — Redis-inspired In-Memory Database

A lightweight Redis-inspired in-memory database built from scratch in Go, focused on understanding the internals of high-performance network services and concurrent storage systems.

**Highlights:**

* Custom TCP server handling concurrent client connections
* RESP (REdis Serialization Protocol) parsing and command processing
* Sharded in-memory data structure to reduce lock contention
* TTL support with active key expiration
* Concurrent access and synchronization mechanisms
* Modular architecture separating networking, protocol parsing, command execution, and storage

**Key concepts:** `Go` · `TCP` · `RESP` · `Concurrency` · `Sharding` · `Synchronization`

→ **[Explore the repository](#)**

---

### 📊 High-Performance Log Ingestion & Analytics System

A high-throughput log processing system designed to efficiently ingest, batch, store, and analyze millions of events.

The project explores performance bottlenecks commonly found in backend systems, including database write overhead, syscall costs, concurrency contention, and inefficient request processing.

**Highlights:**

* High-throughput HTTP log ingestion API
* Worker pool architecture for asynchronous processing
* Buffered channels for decoupling ingestion from persistence
* Batch processing to reduce database round trips
* PostgreSQL bulk insertion using `COPY`
* Analytics for request volume, error rates, latency, and P95 latency
* Performance profiling and bottleneck analysis using Go `pprof`

**Key concepts:** `Go` · `PostgreSQL` · `Worker Pool` · `Batching` · `Profiling` · `Performance Engineering`

→ **[Explore the repository](#)**

---

### ⚖️ Go Load Balancer & API Gateway

An experimental reverse proxy and load balancing system built in Go to explore backend traffic distribution and service reliability.

The project focuses on how a gateway manages multiple backend services, detects service availability, and routes incoming requests efficiently.

**Highlights:**

* Reverse proxy for backend services
* Load balancing algorithms
* Periodic health checking
* Automatic routing to healthy backends
* HTTP/2 communication
* Docker-based multi-service environment
* Real-time metrics for requests, latency, and backend health

**Key concepts:** `Go` · `HTTP/2` · `Reverse Proxy` · `Load Balancing` · `Docker` · `Networking`

→ **[Explore the repository](#)**

---

### 📡 5G Core & SMF Engineering

A collection of experiments and implementations exploring the architecture and signaling procedures of the 5G Core network, with a focus on the Session Management Function (SMF).

The work involves studying standardized 5G interfaces and understanding how control-plane messages are constructed, encoded, transmitted, and processed across network functions.

**Areas explored:**

* 5G Core Service-Based Architecture (SBA)
* Session Management Function (SMF)
* PDU Session lifecycle
* N1/N2 signaling procedures
* NGAP message structure and encoding
* Interaction between SMF, AMF, gNodeB, and UPF
* 3GPP specifications and protocol-driven development

**Key concepts:** `5G Core` · `SMF` · `NGAP` · `PDU Session` · `Networking` · `Telecommunications`

→ **[Explore the repository](#)**

---
