# Vikrant

**20+ years of engineering, architecture, and technology leadership**

Healthcare · BFSI · Telecom

Production AI and ML systems · Cloud platforms · MLOps · Distributed systems · Enterprise data engineering

---

## Profile

Technology leader with 20+ years of experience progressing from software engineering and distributed systems to architecture, platform ownership, and AI/ML leadership.

Recent work spans **Generative AI, machine learning, MLOps, clinical AI, predictive intelligence, and cloud-native AI platforms**, with production implementations across healthcare and enterprise environments.

Engineering foundation includes **carrier-grade telecom platforms, network analytics, security data platforms, enterprise databases, distributed systems, and large-scale data processing**.

I focus on taking AI and ML capabilities from architecture through **production engineering, orchestration, infrastructure, evaluation, observability, governance, and operational adoption**.

---

## Technical Focus

| Area | Technologies & Expertise |
|---|---|
| **Generative AI & LLMs** | AWS Bedrock · LLaMA 3 / 3.1 · RAG · Hybrid Retrieval · LLM-as-Judge · Faithfulness Evaluation · Structured Output Validation · HITL · Token Telemetry |
| **Healthcare AI** | EHR / EMR Data · Clinical Notes · Clinical NLP · SDoH · Risk Stratification · ICD-10 Context · Clinical Workflows · PHI-aware AI |
| **Machine Learning** | CatBoost · Neural Networks · Zero-Shot NLI · BART · RoBERTa · DeBERTa · SHAP · Predictive Modeling · Model Monitoring · Drift Detection |
| **MLOps & AI Lifecycle** | Prefect · Automated ML Pipelines · Model Versioning · CI/CD · Production Monitoring · Automated Retraining · Lifecycle Management |
| **Cloud & AI Infrastructure** | AWS · GCP · Vertex AI · EC2 · ECR · Fargate · Lambda · S3 · EMR · BigQuery · Dataflow · GPU Compute |
| **Data Engineering** | Glue · Athena · SSIS · ETL Pipelines · BigQuery · Dataflow · Data Lake Architecture |
| **Software Engineering** | Python · SQL · PL/SQL · Microservices · Kafka · Distributed Systems · Enterprise Integration |
| **Infrastructure** | Docker · Kubernetes · Cloud-native Architecture · Production Compute · Observability |
| **Enterprise Platforms** | Telecom OSS/BSS · Network Analytics · Security Data Platforms · Conversational AI · Enterprise Data Platforms |

---

# Selected Production Work

## Healthcare AI & MLOps

### Prefect-based ML Orchestration

Built an ML orchestration platform from zero, replacing manual configuration-driven execution with automated workflows across ingestion, preprocessing, data lake, and risk-scoring layers.

**140K+ patients across multiple healthcare implementations**

| Measure | Outcome |
|---|---:|
| Analytics turnaround | **75–85% reduction** |
| 40K-patient implementation | **40 hours → 10 hours** |
| 100K+ patient implementation | **10–15 days → 2–3 days** |
| Infrastructure | **AWS EC2 / Fargate** |

---

### Clinical LLM Platform

Designed production LLM infrastructure on **AWS Bedrock** for clinical summarization using LLaMA 3.1-8B-Instruct.

The platform incorporated structured-output validation, LLM evaluation, exception handling, HITL controls, and token-level cost telemetry.

| Measure | Outcome |
|---|---:|
| Clinical notes | **10K+ notes / run** |
| Cost | **< $0.00025 / note** |
| Orchestration stability | **92%** |
| Structured JSON compliance | **98%** |
| AWS compute cost | **20–30% reduction** |

---

### Clinical NLP Architecture Review

Identified a silent model dependency mismatch before national rollout.

The upstream SDoH pipeline produced **7 features**, while the downstream zero-shot NLP model expected **12 features**.

The issue was identified through independent architecture review before production deployment and influenced the rollout decision.

---

### Production Healthcare Inference

Defined infrastructure architecture for production-scale healthcare inference by evaluating workload characteristics, data volumes, throughput, and compute requirements.

Selected GPU-backed EC2 infrastructure where workload characteristics justified GPU acceleration over standard compute.

---

# Machine Learning Architecture

## Cardinal Health — OptiFreight®

Designed ML architecture for ETA prediction across a healthcare logistics platform processing **20M+ shipments annually**.

**GCP Vertex AI · BigQuery · Dataflow · CatBoost · SHAP · Model Monitoring**

Selected CatBoost after evaluating Random Forest and Neural Network alternatives.

**14M historical shipment records**

| Metric | Result |
|---|---:|
| Precision | **97.66%** |
| F1 | **94.70%** |

Designed explainability, monitoring, drift detection, and model lifecycle capabilities for production ML.

---

# Conversational AI

## JPMorgan Chase — Chase Mobile Virtual Assistant

Worked on enterprise conversational AI capabilities supporting a mobile banking platform serving **50M+ digital customers**.

| Capability | Technology |
|---|---|
| NLP architecture | **RASA** |
| Data / integration layer | **Kafka · Microservices** |
| Conversational capability | **Intent classification · Dialogue orchestration** |
| Platform transition | **IPsoft Amelia → RASA** |

---

# Large-Scale Engineering

## AT&T — Domain 2.0

Led technology delivery and architecture for telecom analytics and operational platforms supporting AT&T's Domain 2.0 transformation.

Architected ETL and analytics frameworks processing **30TB+ of network measurements monthly** for network performance monitoring and fault detection.

**Focus:** Network analytics · ETL architecture · Distributed processing · Operational intelligence · Legacy modernization

---

## Symantec Managed Security Services

Led database architecture modernization and IPv6 transformation across replicated Microsoft SQL Server environments supporting security platforms processing **400B+ threat logs monthly**.

**Focus:** Database architecture · Replication · IPv6 transformation · Large-scale security data

---

## Openwave Telecom Platforms

Engineered carrier-grade mediation, policy control, and traffic-management platforms supporting global telecom operators.

Led the Ireland-to-India engineering transition for platforms supporting a **$40–50M quarterly business**.

**Focus:** Telecom mediation · Policy control · Traffic management · Distributed systems · Platform transition

---

## British Telecom — 21CN

Worked on carrier-grade observability, telemetry, and fault-correlation systems supporting BT's 21CN transformation and service assurance across a network serving **22.5M+ households**.

**Focus:** Network telemetry · Fault correlation · Service assurance · Distributed systems

---

# Engineering Perspective

Production AI is a systems engineering problem.

A model is one component of a larger production system involving:

| Concern | Engineering Considerations |
|---|---|
| **Data** | Quality · Dependencies · Lineage · Feature consistency |
| **Pipelines** | Orchestration · Repeatability · Failure handling |
| **Models** | Evaluation · Versioning · Monitoring · Drift |
| **Infrastructure** | Compute · GPU sizing · Scalability · Availability |
| **LLMs** | Output validation · Cost · Evaluation · Exceptions |
| **Operations** | Observability · Alerting · Recovery · Release readiness |
| **Governance** | Access controls · HITL · Auditability · Responsible AI |
| **Economics** | Compute utilization · Token consumption · Cost controls |

My work focuses on the **engineering decisions and system boundaries** that determine whether AI capabilities can operate reliably in production.

---

# Healthcare Domain

Experience across healthcare data, analytics, and AI workflows:

| Domain | Experience |
|---|---|
| **Healthcare Data** | EHR / EMR · Clinical notes · Patient data |
| **Clinical NLP** | SDoH extraction · Zero-shot NLP · Clinical text processing |
| **Risk & Prediction** | Patient risk stratification · Predictive modeling |
| **Clinical Context** | ICD-10 coding context · Clinical workflows |
| **AI Operations** | PHI-aware workflows · HITL · Model governance |
| **Analytics** | Healthcare analytics · Operational reporting · Risk analytics |

---

# Technical Stack

| Area | Stack |
|---|---|
| **Generative AI** | AWS Bedrock · LLaMA 3 / 3.1 · RAG · Hybrid Retrieval · LLM-as-Judge · Faithfulness Evaluation · HITL |
| **Machine Learning** | CatBoost · BART · RoBERTa · DeBERTa · SHAP · Neural Networks |
| **MLOps** | Prefect · GitLab · Jenkins · Model Versioning · Drift Detection · Automated Retraining |
| **AWS** | EC2 · ECR · Fargate · Lambda · S3 · EMR · RDS · DynamoDB · Glue · Athena |
| **GCP** | Vertex AI · BigQuery · Dataflow |
| **Data Engineering** | ETL · Data Lakes · SSIS · Glue · Athena · BigQuery |
| **Programming** | Python · SQL · PL/SQL |
| **Infrastructure** | Docker · Kubernetes · GPU Compute |
| **Distributed Systems** | Microservices · Kafka · Telecom OSS/BSS · Enterprise Integration |

---

# Engineering Background

```text
Software Engineering
        ↓
Distributed Systems
        ↓
Telecom Platforms
        ↓
Enterprise Data & Analytics
        ↓
Machine Learning
        ↓
MLOps
        ↓
Generative AI
