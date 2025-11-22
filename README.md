# 🧠 RECONNECT-2025: Diabetic Retinopathy Detection using Clinical and Retinal Data

## 📘 Overview
**RECONNECT-2025** is a research-oriented project focused on developing a machine learning framework to **predict the severity level of Diabetic Retinopathy (DR)** using both **clinical data** (e.g., age, gender, blood glucose, blood pressure) and **retinal image features**.  
The system aims to support **early diagnosis** and **clinical decision-making** by identifying disease severity on a scale from 0 (no DR) to 4 (proliferative DR).

This project integrates data analysis, pseudo-label generation, model training, and prediction evaluation following a structured scientific workflow.

---

## 🩺 Research Motivation
Diabetic Retinopathy (DR) is a leading cause of vision impairment among diabetic patients worldwide.  
Early detection and accurate severity grading are crucial for effective treatment.  
However, manual grading is time-consuming and subject to human variability.  
This study proposes a **data-driven AI-assisted framework** that combines clinical and computational intelligence to automate this process.

---

## 🔬 Methodology
The model training follows the structured process shown below:

1. **Input Clinical Data**  
   Collect patient data including age, gender, blood glucose, blood pressure, BMI, and HbA1c levels.

2. **Preprocessing**  
   Handle missing values, normalize numerical data, and encode categorical variables to ensure consistency.

3. **Pseudo-label Generation (XGBoost)**  
   Use XGBoost to generate labels (0–4) representing disease severity based on statistical patterns in the data.

4. **Model Training (Random Forest)**  
   Train a Random Forest classifier on the labeled dataset to predict DR severity levels.

5. **Hyperparameter Tuning**  
   Optimize model parameters through grid search or random search with cross-validation.

6. **Evaluation**  
   Assess performance using **Mean Absolute Error (MAE)** and **Confusion Matrix** to measure classification accuracy.

7. **Prediction**  
   Deploy the model to predict severity levels for new patients or unseen datasets.

---


