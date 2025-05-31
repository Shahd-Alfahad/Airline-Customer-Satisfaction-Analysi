
# ✈️ Airline Customer Satisfaction Analysis

This project analyzes customer satisfaction data from Invistico Airlines using data preprocessing, RDD and SQL operations, and machine learning models. It was submitted as part of the IT462 - Big Data Systems course at King Saud University.

## 📌 Project Overview

The dataset includes over 120,000 records and 23 features, such as customer type, flight class, satisfaction rating, and service quality scores. The objective is to explore factors influencing satisfaction and build predictive models.

## 🧹 Key Steps
- **Data Preprocessing**: Handled missing values, removed outliers, encoded categorical variables, normalized features, and balanced classes.
- **RDD and SQL Analysis**: Used Spark RDDs and SQL to analyze satisfaction based on age, flight class, gender, and more.
- **Machine Learning**: Trained and evaluated models in Spark MLlib:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Gradient Boosted Trees (GBT)

## 🎯 Best Model: Gradient Boosted Trees (GBT)
- Accuracy: ~91%
- F1 Score: ~0.91
- Consistent results across different train-test splits

## 👥 Team Members
- Shahd Alfahad
- Yara Bahmaid
- Reema Aljalajel
- Aljohara Albanyan
- Raseel Alrawdhan
- Majd Aljuraysi

## 📄 Report
The full report is available in `IT462-Project-finalReport-G3.pdf`.

> 🏫 Project submitted for IT462 – Big Data Systems, King Saud University
