# Task 5: Python Basics – Reading Data & Cleaning with Pandas

## 📌 Task Overview
This task focuses on using Python and the Pandas library to read, clean, and transform a real-world dataset. The objective is to understand how Python can efficiently replace manual Excel-based data cleaning for large datasets.

---

## 📊 Dataset Used
- Dataset Name: Titanic Dataset
- Source: Kaggle
- Format: CSV

---

## 🛠 Tools & Libraries
- Google Colab
- Python
- Pandas
- NumPy

---

## 🔧 Steps Performed

1. **Data Loading**
   - Loaded the dataset using `pd.read_csv()`
   - Viewed sample records using `head()` and dataset structure using `info()`

2. **Missing Value Analysis**
   - Identified missing values using `isnull().sum()`
   - Analyzed columns requiring cleaning

3. **Missing Value Handling**
   - Filled missing numerical values (Age) using median
   - Filled missing categorical values (Embarked) using mode
   - Dropped columns with excessive missing values (Cabin)

4. **Duplicate Removal**
   - Detected and removed duplicate rows using `drop_duplicates()`
   - Verified row counts before and after removal

5. **Data Type Conversion**
   - Converted columns to appropriate data types using `astype()`

6. **Feature Engineering**
   - Created a new column `Age_Group` to categorize passengers based on age

7. **Export Cleaned Data**
   - Saved the cleaned dataset as `cleaned_data.csv`

8. **Documentation**
   - Added markdown notes in the notebook explaining each cleaning step

---

## 📁 Files Included
- `Task5_Cleaning.ipynb` – Notebook containing code and markdown explanations
- `cleaned_data.csv` – Final cleaned dataset
- `README.md` – Task documentation

---

## ✅ Final Outcome
- Gained hands-on experience with Pandas for data cleaning
- Learned how to handle missing values and duplicates programmatically
- Understood the importance of data preprocessing in analytics workflows

---

## 🗣 Interview Explanation (Short)
“I cleaned a real-world dataset using Pandas by handling missing values, removing duplicates, creating new features, and exporting a clean dataset for analysis.”
