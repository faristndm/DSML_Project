# Credit Card Default Prediction
This project aims to build a model that predict whether a customer will default their next month credit card payment using mechine learning methods. We used the dataset of credit card users from the UCI repository.

# Project Aims
- preprocessing in the credit card data.
- predicting default for the next month.
- evaluation of algorithms.

# Project Design
the dataet of credit card users that used for this project was downloaded from the UCI repository (https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients) included the data of 30,000 credit card users. It contained informations such as balance limit, basic demographic details, bill amounts of 6 months, payment details of 6 months, also default payment of next month. The project classified the dataset to feature and target  variables where the default in the next month is the target variable.  after this classification, we splited the data to train data and test data in 80:20 proportion.
After evaluation, I choosed the SVM (Support Vector Mechines) for classification, which was found to be highly suited comparing to other models such as Logistic Regression and Decision Tree.

# Dataset
- Dataset Name: Default of Credit Card Clients Dataset
- Source: UCI Machine Learning Repository
- Size: 30,000 observations × 25 columns
- Target Variable: default.payment.next.month (0 = No Default, 1 = Default)
- - Raw data : https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients
  (This data Contains demographic and financial information of 30,000 credit card clients).

# Data Preprocessing: 
steps followed in data preprocessing:
- checked and handled null/missing values
- changed the encoded variables for better clarity
- scaling was done
- splited data into feature and target variables 
- splited data into train data and test data
- https://drive.google.com/drive/folders/1ePDmggpyGbGsrNkEgT3MZ7YsNLoLPBFu
  
# Model Building: 
SVM model was choosed for this project as it provided better results comparing to logistic regression and random forest models.
- https://github.com/faristndm/DSML_Project/blob/597243e9ad76f8e0a1b141b840fc0cc81f530343/Final_Project_Faris.ipynb
- (built model that predicting credit card defaults of nect month).

# Tools used
- python (Jupyter notebook)
- pandas, numpy
- matplotlib
- seaborn
- scikit-learn 

# Results of SVM Test
- Accuracy: 82%
- Precision: 0.84
- Recall:
- Class 0 (Non-defaulters): 0.95
- Class 1 (Defaulters): 0.34
- F1-Score:
- Class 0: 0.89
- Class 1: 0.45
-  this model shows how mechine learning models can be used to analyse the possibility of committing defaults among credit card users which will help to reduce the risk to credit card service providers.

# Author:
- Name: Muhammad Faris T
- Email: faristndm@gmail.com
- LinkedIn: https://www.linkedin.com/in/faris-t-nadapuram-5a7500214
