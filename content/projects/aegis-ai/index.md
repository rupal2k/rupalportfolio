---
title: Aegis AI
date: '2025-03-01'
summary: AI-powered group insurance underwriting platform — XGBoost risk scoring, SHAP explainability, dynamic premium zoning, and a dual-persona dashboard.
tags:
  - XGBoost
  - FastAPI
  - Streamlit
  - Python
  - Machine Learning
image:
  caption: 'Aegis AI — predictive underwriting intelligence'
  focal_point: Smart
---

Aegis AI is an end-to-end group insurance underwriting platform that moves insurers from reactive, historical-claims pricing to real-time predictive intelligence.

**The 5-step intelligence pipeline:**
1. **Ingest** — HRMS, wearables, and clinical notes (19K+ discharge notes parsed)
2. **Score** — XGBoost engine processes 21 engineered health features with Bayesian hyperparameter optimization (Optuna, 60-trial TPE, 3-fold CV)
3. **Explain** — SHAP analysis surfaces the top 5 traceable risk drivers per employee in plain language for underwriters
4. **Price** — Asymmetric zone multipliers: up to 15% discount for healthy workforces, up to 30% loading on critical risk profiles
5. **Report** — Role-based dashboards (Underwriter Console + HR Manager Dashboard) with on-demand ReportLab PDFs

**Dual-persona workspace:** Underwriters see a macro portfolio of 20+ companies ranked by risk; HR managers see only their own company data, enforced via app-level RBAC.

**Deployed on:** Hugging Face Spaces (Streamlit dashboard) · Render (FastAPI backend) · Neon (Serverless Postgres)

**Security:** JWT bearer auth · bcrypt password hashing · HIPAA/SOC 2 aligned headers (HSTS, CSP, X-Frame-Options) · 5 req/min rate limiting

**Stack:** Python · XGBoost · SHAP · FastAPI · Streamlit · PostgreSQL · ReportLab · Docker
