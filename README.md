# Customer Intelligence: RFM Segmentation & Churn Risk Modeling (Python)

## Project Overview

This project develops a comprehensive **Customer Intelligence framework** to identify high-value customers, assess churn risk, and prioritize retention strategies.

Using behavioral transaction data, the analysis combines:

- RFM segmentation  
- Customer Lifetime Value (CLV) modeling  
- Churn probability estimation  
- Risk-adjusted revenue projection  
- Strategic customer prioritization  

The objective is to transform raw transactional data into actionable marketing insights and revenue protection strategies.

## Business Objectives

1. Segment customers based on behavioral patterns (Recency, Frequency, Monetary).
2. Estimate customer lifetime value (CLV).
3. Build a churn probability scoring model.
4. Identify high-value customers at risk of churn.
5. Prioritize retention efforts using value-based ranking.

## Project Workflow

1. Data exploration and cleaning using Python  
2. Feature engineering (Age groups, Family size, Behavioral metrics)  
3. RFM segmentation to identify customer relationship stages  
4. Customer Lifetime Value (CLV) estimation  
5. Recency-weighted value modeling  
6. Churn probability scoring using normalized behavioral metrics  
7. Risk classification and retention prioritization  
8. Strategic insight generation and visualization
   
## Tools & Technologies

- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Plotly  
- Scikit-learn (MinMaxScaler)  

## Methodology

### 1️⃣ RFM Segmentation

Customers were segmented into four relationship stages:

- **Stars**
- **High Potential**
- **Need Attention**
- **Leaky Bucket**

This classification identifies engagement levels and early churn signals.

### 2️⃣ Customer Lifetime Value (CLV)

Multiple CLV metrics were computed:

- Historical CLV  
- 12-month projected CLV  
- Recency-weighted CLV  
- Churn-adjusted CLV  

This approach enables both historical evaluation and forward-looking revenue estimation.

### 3️⃣ Churn Probability Modeling

A churn probability score was constructed using normalized:

- Recency (60% weight)  
- Inverse Frequency (40% weight)  

Customers were classified into:

- Low Risk  
- Medium Risk  
- High Risk  

### 4️⃣ Risk-Adjusted Value Prioritization

By combining:

- Churn Risk  
- 12-month projected CLV  
- RFM Segment  

the model identifies high-value customers requiring immediate retention intervention.

## Key Insights

- Churn risk increases significantly with declining recency and lower purchase frequency.
- Expected annual CLV decreases as churn risk rises, confirming model consistency.
- A subset of high-risk customers still represents substantial projected revenue.
- High-value segments (Stars & Need Attention) drive premium product contribution.
- Behavioral segmentation is more predictive than demographic variables alone.

## Business Impact

This framework enables:

- Risk-adjusted customer valuation  
- Data-driven retention prioritization  
- Revenue protection strategy  
- Customer lifecycle intelligence  

The project demonstrates how behavioral analytics can directly support strategic marketing decisions.

## Skills Demonstrated

- Data cleaning and preprocessing  
- Feature engineering and behavioral metric construction  
- RFM customer segmentation methodology  
- Customer Lifetime Value (CLV) modeling  
- Churn probability estimation  
- Risk-adjusted revenue projection  
- Customer prioritization strategy  
- Exploratory data analysis (EDA) and visualization  
- Analytical reasoning and business insight generation  
- End-to-end customer intelligence workflow  

## Author

Mohamed Fakhri Ben Brahim  
Aspiring Data Analyst | Python | SQL | Power BI | DAX | Advanced Excel
