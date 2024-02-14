# My GradSchool_Projects

This repository is used to document some of my gradschool projects.

## Predicting Number of Ads watched per hour in a Media Platform

The goal of this project is to present the importance of regularization 
when working with regression models and best practices for developing ML 
workflows for estimators that require data transformation before modelling

### Methodology
Time series data of number of ads watched per hour in a media platform was 
used to train unregularized and regularized linear regression models and 
their predictive performances were compared. The ML workflow for the regularized 
regression was developed following best practices for data transformation, 
modelling and testing

### Key Findings
The unregularized model achieved a weighted average percentage error (WAPE) of 
**3.63%** on the training set and **4.73%** on the test set while the regularized model 
achieved a better performance of **4.12%** (training) and **4.34%** (test) respectively. 
The coefficients of the regularized model were also shrunk when compared to the 
unregularized model. These improvements are due to regularization, designed to 
prevent overfitting and improve the performance of the model on the test set. 
Most importantly, we can be confident that we are getting a realistic model 
performance since we employed the best practice in developing our ML workflow.

### Skills Developed
Best practices for developing ML workflows for estimators that require data 
transformation before modelling, intuition and understanding of the benefits 
of regularization in regression models

Read full article [here](https://medium.com/@yusufolonade).

## Data Science Curriculum Design Using Clustering Analysis

The goal of the project is to design a course curriculum for a Master of 
Business and Management in Data Science and Artificial Intelligence program 
at the University of Toronto, covering all technical and business skills 
required for Data professionals

### Methodology
Hierarchical clustering algorithm was implemented to design this curriculum. 
Job posting information was web scraped from Indeed web portal. The logic was 
to cluster skills that appear together in most job postings, the rationale was 
that those skills are likely similar, and it makes sense to teach them together 
in the same course. For example, communication, presentation and leadership skills 
appeared together in most job postings

### Key Findings
Communication, presentation, leadership, python, sql, databases, machine learning and 
big data are the most in-demand skills. These skills and many others have been structured 
into course topics and sequenced according to prerequisites to design the course curriculum 
presented in the notebook.

### Skills Developed
Data Cleaning, Feature Engineering, Exploratory Data Analysis (EDA), Hierarchical Clustering 
Implementation and Analysis

Read full article [here](https://medium.com/@yusufolonade).

## Linear Regression from Sratch Using Direct Solution and Gradient Descent

The goal of the project was to implement linear regression from scratch using a direct 
solution and full-batch gradient descent algorithm. The direct solution produced an RMSE 
value of **0.000172** on the test set while full batch gradient descent produced **0.000173**. 
Direct solution is known to be computationally expensive due to inverse computation hence 
gradient descent algorithm is preferred.

### Skills Developed
Implementation of mathematical formulas with Numpy





