# Customer Churn Prediction using Machine Learning

Predicting customer churn using machine learning techniques to identify hidden patterns and help businesses improve customer retention.

---

## 📌 Project Overview

Customer churn refers to customers who stop using a company’s service.  
Reducing churn is critical for businesses, as retaining customers is often cheaper than acquiring new ones.

This project builds a **machine learning model** to predict whether a customer is likely to churn based on demographic, service usage, and billing information.

---

## 🧠 Problem Statement

- Businesses lose revenue due to customer churn.
- Identifying **high-risk customers early** helps in taking preventive actions.
- Manual analysis is inefficient for large datasets.

👉 **Goal:**  
Build a predictive model that classifies customers as **Churn / No Churn** using historical data.

---

## 🛠️ Tech Stack & Libraries

- **Language:** Python  
- **Data Handling:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn  
- **Model Used:** Random Forest Classifier  

---

## 📂 Dataset Description

The dataset contains customer-level information such as:

- Demographics (Gender, Senior Citizen)
- Account information (Tenure, Contract Type)
- Services used (Phone, Internet)
- Billing details (Monthly & Total Charges)
- Target variable: **Churn (Yes / No)**

> A sample dataset is generated programmatically for demonstration and experimentation.

---

## ⚙️ Project Workflow

### 1️⃣ Data Preparation
- Created a structured dataset with equal-length columns
- Ensured categorical and numerical balance

### 2️⃣ Data Preprocessing
- Converted categorical variables using **Label Encoding**
- Handled scaling using **StandardScaler**

### 3️⃣ Feature Engineering
- Created new features such as:
  - **TotalServicesUsed**
  - **EngagementScore**
- Improved model learning by enriching raw data

### 4️⃣ Feature Selection
- Removed non-informative fields like `customerID`
- Selected relevant predictors for training

### 5️⃣ Model Training
- Split data into training and testing sets
- Trained a **Random Forest Classifier**
- Generated predictions and probabilities

### 6️⃣ Model Evaluation
- Accuracy Score
- Classification Report
- Confusion Matrix
- ROC Curve & AUC Score

---

## 📊 Results & Evaluation

The model performance is evaluated using:

- **Accuracy Score** – overall correctness
- **Confusion Matrix** – churn vs non-churn prediction breakdown
- **ROC Curve** – trade-off between true positive and false positive rates
- **AUC Score** – model’s ability to distinguish classes

Visualizations are generated to clearly interpret results.

---

## 📈 Key Learnings

- Feature engineering significantly improves prediction quality
- Random Forest handles mixed data types effectively
- Evaluation metrics beyond accuracy are essential in churn prediction problems

---

## 🚀 Future Improvements

- Use a real-world telecom churn dataset
- Apply hyperparameter tuning
- Compare multiple models (Logistic Regression, XGBoost)
- Deploy the model using a web framework (Flask / FastAPI)

---

## 👨‍💻 Author

**Mohammed Aasif**  
Computer Science Engineering Student  

- LinkedIn: https://www.linkedin.com/in/mohammed-aasif-create  
- GitHub: https://github.com/aasif-create  

---

⭐ If you found this project useful, feel free to explore the repository and share feedback.
