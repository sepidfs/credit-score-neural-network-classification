# Credit Score Neural Network Classification

This repository presents a machine learning and deep learning–based solution for **credit score classification**, designed to assist financial institutions in assessing customer creditworthiness more accurately and efficiently. The project focuses on automating credit score categorization using **Neural Network models** and data-driven insights.

---

## 📌 Project Overview

Credit score classification plays a crucial role in financial services, supporting decisions related to loan approvals, risk management, and customer segmentation. Traditional rule-based and manual evaluation methods are often time-consuming and error-prone. This project leverages **Neural Networks** to automate and improve the credit scoring process.

The goal is to classify individuals into three predefined credit score categories:

- **Poor**
- **Standard**
- **Good**

---

## 🎯 Objectives

- Design and implement a **Neural Network–based multi-class classification system**
- Reduce manual credit evaluation efforts
- Capture complex, non-linear relationships in financial data
- Improve accuracy and consistency in credit risk assessment

---

## 🧠 Methodology

The project follows a structured machine learning workflow:

- Data preprocessing and cleaning
- Handling numerical and categorical features
- Feature engineering and encoding
- Training and evaluating multiple models
- Neural Network optimization and comparison
- Performance evaluation using accuracy and F1-score

---

## 📊 Dataset

The dataset was obtained from a public Kaggle competition provided by a global finance company.

- **Dataset size:** 100,000 records  
- **Total features:** 27  
- **Removed redundant columns:** `ID`, `Customer_ID`, `Name`, `SSN`, `Month`  
- **Feature types:**  
  - 17 numerical features  
  - 9 categorical features  
- **Target variable:** Credit Score  
  - `Poor`  
  - `Standard`  
  - `Good`

🔗 **Data source:**  
https://www.kaggle.com/datasets/parisrohan/credit-score-classification

---

## 🏆 Results Summary

Multiple machine learning and deep learning models were developed and evaluated.  
Among them, the **EmbedMLP Neural Network** achieved the best overall performance:

- **Accuracy:** ~85.7%  
- **Macro F1-score:** 0.857  

The model demonstrated strong generalization and balanced classification across all credit score classes, outperforming traditional models such as Logistic Regression, Decision Tree, and SVM, as well as more complex architectures like RNNs and Transformers.
---

## 🚀 Applications

This system can support:

- Credit risk assessment
- Loan approval processes
- Customer segmentation
- Scalable and automated financial decision-making

<img width="5000" height="3000" alt="image" src="https://github.com/user-attachments/assets/4aa44c90-135a-4716-ae06-69788e461edb" />

