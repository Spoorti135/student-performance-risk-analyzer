
# Student Performance Risk Analyzer

## Overview
This project identifies students who are academically **at risk** using basic academic indicators.
It applies a simple and explainable machine learning model to support early academic intervention.

The goal is not high accuracy, but **understanding and explanation** of risk factors.

---

## Problem Statement
Educational institutions often struggle to identify students who may fail or drop out early.
This project uses data science techniques to predict whether a student is **At Risk** or **Not At Risk**
based on academic performance data.

---

## Dataset
The dataset contains the following features:

- **attendance** – Class attendance percentage  
- **internal_marks** – Internal assessment marks (out of 30)  
- **assignment_completion** – Assignment submission percentage  
- **lab_score** – Laboratory performance (out of 10)  
- **at_risk** – Target label (YES / NO)

> Note: The dataset used is a simulated dataset created for academic learning purposes.

---

## Methodology
1. Data creation and preprocessing using Pandas  
2. Conversion of categorical labels (YES/NO → 1/0)  
3. Train–test split (80% training, 20% testing)  
4. Model training using **Logistic Regression**  
5. Model evaluation using accuracy and confusion matrix  
6. Interpretation of results using model coefficients  

---

## Model Used
- **Logistic Regression**
  - Chosen for simplicity and explainability
  - Suitable for binary classification problems

---

## Results & Key Insights
- The model successfully predicts whether a student is at risk.
- **Assignment completion** and **attendance** are the strongest indicators of academic risk.
- **Lab performance** has comparatively less influence.
- The model behavior aligns with real-world academic expectations.

---

## Tools & Technologies
- Python  
- Google Colab  
- Pandas  
- Scikit-learn  

---

## Project Status
✅ Core machine learning model completed  
📄 Documentation 
---

## Conclusion
This project demonstrates a complete beginner-level data science workflow:
from data preparation to model training and interpretation.
It can be extended in the future using real institutional data or additional features.

---

## Author
Spoorti Kalakappa Dyampur
