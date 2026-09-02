# Week 1: Data Acquisition, Cleaning and Preprocessing

## 📌 Project Overview

This project was completed as part of my **Virtual Data Science with Python Internship at YuvaIntern**.

The objective of this task was to acquire a publicly available dataset and perform data cleaning and preprocessing using Python. The project focuses on identifying and handling data quality issues such as missing values, duplicate records, incorrect data types, blank entries, and potential outliers.

---

## 📊 Dataset

This project uses the **Telco Customer Churn Dataset**.

The dataset contains information about telecommunications customers, including:

- Customer demographics
- Internet and phone services
- Account information
- Contract details
- Payment methods
- Monthly charges
- Total charges
- Customer churn status

### Dataset Size

- **Rows:** 7,043
- **Columns:** 21

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib

---

## 🔍 Project Workflow

### 1. Data Acquisition

The publicly available Telco Customer Churn dataset was acquired and loaded into Python using Pandas.

### 2. Initial Data Exploration

The dataset was explored using:

- `df.head()`
- `df.shape`
- `df.info()`
- `df.describe()`

### 3. Missing Value Analysis

Missing values were checked using Pandas functions.

Although the initial check showed no standard missing values, further investigation identified blank values in the `TotalCharges` column.

### 4. Duplicate Record Analysis

Duplicate records were checked using:

```python
df.duplicated().sum()
````

No duplicate records were found in the dataset.

### 5. Data Cleaning

The `TotalCharges` column contained blank values and was stored as an object data type.

The column was converted to numeric format and the missing values were handled.

### 6. Outlier Detection

Numerical variables were analyzed using visualization techniques such as boxplots to identify potential outliers.

### 7. Data Preprocessing

Categorical variables were transformed into numerical features using encoding techniques.

The `customerID` column was removed because it is an identifier and does not provide useful information for machine learning models.

---

## 📈 Key Findings

* The dataset contains **7,043 customer records**.
* The dataset originally contains **21 columns**.
* No duplicate records were found.
* The `TotalCharges` column contained **11 blank values**.
* `TotalCharges` was converted from object type to numeric format.
* Missing values were successfully handled.
* Categorical variables were encoded for machine learning.
* The final processed dataset contains no missing values.

---

## 📂 Project Files

| File                                          | Description                      |
| --------------------------------------------- | -------------------------------- |
| `WA_Fn-UseC_-Telco-Customer-Churn.csv`        | Original dataset                 |
| `Week1_Data_Cleaning_and_Preprocessing.ipynb` | Python analysis notebook         |
| `Telco_Customer_Churn_Cleaned.csv`            | Cleaned and preprocessed dataset |
| `Week1_Report_Final_With_Images.docx`         | Complete project report          |

---

## 🎯 Conclusion

This project demonstrates the importance of data cleaning and preprocessing before performing data analysis or building machine learning models.

The Telco Customer Churn dataset was successfully explored, cleaned, and preprocessed using Python. The final dataset is ready for further exploratory data analysis, visualization, clustering, and machine learning tasks.

---

## 👨‍💻 Internship Details

**Internship:** Virtual Data Science with Python Trainee
**Platform:** YuvaIntern / NSDC
**Task:** Week 1 – Data Acquisition, Cleaning and Preprocessing

```

### After pasting:
1. Scroll down.
2. Click **Commit changes**.
3. Click **Commit changes** again if GitHub asks for confirmation.

Then send me a screenshot or say **Done**. 🚀
```
