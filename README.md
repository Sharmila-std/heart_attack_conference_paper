# Heart Attack Risk Prediction Using Voting Classifier Model

This repository contains the implementation of a machine learning-based framework to predict heart attack risk based on medical, lifestyle, and psychological factors. This work was presented as part of the research paper: **"Heart Attack Risk Prediction Using Voting Classifier Model based on Medical and Lifestyle Factors."**

## 📌 Abstract
Heart attacks remain a leading cause of global mortality. This study proposes an ensemble machine learning framework utilizing multiple classification algorithms. By incorporating hyperparameter tuning via GridSearchCV and an ensemble soft voting technique, the model achieves an accuracy of **81.05%** on a comprehensive dataset of 50,000 records.

## 📊 Methodology
The project employs a **Soft Voting Classifier** that aggregates probabilistic predictions from the following eight high-performing models:
* Adaptive Boosting (AdaBoost)
* Gradient Boosting
* Categorical Boosting (CatBoost)
* XGBoost
* Bagging Classifier
* Balanced Random Forest
* Gaussian Naive Bayes
* Decision Tree

### 
## 🛠️ Features & Dataset
The model analyzes 23 distinct features across four categories:
* **Demographics:** Age, Gender, Region.
* **Medical History:** Blood Pressure, Cholesterol, BMI, Heart Rate, Diabetes, Family History.
* **Lifestyle:** Exercise, Smoking, Alcohol, Diet, Sleep, Water Intake.
* **Psychological:** Stress Levels, Mental Health Status.

## 📈 Performance Summary
| Model | Accuracy (Optimal Split/Estimators) |
| :--- | :--- |
| AdaBoost | 88.64% |
| Gradient Boosting | 88.64% |
| CatBoost | 88.64% |
| Bagging | 88.61% |
| **Voting Classifier** | **81.05%** |

## 🚀 Key Findings
* [cite_start]Ensemble methods like Gradient Boosting and AdaBoost showed the highest individual predictive strength[cite: 240].
* [cite_start]The study highlights a significant prevalence of heart attack cases among youth (3,378 cases) compared to the aged group (2,503 cases) in the dataset analyzed[cite: 272, 297].
* [cite_start]Label encoding was utilized for categorical variables to maintain optimal performance without the high dimensionality of one-hot encoding[cite: 117].

## 👥 Authors
* [cite_start]**Sarmiladevi G** - Amrita Vishwa Vidyapeetham [cite: 2, 5]
* [cite_start]**Vibhushana Baskar** - Amrita Vishwa Vidyapeetham [cite: 6, 8]
* [cite_start]**Dheeraj P** - Amrita Vishwa Vidyapeetham [cite: 10, 12]
* [cite_start]**Vandhana S** - Amrita Vishwa Vidyapeetham [cite: 14, 16]
* [cite_start]**Shubha Harini R V** - Amrita Vishwa Vidyapeetham [cite: 18, 20]
* [cite_start]**Kirubavathi G** - Amrita Vishwa Vidyapeetham [cite: 22, 24]
