# **CUSTOMER SEGMENTATION: PROJECT OVERVIEW**
- Performed analysis of customers of a UK business to understand customer behaviour and provide accurate target marketing.
- Used data from 541909 customers and performed analysis with python.
- Created customer clusters based on customer spending habits and how much they spend.
- Optimized Naive Bayes, Logistic regression, Support Vector Classifier and XGBoost to reach the best model.


# **CODE AND RESOURCES USED**
- **Python Version 3.7**
- **Packages**: pandas, numpy, sklearn, matplotlib, seaborn


# **DATA CLEANING**
I made the following changes and created the following variables:

- Removed variable CustomerID with null values
- Made a new column for total amount spent by a customer
- Vectorized description column to prepare text for analysis

# **CLUSTER FORMATION**
Three clusters formed
![alt text](https://github.com/BenOsei-Poku/Ecommerce/blob/master/Ecommerce.png)

# **Model Building**
In order to choose a model, I categorised the customers based on their purchase frequency using percentiles to form classes.
I tried 4 different models:
- Naive Bayes
- Logistic regression
- Support Vector Classifier
- XGBoost


# **Model Performance**
The XGboost model slightly outperformed the logistic regression model with Naive Bayes and Support Vector Classifier having the least performance.
