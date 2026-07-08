# Hey, I'm Hassan Zaib Hayat

**Senior Backend & Data Engineer** with 5+ years designing scalable APIs, microservices, and end-to-end data pipelines. Currently Senior Software Engineer (Backend Lead) at Purelogics, building a HIPAA-compliant healthcare platform serving 1,000+ concurrent users across 20–40 GB datasets.

Built production-grade big-data platforms processing 285M+ e-commerce events and 3.2M+ NYC taxi trips with Hadoop, Spark, Kafka, and Airflow — fronted by React dashboards on Terraform-managed AWS and GCP infrastructure.

Active open-source maintainer — **4 projects on GitHub, 2 published to PyPI with 5,300+ downloads**. AWS Certified Data Engineer. Ship faster with AI-assisted development (Claude Code, GitHub Copilot), backed by published research in blockchain performance optimization (M.Phil., PUCIT).

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/hassan-zaib-hayat)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:hassanzaibhayatske@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white)](https://hassanzaibhayat.com)
[![AWS](https://img.shields.io/badge/AWS-Certified%20Data%20Engineer-FF9900?style=flat&logo=amazonwebservices&logoColor=white)](https://www.credly.com/users/hassan-zaib-hayat)

---

## Open-Source Projects

### django-query-doctor

[![PyPI](https://img.shields.io/pypi/v/django-query-doctor?color=blue)](https://pypi.org/project/django-query-doctor/)
[![Downloads](https://static.pepy.tech/badge/django-query-doctor)](https://pepy.tech/project/django-query-doctor)
[![Downloads/month](https://static.pepy.tech/badge/django-query-doctor/month)](https://pepy.tech/project/django-query-doctor)
[![Python](https://img.shields.io/pypi/pyversions/django-query-doctor)](https://pypi.org/project/django-query-doctor/)
[![Tests](https://img.shields.io/github/actions/workflow/status/hassanzaibhay/django-query-doctor/ci.yml?label=tests)](https://github.com/hassanzaibhay/django-query-doctor/actions)
[![Coverage](https://img.shields.io/badge/coverage-86%25%2B-brightgreen)](https://github.com/hassanzaibhay/django-query-doctor)

Automated Django ORM query diagnosis with prescriptive performance fixes. **5,300+ downloads** — predominantly Linux / Python 3.13 production environments.

- **QueryTurbo** — 3-phase SQL compilation cache (UNTRUSTED→TRUSTED→POISONED) using psycopg3 prepared statements
- **AST-based analyzer** — detects DRF `SerializerMethodField` N+1 patterns at import time, zero runtime overhead
- **Baseline regression detection** — `--save-baseline` / `--fail-on-regression` with GitHub Actions PR annotations
- **8 analyzers** · **749 tests** · **86%+ coverage** · Django 4.2–6.0 · async-safe · mypy strict + ruff clean

```bash
pip install django-query-doctor
```

[GitHub](https://github.com/hassanzaibhay/django-query-doctor) · [PyPI](https://pypi.org/project/django-query-doctor/) · [Docs](https://hassanzaibhay.github.io/django-query-doctor)

---

### pyteam-skills

[![PyPI](https://img.shields.io/pypi/v/pyteam-skills?color=blue)](https://pypi.org/project/pyteam-skills/)
[![Downloads](https://static.pepy.tech/badge/pyteam-skills)](https://pepy.tech/project/pyteam-skills)

CLI tool mining Git history via PyDriller to generate team skill matrices — weighted scoring, recency decay, normalized 1–100 ratings. Outputs interactive Tailwind CSS dashboards with dark mode and filtering.

```bash
pip install pyteam-skills
pyteam-skills init && pyteam-skills scan && pyteam-skills dashboard
```

[GitHub](https://github.com/hassanzaibhay/pyteam-skills) · [PyPI](https://pypi.org/project/pyteam-skills/)

---

### ecommerce-clickstream-platform

[![GitHub](https://img.shields.io/badge/GitHub-ecommerce--clickstream--platform-181717?style=flat&logo=github)](https://github.com/hassanzaibhay/ecommerce-clickstream-platform)
![Events](https://img.shields.io/badge/events-285M-blue)
![Size](https://img.shields.io/badge/dataset-14GB-blue)

End-to-end big-data platform processing 285M e-commerce clickstream events through batch and real-time streaming pipelines.

- **Batch** — 5 PySpark jobs (session analytics, product engagement, conversion funnels, category trends, temporal patterns) + Hadoop MapReduce aggregation
- **Streaming** — Kafka (KRaft) + Spark Structured Streaming → PostgreSQL + FastAPI SSE
- **Dashboard** — React/TypeScript (Tailwind, Recharts, TanStack Query), 4 analytics pages
- **Infra** — 13 Docker services, Airflow orchestration, Terraform on AWS + GCP, CI via GitHub Actions

[GitHub](https://github.com/hassanzaibhay/ecommerce-clickstream-platform)

---

### nyc-taxi-analytics-platform

[![GitHub](https://img.shields.io/badge/GitHub-nyc--taxi--analytics--platform-181717?style=flat&logo=github)](https://github.com/hassanzaibhay/nyc-taxi-analytics-platform)
![Trips](https://img.shields.io/badge/trips-3.2M-blue)

Big-data platform processing 3.2M real NYC taxi trips through batch and real-time pipelines.

- **Batch** — Hadoop MapReduce for zone aggregation, PySpark for hourly demand/revenue analytics
- **Streaming** — Kafka (KRaft) + Spark Structured Streaming with 15-minute sliding windows
- **Backend** — FastAPI (10+ endpoints, async SQLAlchemy, SSE) + React/TypeScript dashboard
- **Infra** — 13 Docker services, 3 Airflow DAGs, Terraform on AWS (EMR, MSK, MWAA, RDS) + GCP (Dataproc, Composer, Cloud SQL), CI via GitHub Actions

[GitHub](https://github.com/hassanzaibhay/nyc-taxi-analytics-platform)

---

## Tech Stack

| Domain | Technologies |
|---|---|
| **Languages** | Python, JavaScript (ES6), TypeScript, SQL, Java |
| **Backend** | Django, DRF, FastAPI, GraphQL (Graphene), Celery, Node.js |
| **Data Engineering** | PySpark, Apache Kafka, Hadoop (MapReduce, HDFS, YARN), Apache Airflow, Spark Structured Streaming, Parquet |
| **Databases** | PostgreSQL, MySQL, Redis, MongoDB, Elasticsearch, MinIO |
| **Cloud & DevOps** | AWS (EC2, S3, RDS, Lambda, SQS, ECS, EMR, MSK, MWAA, Glue, Athena), GCP (Dataproc, Composer, Cloud SQL), Docker, Terraform, GitHub Actions, Jenkins, Linux |
| **Frontend** | React, TypeScript, Tailwind CSS, Recharts, TanStack Query, Vite |
| **Testing & Quality** | pytest, Jest, mypy, ruff, 86%+ coverage practices |
| **AI Tooling** | Claude Code, GitHub Copilot, Prompt Engineering |
| **Practices** | HIPAA Compliance, Microservices, Event-Driven Architecture, Batch & Stream Processing, Agile/Scrum |

---

## Certifications

**Cloud & Data**
- **AWS Certified Data Engineer – Associate (DEA-C01)** — *Amazon Web Services, 2026*
- AWS Certified Solutions Architect – Associate (SAA-C03) — *in progress*

**Courses**
- Java Spring Framework, Spring Boot & Spring AI — *Udemy*
- Blockchain Specialization — *Coursera*
- Python Django – The Practical Guide — *Udemy*
- React Certification · Modern React with Redux — *Udemy*
- The Git and GitHub Bootcamp — *Udemy*

---

## GitHub

[![Followers](https://img.shields.io/github/followers/hassanzaibhay?style=social)](https://github.com/hassanzaibhay?tab=followers)
&nbsp;
[![django-query-doctor](https://img.shields.io/github/stars/hassanzaibhay/django-query-doctor?style=social&label=django-query-doctor)](https://github.com/hassanzaibhay/django-query-doctor)
[![pyteam-skills](https://img.shields.io/github/stars/hassanzaibhay/pyteam-skills?style=social&label=pyteam-skills)](https://github.com/hassanzaibhay/pyteam-skills)
[![ecommerce-clickstream-platform](https://img.shields.io/github/stars/hassanzaibhay/ecommerce-clickstream-platform?style=social&label=ecommerce-clickstream)](https://github.com/hassanzaibhay/ecommerce-clickstream-platform)
[![nyc-taxi-analytics-platform](https://img.shields.io/github/stars/hassanzaibhay/nyc-taxi-analytics-platform?style=social&label=nyc-taxi-analytics)](https://github.com/hassanzaibhay/nyc-taxi-analytics-platform)

---

<p align="center">
  <sub>M.Phil. in Computer Science (PUCIT) · Published research in Blockchain performance optimization (Hyperledger Fabric — 3–4x throughput improvement) · AWS Certified Data Engineer · Senior Backend &amp; Data Engineer · Open to remote opportunities (EU / US / Middle East)</sub>
</p>
