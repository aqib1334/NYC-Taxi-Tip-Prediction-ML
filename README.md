Project Objective: The goal of this project was to build a machine learning model for the New york city Taxi & Limousine Commission (TLC)
to predict whether a rider will be a "generous tipper" (tipping $\geq$ 20%).This helps 
drivers optimize their routes and schedules to maximize their daily revenue.

Technical Approach
I followed the PACE (Plan, Analyze, Construct, Execute) framework to ensure a structured data science workflow.

1. Data Engineering
Filtering: Focused exclusively on Credit Card transactions, as cash tips are not recorded in the dataset.
Feature Creation: Engineered time-of-day bins (AM Rush, PM Rush, Daytime, Nighttime) to capture tipping patterns related to traffic and time.
Data Integration: Merged the primary 2017 trip dataset with auxiliary data containing mean trip duration and predicted fares.

2. Machine Learning Modeling
Algorithm: Developed a Random Forest Classifier to handle complex, non-linear relationships in the data.
Optimization: Utilized GridSearchCV for hyperparameter tuning, focusing on the F1 Score to balance precision and recall

Model Accuracy: The Random Forest model achieved an overall accuracy of 69% in predicting generous tippers.

This project helps drivers optimize their routes and schedules to maximize their daily revenue.







