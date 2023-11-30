# University Intake Prediction Project

## Overview

This project aims to predict university intake based on various factors using classification techniques. The dataset comprises the following columns: 'GRE Score', 'TOEFL Score', 'University Rating', 'SOP', 'LOR', 'CGPA', 'Research', and 'Chance of Admit'.

### Objective

The primary goal is to utilize classification techniques to predict university intake, categorizing the 'Chance of Admit' into binary classes based on a threshold of 0.75.

### Dataset Information

**Features**: 'GRE Score', 'TOEFL Score', 'University Rating', 'SOP', 'LOR', 'CGPA', 'Research'

**Target Variable**: 'Chance of Admit'

## Methodology

**Data Preprocessing**: Handled missing values, feature engineering, and binarized the 'Chance of Admit' column based on a threshold of 0.75.

### Classification Techniques

**Random Forest Classifier**: Ensemble method utilizing multiple decision trees to improve accuracy and reduce overfitting.
**Support Vector Machine (SVM)**: Supervised learning algorithm used for classification tasks, effective in high-dimensional spaces.
**Decision Tree Classifier**: Constructed decision trees to predict the target variable.
**Naive Bayes Classifier**: Probabilistic classifier based on Bayes' theorem with an assumption of feature independence.

### Steps

**Data Preparation**: Loaded the dataset, handled missing values, and performed feature selection.
**Binarization of 'Chance of Admit'**: Converted 'Chance of Admit' into binary classes based on a threshold of 0.75.
**Feature Selection**: Utilized 'GRE Score', 'TOEFL Score', 'University Rating', 'SOP', 'LOR', 'CGPA', 'Research' as features for modeling.
**Model Building and Evaluation**: Implemented Random Forest, SVM, Decision Tree, and Naive Bayes classifiers.
**Performance Evaluation**: Evaluated model performance using accuracy scores, classification reports, confusion matrices.