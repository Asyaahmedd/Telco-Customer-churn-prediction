# Telecom Customers Churn Prediction

Developing an End to End model to predict customers who are more prone to churn. Predicting customer churn is critical for telecommunication companies to be able to effectively retain customers. It is more costly to acquire new customers than to retain existing ones. For this reason, large telecommunications corporations are seeking to develop models to predict which customers are more likely to change and take actions accordingly. In this project, I will build a model to predict how likely a customer will churn by analyzing its characteristics: (1) demographic information, (2) account information, and (3) services information. 

# Project Objective

The objective is to obtain a data-driven solution that will allow us to reduce churn rates and, as a consequence, to increase customer satisfaction and corporation revenue.

# Data set
The data set used in this project is available in the Kaggle (CC BY-NC-ND) and contains nineteen columns (independent variables) that indicate the characteristics of the clients of a fictional telecommunications corporation. The Churn column (response variable) indicates whether the customer departed within the last month or not. The class No includes the clients that did not leave the company last month, while the class Yes contains the clients that decided to terminate their relations with the company. 
the data set contains 19 independent variables, which can be classified into 3 groups:

(1) Demographic Information

• gender: Whether the client is a female or a male (Female, Male).

• SeniorCitizen: Whether the client is a senior citizen or not ( 0, 1).

• Partner: Whether the client has a partner or not (Yes, No).

• Dependents: Whether the client has dependents or not (Yes, No).

(2) Customer Account Information

• tenure: Number of months the customer has stayed with the company (Multiple different numeric values).

• Contract: Indicates the customer’s current contract type (Month-to-Month, One year, Two year).

• PaperlessBilling: Whether the client has paperless billing or not (Yes, No).

• PaymentMethod: The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), 
  Credit Card (automatic)).

• MontlyCharges: The amount charged to the customer monthly (Multiple different numeric values).

• TotalCharges: The total amount charged to the customer (Multiple different numeric values).

(3) Services Information

• PhoneService: Whether the client has a phone service or not (Yes, No).

• MultipleLines: Whether the client has multiple lines or not (No phone service, No, Yes).

• InternetServices: Whether the client is subscribed to Internet service with the company (DSL, Fiber optic, No)

• OnlineSecurity: Whether the client has online security or not (No internet service, No, Yes).

• OnlineBackup: Whether the client has online backup or not (No internet service, No, Yes).

• DeviceProtection: Whether the client has device protection or not (No internet service, No, Yes).

• TechSupport: Whether the client has tech support or not (No internet service, No, Yes).

• StreamingTV: Whether the client has streaming TV or not (No internet service, No, Yes).

• StreamingMovies: Whether the client has streaming movies or not (No internet service, No, Yes).

# Project Tasks:

✔ Understand the problem statement and business case

✔ Import libraries/datasets and perform Exploratory Data Analysis

✔ Perform Data Visualization

✔ Prepare the data before model training

✔ Train and Evaluate a Logistic Regression model

✔ Train and Evaluate a Support Vector Machine Model

✔ Train and Evaluate a Random Forest Classifier model

✔ Train and Evaluate a K-Nearest Neighbor model

✔ Train and Evaluate a Naive Bayes Classifier model

✔ Train and Evaluate a GradientBoostingClassifier

✔ Compare the trained models by calculating AUC score and plot ROC curve


