# Task-02: Exploratory Data Analysis (EDA)

## Overview
This repository contains the solution for Task-02, which focuses on performing data cleaning and exploratory data analysis (EDA) on the Titanic dataset. The goal of this task is to understand the dataset, explore relationships between variables, and identify meaningful patterns and trends using visualizations.

## Dataset
- **Dataset Name:** Titanic Dataset  
- **File Used:** `train.csv`  
- **Source:** Prodigy Infotech / Kaggle  
- **Description:**  
  The dataset contains information about passengers such as age, gender, class, fare, and survival status.

## Objective
- Clean the dataset and handle missing values  
- Perform exploratory data analysis (EDA)  
- Visualize relationships between variables  
- Identify patterns and trends in the data
- 
## Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook
- 
## Workflow

### 1. Data Loading
- Imported required libraries  
- Loaded the dataset using Pandas  
- Reviewed initial rows and structure  

### 2. Data Cleaning
- Handled missing values in `Age` and `Embarked`  
- Dropped the `Cabin` column due to excessive missing data  
- Removed duplicate records  
- Corrected data types where necessary  

### 3. Exploratory Data Analysis
- **Univariate Analysis:**  
  Survival count, gender distribution, age distribution, passenger class  
- **Bivariate Analysis:**  
  Survival vs gender, passenger class, age, embarked port  
- **Multivariate Analysis:**  
  Correlation heatmap and combined survival analysis  

## Key Insights
- Female passengers had a higher survival rate than males  
- First-class passengers were more likely to survive  
- Younger passengers had better survival chances  
- Fare showed a positive correlation with survival  

##  Conclusion
In this task, data cleaning and exploratory data analysis were performed on the Titanic dataset.
Missing values were handled appropriately, and unnecessary columns were removed.
Exploratory analysis revealed strong relationships between survival and variables such as gender, passenger class, and age.
Female and first-class passengers showed higher survival rates. 
These insights help understand underlying patterns and can be useful for predictive modeling.
