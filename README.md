ML-based Loan Approval Prediction using MySQL, Power BI, Python & AWS Cloud

 Overview
This end-to-end project focuses on predicting loan approvals for gig economy workers (such as Uber Drivers, Pizza Delivery & Freelancers) using real-world datasets and multiple cloud and analytics technologies. The objective is to develop a smart credit evaluation system that can help FinTechs and NBFCs make data-driven lending decisions in real time.

Problem Statement
Goal: Predict whether a loan application will be approved based on applicant profiles, credit scores, behavioral signals, and location data.

Define Key Business Questions
To make our analytics meaningful, we should aim to answer questions like:
•	What is the distribution of credit scores among loan applicants?
•	How does credit score affect loan approval rates or loan amounts?
•	Are there regional or time-based patterns in high-risk applicants?
•	What's the average loan amount by risk category (Safe, Moderate, High Risk)?

This project involves:
•	Advanced data analysis using MySQL (AWS RDS) and Python (Colab)
•	 Visual interactive dashboard using Power BI
•	Predictive modeling using Machine Learning
•	 Cloud deployment using AWS S3 + SageMaker

Target Users: FinTech startups, digital lenders, and gig worker-focused NBFCs looking to reduce loan risk and optimize approval processes.
Technologies Used

1.	MySQL (AWS RDS) | Data storage, joins, schema creation, SQL queries 
2.	Power BI | Building visual dashboards & risk heatmaps   
3.	Python (Colab) | EDA, Feature Engineering, Model Training
4.	Pandas, Scikit-learn | Data processing & ML modeling         
5.	AWS S3| Model storage (.joblib & .tar.gz)         
6.	AWS SageMaker| Model deployment and endpoint creation       


Workflow Summary

1.  Data Ingestion & Schema Creation (MySQL via AWS RDS)
- Created tables: `loan_applications`, `credit_scores`
- Normalized structure with foreign keys
 2. SQL Queries & Data Analysis
- Performed joins to enrich loan applications with credit history
- Aggregated credit scores by location and loan status
- Created views for Power BI connection
3. Power BI Visualization
- Imported SQL views into Power BI
- Built dashboards:
  -  Approval rate by city
  -  High-risk score by worker profile
  - Loan amount distribution

4.  Machine Learning in Python
- Cleaned and preprocessed data in Colab
- Feature selection using correlation analysis
- Trained a Logistic Regression model
- Achieved ~86% accuracy in predicting approvals

5. AWS Integration
- Saved model using `joblib` and uploaded to S3
- Created `.tar.gz` archive for SageMaker
- Deployed model to AWS SageMaker endpoint
- Future-ready for real-time scoring via REST API

Key Learnings & Outcomes

- Integrated SQL + Python + AWS in a production-style pipeline
- Performed credit risk analysis for gig economy workers
- Created a deployable ML model using SageMaker
- Built executive-ready dashboards in Power BI


Future Improvements

- Integrate geospatial data for deeper location risk profiling
- Real-time API integration for live scoring from mobile apps
- Add XGBoost and AutoML pipelines for higher performance
- Full CI/CD pipeline on GitHub Actions


Screenshots: 

<img width="1118" height="637" alt="Power BI Dashboard" src="https://github.com/user-attachments/assets/c7ac3ed3-7f08-44f5-999e-3b7d1578bd3c" />

<img width="1905" height="918" alt="Power_BI_DAX_3" src="https://github.com/user-attachments/assets/92fe91ab-5b80-4de6-b678-740918d7e0e5" />
<img width="1907" height="868" alt="Power_BI_DAX_2" src="https://github.com/user-attachments/assets/e285d3e5-6111-4bb4-b31c-deb3cc5e8aea" />
<img width="1904" height="1000" alt="Power_BI_ DAX_1" src="https://github.com/user-attachments/assets/b287aa00-35cf-4e22-a0f1-6019c30e7328" />
<img width="1896" height="692" alt="Power_BI_ModelView_Relationship" src="https://github.com/user-attachments/assets/8b2522c3-0a88-4019-8a22-b5bf4b35ddd0" />
<img width="1910" height="890" alt="Power_BI_DAX_4" src="https://github.com/user-attachments/assets/564d61a8-9b3f-4a1d-84b6-cac49977ad81" />

