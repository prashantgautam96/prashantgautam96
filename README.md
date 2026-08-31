<div align="center">

# 👋 Hi, I'm Prashant Gautam

### Backend Software Engineer · Distributed Systems · Observability

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=900&color=58A6FF&center=true&vCenter=true&width=900&lines=Building+scalable+backend+systems;Java+%7C+Spring+Boot+%7C+Microservices;Distributed+Systems+%7C+Kafka+%7C+Redis;Observability+%7C+OpenTelemetry;System+Design+%7C+Data-Intensive+Systems;Always+learning.+Always+building." alt="Typing SVG" />

<br/>

<a href="https://github.com/prashantgautam96">
<img src="https://img.shields.io/badge/GitHub-prashantgautam96-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>

<a href="https://leetcode.com/u/programmerprashantgautam/">
<img src="https://img.shields.io/badge/LeetCode-128%2B%20Solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode"/>
</a>

<a href="https://www.linkedin.com/">
<img src="https://img.shields.io/badge/LinkedIn-Prashant%20Gautam-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>

</div>

---

## 🧠 About Me

```text
I build backend systems designed to survive real-world complexity.

→ Backend Software Engineer focused on Java & Spring Boot
→ Interested in distributed systems and data-intensive applications
→ Experienced with microservices and event-driven architectures
→ Working with Kafka, Redis and PostgreSQL
→ Building and exploring observability with OpenTelemetry
→ Interested in scalability, reliability and high-performance APIs
→ Currently sharpening Data Structures, Algorithms and System Design
→ Computer Science graduate from IIT Jammu
```

I'm particularly interested in the engineering problems that appear **after systems become complicated**:

* How do we make distributed services observable?
* How do we process millions of events reliably?
* How do we design systems that degrade gracefully?
* How do we scale reads without sacrificing reliability?
* How do we build systems that are easy to operate and debug?
* How do we make infrastructure vendor-neutral?

> **My goal:** become an exceptional backend engineer who can reason from **code → architecture → infrastructure**.

---

# ⚙️ Tech Stack

### 💻 Languages

<p align="left">
<img src="https://skillicons.dev/icons?i=java,python,cpp,js" />
</p>

`Java` · `Python` · `C++` · `JavaScript` · `SQL`

---

### 🚀 Backend

<p align="left">
<img src="https://skillicons.dev/icons?i=spring,nodejs,hibernate" />
</p>

`Java` · `Spring Boot` · `Spring Cloud` · `Spring Data JPA`
`Hibernate` · `REST APIs` · `Microservices`

---

### 🗄️ Databases & Storage

<p align="left">
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis" />
</p>

`PostgreSQL` · `MySQL` · `MongoDB` · `Redis`
`Database Design` · `Indexing` · `Query Optimization` · `JSONB`

---

### 📨 Messaging & Distributed Systems

<p align="left">
<img src="https://skillicons.dev/icons?i=kafka" />
</p>

`Apache Kafka` · `Event-Driven Architecture` · `Message Queues`
`Caching` · `Replication` · `High Availability` · `Fault Tolerance`

---

### 📡 Observability

<p align="left">
<img src="https://skillicons.dev/icons?i=prometheus,grafana" />
</p>

`OpenTelemetry` · `Distributed Tracing` · `Metrics` · `Logs`
`Prometheus` · `Grafana` · `Observability Pipelines`

---

### ☁️ Infrastructure & Tools

<p align="left">
<img src="https://skillicons.dev/icons?i=docker,kubernetes,linux,git,github,idea,postman" />
</p>

`Docker` · `Kubernetes` · `Linux` · `Git`
`GitHub` · `IntelliJ IDEA` · `Postman`

---

# 🏗️ Engineering Interests

<div align="center">

|            Area           | What I'm Exploring                              |
| :-----------------------: | :---------------------------------------------- |
|       🧩 **Backend**      | Java · Spring Boot · REST · Microservices       |
| ⚡ **Distributed Systems** | Kafka · Messaging · Caching · Replication       |
|        🗄️ **Data**       | PostgreSQL · Database Internals · Data Modeling |
|    📡 **Observability**   | OpenTelemetry · Metrics · Logs · Tracing        |
|    🏛️ **Architecture**   | System Design · Scalability · Reliability       |
|   🧠 **Problem Solving**  | DSA · Algorithms · Complexity                   |
|  🤖 **AI Infrastructure** | AI Agents · Governance · Observability          |

</div>

---

# 🚀 Featured Projects

## 🔭 Vantage

### Vendor-Neutral Governance & Observability Layer for Enterprise AI Agents

A platform focused on making enterprise AI agents **observable, governable and controllable** across different AI providers and infrastructure.

### Focus

`AI Agents` · `Governance` · `Observability` · `Distributed Systems`

### Repository

<a href="https://github.com/prashantgautam96/vantage">
<img src="https://img.shields.io/badge/View%20Project-Vantage-58A6FF?style=for-the-badge&logo=github&logoColor=white"/>
</a>

---

## 🔐 AI-Powered SSL Insights & Monitoring

A backend platform for monitoring SSL/TLS certificates and providing intelligent insights around certificate health, expiration and infrastructure visibility.

### Focus

`Java` · `Spring Boot` · `PostgreSQL` · `REST APIs`
`Monitoring` · `AI` · `Infrastructure`

---

## 🌍 LAVA — Land Administration Platform

A multi-tenant land administration platform built around Land Administration Domain Model concepts and distributed backend services.

### Architecture

```text
                        ┌─────────────────┐
                        │   Nx / Angular   │
                        │    Frontend      │
                        └────────┬────────┘
                                 │
                                 ▼
                    ┌────────────────────────┐
                    │   Spring Cloud Gateway │
                    └────────────┬───────────┘
                                 │
                    ┌────────────┴────────────┐
                    ▼                         ▼
           ┌────────────────┐       ┌────────────────┐
           │ Eureka Server  │       │ Config Server  │
           └────────────────┘       └────────────────┘
                    │
                    ▼
          ┌──────────────────────┐
          │   Domain Services    │
          │    Microservices      │
          └──────────┬───────────┘
                     │
             ┌───────┴────────┐
             ▼                ▼
      ┌─────────────┐  ┌─────────────────┐
      │ PostgreSQL  │  │ Hyperledger     │
      │             │  │ Fabric          │
      └─────────────┘  └─────────────────┘
```

### Technologies

`Java` · `Spring Boot` · `Spring Cloud`
`PostgreSQL` · `Eureka` · `Spring Cloud Gateway`
`Hyperledger Fabric` · `REST APIs` · `Microservices`

---

# 🧠 Problem Solving

I practice Data Structures & Algorithms with a focus on **understanding patterns rather than memorizing solutions**.

<div align="center">

### 🧮 128+ LeetCode Problems Solved

<a href="https://leetcode.com/u/programmerprashantgautam/">
<img src="https://img.shields.io/badge/LeetCode-128%2B%20Problems-FFA116?style=for-the-badge&logo=leetcode&logoColor=white"/>
</a>

</div>

### Current Focus

```text
Arrays & Hashing
       ↓
Two Pointers
       ↓
Sliding Window
       ↓
Binary Search
       ↓
Stacks & Queues
       ↓
Trees & Graphs
       ↓
Backtracking
       ↓
Dynamic Programming
```

<a href="https://leetcode.com/u/programmerprashantgautam/">
View my LeetCode Profile →
</a>

---

# 🏛️ System Design

I'm going deep into **large-scale and data-intensive systems**.

### Systems I Study & Design

```text
┌───────────────────────────────────────────────────────────┐
│                    SYSTEM DESIGN                          │
├───────────────────────────────────────────────────────────┤
│                                                           │
│  🔗 URL Shortener           🔔 Notification System        │
│                                                           │
│  🚦 Rate Limiter             📨 Message Queue             │
│                                                           │
│  ⚡ Distributed Cache        🔎 Search System              │
│                                                           │
│  📦 File Storage             ⏱️ Job Scheduler              │
│                                                           │
│  💳 Payment System           📡 Observability Platform    │
│                                                           │
└───────────────────────────────────────────────────────────┘
```

### Core Concepts

`Load Balancing` · `Caching` · `Sharding` · `Replication`

`Consistency` · `Availability` · `Partition Tolerance`

`Kafka` · `Redis` · `PostgreSQL`

`CDN` · `API Gateway` · `Service Discovery`

`Event-Driven Architecture` · `Async Processing`

`Horizontal Scaling` · `Fault Tolerance` · `Backpressure`

---

# 📊 GitHub Analytics

<div align="center">

<img height="180em"
src="https://github-readme-stats.vercel.app/api?username=prashantgautam96&show_icons=true&hide_border=true&theme=github_dark&include_all_commits=true&count_private=true"
alt="Prashant's GitHub Stats"/>

<img height="180em"
src="https://github-readme-stats.vercel.app/api/top-langs/?username=prashantgautam96&layout=compact&hide_border=true&theme=github_dark&langs_count=8"
alt="Prashant's Top Languages"/>

</div>

<br/>

<div align="center">

<img
src="https://streak-stats.demolab.com?user=prashantgautam96&theme=github-dark-blue&hide_border=true"
alt="GitHub Streak"/>

</div>

---

# 📈 Contribution Graph

<div align="center">

<img
src="https://github-readme-activity-graph.vercel.app/graph?username=prashantgautam96&theme=github-dark&hide_border=true&area=true"
alt="GitHub Contribution Graph"/>

</div>

---

# 🏆 GitHub Trophies

<div align="center">

<img
src="https://github-profile-trophy.vercel.app/?username=prashantgautam96&theme=darkhub&no-frame=true&no-bg=true&margin-w=8&row=1"
alt="GitHub Trophies"/>

</div>

---

# 🔥 What I'm Currently Exploring

<div align="center">

```text
                    ┌──────────────────────┐
                    │  DISTRIBUTED SYSTEMS │
                    └──────────┬───────────┘
                               │
              ┌────────────────┼────────────────┐
              ▼                ▼                ▼
        ┌──────────┐     ┌──────────┐     ┌───────────┐
        │  Kafka   │     │  Redis   │     │PostgreSQL │
        └────┬─────┘     └────┬─────┘     └─────┬─────┘
             │                │                  │
             └────────────────┼──────────────────┘
                              ▼
                    ┌───────────────────┐
                    │   OBSERVABILITY   │
                    └─────────┬─────────┘
                              │
                              ▼
                     ┌────────────────┐
                     │ OpenTelemetry  │
                     └────────┬───────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ SYSTEM INTELLIGENCE│
                    └────────────────────┘
```

</div>

---

# 🧭 Current Learning Path

```text
                    Backend Engineering
                            │
                            ▼
                       System Design
                            │
                            ▼
                    Distributed Systems
                            │
              ┌─────────────┼─────────────┐
              ▼             ▼             ▼
          Databases       Kafka         Redis
              │             │             │
              └─────────────┼─────────────┘
                            ▼
                       Observability
                            │
                            ▼
                      OpenTelemetry
                            │
                            ▼
                    AI Infrastructure
```

---

# 🧪 Engineering Philosophy

> **Simple systems first. Scale only when the problem demands it.**

Good backend engineering isn't about using the most technologies.

It's about understanding:

```text
Requirements
     ↓
Constraints
     ↓
Data Model
     ↓
API Design
     ↓
Architecture
     ↓
Failure Modes
     ↓
Observability
     ↓
Scalability
```

The best systems aren't just **fast**.

They're:

**Reliable · Observable · Maintainable · Scalable**

---

# 🎯 Areas I'm Interested In

```text
☕ Java & Spring Boot
🏗️ Backend Architecture
⚡ Distributed Systems
📨 Event-Driven Systems
📡 Observability
🔭 OpenTelemetry
🗄️ Databases
🚀 System Design
🤖 AI Infrastructure
🔐 Infrastructure Security
```

---

# 📫 Let's Connect

I'm always interested in conversations around:

**Backend Engineering · Distributed Systems · System Design**

**Java · Spring Boot · Kafka · PostgreSQL · Redis**

**OpenTelemetry · Observability · AI Infrastructure**

<div align="center">

<a href="https://github.com/prashantgautam96">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>

<a href="https://leetcode.com/u/programmerprashantgautam/">
<img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode"/>
</a>

<a href="https://www.linkedin.com/">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>

</div>

---

<div align="center">

### ⚡ Build systems. Understand systems. Break systems. Improve systems.

<br/>

⭐ **If you find something interesting here, consider starring a repository.**

</div>
