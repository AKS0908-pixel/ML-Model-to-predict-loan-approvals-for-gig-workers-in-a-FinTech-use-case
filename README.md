<img width="1910" height="890" alt="Power_BI_DAX_4" src="https://github.com/user-attachments/assets/a3c41547-27a3-4e89-9ae4-ce910a1d62c9" />ML-based Loan Approval Prediction using MySQL, Power BI, Python & AWS Cloud

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
<img width="1904" height="1000" alt="Power_BI_ DAX_1" src=<img width="1904" height="1000" alt="Powe<img width="1907" height="868" alt="Power_BI_DAX_2" src="https://github.com/user-attachments/assets/ea410f7e-05ed-4fd7-b351-6f335dae8470" />
<img width="1904" height="1000" alt="Power_BI_ DAX_1" src="https://github.com/user-attachments/assets/b287aa00-35cf-4e22-a0f1-6019c30e7328" />
r_BI_ DAX_1" src="https://github.com/user-attachments/assets/66eaeca3-f327-4f23-9af5-4<img width="1910" height="890" alt="Power_BI_DAX_4" src="https://github.com/user-attachments/assets/1e6495d4-f07b-4c38-b263-f9edd4b3885a" />
<img width="1905" height="918" alt="Power_BI_DAX_3" src="https://github.com/user-attachments/assets/e50f5127-ee53-468c-857d-a234f1311230" />
<img width="1907" height="868" alt="Power_BI_DAX_2" src="https://github.com/user-attachments/assets/60bf5ef0-1a9d-4c40-ac38-b30ddaf83ba4" />
<img width="1905" height="918" alt="Power_BI_DAX_3" src="https://github.com/user-attachments/assets/8c8afa29-e49a-45f2-a1a2-ff14500099cf" />
<img width="1904" height="1000" alt="Power_BI_ DAX_1" src="https://github.com/user-attachments/assets/2ca0175e-7a3b-4e0a-aaa6-d3607859d22c" />
<img width="1907" height="868" alt="Power_BI_DAX_2" src="https://github.com/user-attachments/assets/50afafdf-c8bb-4042-a2eb-520590e3aa6e" />
<img width="1896" height="692" alt="Power_BI_ModelView_Relationship" src="https://github.com/user-attachments/assets/9c086e18-c5d6-46ef-a204-ab696c6be5e8" />
08c522f3b24" />
<img width="1910" height="890" alt="Power_BI_DAX_4" src="https://github.com/user-attachments/assets/83df5b6b-cbe4-41b0-9272-5be8be8bab4c" />
<img width="1896" height="692" alt="Power_BI_ModelView_Relationsh<img width="1904" height="1000" alt="Power_BI_ DAX_1" src="https://github.com/user-attachments/assets/286736a7-1780-4480-bb95-f5e5ab7adccc" />
<img width="1896" height="692" alt="Power_BI_ModelView_Relationship" src="https://github.com/user-attachments/assets/8b2522c3-0a88-4019-8a22-b5bf4b35ddd0" />
<img width="1910" height="890" alt="Power_BI_DAX_4" src="https://github.com/user-attachments/assets/564d61a8-9b3f-4a1d-84b6-cac49977ad81" />
<img width="1896" height="692" alt="Power_BI_ModelView_Relationship" src="https://github.com/user-attachments/assets/afcc0cd5-d6d5-48ee-992b-34d0118756f8" />
ip" src="https://github.com/user-attachments/assets/5a5f79b5-7c8b-410b-85e5-4c82621553a4" />
<img width="1905" height="918" alt="Power_BI_DAX_3" src="https://github.com/user-attachments/assets/1aaeb9cb-a787-425c-b6d2-d78bd08ecdf6" />
<img width="1910" height="890" alt="Power_BI_DAX_4" src="https://github.com/user-attachments/assets/33620d4b-9b92-4d1e-b6f0-365a94a52177" />
"https://github.com/user-attachments/assets/c391178e-0e12-4e84-bac3-af2b9d7dabf2" />
![<img width="1905" height="918" alt="Power_BI_DAX_3" src="https://github.com/user-attachments/assets/a1cb3791-e90b-4e3c-8923-e58f925e0609" />
<img width="1896" height="692" alt="Power_BI_ModelView_Relationship" src="https://github.com/user-attachments/assets/5b30baa4-1670-4322-9e57-f2337663d1a7" />
<img width="1907" height="868" alt="Power_BI_DAX_2" src="https://github.com/user-attachments/assets/203b0f80-b400-455a-9e7a-c268c3f4cc31" />
Uploading Power_BI_DAX_4.png…]()
