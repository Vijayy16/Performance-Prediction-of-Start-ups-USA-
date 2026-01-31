
# Performance Prediction of Startups – USA
Duration: Aug 2024 – Dec 2024
Domain: Business Analytics | Predictive Modeling | Strategy & Decision Support

## Project Overview
This project focuses on predicting the performance of startups in the United States using
financial and operational data. The goal is to classify startups as **Successful** or
**Unsuccessful** based on factors such as funding, revenue, expenses, workforce size,
industry, and location.

The analysis demonstrates how predictive analytics and machine learning can support
investment evaluation and strategic decision-making.

---

## Dataset

### Dataset Creation
The dataset was **manually created** to simulate real-world startup performance data.
It represents early- to mid-stage startups operating across multiple industries in the USA.

Each row corresponds to a startup, and each column represents a key business metric.

### Dataset File
- **SPU.xlsx**

### Features Included
- `startup_name` – Name of the startup  
- `funding_usd` – Total funding raised (USD)  
- `employees` – Number of employees  
- `revenue` – Annual revenue (USD)  
- `expenses` – Annual expenses (USD)  
- `industry` – Startup industry sector  
- `location` – City/State in the USA  
- `status` – Startup outcome (Successful / Unsuccessful)

---

## Tools & Technologies Used
- **Python**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Scikit-learn** – Machine learning modeling
- **Jupyter Notebook** – Analysis and experimentation
- **Excel** – Dataset creation and storage

---

## Analysis Performed

### 1. Exploratory Data Analysis (EDA)
- Examined dataset structure and data types
- Generated descriptive statistics
- Identified distributions of funding, revenue, and expenses

### 2. Feature Engineering
- Created a new feature:
  - **Profit = Revenue − Expenses**
- Encoded categorical variables such as industry and startup status

### 3. Target Variable Definition
- Startup performance was encoded as:
  - `1` → Successful
  - `0` → Unsuccessful

---

## Machine Learning Model

### Model Used
- **Logistic Regression**

### Input Features
- Funding amount
- Employee count
- Revenue
- Expenses
- Encoded industry

### Model Objective
Predict whether a startup is **Successful** or **Unsuccessful**.

---

## Model Evaluation

### Metrics Used
- Accuracy
- Precision
- Recall
- F1-score

### Results
- The model achieved **100% accuracy** on the test dataset.

### Interpretation
The perfect accuracy is primarily due to:
- Small dataset size
- Strong separation between profitable and non-profitable startups

This result demonstrates the feasibility of performance prediction but may not generalize
to larger real-world datasets.

---

## Limitations
- Small sample size
- Manually created dataset
- Results may overfit due to strong profit-based separation

---

## Future Improvements
- Expand dataset using real-world startup data
- Apply cross-validation and regularization
- Experiment with advanced models (Random Forest, XGBoost)
- Include time-based and growth-rate features

---

## Repository Structure
README.md
├── SPU.xlsx
└── startup_performance_usa.ipynb


---

## Key Takeaway
This project demonstrates how financial and operational startup data can be transformed
into actionable insights using predictive analytics and machine learning techniques.
