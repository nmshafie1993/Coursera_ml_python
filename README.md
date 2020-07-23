# Loan Prediction Using Classification Machine Learning Algorithms
This repository includes the final project files of 'Machine Learning with Python' course .
In this project, we aim to practice Machine Learning  classification algorithms with Scikit-learn library in IBM Watson Studio. We load a dataset about past loans using Pandas library, and apply the KNN, Decision Tree, SVM, and LogisticRegression algorithms, and find the best one for this specific dataset by accuracy evaluation methods.

# Dataset
Past loan data set includes details of 346 customers whose loan are already paid off or defaulted.<br>
The dataset has the following list of features:<br>
Loan_status	*Whether a loan is paid off on in collection*<br>
Principal	*Basic principal loan amount at the*<br>
Terms	*Origination terms which can be weekly (7 days), biweekly, and monthly payoff schedule*<br>
Effective_date	*When the loan got originated and took effects*<br>
Due_date	*Since it’s one-time payoff schedule, each loan has one single due date*<br>
Age	*Age of applicant*<br>
Education	*Education of applicant*<br>
Gender	*The gender of applican*<br>

# EDA
Below graphs show the ditribution of paid-off an collection in both genders based on different data features such as age, principal, day of the week.<br>
![alt text](https://github.com/nmshafie1993/Coursera_ml_python/blob/master/Gender%20vs%20principles.png)<br>
![alt text](https://github.com/nmshafie1993/Coursera_ml_python/blob/master/Gender%20vs%20day.png)<br>
![alt text](https://github.com/nmshafie1993/Coursera_ml_python/blob/master/gender%20vs%20age.png)<br>

# Model Building
Using encoding approach, the categorical data has been transformed to dummy data. Then, the most 
