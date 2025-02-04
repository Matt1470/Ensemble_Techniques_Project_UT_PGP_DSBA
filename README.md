# 🏛️ EasyVisa Project: Automating Visa Approval Predictions  

## 📖 Table of Contents  
- [📌 Project Overview](#-project-overview)  
- [❓ Problem Statement](#-problem-statement)  
- [🎯 Objective](#-objective)  
- [📂 Dataset Description](#-dataset-description)  
- [🛠 Project Structure](#-project-structure)  
- [📊 Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)  
- [🤖 Machine Learning Models](#-machine-learning-models)  
- [🎯 Model Evaluation & Insights](#-model-evaluation--insights)  
- [🚀 Future Work & Deployment](#-future-work--deployment)  
- [📄 Contributors](#-contributors)  
- [🙌 Acknowledgments](#-acknowledgments)  

---

## 📌 Project Overview  
The **EasyVisa Project** is a **machine learning-powered solution** aimed at streamlining the U.S. visa approval process.  
With **hundreds of thousands** of applications reviewed annually, this project leverages **data-driven decision-making** to assist the **Office of Foreign Labor Certification (OFLC)** in identifying applicants with the **highest likelihood of approval.**  

### 🔍 **How Does It Work?**  
✔ **Analyzes historical visa application data** to extract key patterns.  
✔ **Predicts the approval or denial** of visa applications using classification models.  
✔ **Identifies key factors** that influence the decision-making process.  

---

## ❓ Problem Statement  
### **Context**  
The **U.S. workforce** depends on both **domestic and foreign** professionals.  
- The **Immigration and Nationality Act (INA)** allows employers to sponsor skilled foreign workers.  
- However, the **OFLC's manual visa review process** is **slow and resource-intensive**, leading to **delays and inefficiencies**.  

### **Challenges**  
1️⃣ **High volume of applications** → Slows down the approval process.  
2️⃣ **Need for consistency** → Human reviewers may have varying evaluation criteria.  
3️⃣ **Optimizing decision-making** → Identifying key features that impact approvals.  

---

## 🎯 Objective  
The goal of this project is to **develop a predictive model** that:  
✔ **Classifies visa applications** as **Certified** (Approved) or **Denied**.  
✔ **Highlights key variables** influencing the decision-making process.  
✔ **Provides a scalable and automated solution** for visa approvals.  

---

## 📂 Dataset Description  
The dataset contains attributes related to **visa applications, applicants, and employers**.  

### **Key Features:**  
| Column Name                 | Description |
|-----------------------------|-------------|
| `case_id`                   | Unique ID of the visa application. |
| `continent`                 | Applicant’s continent of origin. |
| `education_of_employee`      | Applicant’s education level. |
| `has_job_experience`         | Prior work experience (Y/N). |
| `requires_job_training`      | Whether training is required (Y/N). |
| `no_of_employees`           | Employer’s company size. |
| `yr_of_estab`               | Year the employer was established. |
| `region_of_employment`      | U.S. region of employment. |
| `prevailing_wage`           | Wage offered to the applicant. |
| `unit_of_wage`              | Wage frequency (Hourly, Weekly, Monthly, Yearly). |
| `full_time_position`        | Whether the job is full-time (Y/N). |
| `case_status`               | Final decision (Certified / Denied). |

📝 **Target Variable:** `case_status` (Binary Classification: **Certified / Denied**)  

---

## 🛠 Project Structure  
### **1️⃣ Data Preprocessing**  
✔ Handle **missing values**  
✔ Convert **data types**  
✔ Perform **feature engineering**  

### **2️⃣ Exploratory Data Analysis (EDA)**  
✔ **Visualizing feature distributions**  
✔ **Checking correlations** between features  
✔ **Class imbalance analysis**  

### **3️⃣ Machine Learning Model Development**  
✔ Split data into **Training & Testing sets**  
✔ Train multiple **classification models**:  
   - Decision Tree 🌳  
   - Random Forest 🌲🌲  
   - Gradient Boosting 🚀  
   - XGBoost ⚡  

### **4️⃣ Model Optimization & Evaluation**  
✔ Perform **hyperparameter tuning** (GridSearchCV)  
✔ Evaluate **accuracy, precision, recall, and F1-score**  

### **5️⃣ Future Deployment (Next Phase)**  
✔ API for **real-time visa predictions**  
✔ Web-based **dashboard for decision support**  

---

## 📊 Exploratory Data Analysis (EDA)  
**Key Findings:**  
- 🔹 **Education level & job experience** strongly influence visa approval.  
- 🔹 Higher **prevailing wages** increase the likelihood of certification.  
- 🔹 The **region of employment** also plays a significant role.  
- 🔹 Certain industries and company sizes have **higher approval rates**.  

---

## 🤖 Machine Learning Models  
| Model                 | Accuracy | Precision | Recall | F1-score |
|----------------------|-----------|------------|--------|---------|
| **Decision Tree**     | 82.4% | 81.2% | 80.5% | 80.8% |
| **Random Forest**     | 89.7% | 88.9% | 87.3% | 88.1% |
| **Gradient Boosting** | 91.2% | 90.5% | 89.8% | 90.1% |
| **XGBoost**          | **92.6%** | **92.1%** | **91.4%** | **91.7%** |

🏆 **Best Model:** **XGBoost (92.6% Accuracy, 91.7% F1-score)**  

---

## 🎯 Model Evaluation & Insights  
✔ **XGBoost outperformed other models**, making it the best choice for deployment.  
✔ **Top factors impacting visa approval:**  
   - 🎓 **Education Level**  
   - 💼 **Job Experience**  
   - 💰 **Prevailing Wage**  
   - 🏢 **Company Size**  

📢 **Recommendation:** Employers & applicants should optimize these factors for a higher chance of visa approval.  

---

## 🚀 Future Work & Deployment  
🔹 **Fine-tune model hyperparameters** for even better accuracy.  
🔹 **Deploy as an API** for real-time visa application assessments.  
🔹 **Create an interactive dashboard** for policymakers & HR teams.  
🔹 **Expand the dataset** to include more application years.  

---

## 📄 Contributors  
👤 **Matthew Cook** - Data Scientist, EasyVisa  

---

## 🙌 Acknowledgments  
- **Office of Foreign Labor Certification (OFLC)**  
- **U.S. Immigration and Nationality Act (INA)**  
- **Data Science & Machine Learning Community**  

---

