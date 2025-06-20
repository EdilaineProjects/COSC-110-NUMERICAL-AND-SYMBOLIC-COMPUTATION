# Laboratory 1: Computational Thinking with the Titanic Dataset

## Course: COSC 110 – Introduction to Computing  
## Lab Title: Computational Thinking with the Titanic Dataset using Python  
## Objective:
This lab aims to help students develop skills in **computational thinking** by working with a real-world dataset. Specifically, the lab focuses on:

- Applying the **four pillars of computational thinking**:  
  1. **Decomposition**  
  2. **Pattern Recognition**  
  3. **Abstraction**  
  4. **Algorithm Design**
- Analyzing the Titanic dataset to identify survival patterns.
- Building a simple **rule-based model** to predict passenger survival.

---

## Dataset:
We used the **Titanic dataset** from [Kaggle](https://www.kaggle.com/c/titanic/data).  
- File used: `titanic.csv` (originally `train.csv` from Kaggle)
- The dataset was placed in the working directory of the notebook.

---

## Laboratory Instructions Summary:

### 🧩 Step 1: Decomposition
- Loaded the dataset using `pandas`.
- Inspected the dataset structure using `.head()`.
- **Objective:** Break down the initial task of data loading and exploration.

💬 **Student Task:** Describe what tasks were involved in data loading (e.g., importing libraries, reading the file, displaying data).

---

### 🔍 Step 2: Pattern Recognition
#### 1. Identify Missing Data
- Used `.isnull().sum()` to check for missing values.
- Analyzed which columns had missing data and discussed if they should be dropped or filled.

#### 2. Explore Survival Rates
- Used `df["Survived"].mean()` to get the survival rate.
- Interpreted the result and discussed what it means in the context of the dataset.

#### 3. Analyze Survival by Age
- Used `matplotlib` to create histograms of survivor and non-survivor age distributions.
- Interpreted the visual differences to infer age-related survival patterns.

💬 **Student Task:** For each section above, write the corresponding algorithm or reasoning using computational thinking principles in your Colab notebook.

---

## Tools and Libraries Used:
- Python 3.x
- Pandas
- Matplotlib
- Jupyter Notebook / Google Colab

---

## Notes:
- All answers to 💡 questions are provided as text in the notebook, applying computational thinking approaches.
- This lab lays the groundwork for analyzing datasets and designing basic predictive models based on observed patterns.

---

## Author:
*Edilaine Dizon*  
*COSC 110 - Laboratory 1*  
