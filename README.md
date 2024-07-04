# Customer_Churn_with_Machine_Learning

![churn](https://github.com/gokhankrbg/Customer_Churn_with_Machine_Learning/assets/143443115/b7d32376-2e47-496e-a423-cd756f7f6ea2)

<span style="font-size:20px; color:green">Problem Statement</span>
​
The objective is to develop a machine learning model that can predict which customers are likely to churn (leave the company). Before building the model, it is essential to perform necessary data analysis and feature engineering steps.
​
<span style="font-size:20px; color:green">Dataset</span>
​
The Telco customer churn dataset contains information about a fictional telecommunication company providing home phone and internet services to 7043 customers in California during the third quarter. It includes details on which customers have left, stayed, or signed up for the service.
​
<span style="font-size:20px; color:green">Dataset Features</span>
​
The dataset comprises 21 variables and 7043 observations:
​
- **CustomerID**: Customer ID
- **Gender**: Gender
- **SeniorCitizen**: Whether the customer is a senior citizen (1, 0)
- **Partner**: Whether the customer has a partner (Yes, No) - marital status
- **Dependents**: Whether the customer has dependents (Yes, No) (children, parents, grandparents)
- **Tenure**: Number of months the customer has stayed with the company
- **PhoneService**: Whether the customer has phone service (Yes, No)
- **MultipleLines**: Whether the customer has multiple lines (Yes, No, No phone service)
- **InternetService**: Customer’s internet service provider (DSL, Fiber optic, No)
- **OnlineSecurity**: Whether the customer has online security (Yes, No, No internet service)
- **OnlineBackup**: Whether the customer has online backup (Yes, No, No internet service)
- **DeviceProtection**: Whether the customer has device protection (Yes, No, No internet service)
- **TechSupport**: Whether the customer has tech support (Yes, No, No internet service)
- **StreamingTV**: Whether the customer has streaming TV (Yes, No, No internet service)
- **StreamingMovies**: Whether the customer has streaming movies (Yes, No, No internet service)
- **Contract**: The contract term of the customer (Month-to-month, One year, Two years)
- **PaperlessBilling**: Whether the customer has paperless billing (Yes, No)
- **PaymentMethod**: The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
- **MonthlyCharges**: The amount charged to the customer monthly
- **TotalCharges**: The total amount charged to the customer
- **Churn**: Whether the customer churned (Yes or No) - customers who left in the past month or quarter
​
Each row represents a unique customer. The variables contain information about customer service, account, and demographic data.
​
<span style="font-size:20px; color:green">Project Outline</span>
​
Our work consists of three main sections: Exploratory Data Analysis (EDA), Feature Engineering, and Modeling. In the EDA section, we will explore the overall picture, capturing numerical and categorical variables. After analyzing numerical and categorical variables, we will perform target variable analysis. (In the target variable analysis, we will analyze the average of the target variable according to categorical variables and the average of numerical variables according to the target variable.) We will analyze outlier and missing values. Then, we will conduct a correlation analysis. In the feature engineering section, we will fill in missing observations based on missing value analyses and derive new features. We will then perform encoding operations and standardize numerical variables, completing all pre-modeling operations. In the modeling stage, we will apply logistic regression and KNN. Models will be evaluated based on success metrics, and hyperparameter optimization will be applied, building the model with the best parameters.
​
