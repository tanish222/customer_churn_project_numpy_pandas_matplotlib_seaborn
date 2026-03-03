##### **Project Overview**

Customer churn is a critical metric for service-based companies. This project explores a dataset containing 21 different attributes of customers to understand why they leave. The analysis includes handling missing data, converting data types for machine learning readiness, and visualizing churn distribution across different categories.



###### 📊 **Dataset Description**

The analysis is performed on a dataset with 7,043 entries and 21 columns. Key attributes include:



Demographics: Gender, Senior Citizen status, Partner, and Dependents.



Services: Phone service, Multiple lines, Internet service, Online security, Tech support, and Streaming services.



Account Info: Tenure, Contract type, Paperless billing, Payment method, Monthly charges, and Total charges.



Target: Churn (Yes/No).



###### 🚀 **Key Features**

Data Cleaning: Automated handling of empty strings in TotalCharges and conversion to numeric types.



Feature Engineering: Mapping categorical integers (like SeniorCitizen) to readable string formats for better visualization.



Visualization: Detailed count plots and distribution charts using Seaborn and Matplotlib to identify patterns in churn.



Data Processing Pipeline

Initial Profiling: Checking for null values and duplicate entries (found 0 duplicates and 0 nulls across standard columns).



Type Conversion: Converting TotalCharges from object to float, specifically handling whitespace anomalies by replacing them with '0'.



Data Transformation: Applying custom conversion functions to improve data interpretability.



📈 Exploratory Data Analysis

The notebook includes a dedicated section for Churn Count visualization, providing a baseline understanding of the class imbalance between churned and retained customers.



###### **💻 Technologies Used**

Python 3



Pandas: For data manipulation and analysis.



NumPy: For numerical operations.



Matplotlib \& Seaborn: For high-level data visualization and aesthetic plotting.

