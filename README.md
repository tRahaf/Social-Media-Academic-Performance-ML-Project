# Predicting Social Media Addiction and Its Impact on Academic Performance

--------------------------------------------------

# Overview:
This project analyzes how social media usage affects students' academic performance using machine learning techniques. The goal is to understand the relationship between usage behavior and academic outcomes.

--------------------------------------------------

# Dataset:
The dataset contains 300 student records and includes:
- Age
- Grade Level
- GPA
- Hours spent on social media
- Academic behavior and usage patterns

Dataset Source:
https://www.kaggle.com/datasets/muqniturrehman/social-media-and-academic-performance-of-students

--------------------------------------------------

# Data Preprocessing:
The dataset required several preprocessing steps:
- Removed extra spaces from column names
- Converted GPA ranges (e.g., 3.5-4.0) into numeric values
- Converted social media usage hours into numeric form
- Applied Label Encoding to categorical variables

--------------------------------------------------

# Feature Selection:
## Selected features:
- Age
- Grade Level
- Hours on Social Media
- GPA
- Affects Performance
- Academic Use Frequency

## Target Variable:
- Overall Effect

--------------------------------------------------

# Machine Learning Models:
The following models were used:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree

--------------------------------------------------

# Results:
- Logistic Regression Accuracy: 23%
- KNN Accuracy: 23%
- Decision Tree Accuracy: 30%

The Decision Tree model achieved the best performance among the tested models.

--------------------------------------------------

# Analysis:
The results show that the dataset presents a challenging prediction problem due to the complexity of student behavior and multiple influencing factors.

Although the accuracy is moderate, the models were able to capture meaningful patterns in the data. The Decision Tree model performed better as it can handle categorical data and non-linear relationships effectively.

These results highlight the importance of feature engineering and the potential for further improvement using more advanced techniques.

--------------------------------------------------

# Conclusion:
The results suggest a slight negative relationship between high social media usage and academic performance.  
However, predicting academic outcomes based only on social media usage remains challenging.
