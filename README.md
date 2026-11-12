<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,30&height=200&section=header&text=hey,%20i'm%20cárol%20✨&fontSize=52&fontColor=22ff7b&fontAlignY=38&desc=data%20scientist%20·%20data%20engineering%20%F0%9F%87%A7%F0%9F%87%B7&descColor=ffffff&descAlignY=58&descSize=18&animation=fadeIn" />

[![Python](https://img.shields.io/badge/Python-22ff7b?style=for-the-badge&logo=python&logoColor=000000)](https://python.org/)
[![SQL](https://img.shields.io/badge/SQL-ff1de9?style=for-the-badge&logo=postgresql&logoColor=ffffff)](https://github.com/carollinaanderson/ML_lexpredict)
[![MLflow](https://img.shields.io/badge/MLflow-8b53fe?style=for-the-badge&logo=mlflow&logoColor=ffffff)](https://github.com/carollinaanderson/ML_lexpredict)
[![Docker](https://img.shields.io/badge/Docker-22ff7b?style=for-the-badge&logo=docker&logoColor=000000)](https://github.com/carollinaanderson/TOOL_task-manager-api)
[![Git](https://img.shields.io/badge/Git-d0ff00?style=for-the-badge&logo=git&logoColor=000000)](https://git-scm.com/)

<br/>

> _end-to-end ML systems · leakage-safe evaluation · data governance as engineering, not slides_

</div>

---

## 👩‍💻 about me

```python
carol = {
    "name"       : "Carolinna Anderson",
    "location"   : "Campo Grande, MS · Brazil 🇧🇷",
    "role"       : "Data Scientist (with Data Engineering depth)",
    "contact"    : "carollinaanderson@icloud.com",
    "languages"  : ["Portuguese (native)", "English (fluent)", "Spanish", "French"],
    "education"  : ["B-Tech Data Science · UFMS", "MBA Data Science & Software Architecture · PUC-PR"],
    "currently"  : "leakage-safe ML pipelines, SHAP explanations, LGPD-aware data governance",
}
```

**What I do, in three lines:**

1. Build end-to-end data and ML systems in Python and SQL: ETL, validation, event-driven ingestion, and classification/forecasting models (LightGBM, XGBoost, Random Forest) explained to non-technical stakeholders with SHAP and p-values.
2. Report model results honestly: temporal validation with leakage control, explicit baselines, confidence intervals, and error slices. If the model does not beat the baseline, the repo says so.
3. Treat data protection as engineering: LGPD/GDPR principles mapped to tests, pseudonymization with keyed hashing, PII gates that fail closed, and secrets scanning in CI. See [`ML_lexpredict/docs/LGPD.md`](https://github.com/carollinaanderson/ML_lexpredict/blob/main/docs/LGPD.md) for what is implemented and where.

---

## 📌 featured projects

| repo | what it proves | stack |
|---|---|---|
| [ML_lexpredict](https://github.com/carollinaanderson/ML_lexpredict) | Leakage-safe ML pipeline for claim value (regression) and appeal outcome (classification) on the public ABJ `abjData::consumo` sample (real TJSP court metadata, MIT-licensed, pseudonymized; synthetic fixtures for tests only). SQL ABT with rolling-window CTEs, temporal validation, LightGBM, exact TreeSHAP, MLflow, FastAPI, Docker, CI, LGPD pseudonymization with a documented risk assessment. | `Python` `SQL` `LightGBM` `SHAP` `MLflow` `FastAPI` `Docker` `LGPD` |
| [TOOL_task-manager-api](https://github.com/carollinaanderson/TOOL_task-manager-api) | Production-grade REST API: Clean Architecture, JWT/OAuth2, PostgreSQL, Docker Compose (multi-stage, non-root), Alembic migrations, pytest (unit + integration), Bandit security scanning, GitHub Actions CI. | `FastAPI` `SQLAlchemy 2.0` `Pydantic v2` `PostgreSQL` `Alembic` `Bandit` |
| [LLM_marketing-os-demo](https://github.com/carollinaanderson/LLM_marketing-os-demo) | Sanitized public demo of a 10-agent orchestration system with MCP tool use (phase handoffs, human-approval gates). Client version under NDA. | `LLM agents` `MCP` `multi-agent` |
| [OPS_documentation-guide](https://github.com/carollinaanderson/OPS_documentation-guide) | Engineering documentation standards: clean code, maintainable architecture, testing strategies, Git workflows. | `docs-as-code` `Mermaid` |

---

## 🛠️ tech stack

**Languages & core:** Python · SQL (PostgreSQL, MySQL, Athena) · Rust (curator migration)

**Machine learning:** LightGBM · XGBoost · Random Forest · scikit-learn · PyTorch · TensorFlow · SHAP · permutation importance · MLflow · hypothesis testing (p-values) · leakage-safe temporal validation

**Data engineering:** ETL/ELT pipelines · web scraping · data validation · S3 data lakes · event-driven ingestion (webhooks, queues, workers) · pandas

**Cloud:** AWS (S3, Athena, Lambda, EC2, Glue, QuickSight, SageMaker) · Databricks/Spark (working knowledge)

**GenAI & agentic AI:** agents with tool use (MCP servers) · RAG · vector search · multimodal LLM pipelines · batch LLM annotation · prompt engineering

**Engineering & DevOps:** FastAPI · Pydantic · SQLAlchemy · Docker (multi-stage, non-root) · GitHub Actions CI · pytest · Alembic · Git/GitHub

**Documented in:** [professional experience details](#-experience-in-short) below; work performed for employers is in private repos under NDA and is described in the CV, not published here.

---

## 💼 experience in short

| role | where | highlights |
|---|---|---|
| Data & AI Consultant | Stardust Studio (2025- ) | 10-agent GenAI orchestration with MCP tool use; event-driven ingestion pipeline (webhook, queue, workers, PostgreSQL) with batch multimodal LLM annotation; RAG from first principles |
| Analytics Engineer → Data/ML Engineer | Mascarenhas Barbosa Advogados (2023-2024) | 42 data/ML projects end to end on 20,000+ legal documents; classification models for case outcome and prioritization; validation pipelines that cut missing data from 98% to 0.2%; AWS migration (S3, Athena, Lambda, QuickSight); trained 80+ staff |
| Data Science Research Specialist & Instructor | Self-employed (2022-2025) | 3 live UFMS workshops (AI 2024; MedTech/HealthTech 2025, 2,000+ views); mentored a team through an end-to-end Databricks workflow on 40 years of INCA childhood cancer data |
| Undergraduate Research Fellow (CNPq PIBIC) | LEPHA/UFMS (2017-2018) | quantitative/qualitative documentary research on 1860s war logistics |

---

<details>
<summary>📈 the gap, and the comeback (in the git log)</summary>

<br/>

> _371 commits in 24 months while employed · **0 commits for 11 straight months** after burnout._

| phase | period | commits | rhythm |
|---|---|---|---|
| 🏢 employed · ML/Data Engineer | Jan 2023 – Dec 2024 | **371** | ~15/month · 21 of 24 months active |
| 🧭 unemployed · job-hunting | Jan – Apr 2025 | 45 | ~11/month |
| 🖤 **burnout void** | **May 2025 – Mar 2026** | **0** | **11 months · zero commits** |
| 🌱 recovery | Apr – Sep 2026 | 120 | back to ~20/month |

A 15-commits-per-month engineer doesn't "take a break" for 11 months. That's burnout: the thing I loved became physically unreachable. The cause has a name, and it resolved.

**The comeback is in the same log:** August 2026 was my best month ever — 82 commits across 9 repos (curator pipeline, AIgency, Stardust Studio, Rust/Dioxus). Burnout broke the streak; the git history proves I rebuilt it.

</details>

---

## 📬 let's connect

<div align="center">

[![Email](https://img.shields.io/badge/carollinaanderson@icloud.com-22ff7b?style=for-the-badge&logo=apple&logoColor=000)](mailto:carollinaanderson@icloud.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-8b53fe?style=for-the-badge&logo=linkedin&logoColor=fff)](https://linkedin.com/in/carollinaanderson)
[![GitHub](https://img.shields.io/badge/carollinaanderson-ff1de9?style=for-the-badge&logo=github&logoColor=fff)](https://github.com/carollinaanderson)

</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,30&height=100&section=footer&text=always%20learning%20·%20always%20shipping%20💚&fontSize=16&fontColor=22ff7b&fontAlignY=65" />
</div>
