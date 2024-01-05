## Overview
This study investigates the predictive analysis of bank customer churn to enhance retention strategies and mitigate revenue loss. The increasing significance of customer retention in the banking sector prompted an exploration into predictive modeling techniques to anticipate customer churn behavior. Leveraging historical customer data and employing advanced machine learning algorithms, this analysis focused on identifying crucial factors influencing churn and building accurate predictive models.
## Dataset Overview
The data required for the predictive analysis was obtained from Kaggle. Initially, the dataset comprised specific 
columns: customer_id, credit_score, country, gender, age, tenure, balance, products_number, credit_card, 
active_member, estimated_salary, and churn. These columns encapsulated crucial customer-related attributes and 
credit card information, forming the basis for our analysis and predictive modeling.The process commenced by 
establishing a connection to an SQLite database and designing tables to organize customer and credit card data. 
Relevant details were extracted from a CSV file, segregating customer-specific and credit card information. Separate 
tables for customers and credit cards were created to organize the data effectively. These tables were subsequently 
merged based on a shared customer ID, resulting in a consolidated dataset named customer_churn_data. This 
comprehensive dataset amalgamates customer profiles and their corresponding credit card information, providing 
a structured foundation for streamlined analysis or predictive modeling, especially in banking scenarios for churn 
prediction.
## Technologies and Libraries Used
1. Programming Language - Python <br>
2. pandas : For Data manipulation and analysis <br>
3. matplotlib : Plotting library for creating visualizations <br>
4. seaborn : Data visualization library based on matplotlib, for statistical graphics <br>
5. sqlite3 : Python interface for SQLite, a lightweight disk-based database <br>
6. csv : Module providing classes for reading and writing CSV files <br>
7. warnings : Provides functions to handle warnings <br>

## Exploratory Data Analysis
Thorough exploratory data analysis (EDA) was conducted to uncover missing values, outliers, and potential data inconsistencies. Additionally, correlation analysis was performed to ascertain the connections between variables and churn behavior.Univariate and bivariate analyses were employed to extract valuable insights aimed at customer retention strategies. 

## Model Development and Evaluation
• 5 Machine Learning models-Random Forest,KNN CLassifier,Logistic Regression, Lasso and Ridge were 
trained and evaluated.
• Random Forest achieved the highest accuracy (85.6%) in predicting churn, followed by KNN Classifier
(81.2%), Logistic Regression (80.77%), Ridge (80.77%) and Lasso (80.83%)
• Feature importance analysis highlighted age, account balance, number of products owned,credit score as influential factors in predicting churn.
