# Ganeshan · Software Engineer & Systems Builder

**Full-Stack Engineering · Machine Learning Systems · Decision Intelligence**  
*Designing and shipping production-grade platforms with robust backends, quantitative ML inference, and responsive user experiences.*

[![GitHub](https://img.shields.io/badge/GitHub-GANESHANCS-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/GANESHANCS)
[![FastAPI](https://img.shields.io/badge/Backend-FastAPI%20%7C%20Spring%20Boot-009688?style=flat-square&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![React](https://img.shields.io/badge/Frontend-React%2018%20%7C%20TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://react.dev/)
[![ML](https://img.shields.io/badge/ML-XGBoost%20%7C%20LightGBM%20%7C%20SHAP-FF6F00?style=flat-square)](https://xgboost.readthedocs.io/)
[![Status](https://img.shields.io/badge/Focus-Production%20Systems%20%26%20ML-10B981?style=flat-square)](https://github.com/GANESHANCS)

---

## What I Build

- Full-stack production systems with clean modular architecture
- Machine-learning inference platforms with explainability and confidence intervals
- Decision intelligence systems with human-in-the-loop review boundaries
- Data-intensive applications with robust schema management
- Secure REST APIs with cryptographic integrity and audit trails
- Operational dashboards and low-latency progressive web applications

---

## Core Engineering

- **Languages:** Python · TypeScript · Java · JavaScript · C# · SQL
- **Backend:** FastAPI · Spring Boot · Flask · Pydantic · SQLAlchemy
- **ML & Data:** XGBoost · LightGBM · Scikit-Learn · SHAP · Pandas · NumPy
- **Frontend:** React · TypeScript · Vite · Tailwind CSS · Framer Motion · Recharts
- **Infrastructure & Tooling:** Docker · Docker Compose · Alembic · Git · GitHub Actions

---

## Engineering Principles

- **Temporal Validation for ML Systems:** Quantitative and risk models enforce temporal anti-leakage boundaries; model evaluations are strictly validated out-of-time rather than using naive random splits.
- **Human-in-the-Loop Decision Boundaries:** Automated scoring remains strictly advisory; high-stakes financial, administrative, or operational state transitions require explicit reviewer authorization.
- **Explainable Model Inference:** All predictive outputs provide transparent attribution (e.g. TreeExplainer SHAP values) so operators understand the exact drivers behind each decision.
- **Cryptographic Auditability:** Critical records, representment evidence, and system mutation trails are sealed with SHA-256 digests and immutable append-only logs.
- **Automated Testing:** Business-critical calculation engines, API contracts, and decision boundaries are protected by comprehensive test suites (`pytest`).
- **Reproducible Deployments:** Environments are containerized with Docker, schemas are tracked via Alembic migrations, and builds are verified before release.

---

## Featured Systems

### [ChargeShield — AI Chargeback Defense & Decision Intelligence](https://github.com/GANESHANCS/ChargeShield)
*AI-powered chargeback defense and decision-intelligence platform with explainable ML, evidence generation, and human-in-the-loop review.*

- **Problem:** Digital merchants suffer negative net recovery when blindly contesting chargebacks due to non-refundable network fees and staff overhead on unwinnable disputes.
- **Architecture:** 4-tier decoupled architecture featuring a **FastAPI** REST API gateway, **React 18 / TypeScript** operational dashboard, **LightGBM** win-probability model, and **ReportLab** dynamic PDF synthesis engine.
- **Key Capabilities:**
  - Cost-sensitive net recovery scoring balancing win probability against filing fees.
  - Dual-layer **SHAP** TreeExplainer attribution for transparent operational explainability.
  - Deterministic state machine enforcing strict human-in-the-loop authorization boundaries.
  - SHA-256 cryptographic evidence hashing and append-only decision audit logging.
  - **194 passing automated unit and integration tests** covering API security, model calibration, and document generation.
- **Stack:** `Python 3.10+` · `FastAPI` · `React 18` · `TypeScript` · `LightGBM` · `SHAP` · `ReportLab` · `SQLite/PostgreSQL` · `Alembic` · `pytest`

---

### [PL ValuEdge — Quantitative Football Valuation & ML Engine](https://github.com/GANESHANCS/premier-league-valuation)
*Quantitative football transfer valuation platform using XGBoost, temporal validation, FastAPI, and an interactive React terminal.*

- **Problem:** Football player transfer valuations are often distorted by media hype, recency bias, and crowd consensus; recruitment analysts lack quantitative, empirical fair-value baselines.
- **Architecture:** **GitHub Pages** React 18 PWA frontend communicating with a containerized **FastAPI** backend, querying a 358 MB SQLite database delivered via compressed GitHub Release assets.
- **Key Capabilities:**
  - Real-time fair value inference powered by an **XGBoost 2.0+** regression model.
  - Out-of-time temporal validation achieving an **Out-of-Time WAPE of 12.89%** and **R² of 0.9457** across 50,149 players and 1.89M match appearances.
  - 80% empirical log-space residual prediction intervals $[p_{10}, p_{90}]$ quantifying market valuation uncertainty.
  - Interactive multi-player comparison terminal with Framer Motion animations and Recharts visualizers.
- **Live Terminal:** 🌐 [PL ValuEdge Web Application](https://ganeshancs.github.io/premier-league-valuation/)
- **Stack:** `Python 3.11` · `XGBoost` · `Scikit-Learn` · `FastAPI` · `React 18` · `Vite` · `Tailwind CSS` · `Framer Motion` · `SQLite`

---

### [CAREFlow India — Healthcare Workflow & HMIS Capacity Analytics](https://github.com/GANESHANCS/careflow)
*Healthcare workflow and HMIS analytics platform for facility capacity monitoring and healthcare demand forecasting.*

- **Problem:** Public health administrators require real-time visibility into bed occupancy, outpatient footfall, and regional resource allocation based on civic health reporting.
- **Architecture:** Containerized **FastAPI** service with **SQLAlchemy 2.0** and **PostgreSQL**, connected to a **React 18 + Tailwind v4** operational dashboard orchestrated via **Docker Compose**.
- **Key Capabilities:**
  - Automated ingestion and quality validation pipeline for Indian Ministry of Health & Family Welfare (MoHFW) HMIS datasets.
  - Multi-variable time-series forecasting for outpatient visits (OPD), inpatient admissions, and institutional deliveries.
  - Alembic-managed relational schema migrations with strict data provenance tracking.
- **Stack:** `FastAPI` · `Python` · `React 18` · `TypeScript` · `Tailwind v4` · `PostgreSQL` · `Docker Compose` · `Alembic` · `pytest`

---

### Bill Fraud Detection *(Local / Upcoming Showcase)*
*Healthcare billing fraud and anomaly detection platform analyzing insurance claim irregularities.*

- **Problem:** Health insurance providers and healthcare administrators face high loss ratios due to duplicate billing, upcoding, and fraudulent claim submissions.
- **Status:** Complete local full-stack implementation; scheduled for public GitHub release following final sanitization.
- **Architecture:** **FastAPI** ML inference backend and **React** dashboard analyzing claim anomalies and provider fraud risk patterns.
- **Stack:** `Python` · `FastAPI` · `React` · `Docker` · `Pandas` · `Scikit-Learn`

---

## Collaboration

### [ZoneZero — Gamified Disaster Readiness & Meteorological Platform](https://github.com/Gauth777/ZoneZero)
*Interactive disaster preparedness platform with real-time weather alerting and gamified incident response simulations.*

- **Role & Collaboration:** Collaborative open-source engineering project with core contributor access.
- **Architecture:** **Java 17** and **Spring Boot** backend consuming live **OpenWeather REST APIs**, paired with dynamic web interfaces and SQLite persistence.
- **Key Capabilities:**
  - Dynamic severity classification (Green / Yellow / Red) based on meteorological threshold triggers.
  - Gamified disaster response simulations and quiz evaluation engines.
- **Stack:** `Java 17` · `Spring Boot` · `Maven` · `SQLite` · `OpenWeather API` · `HTML5/CSS3/JavaScript`

---

## Connect

- **GitHub:** [github.com/GANESHANCS](https://github.com/GANESHANCS)
- **Location:** Chennai, India
