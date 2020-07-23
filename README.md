# Loan Prediction Using Classification Machine Learning Algorithms
This repository includes the final project files of 'Machine Learning with Python' course .
In this project, we aim to practice Machine Learning  classification algorithms with Scikit-learn library in IBM Watson Studio. We load a dataset about past loans using Pandas library, and apply the KNN, Decision Tree, SVM, and LogisticRegression algorithms, and find the best one for this specific dataset by accuracy evaluation methods.

# Dataset
Past loan data set includes details of 346 customers whose loan are already paid off or defaulted.
The dataset has the following list of features:
Loan_status	*Whether a loan is paid off on in collection*
Principal	*Basic principal loan amount at the*
Terms	*Origination terms which can be weekly (7 days), biweekly, and monthly payoff schedule*
Effective_date	*When the loan got originated and took effects*
Due_date	*Since it’s one-time payoff schedule, each loan has one single due date*
Age	*Age of applicant*
Education	*Education of applicant*
Gender	*The gender of applican*

# EDA
Below graphs show the ditribution of paid-off an collection in both genders based on different data features such as age, principal, day of the week.
![alt text](https://github.com/nmshafie1993/Coursera_ml_python/blob/master/Gender%20vs%20principles.png)
![alt text](https://github.com/nmshafie1993/Coursera_ml_python/blob/master/Gender%20vs%20day.png)
![alt text](https://github.com/nmshafie1993/Coursera_ml_python/blob/master/gender%20vs%20age.png)

# Model Building
In the first step, the categorical data has been transformed to dummy data with encoding approach. Then, the most 
