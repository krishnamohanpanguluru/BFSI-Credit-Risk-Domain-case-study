# BFSI-Credit-Risk-Domain-case-study

Problem Statement:

In this assignment, you would face real world data of applications and bureau as shared by Home Credit, to perform the end-to-end process of model development in Credit Risk for Banks, Financial Institutions and NBFCs.

Build a bank’s internal end-to-end scoring mechanism, based on the application information, clubbed with the raw bureau information.

The primary objective of this study is to assist Home Credit in deciding which loan applications should be disbursed, and which should be rejected, based on the applicant’s past behaviour and application information.

Goal:

As a business analyst for Home Credit, you are supposed to first gather the information and clean it to make it usable.

The bureau information is at trade level, each individual trade level information is provided. You need to apply ‘Feature Engineering’ techniques to roll up the information at applicant level, and thereby create manual features for model building.

Build a classification model to differentiate applicants between approves and rejects.

As a business analyst, we have found answers to the below questions for the bank:

How to leverage trade level information for Credit Bureaus by aggregating trade level information to applicant level in order to capture their payment behaviour? Which application or payment behaviour factors significantly influence borrower’s behaviour on any new disbursed loan? After identifying these factors, how to leverage them in the form of a model which can be used for decisioning? Once the model is built, how to translate the model output into strategies and business insights for the bank?



We have performed the following steps in order to analyse and build the end to end process of model development & Evaluation with proper insights and recommendations

Step1 : Data Cleaning , Handle Missing Values & Handle Outliers

Step2 : Exploratory Data Analysis (EDA)

Step3 : Feature Engineering

Step4 : EDA After Merging (New Addition) 

Step5 : Model Development - (Updated with Hyperparameter Tuning)

Step6 : Model Evaluation

Step7 : Business Insights and Recommendations



-  All important data quality checks are performed and inconsistent/missing data is handled appropriately.
-  Relevant exploratory data analysis (EDA) is conducted using plots and summaries. Insights are driven from EDA.
-  Feature engineering is performed an approximate set of features is used to build the model
-  Application and Bureau data sets are merged after taking appropriate analysis on both datasets.
-  Class Imbalance is handled using the SMOTE -Synthetic Minority Oversampling Technique
-  Performed Model Development using multiple classification models on train data
        -  Model 1: Logistic Regression with GridSearchCV
        -  Model 2: Random Forest with GridSearchCV
        -  Model 3: LightGBM with GridSearchCV
-   The model output provides a probability score for the target variables for all tha above mentioned three models.
-  A reasonable number and a variety of different models are tried and best model os choosen based on Key performance metric. 
-  Model evaluation is conducted using an appropriate metric by omputing ROC-AUC on the test data.
-  The model evaluation results are at par with the best possible methods  (out of Logistic Regression, Random Forest, LightGBM): LightGBM (ROC-AUC: 0.7575) 

Business Insights and Recommendations : 
-  Important indicators to the target variable are identified
-  Actionable insights and recommndations are provided for Board.
-  By integrating these insights, we can enhance risk management, optimize credit policies, and improve profitability.


