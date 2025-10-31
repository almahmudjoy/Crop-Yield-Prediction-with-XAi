# 🌾 Crop Yield Prediction using Explainable AI (XAI)

This repository contains a Colab notebook implementation for predicting **crop yield** using machine learning and **Explainable AI techniques (XAI)**.  
The goal is to accurately forecast yield and interpret the key factors influencing model decisions.

---

## 📘 Notebook (Colab)

You can view or run the full notebook here:  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1nsptZ5k9EoKOTQav7FfUBUXzcnZIWFg_?usp=sharing#scrollTo=Ts1zzu72Uuus)

---

## 🎯 Project Overview

- Build regression models to **predict crop yield** based on climate, soil, and crop parameters  
- Compare multiple ML/DL architectures for performance (Random Forest, XGBoost, Neural Network, CropNet etc.)  
- Apply **Explainable AI methods (SHAP / LIME)** to interpret model predictions  
- Visualize feature importance and contribution to yield prediction  
- Explore model transparency to support **data-driven agricultural decisions**

---

## Dataset Overview
<img width="1200" height="428" alt="image" src="https://github.com/user-attachments/assets/d980d45c-8510-4910-a7eb-e3e51dc96de4" />
<img width="807" height="509" alt="image" src="https://github.com/user-attachments/assets/dc24784d-e2d2-49bd-ab70-f6a2a2c9df0c" />

## 📊 Key Highlights

- ✅ Preprocessed and normalized multi-feature agricultural datasets  
- ✅ Trained and tuned multiple predictive models for yield forecasting  
- ✅ Achieved high accuracy and interpretability using SHAP-based analysis  
- ✅ Visualized influential features such as temperature, rainfall, and soil moisture  
- ✅ Designed for real-world agricultural insights and sustainability planning  

---

🧠 Model Architectures Used
- **CropNet**
- **VGG19**
- **VGG16**
- **Logistic Regreesion**
- **Decision Tree**
- **Random Forest**
- **SVM**
- **XGBoost**
  
---

## 📈 Model Performance Summary
 Model           | Accuracy 
|----------------|-------------|
| CropNet        | 0.934684    | 
| VGG19          | 0.9298    | 
| VGG16          | 0.9177    | 
| Logistic Regreesion        | 0.8030   | 
| Decision Tree   | 0.7585    | 
| Random Forest | 0.7524    | 
| SVM       | 0.7459    | 
| XGBoost             | 0.7424    | 

<img width="1718" height="1257" alt="image" src="https://github.com/user-attachments/assets/958e7a91-7959-425c-a55e-a5dc52a30235" />

---

## ⚙️ Tools & Libraries

- **Python**, **Pandas**, **NumPy**  
- **Scikit-learn**, **XGBoost**, **TensorFlow/Keras**  
- **SHAP**, **LIME**, **Matplotlib**, **Seaborn**

---

## 🖼️ Visualizations

## Accuracy and Loss Curves
<img width="1077" height="441" alt="image" src="https://github.com/user-attachments/assets/c9663fe5-b74c-4037-b304-6d685bebd37d" />

## ROC curve and AUC
<img width="590" height="437" alt="image" src="https://github.com/user-attachments/assets/a9ace34e-a30f-45ea-9a3f-65ddc6d1f375" />

## Initialize LIME explainer
<img width="1004" height="288" alt="image" src="https://github.com/user-attachments/assets/f207ed0e-44e3-4498-b9f6-63def1995c51" />

## Plot LIME explanation as bar chart
<img width="556" height="383" alt="image" src="https://github.com/user-attachments/assets/ab9e0e03-d73e-4e7a-8524-d7802290a245" />

## SHAP Summary Plot
<img width="407" height="475" alt="image" src="https://github.com/user-attachments/assets/11ea9cff-574f-4e77-b3b5-bc9da75fb8c6" />

## SHAP Bar Plot showing mean absolute impact of each feature
<img width="434" height="474" alt="image" src="https://github.com/user-attachments/assets/e68ed6a4-b1e6-49fc-9b56-0ab1156418f4" />

## SHAP Force Plot for a single instance
<img width="1263" height="155" alt="image" src="https://github.com/user-attachments/assets/7a157895-e6de-43bc-9804-3ded75f8e61d" />

## SHAP Waterfall Plot
<img width="401" height="443" alt="image" src="https://github.com/user-attachments/assets/8586a6ef-e587-4ca8-a673-f924908a82ce" />

## SHAP Dependence Plot
<img width="592" height="398" alt="image" src="https://github.com/user-attachments/assets/ad443d07-b5e7-47a3-826a-8083dd841e0a" />

---

## 🧩 Workflow

1. **Data Collection & Cleaning** — handle missing values, normalize data  
2. **Feature Engineering** — extract key environmental and soil attributes  
3. **Model Training** — evaluate multiple ML/DL models  
4. **Explainability** — interpret predictions with SHAP/LIME  
5. **Visualization** — plot yield trends, feature importance, and explanations  

---

🧾 References
[Dataset Source (Kaggle)][(https://www.kaggle.com/datasets/samuelotiattakorah/agriculture-crop-yield)

---

💡 Created by Abdullah Al Mahmud Joy

B.Sc. in CSE | Teaching Assistant at BUBT | AI & Deep Learning Enthusiast

---
⭐ **If you find this project useful, please give it a star on GitHub!**
