# Predictive Maintenance Case Study: AI4I 2020 Dataset

This repository presents a real-world, end-to-end machine learning pipeline for predicting machine failures using multisensor time series data. Built for reliability, explainability, and industrial deployment, this project demonstrates how XGBoost and SHAP can power interpretable AI in manufacturing environments.

---

## Key Features

- Exploratory Data Analysis with 10+ visualizations
- Real failure mode analysis: HDF, TWF, OSF, etc.
- Predictive Modeling with XGBoost and RandomForest
- SHAP Explainability to uncover feature impact
- IEEE-Style Architecture Diagram (for paper & deployment)
- Research-ready paper draft targeting IEEE Access

---

## 📊 Dataset

- Source: [AI4I 2020 - Kaggle](https://www.kaggle.com/datasets/shrutimechlearn/ai4i2020-predictive-maintenance-dataset)
- Description: 10,000 records of machine sensor telemetry with 5 types of failures labeled.
- Key Features: Torque, RPM, Temperatures, Tool Wear

---

## Getting Started

```bash
git clone https://github.com/your-username/predictive-maintenance-case-study-ai4i2020.git
cd predictive-maintenance-case-study-ai4i2020
pip install -r requirements.txt
jupyter notebook
```

## Folder Structure
```
├── data/                 # Dataset CSV
├── notebooks/            # 5 structured Jupyter notebooks
├── plots/                # All exported PNG charts
├── diagrams/             # Architecture diagram
├── src/                  # Python scripts for modeling
├── report/               # IEEE paper drafts (Markdown/LaTeX)
├── requirements.txt
└── README.md

```
## Research Paper Preview
I am preparing a journal submission for IEEE Access titled:

"Predicting Machine Failures with Multisensor Time Series: A Real-World Case Study"

📬 Coming soon in [report](/report/ieee_draft.md).