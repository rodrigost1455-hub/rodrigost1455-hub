# Hi, I'm Rodrigo Santana 👋

**AI Engineer · Quality Engineering Background · M.Sc. Artificial Intelligence (Dec 2026)**

I build AI-powered systems for environments where software failures have physical consequences. My background is 3+ years as a Quality Engineer in Tier-1 automotive manufacturing (Ford, GM, Stellantis supply chain) — which means I don't just write models, I understand the operational context they live in: what a defect escape costs, why interpretability matters when you're answering to Ford, and how to frame a business decision as an ML problem.

Currently transitioning fully into AI Engineering, with production experience in Claude API + LangChain + FastAPI and a growing ML portfolio anchored in real industrial data.

---

## 🔧 What I build

```python
stack = {
    "AI / ML":     ["Claude API", "LangChain", "scikit-learn", "XGBoost",
                    "IBM Watson AutoAI", "pandas", "SMOTE", "GridSearchCV"],
    "Backend":     ["FastAPI", "Python", "Node.js", "PostgreSQL", "Supabase"],
    "Frontend":    ["React", "Next.js", "Vite", "Tailwind CSS"],
    "Deployment":  ["Vercel", "Railway", "Docker"],
    "Domain":      ["IATF 16949", "SPC", "APQP", "8D", "FMEA",
                    "Automotive Quality", "PHEV Electronics"],
}
```

---

## 🚀 Featured Projects

### 🦇 Batcomputer ML — Interactive ML Explainer
> *Teaching ML to non-technical audiences through real industrial data*

Single-page interactive web experience covering the full machine learning workflow applied to a real automotive sensor classification problem (462 Hall-effect sensors, Ford South Africa failure analysis). Features a live precision/recall trade-off slider, scroll-triggered chapter narrative, and Python code snippets — built to communicate ML decisions to non-technical stakeholders.

`React` `Vite` `Tailwind` `Framer Motion`
[🌐 Live](https://batcomputer-ml-educativo.vercel.app/)

---

### 📓 Batcomputer ML — End-to-End Colab Notebook
> *63-cell ML pipeline on real industrial data, explained line by line*

Complete Jupyter notebook covering EDA, preprocessing, 5-model comparison, custom decision thresholds, cross-validation, feature importance, GridSearchCV hyperparameter tuning, and SMOTE class balancing — on a real dataset of 462 automotive current sensors. Every code line is commented; every section builds intuition before code.

**Results:** 79% villain recall → 82% precision after SMOTE · `Margen_Ford_mV` confirmed as top feature · threshold tuned from business cost asymmetry (escaped defect >> false rejection)

`Python` `scikit-learn` `XGBoost` `imbalanced-learn` `pandas` `matplotlib`
[📓 Open in Colab](#) · [📁 GitHub Repo](#)

---

### 🤖 Predictive Maintenance — IBM AutoAI + Next.js
> *AutoML pipeline from model selection to production deployment*

End-to-end predictive maintenance classifier on the AI4I industrial benchmark dataset. Uses IBM Watson AutoAI to train and compare models, deployed as an interactive Next.js application. Demonstrates the full cycle from AutoML to production inference UI.

`Python` `scikit-learn` `XGBoost` `imbalanced-learn` `pandas` `matplotlib`
[📓 Colab](https://colab.research.google.com/drive/1394slKkrrFrh3NdkriYK7LtGKczcvQYI?usp=sharing) · [📁 GitHub](https://github.com/rodrigost1455-hub/Mantenimiento_Predictivo_MJ)

---

### 📊 StatPro Industrial — SPC Platform
> *Offline-first SPC web platform deployed inside Yazaki's corporate firewall*

Production-grade Statistical Process Control platform with Cp/Cpk/Pp/Ppk, P-Charts, Attribute Gage R&R, and PDF/XLSX export. Zero external dependencies — fully functional inside a closed corporate network. Active internal use at Yazaki YED.

`React` `Vite` `JavaScript` `IATF 16949`
[🌐 Live](https://stat-pro-ebcp.vercel.app/)

---

### ⚙️ FA Report Automation System
> *12-page technical PDFs generated automatically from raw inspection data*

Full-stack system that replaces a 3-hour manual process with a sub-2-minute automated pipeline. Inspectors input raw failure analysis data; the system generates a complete, formatted 12-page PDF report. Deployed on Railway with FastAPI + Next.js + Supabase.

`FastAPI` `PyMuPDF` `Next.js` `Supabase` `Railway` `Python`

---

### 📋 8D Quality Management System
> *Internal non-conformance tracking and corrective action platform*

Web application for 8D problem-solving workflow management: D1–D8 wizard, SLA banners, email notifications, and executive reporting. Built as an alternative to Power Apps for Yazaki's Dev/IT stack.

`React` `FastAPI` `PostgreSQL` `Railway`

---

### 🏪 Axionix — Business Operating System *(Founder & Lead Developer)*
> *Multi-tenant SaaS platform for SMBs — 6+ active clients*

Full-stack SaaS and POS system across three product divisions (Core SaaS, POINT POS, Enterprise) sharing unified auth, DB, and real-time sync. WhatsApp AI agent handling 1,800+ SKUs. Active deployments across Durango, Mexico.

`React` `FastAPI` `Supabase` `Next.js` `Vercel` `Twilio`
[🌐 Live](https://axionix-seven.vercel.app/)

---

## 📌 Now

- 🏭 **Working:** Quality/AI Engineer @ Yazaki YED — building internal AI tools for manufacturing
- 🎓 **Studying:** M.Sc. Artificial Intelligence @ Universidad Tecmilenio (Dec 2026)
- 🌍 **Open to:** AI Engineer, ML Engineer, Forward Deployed Engineer roles — Mexico (~40k MXN) or international (~90k USD). Open to relocation.
- 🔑 **Differentiator:** Claude API + LangChain + FastAPI in production, anchored by real domain expertise in automotive quality

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/tu-perfil)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:tu@email.com)

---

*4× Anthropic Certified (Claude API · Agent Skills · MCP · Claude Code) · C1 English (ITEP)*
