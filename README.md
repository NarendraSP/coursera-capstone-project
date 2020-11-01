Repository for capstone project for IBM professional certificate in "Machine Learning with Python".


## ML_Project Notebook
coursera course title: 'Machine Learning with Python'

**Project : Build a classifier to predict whether a loan case will be paid off or not**

## Project Details
In this project, I will complete a notebook where I will build a classifier to predict whether a loan case will be paid off or not.

I load a historical dataset from previous loan applications, clean the data, and apply different classification algorithm on the data.
I am expected to use the following algorithms to build my models:

- k-Nearest Neighbour
- Decision Tree
- Support Vector Machine
- Logistic Regression

The results is reported as the accuracy of each classifier, using the following metrics when these are applicable:

- Jaccard index
- F1-score
- LogLoass


## Objectives
In this notebook we try to practice all the classification algorithms that we learned in this course.
We load a dataset using Pandas library, and apply the following algorithms, and find the best one for this specific dataset by accuracy evaluation methods.
- 1. Building model using KNN, finding the best k and accuracy evaluation 
- 2. Building model using Decision Tree and find the accuracy evaluation 
- 3. Building model using SVM and find the accuracy evaluation 
- 4. Building model using Logistic Regression and find the accuracy evaluation 

## About dataset
This dataset is about past loans. The __Loan_train.csv__ data set includes details of 346 customers whose loan are already paid off or defaulted. It includes following fields:

| Field          | Description                                                                           |
|----------------|---------------------------------------------------------------------------------------|
| Loan_status    | Whether a loan is paid off on in collection                                           |
| Principal      | Basic principal loan amount at the                                                    |
| Terms          | Origination terms which can be weekly (7 days), biweekly, and monthly payoff schedule |
| Effective_date | When the loan got originated and took effects                                         |
| Due_date       | Since it’s one-time payoff schedule, each loan has one single due date                |
| Age            | Age of applicant                                                                      |
| Education      | Education of applicant                                                                |
| Gender         | The gender of applicant                                                               |

## Report
You should be able to report the accuracy of the built model using different evaluation metrics:
| Algorithm          | Jaccard | F1-score | LogLoss |
|--------------------|---------|----------|---------|
| KNN                | ?       | ?        | NA      |
| Decision Tree      | ?       | ?        | NA      |
| SVM                | ?       | ?        | NA      |
| LogisticRegression | ?       | ?        | ?       |


## Classification Predictive Modeling
In machine learning, classification refers to a predictive modeling problem where a class label is predicted for a given example of input data.

Examples of classification problems include:
- Given an example, classify if it is spam or not.
- Given a handwritten character, classify it as one of the known characters.
- Given recent user behavior, classify as churn or not.
