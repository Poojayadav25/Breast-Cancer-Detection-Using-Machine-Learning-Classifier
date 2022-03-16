# Breast-Cancer-Detection-Using-Machine-Learning-Classifier
## Goal of the ML project
We have extracted features of breast cancer patient cells and normal person cells. As a Machine learning engineer / Data Scientist has to create an ML model to classify malignant and benign tumor. To complete this ML project we are using the supervised machine learning classifier algorithm.
![images](https://user-images.githubusercontent.com/90573789/158646640-f5e4d8fb-a34e-4510-866f-f15e98e6de2e.jpg)
Simple App which can detect Weather they have Cancer or not depending up on users data provided to the application.

- Created an app that detects wheather they have Cancer or not to help doctors with 98% accuracy .
- Data collected from Open source websites from Internet .
- Processed features to make data look's like perfect and to get good accuracy with less loss
- I had used Ada boost Classifier ,XGBoost ,Logistic ,support vector,naive bays,decision tree,random forest to reach best model
## Code and Resources Used :
Python Version : 3.7
Packages: pandas, numpy, sklearn, matplotlib, seaborn, selenium, flask, json, pickle
## Data Cleaning 
Data look's perfect and there is no null data present in this data set .
## EDA :
I looked at the distributions of the data and the value counts for the various categorical variables.
<img width="915" alt="Screenshot 2022-03-16 220642" src="https://user-images.githubusercontent.com/90573789/158647506-d67a5890-85f2-4718-b3ed-1d76f8a97695.png">
## Model Building :
First, I transformed the categorical variables into dummy variables. I also split the data into train and tests sets with a test size of 20%.
I tried three different models and evaluated them using Classification Metrics. I chose Confusion Matrix Because it's better to understand how many features are going to support and not going to support .
I tried 7 different models:

- Support Vector Classifier: It classifies data perfectly
- Logistic Regression
- K-Nearest Neighbour Classifier
- Naive Bayes Classifier
- XGBoost Classifier
- Adaboost classifier
- Random forest classifier
- Decision tree classifier
## Model Performance :
The XGBoost model far outperformed the other approaches on the test and validation sets.

- XGBoost Classifier : Accuracy = 98
- Support Vector Classifier : Accuracy =96
- Logistic Regression : 97
- Decision Tree Classifier : 94
- K-Nearest Neighbour Classifier : 94
- Naive Bayes Classifier : 94
- Adaboost classifier : 94.73
- Random forest classifier : 97
## conclusion:
Breast Cancer Detection App Using Machine Learning XGBoost Classifier



