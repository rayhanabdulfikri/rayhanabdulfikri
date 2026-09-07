```markdown
# Rayhan Abdul Fikri
### Data Platform & AI Systems Engineer

Specializing in reliable data infrastructure, distributed pipeline architecture, and production-grade LLM/RAG integration. Focused on system correctness, observability, query optimization, and cost-efficient cloud storage.

[LinkedIn](https://www.linkedin.com/in/rayhan-abdul-fikri/) &nbsp;|&nbsp; [GitHub](https://github.com/rayhanabdulfikri) &nbsp;|&nbsp; [Email](mailto:rayhanabdulf10@gmail.com)

---

### Engineering Philosophy

* **Idempotency by Default:** Pipelines are built to recover from failures without data duplication or state drift.
* **Schema Rigor & Contract-First:** Data boundaries and schema enforcement precede transformation logic.
* **Zero-Hallucination AI Integration:** LLM layers treat output parsing and context retrieval (RAG) with the same strict deterministic contracts as database queries.
* **Measurable Trade-offs:** Optimizing for throughput, storage cost, latency, or compute efficiency based on explicit system constraints.

---

### Core Competencies & Architecture Domains

| Domain | Systems & Architectural Focus |
| :--- | :--- |
| **Data Engineering** | Analytical Warehousing, BigQuery partitioning/clustering, relational modeling, complex transformation DAGs, ETL/ELT optimization, pipeline instrumentation |
| **Generative AI Systems** | Retrieval-Augmented Generation (RAG), vector context assembly, domain grounding, deterministic JSON schema output parsing, LLM evaluation pipelines |
| **Infrastructure & Tools** | Linux environment orchestration, Docker containerization, cloud compute/storage primitives, Git-based CI/CD workflows, automated monitoring |
| **Analytical Modeling** | Dimensional modeling, metric store logic, SQL window functions, statistical validation, exploratory data architectures |

---

### Technical Portfolio & Architectures

#### 1. Decoupled Email Event & State Ingestion Engine
*Automated asynchronous communication pipeline backed by relational state machines.*

* **Architecture:** Decoupled outbound SMTP delivery from asynchronous inbound IMAP response pollers to avoid blocking worker threads.
* **Reliability:** Built structured event classification logic to persist interaction states into transactional storage (MySQL), handling edge cases such as connection timeouts and message retries.
* **Outcome:** Clean separation between network I/O, state classification, and persistent tracking layers.

#### 2. Enterprise Big Data Aggregation & Analytical Modeling
*Analytical workload pipeline built around Kimball dimensional modeling patterns.*

* **Implementation:** Designed end-to-end SQL transformation procedures across large operational datasets; implemented dimension tables and partitioned fact aggregates.
* **Consumption Layer:** Built interactive executive monitoring layers in Looker Studio, establishing direct visibility over critical operational business metrics.

#### 3. Grounded Retrieval-Augmented Generation (RAG) Backend
*Backend system integration for strict, context-constrained language model workflows.*

* **Execution:** Designed RESTful API endpoints interfacing with LLMs, enforcing deterministic schema outputs via JSON formatting constraints.
* **Validation:** Implemented grounding evaluation loops to benchmark response fidelity against reference documentation and prevent unconstrained output drift.

---

### System Architecture Snapshot

```text
               +-------------------------------------------+
               |           Ingestion & Storage             |
               |   OLTP Databases / Event Logs / Webhooks  |
               +-------------------------------------------+
                                     │
                                     ▼
               +-------------------------------------------+
               |        Transformation & Processing        |
               |    SQL Optimization / Idempotent DAGs     |
               +-------------------------------------------+
                                     │
                   ┌─────────────────┴─────────────────┐
                   ▼                                   ▼
+------------------------------------+   +------------------------------------+
|         Data Warehousing           |   |       Grounded AI Context          |
|  BigQuery / Partitioned Analytics  |   |  Vector Embeddings / RAG Retrieval |
+------------------------------------+   +------------------------------------+
                   │                                   │
                   ▼                                   ▼
         [ Business Analytics ]              [ Deterministic APIs ]

```

---

### Technical Proficiencies

* **Languages & Scripting:** Python, Advanced SQL, Bash/Shell
* **Data Processing & Platforms:** Google Cloud Platform (BigQuery, Cloud Storage), MySQL, Relational Schema Design
* **AI & Integration Engineering:** RAG Architectures, Grounding Verification, Structured Output Validation, REST API Design
* **DevOps & System Runtime:** Linux internals, Docker, Git version control, automation daemons

---

### Professional Engagements

* **Backend AI Systems Intern** — *Flyrank AI*
Architected and evaluated backend API integrations for LLMs; implemented structured output validation and grounding pipelines.
* **Technical Facilitator** — *Dicoding × Google Cloud*
Delivered architectural guidance and technical onboarding across Google Cloud Platform foundational labs and operational tracks.
* **Data Analytics Intern** — *PT Kimia Farma Tbk. × Rakamin Academy*
Engineered aggregation procedures, clean data transformations, and dimensional reporting models on operational data.

---

### Professional Focus

Open to Data Engineering, Data Platform, and AI Systems Engineering engagements focusing on scalable infrastructure, pipeline reliability, and robust data foundations.

```

```
