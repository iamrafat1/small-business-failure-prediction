# AI-Driven Small Business Failure & Survival Analysis (USA, 2017–2022)

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Jupyter Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Project-Active-success)

---

## 📌 Project Overview  
This project builds a data-driven, AI-assisted framework to analyze **U.S. small-business survival, failure risk, and economic vulnerability** using multi-year datasets published by the **U.S. Small Business Administration (SBA)** and the **U.S. Bureau of Labor Statistics (BLS)**.

The purpose of this analysis is to understand trends in business formation, labor costs, receipts distribution, and industry-level risk, and to support **evidence-based policymaking, entrepreneurship strategy, and economic development research**.

---

## 🎯 Key Features

✅ Multi-year trend analysis of U.S. business activity (2017–2022)  
✅ Survival & failure patterns using BLS cohort model  
✅ Industry-level risk classification using Random Forest (AUC ≈ **0.992**)  
✅ Comparison of micro-, small-, and large-enterprise economic impact  
✅ Automatic detection of high-risk industries and policy recommendations  
✅ Single Jupyter Notebook — fully reproducible and parameterized  

---

## 📂 Repository Contents

| File | Description |
|-------|-------------|
| `small_business.ipynb` | Main analysis notebook (EDA, ML, risk insights, plots) |
| `us_business.csv` | SBA dataset (firm size, employment, payroll, receipts) |
| `us_business_year.csv` | Industry-year dataset for predictive modeling |
| `us_business_new.csv` | Cleaned dataset used in notebook |
| `bls.csv` | BLS business cohort survival dataset |
| `requirements.txt` | Python dependencies |
| `*.jpeg` | Exported charts used in this README |

---

## 📊 Key Visual Outputs

#### 1️⃣ Multi-Year Trend Analysis (SBA)
![Business Trends](trends.jpeg)

#### 2️⃣ High-Risk Industry Failure Probability
![Risk Dashboard](highrisk.jpeg)

#### 3️⃣ Receipts vs Labor Cost Comparison
![Receipts vs Labor Cost](small%20business.jpeg)

#### 4️⃣ Small-Business Failure Rate (BLS Cohorts)
![Failure Rate](failure%20rate.jpeg)

---

## 📈 Predictive Model Summary

| Model | Type | AUC Score |
|--------|------|-----------|
| Random Forest | Classification | **0.992** |
| Gradient Boosting | Classification | 0.964 |

**Most influential risk factors:**
- % of micro-enterprises in the industry  
- Labor cost ratio for small employers  
- Small-firm receipts share vs overall revenue  
- Productivity per employee and per firm  

---

## 📑 Research Background  

This repository also supports the author’s accepted IEEE research paper:

> **Mahmud, I. (2025). _“AI-Enabled Small Business Survival Analysis in the United States.”_ IEEE ICECET 2025, Paris.**  
> The research is used as supporting evidence in an EB-2 NIW immigration petition to demonstrate U.S. national-interest impact.

---

## 🚀 How to Run the Notebook

### 1️⃣ Install dependencies
```bash
pip install -r requirements.txt
