# Internship_Task_1
# Titanic Dataset Analysis 🛳️

This project is focused on performing **Exploratory Data Analysis (EDA)** on the Titanic dataset. The goal is to understand the structure, clean the data, and extract meaningful insights that could later support predictive modeling.

---

## 📁 Dataset

The dataset used is the **Titanic dataset**, which includes data on passengers such as:

- Passenger id
- Passenger class (Pclass)
- Survived
- Sex
- Name
- Sibsp
- Ticket
- Cabin
- Age
- Fare
- Embarked port
- Survival status

---

## 📌 Objectives

- Load and inspect the Titanic dataset
- Handle missing and duplicate values
- Perform basic statistical analysis
- Visalizing and removing outliers
- Prepare the data for further machine learning tasks

---

## 🛠️ Tools & Libraries Used

- Python
- Jupyter Notebook
- `pandas` for data manipulation
- `numpy` for numerical operations
- `matplotlib` and `seaborn` for Data Visualization
---

## 🔍 Workflow Summary

1. **Data Import**
   - Load the dataset using `pandas.read_csv()`

2. **Initial Data Exploration**
   - View dataset with `.head()`
   - Understand structure with `.info()` and `.describe()`

3. **Data Cleaning**
   - Check and handle missing values using `.isnull().sum()`
   - Identify and address duplicate records with `.duplicated().sum()`

4. **Data Analysis**
   - Converted categorical features into numerical using Labelencoding.
   - Standardize the numerical features
5. **Data  Visualization**
   - Visualize outliers usng box plot and removed them using IQR

---
