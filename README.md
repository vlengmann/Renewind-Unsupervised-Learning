
# ReneWind - Predictive Maintenance for Wind Turbines
---
## Overview

#### This project aims to develop a machine learning model to predict failures in wind turbine generators, enabling proactive maintenance and reducing operational costs. By accurately predicting potential failures, ReneWind can implement timely repairs or replacements, minimizing downtime and optimizing resource allocation.
---
## Dataset Summary
The dataset provided by ReneWind consists of:

**Train.csv:** Contains 20,000 training examples with 40 features.
**Test.csv:** Contains 5,000 testing examples with 40 features.
The target variable is binary, indicating whether a failure occurred (1) or not (0). The features represent sensor data collected from various components of the wind turbine, such as gearbox, tower, blades, brakes, and environmental factors.

## Methodology
### Data Exploration and Preprocessing:

Analyze the data distribution
Split the data into training and validation sets.

### Model Selection and Training:
Experiment with various classification algorithms, such as:

#### Ensemble Methods:
- **Random Forest:** Combines multiple decision trees to improve accuracy and reduce overfitting.
- **Gradient Boosting:** Sequentially builds models, focusing on correcting the errors of previous models.
- **Adaboost:** Iteratively weights misclassified samples to improve model performance.
### Traditional Methods:
- **Logistic Regression:** Models the probability of a binary outcome.
- **Decision Tree:** Creates a tree-like model of decisions and their possible consequences.
- **Bagging Classifier:** Trains multiple models on different subsets of the data and averages their predictions.
- **XGBoost:** A powerful gradient boosting framework that optimizes performance and efficiency.

### Model Pipeline:

Developed a robust pipeline to streamline the entire modeling process, including data preprocessing, feature engineering, model training, hyperparameter tuning, and evaluation.

Utilized tools like scikit-learn's Pipeline and RandomizedSearchCV to automate and optimize the workflow.

### Model Evaluation:
Evaluate the performance of each model using appropriate metrics:
- Accuracy
- Precision
- Recall
- Confusion Matrix metrics
- F1-score
- ROC curve
- AUC-ROC curve

Consider the cost implications of false positives, false negatives, and true positives when choosing the best model.
### Model Deployment:
Deploy the selected model into a production environment to make real-time predictions.
Integrate the model with the wind farm's monitoring system to trigger maintenance actions.

---
## Languages and Utilities used
- Python
- Google Colab 
---
## Environments used
- Windows 11







