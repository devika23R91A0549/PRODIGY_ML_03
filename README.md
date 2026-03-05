## 📌 Project Overview

This project implements a **Support Vector Machine (SVM)** classification model to predict whether a bank customer will accept a **personal loan offer**.

The model is trained using the **UniversalBank dataset**, which contains demographic and financial information about customers.

The goal is to analyze customer data and build a machine learning model that can help banks **identify potential loan customers**.

---

## 🎯 Objectives

* Perform **data preprocessing and cleaning**
* Analyze the dataset using **data visualization**
* Build an **SVM classification model**
* Compare different **SVM kernels**
* Evaluate the model using **accuracy, confusion matrix, and classification report**

---

## 📂 Dataset Information

The dataset contains customer information such as:

| Attribute          | Description                                                  |
| ------------------ | ------------------------------------------------------------ |
| ID                 | Customer ID                                                  |
| Age                | Age of the customer                                          |
| Experience         | Years of professional experience                             |
| Income             | Annual income ($000)                                         |
| ZIP Code           | Customer ZIP code                                            |
| Family             | Family size                                                  |
| CCAvg              | Average monthly credit card spending                         |
| Education          | Education level (1: Undergrad, 2: Graduate, 3: Professional) |
| Mortgage           | House mortgage value                                         |
| Personal Loan      | Target variable (0 = No, 1 = Yes)                            |
| Securities Account | Whether customer has securities account                      |
| CD Account         | Whether customer has certificate of deposit                  |
| Online             | Internet banking usage                                       |
| CreditCard         | Whether customer uses bank credit card                       |

---

## ⚙️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## 🧠 Machine Learning Model

The following models were implemented:

* **SVM with Linear Kernel**
* **SVM with RBF Kernel**
* Hyperparameter tuning using **Grid Search**

---

## 📊 Data Visualization

Several visualization techniques were used to understand the dataset:

* Loan Acceptance Distribution
* Income Distribution
* Age Distribution
* Education vs Loan Acceptance
* Correlation Heatmap
* Income vs Loan Acceptance
* Credit Card Usage Analysis
* Mortgage Distribution
* Confusion Matrix Heatmap
* Model Accuracy Comparison

---

## 📈 Model Evaluation Metrics

The model was evaluated using:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1 Score

Example metrics:

```
Accuracy: ~97% – 98%
```

---

## 📊 Example Confusion Matrix

| Actual / Predicted | No Loan             | Loan                |
| ------------------ | ------------------- | ------------------- |
| No Loan            | High True Negatives | Few False Positives |
| Loan               | Few False Negatives | Correct Predictions |

---

## 🚀 Project Workflow

1. Import required libraries
2. Load dataset
3. Data cleaning and preprocessing
4. Feature selection
5. Train-test split
6. Data standardization
7. Train SVM model
8. Model evaluation
9. Visualization of results

---
