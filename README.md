# 👋 Hi, I'm Albert Glenn

💾 **Data & AI Engineering** | ⚙️ Pipeline Performance & Cost Optimization | 🔐 Governance & Security | ☁️ Cloud Lakehouse | 📊 Data for Business Impact

---

## 🚀 About Me

I build **production-grade, governed data platforms** that transform raw, high-volume data into **trusted, KPI-ready datasets** for analytics, operations, and machine learning.

My background in **cybersecurity** shapes how I design data systems: **least privilege by default, auditable pipelines, centralized business logic, and cost-aware execution**.

**My edge:** I design Lakehouse pipelines that **scale cleanly**, **control cloud spend**, and **prevent metric drift**, so data teams can ship insights faster *without sacrificing security or reliability*.

I’m currently completing the **Zero to Mastery Data Engineering Career Path**, applying every concept directly to **real-world healthcare and public-sector projects** on **AWS and Databricks**.

---

## 🧠 How I Think: Production & Business-Impact Engineering

I approach data engineering with the same mindset used in regulated, enterprise environments:

* 📉 **Cost efficiency by design** using Delta Lake best practices
  *(partitioning, Z-Ordering, file compaction, pre-aggregation)*
* ⚡ **Performance-first pipelines** that minimize cluster hours and query latency
* 🧱 **Medallion Architecture (Bronze / Silver / Gold)** for safe reuse across teams
* 🔐 **Governance & access control** via Unity Catalog, IAM AssumeRole, and RBAC
* 📊 **Centralized KPI logic in SQL** to eliminate BI-layer duplication and metric inconsistency

> **Goal:** help organizations **do more with data while spending less securely and at scale**.

---

## 🧱 What I Build

✅ Batch-first, Lakehouse-style pipelines (Spark, Delta Lake, S3)
✅ Analytics- and ML-ready **Gold-layer datasets**
✅ SQL-first transformation and KPI logic
✅ Secure cloud integrations (IAM, Unity Catalog, external locations)
✅ OLTP + OLAP-friendly data models (reporting & analytics layers)
✅ Early-stage orchestration, monitoring, and CI/CD patterns

I blend **data engineering fundamentals**, **cloud security**, and **business context** to build systems that hold up in production.

---

## 🧰 Tech Stack

**Languages & Querying**

* Python, SQL (Databricks SQL, PostgreSQL)

**Lakehouse & Data Engineering**

* Databricks, Apache Spark, Delta Lake, Delta Live Tables (DLT)
* AWS S3, AWS Glue, Amazon Athena

**Governance & Security**

* Databricks Unity Catalog (RBAC, lineage, schema enforcement)
* AWS IAM (STS AssumeRole, least-privilege access)

**Streaming & Orchestration (Growing Focus)**

* Apache Kafka
* Apache Airflow

**Analytics & ML (Supporting Skills)**

* Power BI
* scikit-learn, TensorFlow
* Streamlit (lightweight apps & demos)

**Cloud & DevOps**

* AWS (primary), some Azure exposure
* Git/GitHub, Docker

---

## 🌟 Featured Projects

### 1️⃣ 🚨 NYC 911 Operational Performance Lakehouse (Databricks DLT)

**Repo:**
👉 [https://github.com/albe290/nyc_911_project](https://github.com/albe290/nyc_911_project)

**What it is:**
A **production-grade Databricks Lakehouse** built with **Delta Live Tables (DLT)** to process **10+ years of NYC 911 operational data (2014–present)** into trusted, KPI-ready datasets for **SLA monitoring and executive analytics**.

**Architecture & Highlights:**

* Bronze → Silver → Gold pipelines using **DLT (SQL-first)**
* Immutable raw ingestion with schema enforcement and data quality validation
* Centralized KPI logic for:

  * Incident volume trends
  * Response-time SLAs
  * SLA breach rates
* Unity Catalog + AWS IAM (STS AssumeRole) for **credential-free, governed access**
* Gold-only consumption model for BI and analytics

**Why it matters:**
Demonstrates how to build **auditable, cost-efficient, and governance-first analytics pipelines** suitable for **regulated public-sector and enterprise environments**.

---

### 2️⃣ 🏥 ER Wait-Time Analytics (AWS + Databricks | Medallion Architecture)

**Repo:**
👉 [https://github.com/albe290/ER-Wait-Time-Analytics-AWS-Databricks-Medallion-Architecture](https://github.com/albe290/ER-Wait-Time-Analytics-AWS-Databricks-Medallion-Architecture)

**What it is:**
A **Lakehouse analytics pipeline** analyzing Emergency Room performance across U.S. hospitals using:

* AWS S3 for raw and curated data zones
* Databricks SQL + Delta Lake for Bronze → Silver → Gold transformations
* Unity Catalog + IAM for secure, governed data access

**Gold-layer KPIs include:**

* Top 20 / Bottom 20 hospitals (NY)
* State-level ER performance
* Condition-level wait-time trends

**Why it matters:**
Shows how **healthcare analytics pipelines** can be built to support **operational decision-making** while maintaining **performance, security, and cost discipline**.

---

### 3️⃣ 🔐 Healthcare Data Engineering Troubleshooting (IAM + Databricks)

**Repo:**
👉 [https://github.com/albe290/healthcare-data-engineering-troubleshooting](https://github.com/albe290/healthcare-data-engineering-troubleshooting)

**What it is:**
A focused troubleshooting case study documenting how I resolved a **PERMISSION_DENIED IAM issue** between **Databricks and AWS S3** when configuring Unity Catalog external locations.

**Key takeaways:**

* Traced active IAM roles using `DESCRIBE STORAGE CREDENTIAL`
* Fixed trust policies and external ID mismatches
* Corrected S3 bucket policies for least-privilege access
* Captured before/after errors, screenshots, and final validation

**Why it matters:**
Highlights **real-world cloud security debugging skills** the kind of issues that frequently block production data platforms.

---

### 4️⃣ ❤️ Heart Disease Prediction (ML + Data Engineering Foundation)

**Repo:**
👉 [https://github.com/albe290/Heart-Disease-Prediction](https://github.com/albe290/Heart-Disease-Prediction)

**What it is:**
An end-to-end machine learning project predicting heart disease risk using structured healthcare data.

**Highlights:**

* Data preparation, feature engineering, modeling, and evaluation
* scikit-learn and TensorFlow experimentation
* Planned evolution into a **Lakehouse-backed ML pipeline**:

  * Raw ingestion into S3 / Delta
  * Feature engineering in Databricks
  * Gold-layer ML-ready feature tables

**Why it matters:**
Connects **data engineering foundations with applied machine learning**  reflecting how modern data teams operate.

---

## 🎯 Current Focus

* Advanced **Databricks & Delta Lake** patterns
* **Spark SQL performance tuning** and cost optimization
* Secure **AWS-based Lakehouse architectures**
* SQL & system design interview preparation
* Publishing **architecture breakdowns and case studies** on GitHub and Medium

---

## 🔜 What’s Coming Next

* Real-time risk / fraud-style pipeline (Kafka + Spark Streaming + Delta)
* More **Lakehouse-style healthcare and fintech projects**
* Stronger **metric layers and dashboards** (Power BI, Databricks Lakeview)
* CI/CD and orchestration around data pipelines

---

## 📫 Connect With Me

* 💼 LinkedIn: [https://www.linkedin.com/in/aalbertglenn/](https://www.linkedin.com/in/aalbertglenn/)
* ✍🏽 Medium: [https://medium.com/@AlbertGlenn](https://medium.com/@AlbertGlenn)
* 💻 GitHub: [https://github.com/albe290](https://github.com/albe290)

If you’re building **modern, governed data platforms** and care about **performance, cost efficiency, and real business impact**, I’d love to connect and collaborate.


