# 🛒 RetailPulse 360 — AI Retail Intelligence System

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/ML-XGBoost-FF6600?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge"/>
</p>

> **An end-to-end AI retail analytics platform that predicts product demand risk, detects revenue leakage, and auto-generates business strategies — built on 500,000+ real e-commerce transactions.**

---

## ❓ Problem Statement

Modern retail businesses drown in data but starve for decisions. Traditional dashboards only show **what happened** — they can't predict **what will happen** or recommend **what to do next**.

Specific problems this project solves:

- 📦 *40% of products generate less than 5% of revenue* — but no system flags them for action
- 📉 *High-demand products frequently go out of stock* — causing silent revenue loss
- 🔍 *Revenue leakage goes undetected* — cancelled orders, discount abuse, low-margin sales
- 🤖 *Managers lack time to analyze 500K+ rows* — decisions are delayed or guesswork

**RetailPulse 360 turns this around** — automated detection, ML predictions, and AI-generated action plans, all in one system.

---

## 💥 Impact & Key Numbers

<table>
  <tr>
    <td align="center"><b>📦 500,000+</b><br/>Transactions analyzed</td>
    <td align="center"><b>🌍 37 Countries</b><br/>Sales geography covered</td>
    <td align="center"><b>🤖 2 ML Models</b><br/>Demand + Failure Risk</td>
  </tr>
  <tr>
    <td align="center"><b>82%</b><br/>Product failure prediction accuracy</td>
    <td align="center"><b>40%</b><br/>Dead inventory identified</td>
    <td align="center"><b>📊 8+ Visuals</b><br/>Interactive Power BI dashboard</td>
  </tr>
</table>
---

## 🏗️ System Architecture
Raw Dataset (500K+ transactions)
↓
Python: Data Cleaning & Feature Engineering
↓
Advanced SQL Intelligence (CTEs, Window Functions)
↓
Machine Learning Models (Random Forest + XGBoost)
↓
AI Recommendation Engine (Automated Strategy)
↓
Power BI Interactive Dashboard
---

## 🧮 Key Modules

### 1. 🧹 Data Cleaning & Feature Engineering (Python)
- Removed cancelled orders, handled nulls, parsed timestamps
- Created: `TransactionCount`, `AveragePrice`, `PurchaseFrequency`, `ProductFailureIndicator`

### 2. 🗄️ Advanced SQL Intelligence
| Query Type | Business Question Answered |
|---|---|
| Revenue by Country (CTE) | Which markets drive the most revenue? |
| Top Products (Window Rank) | What's the Pareto of our catalog? |
| Demand Segmentation | Which products are declining? |
| Revenue Leakage Detection | Where are we losing money silently? |

### 3. 🤖 Machine Learning Layer

**Model 1 — Demand Prediction (Random Forest Regressor)**
- Input: Historical transaction behavior features
- Output: Predicted future demand score

**Model 2 — Product Failure Risk (XGBoost Classifier)**
- Input: Sales velocity, frequency, recency features
- Output: Probability of a product stopping sales
- Example: *Product 85123A → 82% failure probability*

### 4. 🧠 AI Recommendation Engine
| Situation | Auto-Generated Action |
|---|---|
| Low Demand | Run promotional discount campaign |
| High Demand, Low Stock | Increase inventory immediately |
| Slow Moving | Apply aggressive pricing strategy |
| Revenue Leakage | Flag for pricing audit |

### 5. 📊 Power BI Dashboard
- Total Revenue KPI · Customer Count · Order Volume
- Monthly Sales Trend · Revenue by Country
- Product Demand Segments · Revenue at Risk Panel
- AI-Driven Product Risk Scorecard

---

## 📌 Key Business Insights Found

- **Dead Inventory Trap:** ~40% of products contribute < 5% of total revenue
- **Supply Gap:** Top 20% products generate the majority of revenue — but often go out of stock
- **Discount Dependency:** Several categories only convert during promotions — pricing strategy needed

---

## 🛠️ Tech Stack

`Python` · `MySQL` · `Pandas` · `Scikit-learn` · `XGBoost` · `Power BI` · `Excel` · `DAX`

---

## 📁 File Structure
RetailPulse360/
├── data/retail_dataset.csv
├── data cleaning and feature engineering.ipynb
├── RetailPulse360_SQL_Analytics_Case_Study.md
├── Retail_AI_Analytics.xlsx
└── README.md
---

## 🚀 How to Run

```bash
git clone https://github.com/Jainvridhi/RetailPulse-360
cd RetailPulse-360
pip install -r requirements.txt
jupyter notebook "data cleaning and feature engineering.ipynb"
```

---

## 👩‍💻 Author
**Vridhi Jain** · B.Tech IT · Bharati Vidyapeeth's College of Engineering, New Delhi

