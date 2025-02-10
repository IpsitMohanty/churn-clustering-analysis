# Churn Prediction Pipeline
A machine learning pipeline for **predicting customer churn** using **clustering, re-sampling techniques (SMOTE), and classification models**.

---

## Project Overview
This project aims to **predict customer churn** using various **machine learning techniques**, including:
- **Preprocessing pipeline** for numerical & categorical features.
- **Clustering (KMeans & GMM)** to extract meaningful patterns.
- **Resampling (SMOTE)** to handle class imbalance.
- **Modeling (Random Forest, Logistic Regression, etc.)** to classify customers.

The insights from this project can help businesses **improve retention strategies** and **reduce customer churn**.

---

##  Dataset
The dataset used is **`aavail-target.csv`**, containing:
- **Customer demographics** (e.g., age, country, subscription type).
- **Streaming behavior** (e.g., `num_streams` watched).
- **Churn label** (`is_subscriber`: 1 = Active, 0 = Churned).

---

##  Workflow
### ✅ **Step 1: Preprocessing**
- Handle missing values  
- Scale numerical features  
- Encode categorical variables  

### ✅ **Step 2: Train Baseline Model**
- Logistic Regression / Random Forest  
- Evaluate F1-score  

### ✅ **Step 3: Add Clustering**
- **KMeans & GMM clustering** as feature engineering  
- Compare performance with/without clustering  

### ✅ **Step 4: Apply Re-Sampling (SMOTE)**
- Handle class imbalance  
- Improve model performance  

### ✅ **Step 5: Hyperparameter Tuning (Optional)**
- GridSearchCV for optimal parameters  

---

## Technologies Used
- **Python, NumPy, Pandas, Scikit-Learn**
- **Matplotlib, Seaborn (Visualization)**
- **Imbalanced-Learn (SMOTE)**
- **Jupyter Notebook**

---
