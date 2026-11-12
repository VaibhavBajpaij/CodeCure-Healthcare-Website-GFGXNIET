# CodeCure — AI-Assisted Healthcare & Symptom Prediction Web App

[![Python](https://img.shields.io/badge/Python-Flask-3776AB?style=flat-square&logo=python&logoColor=white)](https://github.com/VaibhavBajpaij/CodeCure-Healthcare-Website-GFGXNIET)
[![ML](https://img.shields.io/badge/ML-Scikit--Learn_%26_TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)](https://github.com/VaibhavBajpaij/CodeCure-Healthcare-Website-GFGXNIET)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)

**CodeCure** is a full-stack Python **Flask** and **SQLAlchemy** healthcare web application featuring patient/doctor appointment workflows, automated PDF prescription generation, health analytics with **Plotly**, and symptom-based disease prediction powered by **Scikit-learn** and **TensorFlow**.

---

## Key Features

- **Patient & Doctor Portals:** Registration, role-based views, session authentication, and appointment booking/status tracking via SQLite/SQLAlchemy.
- **Symptom-Based Disease Prediction:** Decision Tree classifier (`scikit-learn`) trained on 132 clinical symptom indicators returning predicted diagnosis and probability score.
- **Diagnostics & Medical Imaging Modules:** Dedicated endpoints for lung and cataract screening workflows (`TensorFlow / Keras`).
- **Prescription PDF Export & Mail Alerts:** Dynamic prescription PDF generation (`ReportLab`) and SMTP notifications (`Flask-Mail`).

---

## Architecture Overview

```mermaid
flowchart LR
    U[Patient / Doctor Browser] --> F[Flask Routes & Jinja2 Templates]
    F --> DB[(SQLite / SQLAlchemy ORM)]
    F --> ML[Scikit-learn & TensorFlow Predictors]
    F --> PDF[ReportLab PDF & Flask-Mail]
```

---

## Local Setup

```bash
git clone https://github.com/VaibhavBajpaij/CodeCure-Healthcare-Website-GFGXNIET.git
cd CodeCure-Healthcare-Website-GFGXNIET
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

Create a `.env` file with `FLASK_SECRET_KEY`, `MAIL_SERVER`, `MAIL_USERNAME`, and `MAIL_PASSWORD`, then run:

```bash
python app.py
```

---

## Tech Stack

`Python` · `Flask` · `SQLAlchemy` · `SQLite` · `Scikit-learn` · `TensorFlow` · `Plotly` · `Pandas` · `ReportLab`
