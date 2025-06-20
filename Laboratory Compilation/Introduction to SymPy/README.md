
# Laboratory 2: Basic Data Cleaning and Visualization of the Titanic Dataset

## Course: COSC 110 – Introduction to Computing  
## Lab Title: Basic Data Cleaning and Visualization of Titanic Dataset  

## Objective:
This laboratory exercise aims to introduce students to essential data cleaning and basic visualization techniques using Python and Pandas. By the end of this lab, students will:

- Understand and apply standard data cleaning processes.
- Handle missing data, duplicates, and incorrect data types.
- Prepare a dataset for analysis through proper formatting and cleaning.
- Conduct basic exploratory data analysis through visualizations.

---

## Dataset:
We used the **Titanic dataset** from [Kaggle](https://www.kaggle.com/c/titanic/data), specifically the file named `train.csv`. This file was loaded into a DataFrame and served as the main working dataset throughout the lab.

---

## Laboratory Instructions Summary:

### 🧼 Step 1: Load the Data
The dataset is first loaded into the workspace using Pandas. This allows for easy manipulation and analysis of the data.

### 🧠 Step 2: Understand the Data
Explore the dataset's structure using functions that describe the types of data in each column, provide statistical summaries, and reveal the dataset's overall shape and features. Identifying data types and unusual formats is part of this step.

### 🔎 Step 3: Check for Missing Values
Identify which columns contain missing values and how many are present. This step is essential to determine how the missing data should be handled in the next phase.

### 🛠 Step 4: Handle Missing Values
Missing values are addressed using different strategies:
- **Filling in missing values** (e.g., using the median for numerical data).
- **Dropping columns** with excessive missing data that can't be reliably imputed.

### 🧹 Step 5: Remove Duplicates
This step ensures that no redundant or repeated data exists in the dataset. Duplicate rows are identified and removed to maintain data integrity.

### 🏷 Step 6: Fix Data Types
Columns representing categories (such as survival status or class) are converted to categorical data types to improve data management and reduce memory usage.

---

## Basic Data Visualizations

As part of **Exploratory Data Analysis (EDA)**, students are required to visualize patterns and trends from the cleaned dataset to gain deeper insights.

### 📊 Visualization Tasks:

1. **Bar Plot of Survival Count**  
   A bar chart is used to show how many passengers survived versus those who didn’t.

2. **Histogram of Age Distribution**  
   A histogram shows the distribution of passengers' ages, helping us understand age trends in the dataset.

3. **Survival Rate by Gender**  
   A grouped bar chart reveals survival differences between male and female passengers, showcasing one of the key insights from the Titanic data.

---

## Summary:
This lab introduces foundational techniques in cleaning and preparing real-world data. By completing it, students gain hands-on experience with the practical challenges of missing values, duplicates, and inconsistent formatting. The visualizations help develop early insights that support further computational thinking and data modeling.

---

## Author:
*Edilaine Dizon*  
*COSC 110 - Laboratory 3*
