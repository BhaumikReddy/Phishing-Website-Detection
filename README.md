# Phishing Website Detection

## 📌 Overview
Phishing attacks are one of the most common cybersecurity threats, tricking users into revealing sensitive information such as usernames, passwords, and financial details. This project utilizes **machine learning** techniques to detect phishing websites based on various features.

## 📂 Dataset
The dataset used in this project is sourced from Kaggle:  
[Phishing Website Detector Dataset](https://www.kaggle.com/eswarchandt/phishing-website-detector)  

It contains multiple attributes that help in distinguishing between **legitimate** and **phishing** websites.

## 🎯 Goal
The main goal of this project is to:
- Build a machine learning model to detect phishing websites.
- Compare different classification algorithms to identify the best-performing model.

## 🛠️ Technologies Used
- **Python** 
- **Pandas, NumPy** (Data Processing)
- **Scikit-learn** (Machine Learning)
- **Matplotlib, Seaborn** (Visualization)

## ⚙️ Machine Learning Models Used
The following classification algorithms were implemented and compared:
1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **Random Forest Classifier**
4. **K-Nearest Neighbors (KNN)**
5. **Support Vector Machine (SVM)**
6. **Gradient Boosting**
7. **AdaBoost Classifier**

## 📊 Model Performance
| Model                        | Accuracy (%) |
|------------------------------|-------------|
| **Random Forest Classifier** | **97.05**   |
| **Decision Tree Classifier** | **94.72**   |
| Logistic Regression          | 92.76       |
| AdaBoost Classifier          | 91.04       |
| Gradient Boosting            | 84.11       |
| KNN Algorithm                | 63.52       |
| Support Vector Machine (SVM) | 56.04       |

Based on accuracy scores, **Random Forest Classifier** and **Decision Tree Classifier** performed the best.