# Car Insurance Fraud Detection

## Project Overview

Insurance fraud is a major challenge for insurance companies, leading to significant financial losses and increased operational costs. This project develops a Machine Learning classification model to identify potentially fraudulent car insurance claims using customer, policy, vehicle, and accident-related information.

The project demonstrates an end-to-end machine learning workflow, including data cleaning, exploratory data analysis (EDA), feature engineering, data preprocessing, model development, and performance evaluation.

---

## Problem Statement

The objective of this project is to build a predictive model capable of classifying insurance claims as fraudulent or non-fraudulent based on historical claim data.

By accurately detecting suspicious claims, insurance companies can reduce fraud-related losses, improve operational efficiency, and support data-driven decision-making.

---

## Dataset Information

* Records: 30,000 Insurance Claims
* Features: 24 Variables
* Target Variable: Fraud Status

The dataset includes information related to:

* Customer demographics
* Policy details
* Vehicle information
* Accident characteristics
* Claim amounts
* Insurance coverage
* Fraud indicators

---

## Project Workflow

### 1. Data Preprocessing

* Handled missing values
* Removed inconsistencies and duplicate records
* Encoded categorical variables
* Applied feature scaling where required
* Prepared data for machine learning models

### 2. Exploratory Data Analysis (EDA)

Performed data analysis to understand:

* Fraud distribution
* Claim amount patterns
* Customer and vehicle characteristics
* Relationships between features and fraud occurrence
* Potential predictors of fraudulent claims

### 3. Model Development

Implemented and evaluated multiple classification algorithms:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

### 4. Model Evaluation

Models were compared using classification performance metrics such as:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## Results

Among the evaluated models, the Random Forest Classifier achieved the best overall performance.

**Best Model:** Random Forest Classifier

**Accuracy:** 88.52%

The results demonstrate that machine learning techniques can effectively identify fraudulent insurance claims and assist insurance companies in risk management and fraud prevention.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Data Visualization
* Classification Modeling
* Model Evaluation
* Machine Learning
* Business Problem Solving

---

## Repository Contents

* Car_Insurance_Fraud_Detection_project.ipynb
* car_insur.csv
* README.md

---

## Project Objective

To leverage machine learning techniques for detecting fraudulent car insurance claims and demonstrate a complete data science workflow from raw data to predictive modeling and business insights.

 ## Problem Statement 
🚗 Car Insurance Claims – Fraud Detection


Insurance fraud is a significant challenge that causes massive financial losses and is difficult to detect through manual reviews alone. This project leverages Machine Learning to automate the identification process by analyzing complex patterns within policyholder demographics and accident reports.
    
The goal is to build a reliable predictive model that can accurately distinguish between fraudulent and legitimate claims.
    
This automated solution helps insurance providers reduce risk, improve operational efficiency, and ensure faster processing for honest customers.

## DataSet Description
months_as_customer : Number of months the lead has been a customer

age : Age of the policyholder

policy_number : Unique identifier for the insurance policy

policy_state : The state where the policy was issued

policy_deductable : The amount paid by the insured before insurance coverage kicks in

policy_annual_premium : The yearly premium paid by the customer

umbrella_limit : Additional liability insurance beyond standard limits

insured_sex : Gender of the policyholder

insured_education_level : Educational background of the insured

insured_occupation : Professional occupation of the policyholder

insured_hobbies : Hobbies or interests of the insured

incident_type : Category of the accident (e.g., Multi-vehicle Collision, Theft)

collision_type : Point of impact during the collision (Front, Rear, Side)

incident_severity : Level of damage caused by the incident (Major, Minor, Total Loss)

authorities_contacted : Type of authority notified at the scene

incident_hour_of_the_day : The specific hour when the accident occurred

number_of_vehicles_involved : Total count of vehicles involved in the accident

witnesses : Number of individuals who witnessed the incident

total_claim_amount : The total financial claim made by the insured

fraud_reported : Whether fraud was reported (Y/N)

## Goal 

predicts if an insurance claim is fraudulent or not.

Dependent Variable (Target Variable):

fraud_reported is the target variable that indicates whether an insurance claim is fraudulent ('Y') or legitimate ('N'). It serves as the primary label that the model learns to predict based on the provided policy and incident details.
