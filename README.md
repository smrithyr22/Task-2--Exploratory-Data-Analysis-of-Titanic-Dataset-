# Task-2--Exploratory-Data-Analysis-of-Titanic-Dataset

## 📊 Titanic Dataset - Data Cleaning and Exploratory Data Analysis (EDA)

This repository contains Task 02 of the SkillCraft Technology Data Analysis Series. The goal of this project is to perform data cleaning and exploratory data analysis (EDA) on the popular Titanic dataset from Kaggle.

## ✅ Objectives:

1. Handle missing values and perform    data cleaning

2. Explore and visualize the dataset using statistical summaries and plots

3. Identify patterns and trends in the data

4. Analyze relationships between variables such as survival, age, gender, class, fare, etc.

## 🔍 Key Features:

✅ Missing value treatment and data type correction

✅ Conversion of target variable (Survived) from 0/1 to No/Yes

✅ Visual exploration using seaborn and matplotlib

✅ Survival analysis by sex, class, age, and fare

✅ Correlation heatmap of numerical variables
   
 ## 📂 Dataset

The dataset used is the [Titanic dataset](https://www.kaggle.com/c/titanic/data), which includes information such as:
- Passenger demographics (Age, Sex, Class)
- Ticket and fare details
- Whether the passenger survived or not

## 🔧 Data Cleaning

Key steps in cleaning the dataset:
- Handling missing values in `Age` and `Embarked`
- Dropping the `Cabin` column due to too many missing entries
- Converting `Survived` values from `0`/`1` to `'No'`/`'Yes'`
- Changing data types for categorical variables

---

## 📊 Visualizations Included:
- 🔹 Correlation Heatmap
- 🔹 Survival Rate by Sex
- 🔹 Survival Rate by Passenger Class
- 🔹 Age Distribution by Survival
- 🔹 Fare Distribution by Survival

These help identify patterns and relationships within the data that impact survival chances.

---

## 🛠️ Technologies Used

- **Python**  
- **Pandas** – for data manipulation  
- **Seaborn** & **Matplotlib** – for visualization  
- **Jupyter Notebook** – for interactive analysis
