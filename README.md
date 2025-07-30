
Financial institutions struggle to assess creditworthiness of gig workers due to inconsistent income patterns. This project uses alternative indicators to build a loan approval prediction model.

---

## 📊 Dataset Overview

We merged two datasets:

- `loan_applications.csv` — info on loan requests, approval status
- `credit_scores.csv` — behavioral and financial credit scores of applicants

---

## 🛠️ Tools & Tech Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib & Seaborn
- AWS RDS & SageMaker 
- Power BI (for visualizations)

# 🏦 FinTech Project: Loan Approval Prediction for Gig Workers

🎯 **Objective:** Use data analytics and machine learning to predict loan approval outcomes for gig workers using financial, behavioral, and credit-based indicators.

---

## 📌 Business Context

Gig workers form a rising customer segment for FinTech lenders, but traditional credit scoring often fails to evaluate their risk effectively. This project builds an **ML-driven Early Warning System (EWS)** to assist FinTech firms in assessing loan eligibility using non-traditional metrics.

---

## 🗂️ Project Structure

```bash
fintech-loan-approval-ml/
├── README.md
├── data/
│   ├── loan_applications.csv
│   └── credit_scores.csv
├── notebooks/
│   └── EDA_and_Modeling.ipynb
├── scripts/
│   ├── data_cleaning.py
│   ├── model_training.py
│   └── utils.py
├── visuals/
│   └── PowerBI_dashboard.pbix
├── requirements.txt
└── aws/
    ├── rds_connection.py
    └── config.env

💽 Data Sources
loan_applications: Application ID, worker ID, loan amount, status, date, city

credit_scores: Credit score metrics, behavioral score, financial activity

worker_profiles (planned): Worker demographics & geographic risk

Tools & Technologies Used
Area	Tools / Platforms
Data Handling	Python, Pandas, NumPy
Database	MySQL (via AWS RDS)
Data Viz	Power BI, Seaborn, Matplotlib
ML Models	Scikit-learn (Logistic Regression, RF)
Cloud Integration	AWS RDS (connected via SQLAlchemy + pymysql)
IDEs	Google Colab, VS Code

Exploratory Data Analysis (EDA)
Connected MySQL tables via AWS RDS using foreign keys

Performed missing value analysis, correlation heatmaps

Identified:

Credit score has highest influence on loan approval

Riskier cities showed lower approval likelihood

Loan amount range often influences rejection

 Machine Learning Modeling
Step	Description
Target Variable	loan_status (Approved / Rejected)
Algorithms Tried	Logistic Regression, Random Forest, XGBoost
Best Model	Random Forest Classifier — 87% Accuracy
Evaluation Metrics	Accuracy, Confusion Matrix, AUC-ROC Curve

 Power BI Dashboard (FinTech View)
Loan approval trend over time

City-wise default risk heatmap

Credit Score Distribution

Application Status Breakdown

Filter by:

Worker ID

Application Status

Credit Score Range

Results & Key Insights
Gig workers with high behavioral scores were 3x more likely to be approved.

Majority of rejections were clustered around low-income and Tier-3 cities.

Data-driven Early Warning System (EWS) flags high-risk applicants in real-time.
