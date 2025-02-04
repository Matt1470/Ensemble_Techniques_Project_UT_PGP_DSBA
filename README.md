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
- [📄 Author](#-author)  
- [🙌 Acknowledgments](#-acknowledgments)  

---

## 📌 Project Overview  
The **EasyVisa Project** is a **machine learning-based decision-support system** designed to assist the **Office of Foreign Labor Certification (OFLC)** in **streamlining the U.S. visa approval process**.  

With the **growing demand for foreign workers** and **hundreds of thousands** of applications processed annually, a **data-driven solution** can significantly improve efficiency, reduce workload, and ensure **fairer, faster decision-making**.  

### 🔍 **How Does It Work?**  
✔ **Uses historical visa application data** to uncover key trends and patterns.  
✔ **Applies machine learning models** to classify visa applications as **Certified (Approved)** or **Denied**.  
✔ **Identifies the most influential factors** affecting visa approval.  

---

## ❓ Problem Statement  
### **Context**  
The **Immigration and Nationality Act (INA)** allows U.S. employers to hire foreign talent. However, the **OFLC's manual review process** is:  
- **Slow** 🚶 → High application volume causes processing delays.  
- **Inconsistent** ⚖️ → Subjectivity in decisions may lead to **bias**.  
- **Resource-Intensive** 🏗️ → Requires substantial human oversight.  

### **Challenges**  
1️⃣ **High application volume** → Causes bottlenecks in processing.  
2️⃣ **Lack of consistency** → Decision-making can be subjective.  
3️⃣ **Key approval factors unknown** → Employers and applicants lack transparency.  

---

## 🎯 Objective  
This project aims to develop a **machine learning model** that:  
✔ **Accurately predicts** visa approval or denial.  
✔ **Identifies key approval factors** for better policy-making.  
✔ **Enhances decision efficiency** for the OFLC.  

---

## 📂 Dataset Description  
The dataset includes information on **applicants, employers, and job roles**.  

### **Key Features:**  
| Column Name                 | Description |
|-----------------------------|-------------|
| `case_id`                   | Unique ID for each visa application. |
| `continent`                 | Applicant’s continent of origin. |
| `education_of_employee`      | Applicant’s education level. |
| `has_job_experience`         | Prior work experience (Y/N). |
| `requires_job_training`      | Whether the job requires training (Y/N). |
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
✔ Handled **missing values**  
✔ Converted **data types**  
✔ Applied **feature engineering**  

### **2️⃣ Exploratory Data Analysis (EDA)**  
✔ Visualized **feature distributions**  
✔ Examined **correlations between key factors**  
✔ Addressed **class imbalance in visa approvals**  

### **3️⃣ Machine Learning Model Development**  
✔ Split data into **Training & Testing sets**  
✔ Trained multiple **classification models**:  
   - Decision Tree 🌳  
   - Random Forest 🌲  
   - Gradient Boosting 🚀  
   - XGBoost ⚡  

### **4️⃣ Model Optimization & Evaluation**  
✔ Performed **hyperparameter tuning** (GridSearchCV)  
✔ Evaluated performance using **accuracy, precision, recall, and F1-score**  

### **5️⃣ Future Deployment (Next Phase)**  
✔ API for **real-time visa predictions**  
✔ Web-based **dashboard for decision support**  

---

## 📊 Exploratory Data Analysis (EDA)  
### **Key Findings:**  
- 🎓 **Higher education levels** significantly improve visa approval chances.  
- 💼 **Work experience** plays a **major role** in certification likelihood.  
- 💰 **Higher wages** lead to **increased approval rates**.  
- 🏢 **Larger companies** (more employees) have **higher visa approval rates**.  
- 🌍 **Employment region matters** → Some U.S. regions approve more visas than others.  

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
✔ **XGBoost outperformed all other models** and is the best candidate for deployment.  
✔ **Key approval factors identified:**  
   - 🎓 **Education Level**  
   - 💼 **Job Experience**  
   - 💰 **Prevailing Wage**  
   - 🏢 **Company Size**  

📢 **Recommendation:** Employers & applicants should focus on these factors to **increase visa approval chances**.  

---

## 🚀 Future Work & Deployment  
🔹 **Further fine-tuning of hyperparameters** for improved accuracy.  
🔹 **Deployment via API** for real-time decision support.  
🔹 **Development of an interactive dashboard** for policymakers.  
🔹 **Integration with historical visa trends** to improve predictions.  

---

## 📄 Author  
👤 **Matthew Cook**  
📧 Email: matthewcook755@gmail.com  
🔗 LinkedIn: [Matthew Cook](https://www.linkedin.com/in/matthew-cook-4a92627a/)  

---

## 🙌 Acknowledgments  
- **Office of Foreign Labor Certification (OFLC)**  
- **U.S. Immigration and Nationality Act (INA)**  
- **Data Science & Machine Learning Community**  


---

