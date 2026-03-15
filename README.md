# ConnectaTel-Analysis
Data-driven user segmentation and behavior analysis for ConnectaTel: Optimizing telecommunications service plans.

📞 Customer Behavior Analysis: ConnectaTel
🎯 Project Objective

The main objective of this project is to conduct an exploratory and statistical analysis of ConnectaTel customers, a telecommunications company. By processing usage data (calls and messages) and demographic profiles, the project aims to identify consumption patterns, detect outliers, and propose segmentation strategies to enhance the company's commercial offerings.

📊 Datasets Used
The analysis is based on three main data sources:

    plans.csv: Details of the plans (Basic and Premium), including pricing and limits.

    users.csv: Demographic information (age, city, registration date).

    usage.csv: Detailed logs of actual service consumption (messages and calls).

🛠️ Analysis Stages

    Data Cleaning: Handling missing values (imputation with 0) and variable standardization.

    Exploratory Data Analysis (EDA): Visualization of age distributions and consumption by plan.

    Outlier Detection: Implementation of the IQR (Interquartile Range) method to identify "Heavy Users."

    Segmentation: Classification of customers by Usage Level (Low, Medium, High) and Age Group (Youth, Adult, Senior).

    Executive Insights: Formulation of strategic business recommendations based on findings.

🚀 How to Run the Project

    Clone this repository or download the files.

    Upload the .ipynb file to Google Colab.

    Ensure the .csv files are uploaded to the Colab environment so the code can read them.

    Execute the cells sequentially.

🧬 Reproducibility Guide

To replicate the results:

    Use Python 3

    Required Libraries: pandas, matplotlib, seaborn.

    Segmentation thresholds used:

        Low Use: < 5 calls AND < 5 messages.

        Medium Use: < 10 calls AND < 10 messages.

        High Use: Remaining cases (at least one metric ≥ 10).

        
