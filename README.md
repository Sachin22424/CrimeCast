# 🔍 CrimeCast – Crime Category Prediction using Machine Learning

CrimeCast is a machine learning-based project aimed at forecasting crime categories using real-world crime data. By analyzing temporal, spatial, and demographic features, CrimeCast helps in understanding crime trends, enabling law enforcement agencies to allocate resources more efficiently and proactively.

## 📌 Project Overview

The rise in urban crime necessitates smarter tools for prediction and prevention. CrimeCast leverages machine learning models to classify crimes into categories such as:
- Property Crimes
- Violent Crimes
- Crimes Against Persons

The project uses historical crime records with details like location, time, victim characteristics, and weapons involved to predict crime categories and uncover spatial-temporal patterns.

## 👥 Team Members

| Name           | Roll No. | Contribution |
|----------------|----------|--------------|
| Sachin Maurya  | 2022424  | Data collection, preprocessing, documentation, web development |
| Niteen Kumar   | 2022336  | Exploratory Data Analysis (EDA), feature engineering, optimization |
| Pratham Mittal | 2022373  | Model selection, training, and evaluation |
| Satyam         | 2022462  | Model optimization and final evaluation |

## 📂 Dataset

The dataset includes crime reports with the following key features:

- Location (Latitude, Longitude, Area Name)
- Time Occurred, Date Reported
- Victim Age, Sex, Descent
- Weapon Used, Premise Details
- Status and Modus Operandi
- Target: `Crime Category`

### 🛠 Preprocessing Steps:
- Feature selection and engineering
- Handling missing values (imputation/removal)
- Date and time formatting
- One-hot and label encoding
- Scaling numerical variables (Min-Max)

## 📈 Exploratory Data Analysis (EDA)

- Histograms and boxplots for feature distributions
- Heatmaps for correlation analysis
- Outlier detection in numeric features
- Time-based trends in crime occurrences

## 🤖 Models Trained

| Model              | Accuracy | Precision | Recall | F1 Score |
|--------------------|----------|-----------|--------|----------|
| Naive Bayes        | 33.90%   | 79.00     | 34.00  | 42.00    |
| Random Forest      | 83.55%   | 83.12     | 84.34  | 82.47    |
| XGBoost ✅          | 87.10%   | 87.00     | 85.32  | 86.88    |
| SVM                | 86.18%   | 85.68     | 85.45  | 72.60    |
| MLP Classifier     | 86.10%   | 85.00     | 86.17  | 86.00    |

- **XGBoost** emerged as the top performer, offering the best overall performance across metrics.

## 🔁 Validation

- 10-fold Cross-Validation was used to ensure generalizability and reduce overfitting.

## 🗓️ Timeline

- ✅ Dataset Collection & Cleaning
- ✅ Exploratory Data Analysis (EDA)
- ✅ Feature Engineering
- ✅ Model Training & Hyperparameter Tuning
- ✅ Final Evaluation & Report Preparation
- ✅ Feedback Integration

## 📚 References

1. Seidensticker & Schwarz (2022) – *The SKALA Approach for Predictive Policing*
2. Shah, Bhagat & Shah – *Crime Forecasting using ML and CV Techniques*
3. Zhu et al. (2021) – *Crime Prediction using Urban Heterogeneous Data*
4. Martinez et al. (2022) – *ML Models for Crime Categorization*
5. McGlohon et al. (2018) – *Crime and Punishment: Urban Crime Prediction*

## 🔗 GitHub Repository

🔗 [CrimeCast GitHub Repo](https://github.com/Sachin22424/CrimeCast)

---

> ⚠️ This project is for academic and research purposes. Real-world deployment must consider ethical, legal, and social implications of predictive policing tools.

