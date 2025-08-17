# 📊 Telecom Churn Prediction

## 📌 Project Overview
This project aims to **predict customer churn** in a telecom company using **machine learning models**.  
Churn prediction helps businesses identify customers who are likely to leave, so that they can take preventive actions such as offering promotions, improving service, or strengthening customer engagement.  

The project was implemented on **Google Colab** using Python and popular ML libraries.

---

## 🛠 Steps Followed

### 1. 🔹 Data Cleaning
- Handled missing values and inconsistent entries  
- Removed duplicate records  
- Converted categorical variables into proper formats  

### 2. 📊 Exploratory Data Analysis (EDA) & Visualization
- Analyzed customer behavior patterns (tenure, monthly charges, etc.)  
- Visualized distributions using **Matplotlib & Seaborn**  
- Identified key churn indicators  

### 3. 🔧 Data Preprocessing
- Scaled numerical features  
- Applied Label encoding for categorical variables  
- Split dataset into training and testing sets  

### 4. 🤖 Machine Learning Models
Trained and evaluated multiple models for predicting churn:
- **Logistic Regression**  
- **K-Nearest Neighbors (KNN)**  
- **Support Vector Classifier (SVC)**  
- **Decision Tree Classifier**  
- **Random Forest Classifier**  

### 5. 📈 Model Evaluation
- Evaluated models using **accuracy, precision, recall, and F1-score**  
- Compared performance to identify the best model  
- Visualized confusion matrices for better insights  

---

## 🚀 Results
- Random Forest & Logistic Regression provided the most balanced performance.  
- Feature importance analysis highlighted that **tenure, contract type, and monthly charges** are strong predictors of churn.  

---

## 🛠 Tech Stack
- **Languages & Libraries**: Python, Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn  
- **Environment**: Google Colab / Jupyter Notebook  
