# Customer Churn Analysis Case Study

---

## Problem Statement

Customer churn is a critical issue for telecom companies, directly impacting revenue and profitability. Without clear insights into why customers leave and which current customers are at risk, companies struggle to implement effective retention strategies.

The goal of this project was to:

* Analyze **historical churn patterns**
* Identify **key drivers of churn**
* Build a **predictive model** to score current customers by churn risk
* Provide **business-friendly dashboards** to support proactive retention efforts

---

## Tools & Technologies

* **Power BI** (interactive dashboards, Q\&A)
* **Python** (data preprocessing, machine learning)
* **scikit-learn** (ML modeling)
* **Pandas** (data wrangling)
* **Jupyter Notebook** (analysis and modeling)
* **Kaggle Telecom Customer Churn Dataset**

---

## Implementation

The project was completed in four stages:

### 1. Churned Customer Analysis

Segmented churned customers and analyzed their behavior using Power BI. Key variables included **contract type**, **payment method**, **tenure**, and **monthly charges**. Insights were visualized to help the business understand churn patterns.

### 2. Overall Customer Analysis

Analyzed the full customer base to identify broader trends. Created **segmentation views** and **demographic overlays** in Power BI to compare churned vs. non-churned customers.

### 3. Churn Risk Prediction (Machine Learning)

Developed a **classification model** (Logistic Regression) to predict churn risk for current customers:

* Engineered relevant features (tenure, contract type, service usage, etc.)
* Trained and validated the model
* Scored current customers and categorized them by **low, medium, or high risk**
* Integrated risk scores into Power BI dashboards

### 4. Business Q\&A and Insights

Enabled Power BI’s Q\&A feature to allow **ad-hoc analysis** by business users using natural language queries.

---

## Challenges

* **Data quality:** The dataset required significant preprocessing (missing values, categorical encoding, outlier handling).
* **Feature selection:** Identifying the most predictive features for the ML model required multiple iterations and tuning.
* **Model interpretability:** Translating model results into **business-friendly insights** was key to adoption.
* **Visualization:** Designing dashboards that are both **insightful and actionable** for business teams required thoughtful iteration.

---

## Output / Results

* Identified key churn drivers, including **contract type**, **short tenure**, and **automatic payment methods**.
* Built a **churn risk prediction model** with strong classification performance.
* Scored **current customer base** for future churn risk.
* Delivered an **interactive Power BI report** with:

  * Churn trend visualizations
  * Key driver analysis
  * Current customer churn risk scores
  * Natural language Q\&A interface
* Created a foundation for **targeted retention campaigns** and **data-driven decision-making**.
