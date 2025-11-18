# 👋 Hi, I'm Albert Glenn

💾 **Data Engineering** | ⚙️ Pipeline Performance & Cost Optimization | ☁️ Cloud + Streaming | 📈 Data for Business Impact  

---

## 🚀 About Me

I build **scalable, secure, and cost-efficient** data systems that turn raw data into trusted, analytics-ready assets for dashboards, machine learning, and decision-making.

**My edge:** I design pipelines that **reduce compute & storage spend** while **improving speed, reliability, and governance** — so teams can ship insights faster without burning through cloud credits.

I’m currently completing the **Zero to Mastery Data Engineering Career Path** and applying every concept in **real-world healthcare projects** on AWS and Databricks.

---

## 💡 How I Think: Business Impact Engineering

I focus on **performance + cost optimization + governance**:

- 📉 **Lower cloud costs** using Delta Lake best practices  
  *(partitioning, Z-Ordering, file compaction, caching)*  
- ⚡ **Faster ETL & analytics** → less runtime, fewer cluster-hours  
- 🔁 **Medallion Architecture (Bronze/Silver/Gold)** so data can be reused safely across teams  
- 🔐 **Schema enforcement + RBAC** for compliance and access control  
- 🚀 **BI & ML velocity** → getting from raw data to decisions quickly

> My goal: help companies **do more with data while spending less**.

---

## 🧱 What I Build

✅ Batch & (future) streaming pipelines (Spark, S3, Kafka)  
✅ Data lakes / Lakehouse with **Delta Lake**  
✅ OLTP + OLAP data modeling (star schemas, reporting models)  
✅ Secure environments (IAM, Unity Catalog, RBAC, secrets)  
✅ Analytics & ML-ready datasets for downstream teams  
✅ Early-stage workflow automation & CI/CD around data projects  

I blend **data engineering fundamentals** with **business-first thinking**.

---

## 🧰 Tech Stack

**Languages & Data**
- Python, SQL (PostgreSQL, Databricks SQL)

**Data Engineering**
- Databricks, Spark, Delta Lake  
- AWS S3, Glue, Athena  
- (Learning) Kafka, Airflow, Workflows/Orchestration

**Modeling & Storage**
- Parquet, Delta, Medallion Architecture  
- Partitioning, Z-Order, ACID guarantees

**Analytics & ML (Support Skills)**
- Power BI  
- scikit-learn, TensorFlow  
- Streamlit for lightweight apps

**Cloud & Dev**
- AWS (primary) + some Azure experience  
- Docker, Git/GitHub  

---

## 🌟 Featured Projects

### 1️⃣ 🏥 ER Wait-Time Analytics (AWS + Databricks + Medallion Architecture)

**Repo:**  
👉 [ER-Wait-Time-Analytics-AWS-Databricks-Medallion-Architecture](https://github.com/albe290/ER-Wait-Time-Analytics-AWS-Databricks-Medallion-Architecture)

**What it is:**  
A **production-style Lakehouse pipeline** that analyzes Emergency Room (ER) performance across U.S. hospitals using:

- AWS S3 for raw + curated zones  
- Databricks SQL + Delta Lake for Bronze → Silver → Gold  
- Unity Catalog + IAM for secure S3 access  
- Partitioned, analytics-ready Gold tables for:
  - Top 20 / Bottom 20 hospitals (NY)
  - State-level performance
  - Condition-level quality

**Why it matters:**  
Gives hospital and state leaders **clear, governed, cost-optimized analytics** to improve ER throughput and patient outcomes.

---

### 2️⃣ 🔐 Healthcare Data Engineering Troubleshooting (IAM + Databricks Integration)

**Repo:**  
👉 [healthcare-data-engineering-troubleshooting](https://github.com/albe290/healthcare-data-engineering-troubleshooting)

**What it is:**  
A focused repo documenting how I debugged a **PERMISSION_DENIED IAM error** between **Databricks and AWS S3** while setting up Unity Catalog external locations.

**Highlights:**

- Used `DESCRIBE STORAGE CREDENTIAL` to trace which IAM role Databricks was using  
- Fixed misconfigured **trust policies** and **external IDs** in IAM  
- Updated S3 bucket policies for least-privilege access  
- Captured **before/after screenshots**, error messages, and final working setup

**Why it matters:**  
Shows **real-world troubleshooting skills** around IAM, Unity Catalog, and cloud security — the kind of issues that actually block data teams in production.

---

### 3️⃣ ❤️ Heart Disease Prediction (ML + Data Engineering Foundation)

**Repo:**  
👉 [Heart-Disease-Prediction](https://github.com/albe290/Heart-Disease-Prediction)

**What it is:**  
A machine learning project focused on predicting heart disease risk using structured healthcare data.

**Highlights:**

- End-to-end ML workflow (data prep → modeling → evaluation)  
- Models with scikit-learn / TensorFlow (in progress & iterating)  
- Plans to integrate this into a **Lakehouse-style pipeline**:
  - Ingest raw data into S3 / Delta  
  - Use Databricks for feature engineering  
  - Serve ML-ready features from Gold tables  

**Why it matters:**  
Connects **data engineering + ML** in a healthcare context — exactly where modern data teams are headed.

---

## 🎯 Current Focus

- Deepening my **Databricks + Delta Lake** skills  
- Getting sharper at **Spark SQL performance tuning**  
- Designing reliable **AWS-based data lake architectures**  
- Practicing **system design & SQL interview patterns**  
- Publishing more **case studies & breakdowns** of my projects on GitHub and Medium  

---

## 🔜 What’s Coming Next

- A **real-time fraud or transaction-risk pipeline** (Kafka + Spark Streaming + Delta)  
- More **Lakehouse-style healthcare & fintech projects**  
- Stronger **dashboard and metric layers** (Power BI, Lakeview, etc.)  
- CI/CD + orchestration around my data pipelines  

---

## 📫 Connect with Me

- 💼 LinkedIn: [https://www.linkedin.com/in/aalbertglenn/](https://www.linkedin.com/in/aalbertglenn/)  
- ✍🏽 Medium: [https://medium.com/@AlbertGlenn](https://medium.com/@AlbertGlenn)  


If you’re building **modern data platforms** and care about **performance, cost efficiency, and real business impact**, I’d love to connect and collaborate.


