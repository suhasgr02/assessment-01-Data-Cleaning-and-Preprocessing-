# 🧹 Data Cleaning and Preprocessing with Python (Pandas)

This project demonstrates a basic data cleaning and preprocessing pipeline using **Python** and **Pandas**. It handles missing values, removes duplicates, standardizes text and date formats, and ensures clean column naming—essential steps in any data analytics or machine learning workflow.

---

## 📁 Dataset

- The dataset used ('/content/marketing_campaign.csv') should be a raw CSV file containing real-world inconsistencies such as:
  - Missing values
  - Duplicate rows
  - Inconsistent formatting
  - Mixed case column names
  - Incorrect data types

---

## 🛠 Tools & Technologies
- Python 3.x
- Pandas
- Jupyter Notebook / Python Script

---

## ✅ Features

The script performs the following operations:

1. **Missing Values**
   - Fills missing values in numerical columns like `age` using the mean.
   - Drops rows with missing values in critical columns like `gender`.

2. **Remove Duplicates**
   - Removes all duplicate records from the dataset.

3. **Text Standardization**
   - Standardizes text entries in columns like `gender` (e.g., `m`, `Male`, `female` → `Male`, `Female`).

4. **Date Formatting**
   - Converts date columns into consistent `dd-mm-yyyy` format.

5. **Column Renaming**
   - Renames all columns to lowercase and replaces spaces with underscores for easier manipulation.

6. **Data Type Correction**
   - Converts fields like `age` to integer types.


