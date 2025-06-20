# 💼 Climbing the Ladder: How Gender, Education, and Seniority Shape Pay in the Workplace

> A statistical analysis of how workplace compensation is influenced by gender, education level, and job seniority.

## 📘 Project Overview

This project investigates the intersection of gender, education, and seniority in shaping employee pay using a dataset of 1,000 employee records from Kaggle. Through statistical visualizations and derived metrics, the project uncovers insights about pay gaps, performance, and structural disparities in workplace compensation.

📊 [Dataset on Kaggle](https://www.kaggle.com/datasets/mexwell/employee-performance-and-productivity-data)

---

## 🎯 Objectives

- Analyze how **job seniority** affects performance and base pay.
- Measure the impact of **education level** on earnings growth.
- Quantify the **gender pay gap** across job roles and levels.
- Explore correlations between performance score, base pay, and bonus.
- Provide **recommendations** for closing compensation gaps and improving fairness.

---

## 🧹 Key Feature Engineering

- **Workload Intensity** = `Work_Hours_Per_Week / Projects_Handled`  
- Created visual breakdowns by:
  - **Job Title**
  - **Education Level**
  - **Seniority Level**
  - **Gender**

---

## 📊 Highlights & Visual Insights

### 🔸 Gender Pay Gap
- Women earn **8.65% less** than men on average.
- Pay gaps persist across **all seniority levels**.

### 🔸 Education Level vs Pay
- Higher education leads to higher base pay and bonuses.
- Growth flattens at PhD level.
- Visuals: Bar charts grouped by education level and gender.

### 🔸 Seniority vs Pay
- Strong positive correlation between years at company and compensation.
- Gender disparity remains even when controlling for seniority.

### 🔸 Correlation Matrix
- Seniority ↔ Base Pay: Moderate positive relationship
- Performance Score ↔ Bonus: Strong correlation

---

## 📋 User Demographics Snapshot

| Seniority | Female | Male | % Female | % Male | Total |
|-----------|--------|------|----------|--------|-------|
| 1         | 83     | 112  | 43%      | 57%    | *     |
| 2         | 102    | 107  | 49%      | 51%    | 209   |
| 3         | 106    | 113  | 48%      | 52%    | 219   |
| 4         | 80     | 104  | 43%      | 57%    | 184   |
| 5         | 97     | 96   | 50%      | 50%    | 193   |
| **Total** | **468**|**532**|          |        | **1000**|

---

## 📌 Recommendations

- **Close Gender Pay Gaps**  
  Conduct equity reviews at senior and highly educated levels.

- **Incentivize Growth Segments**  
  Focus on employees with 3–4 years of experience — peak opportunity for retention.

- **Strengthen Performance Metrics**  
  Align bonuses and evaluations using consistent, data-driven criteria.

---

## 📁 Repository Contents

- `notebook.ipynb`: Full analysis pipeline including data cleaning, EDA, and modeling
- `dataset.csv`: Cleaned dataset (if publicly shareable)
- `charts/`: Visualizations (bar charts, boxplots, correlation maps)
- `README.md`: Project overview and instructions

---


## 🔗 Source & Tools

- [Dataset from Kaggle](https://www.kaggle.com/datasets/mexwell/employee-performance-and-productivity-data)
- Python Libraries: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

---

## 📈 Future Enhancements

- Add regression modeling to predict bonus or pay
- Introduce dashboard using Streamlit for real-time salary insights
- Integrate external benchmarks for industry comparison
