# Airline-Passenger-Satisfaction

This research involves using machine learning to address a binary classification problem in the airline sector.

## Aim:
The goal of this project is to create precise predictions about whether a customer will be satisfied with the service they received based on prior data.

## Methodology:
While the specifics of the methodology used in this project will be further discussed in the sections that follow, it is important to note that 16 machine learning models were applied, compared, and contrasted in order to determine which one performed the best.

### 01. Import CPU Python Libraries 

### 02. Function Helper

### 03. Import Dataset & Data Description
        - Import CSV File
        - Data Description

### 04. Data Understanding
        - Data Information
        - Data Summary Statistic
        - Data Variance

### 05. Select the Featurs

### 06. Data Pre-Processing
        -  Drop Variables 
        - Convert Data Type
        - Missing Value

### 07. Exploratory Data Analysis
        - DV Visualization
        - Categorical IDV
        - Categorical IDV With DV
        - Numerical IDV
        - Numerical IDV With DV

### 08. Data Transformation
        - Standard Scaler

### 09. Feature Selection
        - Wrapper - Forward

### 10. Feature Engineering 
        - LableEncoder

### 11. Statistics
        - Correlations IDV with DV
        - Correlation between all the Variables

### 12. Resampling Data
        - SMOTE

### 13. Data Splitting 

### 14. Standard Machine Learning Models 
      - Fit the Machine Learning Models 'Train the Models'
        -        Random Forest Classifier
        -        Gradient Boosting Classifier
        -        Histogram-based Gradient Boosting Classification Tree
        -        AdaBoost Classifier
        -        Extra Trees Classifier
        -        K Neighbors Classifier
        -        Naive Bayes Classifiers
        -        Naive Bayes Classifier for Multivariate Bernoulli
        -        Decision Tree Classifier
        -        Logistic Regression Classifier
        -        Logistic Regression CV Classifier
        -        Stochastic Gradient Descent Classifier
        -        Linear Perceptron Classifier
        -        XGBoost Classifiers
        -        Support Vector Machines Classifiers
        -        Linear Support Vector Classification
        -        Multilayer Perceptron Classifier
      - Predicat X_test
      - Models Evaluation
        -       Accuracy Score
        -       Classification Report
        -       Confusion Matrix

### 15. Accuracy Score Summary 

## Results:
The results for this project it is showing Random Forest Classifier, Extra Trees Classifier, and XGBoost Classifiers with accuracy (96.4, 96.4, and 95.8) respectively.

![Screenshot 2022-06-23 010905](https://user-images.githubusercontent.com/82437810/175097033-58eb89dc-1396-42a2-b0fa-21f44492bcec.png)


![newplot](https://user-images.githubusercontent.com/82437810/175095570-b5fac421-54c9-4068-b93e-815760cd9f3e.png)

## Discussion:
Although it has been shown that the  Random Forest Classifier, Extra Trees Classifier, and XGBoost Classifiers models have the highest accuracy when compared to all the other models, this score is not the only factor to take into consideration when selecting a model.

## Optimization:
It is to be mentioned that this performance can be expected to improve further by optimizing the models utilized. This can be done by experimenting further in terms of changing the hyper-parameters of the models, changing the method of feature selection, or using a different method of data transformation before deploying the machine learning models.
