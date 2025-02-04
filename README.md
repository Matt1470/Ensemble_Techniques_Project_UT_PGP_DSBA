# EasyVisa Project

## Overview

The **EasyVisa Project** is a data-driven solution designed to facilitate the visa approval process in the United States. With the increasing number of visa applications processed annually, the Office of Foreign Labor Certification (OFLC) seeks a **Machine Learning-based approach** to streamline and automate the identification of applicants with a higher likelihood of visa approval.

This project analyzes the provided dataset and leverages **classification models** to:

- Assist in the visa approval decision-making process.
- Recommend whether an applicant’s visa should be **certified** or **denied** based on key influencing factors.

## Problem Statement

### Context

The U.S. workforce relies on both domestic and international talent. The **Immigration and Nationality Act (INA)** allows U.S. employers to hire foreign workers to fill skill shortages while ensuring compliance with labor laws to protect domestic workers. 

The **OFLC** processes **hundreds of thousands** of labor certification applications each year. The **manual review process** is **time-consuming and inefficient**, leading to increased demand for **automated decision-support tools**.

### Objective

The project aims to develop a **classification model** to:

1. **Predict visa approval status** based on applicant and employer data.
2. **Identify key features** influencing visa approval.
3. **Optimize and improve decision-making** for visa applications.

## Dataset Description

The dataset contains attributes related to visa applications, applicants, and employers. Key features include:

- **case_id**: Unique ID of each visa application.
- **continent**: Origin continent of the employee.
- **education_of_employee**: Education level of the applicant.
- **has_job_experience**: Whether the applicant has prior job experience (`Y/N`).
- **requires_job_training**: Whether the job requires training (`Y/N`).
- **no_of_employees**: Number of employees in the employer’s company.
- **yr_of_estab**: Year the employer's company was established.
- **region_of_employment**: U.S. region where the foreign worker will be employed.
- **prevailing_wage**: The average wage paid to similar workers in the employment region.
- **unit_of_wage**: Wage frequency (`Hourly`, `Weekly`, `Monthly`, `Yearly`).
- **full_time_position**: Whether the job is a full-time position (`Y/N`).
- **case_status**: The visa application's final status (`Certified` or `Denied`).

## Project Structure

### 1. **Data Preprocessing**
   - Load the dataset
   - Handle missing values
   - Data type conversion
   - Feature engineering and transformations

### 2. **Exploratory Data Analysis (EDA)**
   - Visualizing distributions of key features
   - Identifying trends and correlations
   - Checking for class imbalances in `case_status`

### 3. **Model Development**
   - Train/Test split
   - Feature selection
   - Model selection:
     - Decision Tree
     - Random Forest
     - Gradient Boosting
     - XGBoost
   - Model evaluation using accuracy, precision, recall, and F1-score

### 4. **Hyperparameter Tuning**
   - GridSearchCV to optimize model performance

### 5. **Model Deployment (Future Work)**
   - API for real-time predictions
   - Web-based dashboard integration

## Results & Insights

- The classification models predict visa approval with **high accuracy**.
- Key drivers influencing visa approval include **education level, job experience, wage, and employer size**.
- Further optimization can enhance model performance and deployment feasibility.

## Contributors

- **Matthew Cook** - Data Scientist, EasyVisa

## Acknowledgments

- **Office of Foreign Labor Certification (OFLC)**
- **Immigration and Nationality Act (INA)**
- **Data Science & Machine Learning Community**
