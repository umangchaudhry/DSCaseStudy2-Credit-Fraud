# DSCaseStudy2-Credit-Fraud README
    Group Project (Team 2) for Vanderbilt DSI Course 5360: Case Studies in Data Science. This is Case Study #2, Detecting Credit Card Fraud

    Original Project Link: https://data-flair.training/blogs/data-science-machine-learning-project-credit-card-fraud-detection/

## This Repo is organized in the following manner: 
    1. Data - This contains the Credit Fraud dataset which is used to train our machine learning models.
    2. ipynb files - Run these files to present the model performance in each ML model after training Credit Fraud dataset.
    3. HTML files - (add something here plz)

## ipynb file description


    1.XGBoost_and_GDB_Model.ipynb
    
        In this notebook, since most of our columns in the dataset has already been scaled, we could scale the time and amount 
        to improve the convergence speed of the model and also enhance model accuracy. Then we used the dataset to train our XGB 
        model and output our model performance such recall and precision and plot the feature importance hist graph to see the model's 
        influential factors. And then we use the same way to train GBD model. The average performance of GBD is no so good. 
        Thus we choose XGB model from the two models and  then we do further exploration on XGB model by using UnderSampling 
        technique and OverSampling technique to seek for a better model performance and solve imbalance data problem. 
        The underSampling technique does help us detect most of fraud cases but it also affects XGB model's precision. 
        Oversampling did not bring much improvement on XGB models. Thus, we still insists on using XGB without using UnderSampling 
        and OverSampling. Finally, we use cross validation method to turn the better parameter for XGB and show our final                         results of XGB model.
        

