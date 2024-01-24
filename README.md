# Predictive Analysis of Diabetes Health Indicators

The objective of this project is to study the risk factors and indicators of the disease and build a classification model that can predict whether a person is at risk of diabetes. This can potentially help is early detection of the disease and discover the key underlying causes.

## About the Dataset

UCI: [CDC Diabetes Health Indicators](https://archive.ics.uci.edu/dataset/891/cdc%2Bdiabetes%2Bhealth%2Bindicators)

The dataset consists of 70692 responses from a CDC's BRFSS2015 survey. It consists of 22 variables, of which, 21 are predictor variables and 1 is the target variable

## Flow of the Project:
### Data Preprocessing:
We start by checking for null values and duplicates in our data, promptly cleaning up any issues found. To also get deeper understanding of the data, we look for correlations and patterns among the predictors to gain deeper insights.
### Feature Engineering:
We implement Jaccard Similarity index to check the similarity between the columns. Identify and eliminate duplicate rows in the data having high correlation between columns.
### Data Splitting:
This involves splitting the data into sets to train and test the model. Data was split into 3 sets across the 2 models implemented.
### Logistic Regression with Elastic Nets:
Implementation of Logistic regression with elastic nets for binary classification as a baseline model.
### Neural Networks:
Deep Neural Network with 3 hidden layers has been implemented as the second model.
### Bias-Variance Trade-off:
Represents the balance between a model's simplicity (bias) and its sensitivity to training data (variance).
Model Evaluation: The model’s accuracy will be tested using several metrics such as accuracy, precision, recall and F1-Score.

## Result:
The comparative analysis between the Logistic Regression model and the Neural Network model for diabetes prediction highlighted distinct trade-offs in performance, time, and cost. The Neural Network model demonstrated superior precision and accuracy, indicating a stronger predictive capability at the expense of increased computational time and cost. Conversely, the Logistic Regression model was faster and more cost-effective, but less accurate. The selection between these models would depend on the specific application needs, balancing the importance of predictive accuracy against computational constraints.