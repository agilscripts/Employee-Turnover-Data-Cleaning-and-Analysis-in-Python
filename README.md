# Employee-Turnover-Data-Cleaning-and-Analysis-in-Python
A Python-based project for cleaning and analyzing employee turnover data. This repository includes code to handle missing values, outliers, and duplicate entries, along with a discussion on the data cleaning techniques used.


---


```markdown
# Employee Turnover Data Cleaning and Analysis

## Description
This repository contains the Python code and corresponding files for data profiling, cleaning, and analysis of an employee turnover dataset. The project focuses on handling various data quality issues, such as missing values, duplicate entries, inconsistent data, and outliers.

The dataset includes multiple employee-related features such as age, salary, job role, and tenure, which are analyzed to help understand factors influencing employee turnover.

---

## Features
- **Data Profiling:** Review the dataset structure, including data types, columns, and sample values.
- **Data Cleaning:** Remove duplicate entries, handle missing values using median/mode replacements, and treat outliers using the Interquartile Range (IQR) method.
- **Code Demonstration:** A clear step-by-step walkthrough of how to implement data cleaning techniques in Python.

---

## Installation and Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/employee-turnover-cleaning.git
   ```

2. Navigate to the project directory:
   ```bash
   cd employee-turnover-cleaning
   ```

3. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## How to Use
1. Ensure the employee turnover dataset is available in the specified path or update the file path in the code.
2. Run the Python script `data_cleaning.py` to clean the dataset and generate a cleaned CSV file.
3. The code can be run in Jupyter Notebook, Visual Studio Code, or any other IDE that supports Python.

---

## Data Cleaning Techniques:
1. **Duplicate Removal:** Using `.drop_duplicates()` to eliminate duplicate rows.
2. **Handling Missing Values:**
   - For numeric columns: Replaced with median values.
   - For categorical columns: Replaced with mode values.
3. **Outlier Treatment:** Applied capping (winsorizing) using the IQR method to treat extreme values.

---

## Programming Environment
This project is implemented in Python using the following libraries:
- **pandas** for data manipulation
- **NumPy** for numerical operations
- **matplotlib** (optional) for visualization
