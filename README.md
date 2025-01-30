![logo](https://github.com/user-attachments/assets/30b7035e-2f83-44d4-845d-be1e7546ae45)


# Airline Customer Satisfaction Predictor: A Machine Learning Model for Predicting Customer Satisfaction

1. [Introduction](#introduction-)
2. [Description](#description-)
3. [Installation](#installation-)
4. [Contact](#contact-)


## Introduction 📝
This project is about predicting customer satisfaction regarding their flight experience which is affected by numerous features. Some of these features include basic information such as age and class, however, there are more specific features that detail the flight experience such as departure and arrival delays, legroom service, Flight distance, and many more.    

**Technologies and Concepts used**
1. Python for building and implementing machine learning models.
2. Skicit-learn used for data preprocessing, feature selection, and implementing machine learning
3. Matplotlib and Seaborn for data visualizations
4. LightGBM and Decision Tree for the Machine Learning models
5. Streamlit for ML deployment
6. Joblib for saving and loading machine learning models efficiently.


## Description 🎯
**EDA** (Below are examples of the EDA performed and its results)
![heatmap](https://github.com/user-attachments/assets/f78a3600-a006-4b42-86ad-acfab1af4fd7)


Correlation Heatmap Summary
The heatmap highlights key correlations in the dataset:

Positive Correlations:

"Ease of Online Booking" and "Online Boarding" (0.71).
"Class" (0.49) and "Loyal Customer" (0.39) strongly influence satisfaction.
"Inflight Entertainment" and "Inflight Service" (0.61).
Minimal Impact:

Delays show negligible correlation with satisfaction (-0.01 to -0.02).
![sample](https://github.com/user-attachments/assets/0690fe97-fc08-418d-9c00-6335b8187710)

Flight Distance Data Analysis
The data is right-skewed, with most flights under 1000 units.
The boxplot highlights a compact range for typical flights and several outliers beyond 4000 units, representing long-haul flights.
Most flights are short, with a small number of extremely long-distance flights.

**Preprocessing**

![smote](https://github.com/user-attachments/assets/82c18876-9504-45b9-9ff8-260a0ff55678)
![SMOT2](https://github.com/user-attachments/assets/32bca048-b0f0-4607-a881-939fbdc7aa8f)





The images above showcase SMOTE being used to handle class imbalance.

**MACHINE LEARNING**
![dec1](https://github.com/user-attachments/assets/6c044df1-3822-4faf-8f34-ddb7434a88fb)
![dec2](https://github.com/user-attachments/assets/a7ea8f1b-6d0c-4ae9-bfa3-1d4c8f81b34b)

Training vs Test Performance:

The model performs slightly better on the training set (86% accuracy) than on the test set (82%), indicating minor overfitting.
Class Imbalance Handling:

High recall for class 1 (positive class) indicates strong performance in identifying positives.
Lower recall for class 0 (negative class) on both sets highlights the difficulty in detecting all negative cases.
Precision and Recall Trade-Off:

Precision for class 1 drops on the test set (0.71), suggesting more false positives on unseen data.

**FEATURE IMPORTANCE**
![FEATURE](https://github.com/user-attachments/assets/e92cfa17-bae5-4742-92a0-b7d3719e291a)

Feature importance to acquire the top 10 features out of 32 features that affect customer satisfaction.



🚀 Streamlit Deployment - https://app-apppy-4aspww2t4wz2nkuyqnnjui.streamlit.app/










## Installation ⚙️

**Clone the repo**
```bash
git clone https://github.com/jaylesmajor/Airline-Satisfaction-Classification
```

## Contact 📧
Jayles Escolar - jayles.escolar@yahoo.com

Project link: https://github.com/jaylesmajor/Airline-Satisfaction-Classification

 
