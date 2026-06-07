COVID-19 DATA ANALYSIS & DASHBOARD SYSTEM (KAGGLE DATASET)

Project Overview

The COVID-19 pandemic generated massive amounts of data across the world, including confirmed cases, deaths, recoveries, and active cases. Analyzing such data is essential to understand trends, identify patterns, and support decision-making.

However, accessing real-world datasets can sometimes be challenging due to availability, size, or dependency issues. To address this, this project introduces a COVID-19 Data Analysis System using Synthetic Data.

In this project, a dataset is generated using the Python Faker library to simulate realistic COVID-19 statistics. The generated data is then used to perform Exploratory Data Analysis (EDA) and visualization to understand trends and relationships.

Objective

The main objective of this project is to analyze COVID-19 trends using a self-generated dataset and derive meaningful insights. The key goals include:

  Generate a realistic synthetic dataset using Faker
    Simulate COVID-19 case patterns across countries
    Perform data cleaning and preprocessing
    Analyze trends over time
    Compare country-wise data
    Identify relationships between variables
    Visualize data using charts and graphs
    Extract insights from the analysis

Technologies Used

  Python
    Pandas
    NumPy
    Matplotlib
    Seaborn
    Plotly

Project Workflow

1. Data Generation

    Dataset is created using the Faker library
    Random values simulate real-world COVID patterns
    Multiple countries and dates are included

2. Data Cleaning & Preprocessing

    Converted date column to proper datetime format
    Removed duplicate records
    Handled missing values
    Ensured numerical consistency

3. Exploratory Data Analysis (EDA)

    Calculated total confirmed, deaths, and recoveries
    Analyzed data distribution
    Studied trends over time

4. Trend Analysis

    Observed growth of confirmed cases over time
    Identified peak periods
    Compared daily changes

5. Country-Based Analysis

    Identified most affected countries
    Compared confirmed, deaths, and recoveries
    Analyzed country-wise distribution

6. Relationship Analysis

    Confirmed vs Deaths
    Confirmed vs Recovered
    Active vs Confirmed
    Correlation between variables

7. Data Visualization

    Line chart → Trend over time
    Bar chart → Country comparison
    Pie chart → Case distribution
    Scatter plot → Relationships
    Heatmap → Correlation analysis
    Interactive charts using Plotly

Key Insights

  COVID-19 cases show fluctuating trends over time
    Some countries consistently report higher cases
    Strong relationship exists between confirmed and deaths
    Recovery rates vary across countries
    Active cases depend heavily on recovery trends

Future Improvements

  Build interactive dashboard using Plotly Dash
    Integrate real-time COVID dataset
    Apply machine learning models for prediction
    Deploy as a web application

Output Overview:
<img width="753" height="681" alt="image" src="https://github.com/user-attachments/assets/851ff2e2-40c5-4c3b-97e4-9acbdf9fafb4" />
<img width="726" height="532" alt="image" src="https://github.com/user-attachments/assets/54faa9ae-19e8-4dba-9b58-243b0ab983b9" />
<img width="710" height="606" alt="image" src="https://github.com/user-attachments/assets/78a54b96-4368-46ae-aef1-7d8629a5451c" />
<img width="758" height="563" alt="image" src="https://github.com/user-attachments/assets/e553faff-ab99-4b18-8a7e-73a008df1883" />

Conclusion

This project demonstrates how synthetic data can be effectively used for analysis when real-world datasets are unavailable. It helps in understanding data trends, visualization techniques, and real-world project workflows.

Acknowledgement

This project is created for educational purposes to learn data analysis and visualization techniques.
