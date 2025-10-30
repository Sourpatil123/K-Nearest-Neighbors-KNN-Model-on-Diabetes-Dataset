# K-Nearest-Neighbors-KNN-Model-on-Diabetes-Dataset

📘 Project Overview

This project implements the K-Nearest Neighbors (KNN) algorithm to predict the likelihood of diabetes based on various health indicators. The model classifies patients as diabetic or non-diabetic using a distance-based learning approach that evaluates feature similarity between data points.

🎯 Objective

To develop and evaluate a KNN Classification Model that accurately predicts diabetes status and maintains a good balance between precision, recall, and F1-score for both training and testing datasets.

🧩 Dataset Description

The Diabetes Dataset contains several medical and physiological parameters that influence the onset of diabetes.

Typical features include:

Pregnancies: Number of pregnancies

Glucose: Plasma glucose concentration

Blood Pressure: Diastolic blood pressure

Skin Thickness: Triceps skin fold thickness

Insulin: Serum insulin level

BMI: Body Mass Index

DiabetesPedigreeFunction: Family history indicator

Age: Age in years

The target variable indicates whether a person is diabetic (1) or non-diabetic (0).

⚙️ Technologies Used

Language: Python 🐍

Libraries:

pandas – Data manipulation and cleaning

numpy – Mathematical computation

matplotlib / seaborn – Visualization

scikit-learn – Machine learning and model evaluation

🧮 Model Development Steps

Data Preprocessing

Handled missing or zero values in medical features

Normalized the dataset using StandardScaler

Split data into training and testing sets

Model Building

Imported and initialized KNeighborsClassifier

Selected the optimal k value through experimentation or elbow method

Model Evaluation
|  Dataset  | Precision | Recall | F1-Score |
| :-------: | :-------: | :----: | :------: |
| **Train** |    0.82   |  0.89  |   0.85   |
|  **Test** |    0.80   |  0.79  |   0.80   |

✅ The results show that the KNN model performs consistently well on unseen data with strong recall, indicating that it successfully identifies most diabetic patients.

🔍 Insights

High recall on training data (0.89) suggests strong sensitivity to diabetic cases.

The model maintains a solid balance between precision and recall on test data, proving it generalizes well.

Fine-tuning k and distance metrics could further enhance accuracy.

📈 Visualization

Confusion Matrix – To visualize true and false classifications.

ROC Curve – To evaluate the model’s diagnostic ability.

Elbow Plot – To determine the best k value for optimal accuracy.

Evaluated model using precision, recall, and F1-score metrics for both train and test sets

📊 Model Performance
