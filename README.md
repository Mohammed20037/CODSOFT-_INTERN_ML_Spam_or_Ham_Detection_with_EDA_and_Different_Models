# CODSOFT_INTERN_ML_Spam_or_Ham_Detection_with_EDA_and_Different_Models

## Introduction

Welcome to the "Spam or Ham Detection with EDA and Different Models" project. This project is part of an ML internship with CodSoft, where we aim to tackle the challenging task of spam detection using a combination of Exploratory Data Analysis (EDA) and various machine learning models. Effective spam detection is crucial for email filtering and text classification.

## Dataset

Our dataset consists of a curated collection of messages, each classified as either "spam" or "ham" (non-spam). Prior to analysis and model training, we've meticulously preprocessed and cleaned the data to ensure its quality.

## Exploratory Data Analysis (EDA)

In this project, EDA plays a pivotal role in understanding the dataset's characteristics. We leverage data visualization, statistical analysis, and feature engineering techniques to gain insights into the distribution of spam and ham messages. These insights help improve the performance of our machine learning models.

## Model Comparison

Our journey involves the implementation and evaluation of several machine learning models, each designed to classify messages as spam or ham. Below is a comprehensive comparison of these models:

1. **Naive Bayes**:
   - Accuracy: 0.961
   - F1-Score (spam class): 0.83
   - While displaying good overall accuracy, this model exhibits lower precision and recall for the spam class, indicating potential areas for improvement.

2. **Logistic Regression**:
   - Accuracy: 0.944
   - F1-Score (spam class): 0.73
   - This model delivers decent accuracy but struggles with precision and recall for the spam class, implying the presence of false positives and false negatives.

3. **Decision Tree**:
   - Accuracy: 0.956
   - F1-Score (spam class): 0.82
   - It offers competitive accuracy with balanced precision and recall for the spam class.

4. **Random Forest**:
   - Accuracy: 0.971
   - F1-Score (spam class): 0.87
   - This model stands out with high accuracy and balanced precision and recall for the spam class.

5. **AdaBoost**:
   - Accuracy: 0.955
   - F1-Score (spam class): 0.80
   - Although accuracy is respectable, precision and recall for the spam class may require further refinement to mitigate false positives and false negatives.

6. **Gradient Boosting**:
   - Accuracy: 0.956
   - F1-Score (spam class): 0.80
   - Similar to AdaBoost, this model maintains balanced accuracy while exhibiting lower precision and recall for the spam class.

7. **K-Nearest Neighbors (KNN)**:
   - Accuracy: 0.903
   - F1-Score (spam class): 0.41
   - This model experiences lower overall accuracy and faces challenges in precision and recall for the spam class.

8. **Support Vector Machine (SVM)**:
   - Accuracy: 0.971
   - F1-Score (spam class): 0.88
   - SVM impresses with high accuracy and well-balanced precision and recall for the spam class.

9. **Grid Search with SVM**:
   - Accuracy: 0.983
   - F1-Score (spam class): 0.93
   - The Grid Search with SVM emerges as the top-performing model, achieving the highest accuracy and demonstrating robust precision and recall for the spam class.

## Conclusion

This project, undertaken as part of an ML internship with CodSoft, provides invaluable insights into the effectiveness of various machine learning models for spam detection. Our results have significant implications for email filtering and text classification systems.

In summary:

- **Grid Search with SVM** is the standout model, boasting the highest accuracy and superior precision and recall for the spam class.

- **Random Forest** also delivers commendable performance, with high accuracy and competitive precision and recall.

- When striking a balance between accuracy and spam class detection is crucial, **Decision Tree** and **Support Vector Machine (SVM)** are solid choices.

- Models such as **Naive Bayes**, **Logistic Regression**, **AdaBoost**, and **Gradient Boosting** exhibit promise but may benefit from further fine-tuning for improved spam class detection.

- **K-Nearest Neighbors (KNN)** ranks lowest among the models, with lower accuracy and significant challenges in detecting spam.

We hope this project serves as a valuable resource for building robust spam filters and email classification systems. Thank you for exploring our work!
