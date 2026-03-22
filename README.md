# RetailPulse 360

### AI-Powered Demand, Risk & Action Intelligence for E-Commerce

RetailPulse 360 is an end-to-end retail analytics system designed to analyze sales performance, predict product demand risk, detect revenue leakage, and generate AI-driven business recommendations.

The project simulates a real-world e-commerce analytics environment similar to Amazon or Flipkart by combining **data engineering, SQL analytics, machine learning, and interactive business dashboards**.

---

# Project Objective

Traditional dashboards only show what happened.

RetailPulse 360 goes further by answering:

• Which products will stop selling soon?
• Where is the company losing revenue?
• Which products require inventory adjustment?
• What business action should be taken automatically?

---

# Tech Stack

Python
SQL (MySQL)
Excel
Power BI
Machine Learning (Scikit-learn / XGBoost)

---

# Project Architecture

Raw Dataset
↓
Python Data Cleaning & Feature Engineering
↓
Advanced SQL Business Intelligence
↓
Machine Learning Models
↓
AI Recommendation Engine
↓
Power BI Interactive Dashboard

---

# Dataset

Online Retail Dataset containing **500,000+ transactions** including:

InvoiceNo
StockCode
Quantity
UnitPrice
CustomerID
Country
InvoiceDate

---

# Key Modules

## 1. Data Cleaning & Feature Engineering (Python)

Performed data preprocessing using Pandas:

• Removed cancelled orders
• Handled missing values
• Converted transaction timestamps
• Created revenue and transaction features

Key features created:

TransactionCount
AveragePrice
PurchaseFrequency
ProductFailureIndicator

---

## 2. Advanced SQL Intelligence

Used SQL analytics to extract business insights.

Key SQL techniques:

CTEs
Window Functions
Ranking
Aggregation

Examples:

Revenue by Country
Top Selling Products
Demand Segmentation
Revenue Leakage Detection

Example insight:

Top 20% products generate the majority of total revenue.

---

## 3. Machine Learning Layer

Two predictive models were developed.

### Demand Prediction Model

Predicts future product demand based on historical transaction behavior.

Algorithm:
Random Forest Regressor

---

### Product Failure Risk Model

Predicts products likely to stop selling in the near future.

Algorithm:
XGBoost / Random Forest

Output Example:

Product 85123A → 82% probability of demand failure

---

## 4. AI Recommendation Engine

A Generative AI layer produces business strategies automatically.

Examples:

Low Demand Product
→ Run a promotional discount campaign

High Demand Product
→ Increase inventory to prevent stockouts

Slow Moving Inventory
→ Apply aggressive pricing strategy

---

## 5. Power BI Dashboard

An interactive analytics dashboard visualizes business intelligence and predictive insights.

Dashboard Features:

• Total Revenue KPI
• Customer & Order Metrics
• Monthly Sales Trends
• Revenue by Country
• Top Selling Products
• Product Demand Segmentation
• Revenue at Risk Metric
• AI-Driven Product Risk Panel

---

# Key Business Insights

### Dead Inventory Trap

Approximately **40% of products contribute less than 5% of revenue**.

Recommendation
Remove or discount slow-moving inventory.

---

### High Demand Supply Gap

Certain high-demand products frequently go out of stock.

Recommendation
Increase inventory levels to prevent revenue loss.

---

### Discount Dependency

Some product categories only sell during promotional discounts.

Recommendation
Reevaluate pricing strategy.

---

# Project Structure

RetailPulse360
│
├── data
│   └── retail_dataset.csv
│
├── python
│   ├── data_cleaning.ipynb
│   ├── feature_engineering.ipynb
│   └── machine_learning_models.ipynb
│
├── sql
│   └── advanced_retail_analysis.sql
│
├── powerbi
│   └── RetailPulse360_Dashboard.pbix
│
├── images
│   └── dashboard_screenshots
│
└── README.md

---

# Business Impact

RetailPulse 360 identifies:

• Revenue leakage
• Product demand risks
• Inventory inefficiencies

and provides **data-driven strategic recommendations** to improve revenue performance.

---

# Author

Vridhi Jain
B.Tech – Information Technology

Focused on Data Analytics, Machine Learning, and Business Intelligence.
