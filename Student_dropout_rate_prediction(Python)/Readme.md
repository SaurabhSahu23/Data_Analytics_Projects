# Student Dropout Rate Prediction

## Project Overview

Student dropout is a significant challenge for educational institutions, impacting academic outcomes, institutional performance, and resource allocation. Early identification of at-risk students enables institutions to provide targeted interventions and improve student retention.

This project develops a Machine Learning classification model to predict a student's academic outcome based on demographic, academic, financial, and enrollment-related factors. The model classifies students into one of three categories:

* Dropout
* Enrolled
* Graduate

The project demonstrates an end-to-end data science workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, model development, and performance evaluation.

---

## Problem Statement

Educational institutions need effective methods to identify students who are at risk of dropping out before they leave their programs.

The objective of this project is to build a predictive model capable of classifying student outcomes using historical student data. Accurate predictions can help institutions improve retention strategies, allocate support resources effectively, and enhance overall student success.

---

## Dataset Information

* Records: 4,424 Students
* Features: 37 Variables
* Target Variable: Student Outcome

The dataset includes information related to:

* Student demographics
* Academic background
* Admission information
* Family education and occupation
* Financial status
* Scholarship status
* Tuition fee payments
* Enrollment details
* Academic performance indicators

Target Classes:

* Dropout
* Enrolled
* Graduate

---

## Project Workflow

### 1. Data Preprocessing

* Data quality assessment
* Handling missing and inconsistent values
* Feature preparation for machine learning
* Data transformation and encoding
* Train-test split

### 2. Exploratory Data Analysis (EDA)

Analyzed factors influencing student outcomes, including:

* Admission grades
* Scholarship status
* Tuition fee payment status
* Age at enrollment
* Academic performance
* Socioeconomic indicators

### 3. Model Development

Implemented and evaluated:

* Decision Tree Classifier
* Random Forest Classifier

### 4. Model Evaluation

Models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Performance Comparison

---

## Results

| Model                    | Accuracy |
| ------------------------ | -------- |
| Decision Tree Classifier | 67.57%   |
| Random Forest Classifier | 76.16%   |

### Best Performing Model

**Random Forest Classifier**

**Accuracy: 76.16%**

The Random Forest model demonstrated better generalization and predictive performance compared to the Decision Tree model.

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
* Predictive Analytics

---

## Project Objective

To leverage machine learning techniques to predict student academic outcomes and identify factors associated with student dropout, enabling data-driven interventions to improve student retention and success.
