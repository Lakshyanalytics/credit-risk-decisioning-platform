# 🏦 End-to-End Agentic Credit Risk Engine

### *Bridging Traditional Finance (TradFi) with Generative AI*

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)
![Machine Learning](https://img.shields.io/badge/Model-Logistic%20Regression-orange)
![Llama 3](https://img.shields.io/badge/LLM-Llama%203-green)
![SHAP](https://img.shields.io/badge/Explainability-SHAP-purple)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

---

# 📌 Project Overview

This project demonstrates an **end-to-end Credit Risk Decision Engine** inspired by modern banking workflows.

Rather than stopping at default prediction, the application integrates **credit scorecard modeling**, **AI-assisted decision support**, **portfolio risk analytics**, **stress testing**, and **model monitoring** into a single interactive platform.

The engine follows an interpretable scorecard approach using **Weight of Evidence (WoE)**, **Information Value (IV)**, and **Logistic Regression**, while leveraging **Generative AI** to enhance underwriting decisions and customer communication.

---

# 🚀 Key Features

### ✅ Credit Risk Scorecard

- Weight of Evidence (WoE) Transformation
- Information Value (IV) Feature Selection
- Logistic Regression Scorecard
- Credit Score Generation
- Risk Tier Classification

---

### 🤖 AI Risk Analyst

Powered by **Llama 3** via **Groq API**

Capabilities include:

- Customer decision email generation
- AI-assisted underwriting support
- SHAP-based technical explanation
- Plain-English model interpretation

---

### 📊 Portfolio Analytics

Interactive dashboard including:

- Portfolio Risk Distribution
- Risk Concentration Heatmap
- Loan Purpose Analysis
- Expected Default Rate
- Portfolio Capital Loss Estimation

---

### 📉 Stress Testing

Simulates adverse economic scenarios by:

- Adjusting default probabilities
- Stressing portfolio risk
- Estimating projected capital loss

---

### ⚙️ MLOps Model Monitoring

Production-style monitoring dashboard featuring:

- Model Health Monitoring
- Credit Score Drift Tracking
- Drift Threshold Alerts
- Concept Drift Simulation

---

# 🖥️ Application Preview

## 📝 Loan Application

Predict applicant creditworthiness, generate credit scores, classify borrowers into risk tiers, and visualize feature contributions using SHAP.

<img width="1241" height="803" alt="image" src="https://github.com/user-attachments/assets/f76c54b2-5d4e-4982-95b9-ef4cb501e5e3" />


---

## 📊 Portfolio Risk & Stress Testing

Analyze portfolio-level default risk and simulate changing macroeconomic conditions.

<img width="1476" height="834" alt="image" src="https://github.com/user-attachments/assets/c347b45c-808f-46ae-b3be-75485c6fe016" />


---

## 🤖 AI Risk Analyst

Generate customer communication and explain model decisions using Llama 3.

<img width="1498" height="794" alt="image" src="https://github.com/user-attachments/assets/5c32d99c-b0da-4997-86cf-79ee63cb9e99" />

<img width="1489" height="789" alt="image" src="https://github.com/user-attachments/assets/d5cedd15-1f68-4531-9581-c24999943c9f" />


---

## 📈 MLOps Model Health Monitor

Track score stability and monitor concept drift in production.

<img width="1474" height="807" alt="image" src="https://github.com/user-attachments/assets/ea145245-0860-4e5f-892e-12187543a707" />


---

# 🏗️ Project Structure

```
.
├── 01_credit_risk_data_preprocessing_eda.ipynb
├── agentic_credit_risk_decision_engine.ipynb
├── README.md
```

---

# 🔄 Project Workflow

```
Loan Application
        │
        ▼
Data Preprocessing
        │
        ▼
WoE Transformation
        │
        ▼
Information Value Analysis
        │
        ▼
Logistic Regression Scorecard
        │
        ▼
Probability of Default
        │
        ▼
Credit Score
        │
        ▼
Risk Classification
        │
        ├──────────────┐
        ▼              ▼
 Portfolio         AI Risk Analyst
 Analytics             │
        │              ▼
        │      Customer Communication
        │
        ▼
 MLOps Monitoring
```

---

# 🧠 Machine Learning Pipeline

- Data Cleaning
- Exploratory Data Analysis
- WoE Encoding
- Information Value Analysis
- Logistic Regression
- Credit Score Generation
- SHAP Explainability
- Risk Tier Assignment

---

# 🏗️ Technical Architecture

The application combines traditional credit risk modeling with modern AI technologies to deliver an end-to-end decisioning platform. Each component has a dedicated role, from data preprocessing and scorecard development to explainability, portfolio analytics, AI-assisted underwriting, and deployment.

| Component | Technology | Description |
|-----------|------------|-------------|
| **Data Processing** | Pandas, NumPy | Data ingestion, preprocessing, exploratory analysis, feature engineering, and WoE/IV transformations. |
| **Credit Risk Modeling** | Scikit-learn, Statsmodels | Logistic Regression scorecard development, Probability of Default (PD) estimation, and credit score generation. |
| **Explainability** | SHAP | Explains individual credit decisions by identifying the contribution of each feature to the applicant's credit score. |
| **Portfolio Analytics** | Pandas, Matplotlib, Seaborn | Portfolio-level risk analysis, stress testing, default rate estimation, and capital loss visualization. |
| **Generative AI** | LangChain, Groq API, Llama 3 | AI-powered underwriting assistant for customer communication and technical explanation of model decisions. |
| **Dashboard** | Streamlit | Interactive web application for loan officers and risk managers to evaluate applicants and monitor portfolio performance. |
| **Model Monitoring** | Python, Matplotlib | Simulates model health monitoring, concept drift detection, and score stability tracking. |
| **Deployment** | Streamlit | Local deployment of the interactive credit risk decision engine. |

---

# 📂 Dataset

**German Credit Dataset**

- 1,000 Loan Applicants
- 20 Predictor Variables
- Binary Credit Risk Classification

Source:

https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)

---

# 💼 Business Applications

This project demonstrates concepts commonly used in:

- Credit Risk Analytics
- Retail Banking
- Consumer Lending
- Scorecard Development
- Explainable AI
- Portfolio Risk Management
- Stress Testing
- AI-assisted Underwriting

---

# 🎯 Future Improvements

- Probability of Default (PD) Calibration
- LGD & EAD Estimation
- Expected Credit Loss (ECL)
- Population Stability Index (PSI)
- Champion-Challenger Models
- Automated Model Retraining
- Docker Deployment
- Cloud Deployment

---

# 👨‍💻 Author

**Lakshya Rana**

M.Sc. Financial Economics

Credit Risk | Machine Learning | Generative AI | Data Analytics

LinkedIn: *https://www.linkedin.com/in/lakshyarana01/*

---

## ⭐ If you found this project useful, consider giving it a star!
