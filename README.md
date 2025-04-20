🚗 Exploratory Data Analysis (EDA) on Vehicle Insurance Dataset
This project performs an in-depth exploratory data analysis on a large vehicle insurance dataset to uncover patterns and insights that can assist in understanding insurance claim behavior.

📁 Dataset Overview
Source: [Vehicle_Insurance.csv]

Records: 381,109 entries

![](https://github.com/Shria-Bhardwaj/VEHICLE-INSURANCE/blob/main/1.png)

Features: 12 attributes including demographics, policy details, vehicle condition, and claim response

📌 Project Objectives
Understand customer demographics and behavior

Identify key factors affecting insurance claim responses

Clean and preprocess data for further modeling

Visualize trends and relationships among variables

🧰 Tools & Technologies
Python (Pandas, NumPy, Seaborn, Matplotlib)

Jupyter Notebook

EDA techniques for feature understanding and data cleaning

🧪 Key Steps
🔍 1. Data Loading & Inspection
Read and examine dataset structure, types, and basic statistics.

🧹 2. Data Cleaning
Verified absence of missing values.

![](https://github.com/Shria-Bhardwaj/VEHICLE-INSURANCE/blob/main/2.png)


Outliers in Annual_Premium and Driving_License removed using IQR.

![](https://github.com/Shria-Bhardwaj/VEHICLE-INSURANCE/blob/main/3.png)

![](https://github.com/Shria-Bhardwaj/VEHICLE-INSURANCE/blob/main/4.png)


📊 3. Data Visualization
Distribution plots of gender, age, premiums, and policy sales channels

![](https://github.com/Shria-Bhardwaj/VEHICLE-INSURANCE/blob/main/5.png)

Count and box plots for analyzing relationships between features and the target variable Response.

📈 4. Feature-wise Analysis
Gender vs Response: Males showed higher claim interest.

Vehicle Damage: Strongly correlated with claim response.
![](https://github.com/Shria-Bhardwaj/VEHICLE-INSURANCE/blob/main/6.png)

Age & Premium Analysis: Older users and higher premiums showed distinct patterns.

Policy Sales Channel & Region: Insights into effectiveness and regional trends.
![](https://github.com/Shria-Bhardwaj/VEHICLE-INSURANCE/blob/main/7.png)

Previously Insured: Previously uninsured customers are more likely to respond positively.

📉 Insights
People with vehicle damage history are more likely to opt for insurance.

Younger age groups and lower premiums show less interest in buying insurance.

Certain policy sales channels perform significantly better.

Region Code shows strong variance in response behavior.
