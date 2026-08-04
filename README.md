# Emails-Data
A simple Python project for exploring and analyzing email data using Pandas, including data loading, cleaning, and basic feature inspection.
# 📧 Email Data Analysis using Pandas

## 📌 Project Overview

This project focuses on **basic data analysis and exploration** of an email dataset using **Python and Pandas**. The goal is to understand the dataset structure, inspect columns, and perform initial data cleaning and transformations.

---

## 📂 Dataset

* File used: `emails.csv`
* The dataset contains email-related information including categorical columns such as **connevey** and numerical/other attributes.

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas

---

## 🔄 Steps Performed

### 1. Load the Dataset

```python
import pandas as pd

df = pd.read_csv('emails.csv')
```

---

### 2. Data Exploration

* Accessed specific column:

```python
df['connevey']
df.connevey
```

* Checked unique values:

```python
df['connevey'].unique()
```

* Explored available functions:

```python
dir(df['connevey'])
```

---

### 3. Data Validation

* Checked for non-null values:

```python
df.notnull()
```

---

### 4. Sorting Data

* Sorted dataset based on a column:

```python
df.sort_values(['valued'], ascending=False)
```

---

### 5. Renaming Columns

```python
df.rename(columns={"Jay": "Varun", "dry": "DA"})
```

---

### 6. Value Counts

* Counted frequency of values:

```python
df['connevey'].value_counts()
```

---

## 📊 Key Insights

* Identified unique categories in the dataset
* Checked data quality (null values)
* Understood distribution of categorical data
* Performed basic transformations like sorting and renaming

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/email-data-analysis.git
```

2. Install dependencies:

```bash
pip install pandas
```

3. Run the script or Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📌 Future Improvements

* Perform detailed data cleaning
* Handle missing values properly
* Apply machine learning models for classification
* Visualize data using Matplotlib/Seaborn

---

## 👤 Author

**Varun Shah**

---

⭐ If you found this helpful, please give it a star!
