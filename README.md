# Prediction of Kyphosis using Decision Tree and Random Forest Algorithms
Objective:
To build predictive models using Decision Tree and Random Forest algorithms that classify whether a patient has Kyphosis (forward rounding of the back) after corrective spinal surgery, based on clinical features.
🛠️ Tools & Technologies:
Programming Language: Python

Libraries: pandas, numpy, sklearn, matplotlib, seaborn

Algorithms: Decision Tree, Random Forest
🔍 Project Steps:
1. Data Exploration and Preprocessing: 
Load the dataset

Check for missing values

Encode the categorical target variable (Kyphosis: yes → 1, no → 0)

Split the data into training and testing sets

2. Decision Tree Model:
Train a Decision Tree Classifier using sklearn.tree.DecisionTreeClassifier


Evaluate model using:

Confusion Matrix

Accuracy

Precision, Recall, F1-score

3. Random Forest Model:
Train a Random Forest Classifier using sklearn.ensemble.RandomForestClassifier

Use feature importance to analyze key predictors

Compare performance with Decision Tree
