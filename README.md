# 🏥 Heart Failure Risk Prediction & Key Health Indicator Analysis  
📌 **DSBA 2024 | Foundation of Machine Learning Assignment**  

## 📖 Overview  
This repository contains a **machine learning project** focused on **heart failure risk prediction** and **key health indicator analysis**. The project is part of the **2024 DSBA (Data Science & Business Analytics) Foundation of Machine Learning course at CentraleSupélec**.  

We leverage **supervised learning models** (Random Forest, SVM, XGBoost) to predict heart disease based on **clinical health indicators**. The dataset used is the **Kaggle Heart Failure Prediction Dataset**, which includes **13 medical features** related to cardiovascular health.  

## 🎯 Project Objectives  
✔ Develop machine learning models to predict **heart failure risk**  
✔ Analyze the **importance of key health indicators** in heart disease  
✔ Optimize models using **cross-validation and hyperparameter tuning**  
✔ Compare model performance using **recall, F1-score, and ROC-AUC**  

## 🗂️ Repository Structure  
## 📂 Repository Structure  
```bash
📁 Heart_Failure_Prediction  
│── 📜 README.md                  # Project documentation  
│── 📊 data/                       # Dataset used for training/testing  
│   ├── heart.csv                  # Kaggle Heart Failure Prediction Dataset  
│── 📈 notebooks/                  # Jupyter Notebooks for analysis & modeling  
│   ├── EDA.ipynb                   # Exploratory Data Analysis (EDA)  
│   ├── Random_Forest.ipynb         # Random Forest Model  
│   ├── SVM.ipynb                   # Support Vector Machine (SVM) Model  
│   ├── XGboost.ipynb               # XGBoost Model  
│── 📄 reports/                    # Project reports & documentation  
│   ├── Machine_Learning_Final_Report.pdf  # Final project report  
```

## 🔍 Dataset Description  
The dataset consists of **918 patient records** with **13 key medical attributes**, including:  
- **Age**  
- **Cholesterol Levels**  
- **Resting Blood Pressure (RestingBP)**  
- **Max Heart Rate (MaxHR)**  
- **ST Segment Slope (ST_Slope)**  
- **Exercise-Induced Angina**  

Target Variable:  
- **Heart Disease (1 = Diagnosed, 0 = Not Diagnosed)**  

## 🏆 Machine Learning Models Used  
- **📊 Exploratory Data Analysis (EDA)**: Feature distributions, correlation analysis  
- **🌲 Random Forest**: Best-performing model, achieving **Recall = 89.72% and ROC-AUC = 94.74%**  
- **📈 Support Vector Machine (SVM)**: Fine-tuned for recall, improved **F1-score to 91.35%**  
- **⚡ XGBoost**: Competitive performance with **ROC-AUC of 92.72%**  

## 📊 Key Results  
| Model          | Recall (%) | Precision (%) | F1-Score (%) | ROC-AUC (%) |
|---------------|-----------|--------------|-------------|------------|
| **Random Forest** | **89.72**   | **91.43**     | **90.57**    | **94.74**    |
| **SVM (Optimized)** | 93.14   | 89.62      | 91.35    | 93.64    |
| **XGBoost**    | 91.59   | 82.35      | 86.73    | 92.72    |

## 🛠️ Model Implementation Steps  
1️⃣ **Data Preprocessing**: Handling missing values, feature scaling, one-hot encoding  
2️⃣ **Exploratory Data Analysis (EDA)**: Feature selection & distribution analysis  
3️⃣ **Model Training**: Training and hyperparameter tuning using **Grid Search & Cross-Validation**  
4️⃣ **Performance Evaluation**: Comparing recall, precision, F1-score, and ROC-AUC  

## 📌 Conclusion  
- **Random Forest** emerged as the best-performing model due to its balance between **recall, interpretability, and robustness**  
- **ST Slope, Cholesterol, and Exercise-Induced Angina** were identified as the **most significant predictors**  
- Future work includes **deep learning approaches, time-series data integration, and model explainability improvements**  

---

## 📬 Contact  
📧 **Authors**:  
- **Lanxin LI** | lanxin.li@student-cs.fr  
- **Meng XIA** | meng.xia@student-cs.fr  
- **Hanqi YANG** | hanqi.yang@student-cs.fr  

📖 **CentraleSupélec, Paris, France**  
📝 **DSBA M2, Foundation of Machine Learning**  
