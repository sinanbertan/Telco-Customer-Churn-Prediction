
# Indians-Diabetes-Classification-EDA
- This project focuses on prediction if Telco customers churn or not. The project includes machine learning, exploratory data analysis (EDA), and data visualization techniques to gain insights into the dataset and understand its patterns. The project uses the Telco-Customer-Churn.csv dataset, which can be downloaded from Kaggle:https://www.kaggle.com/datasets/blastchar/telco-customer-churn


# ACKNOWLEDGEMENTS

## DATA CONTENT
### Analysis of data columns to identify independent and dependent variables:

* X is the independent variables - the variables we are using to make predictions

* customerID - unique value identifying customer
* gender - whether the customer is a male or a female
* SeniorCitizen - whether the customer is a senior citizen or not (1, 0)
* Partner - whether the customer has a partner or not (Yes, No)
* Dependents - whether the customer has dependents or not (Yes, No). A dependent is a person who relies on another as a primary source of income,
* tenure - number of months the customer has stayed with the company
* PhoneService - whether the customer has a phone service or not (Yes, No)
* MultipleLines - whether the customer has multiple lines or not (Yes, No, No phone service)
* InternetService - customer’s internet service provider (DSL, Fiber optic, No)
* OnlineSecurity - whether the customer has online security or not (Yes, No, No internet service)
* OnlineBackup - whether the customer has online backup or not (Yes, No, No internet service)
* DeviceProtection - whether the customer has device protection or not (Yes, No, No internet service)
* TechSupport - whether the customer has tech support or not (Yes, No, No internet service)
* StreamingTV - whether the customer has streaming TV or not (Yes, No, No internet service)
* StreamingMovies - whether the customer has streaming movies or not (Yes, No, No internet service)
* Contract - type of contract according to duration (Month-to-month, One year, Two year)
* PaperlessBilling - bills issued in paperless form (Yes, No)
* PaymentMethod - payment method used by customer (Electronic check, Mailed check, Credit card (automatic), Bank transfer (automatic))
* MonthlyCharges - amount of charge for service on monthly bases
* TotalCharges - cumulative charges for service during subscription (tenure) period
* y is dependent variable - variable we are trying to predict or estimate
## Installation
The following tools were used for this analysis:

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scipy
- Sklearn

- To run this project, you will need to have Python 3 installed on your machine. You can install the required libraries by running the following command:


- pip install pandas matplotlib seaborn numpy plotly Sklearn 
## Usage 
- To run the analysis, simply execute the notebook. The script will generate several visualizations that help illustrate analysis of data.
## Roadmap

1. IMPORTING LIBRARIES

2. LOADING DATASET

3. DATA DESCRIPTION

4. EXPLORATORY DATA ANALYSIS

5. FEATURE ENGINEERING

6. MISSING VALUES

7. DATA VISUALIZATION

8. OUTLIER DETECTION

9. DATA PREPROCESSING

10. MODEL TRAINING AND EVALUATING

11. FEATURE IMPORTANCE

12. AUC-ROC

13. MODEL TUNING

14. CONCLUSION


 The analysis includes visualizations using Matplotlib, Plotly and Seaborn.

## Contributing

- Contributions to this project are welcome. If you notice any errors or have ideas for additional analyses, please feel free to open an issue or submit a pull request.


## Conclusion 

* Conclusion: Understanding and Predicting Customer Churn in Telco Services

* In this project, we embarked on a journey to understand and predict customer churn in the telecommunications industry using advanced machine learning techniques. Our primary objective was to build a robust classification model that could accurately predict whether a customer is likely to churn or not, based on a variety of features derived from the telco customer churn dataset.

* Through meticulous data preprocessing, feature engineering, and model training, we successfully constructed a logistic regression classification model that achieved an impressive accuracy score of 0.809. This score indicates that our model is adept at distinguishing between loyal customers and those at risk of churning.

