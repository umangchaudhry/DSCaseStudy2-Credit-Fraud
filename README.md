# DSCaseStudy2-Credit-Fraud README
    Group Project (Team 2) for Vanderbilt DSI Course 5360: Case Studies in Data Science. This is Case Study #2, Detecting Credit Card Fraud

    Original Project Link: https://data-flair.training/blogs/data-science-machine-learning-project-credit-card-fraud-detection/

## This Repo is organized in the following manner: 
    1. Data - This contains the link of Credit Fraud dataset which is used to train our machine learning models. The dataset is too large to be stored on github. In order to run this repo, please download the dataset from the given link under the data folder and save the csv file in the data folder. 
    2. ipynb files - Run these files to present the model performance in each ML model after training Credit Fraud dataset.
    3. HTML files - Basic statistical analysis reports for the entire dataset and only the fraud data.

## ipynb file description
    Please ensure creditcard.csv is downloaded and saved to the data folder in this repository before running any of these files.

    1.XGBoost_and_GDB_Model.ipynb
        We scale time and amout to improve convergence speed of the model and also enhance model accuracy. Then we compare XGB and GBD model performance. After choosing XGB model, we use two different sampling methods techique on XGB models. Finally, we use cross validation method to turn the parameter for XGB and show our final results of XGB model.

    2. RF_credit card.ipynb
    
       Random Forest model pipeline with three different sampling methods.
   
    3. RF_test_db_for_dashboard.ipynb   
    
       Generating test data with preditc probability for Random Forest which will be used for the dashboard.
       
    4. SVM.ipynb
    
       This file performs analysis with support vector machine(SVM) model. The results are presented in a confusion matrix.
       
    5. neural_net.ipynb
    
       This file provides the framework for a deep neural network (DNN) that can be used for binary classification. Preprocessing steps are run before the model for both undersampling and oversampling techniques. Evaluation metrics are available under the prediction sections of each model's improvements. 
       
    6. LogisticRegression.ipynb
    
       This file develops a logistic regression model told predict credit card fraud. Additionally, results of the model are also presented in the form of a confusion matrix within this file.
       
    7. Dashboard.ipynb
       
       This file has the code that is used to run the Dashboard. Before running this file, please run RF_test_db_for_dashboard. This ipynb creates a csv that acts as the source data for the dashboard. In the case the dashboard still does not run, please make sure that the resulting csv file called "test_df_full.csv" is saved to the data folder. To run the dashboard, please run the entire file in Jupyter Notebooks. You may need to change jupyter notebook settings in order to display in-line animations and the dashboard. 
