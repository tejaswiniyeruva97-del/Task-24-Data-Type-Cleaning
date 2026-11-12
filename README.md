# Task-24-Data-Type-Cleaning
## VEDA TECHNOLOGY – AI & ML Internship

### Project Overview
This project focuses on identifying incorrect data types in a dataset and converting columns into appropriate data types using Python and Pandas.

### Objective
To understand the importance of correct data types in data analysis and machine learning.

### Tools and Technologies
- Python
- Pandas
- NumPy
- Google Colab
- Jupyter Notebook

### Dataset
The project uses an Employee Dataset containing the following columns:

| Column Name | Description |
|---|---|
| Employee_ID | Employee identification number |
| Name | Employee name |
| Age | Employee age |
| Salary | Employee salary |
| Joining_Date | Employee joining date |
| Department | Employee department |

### Steps Performed

1. Imported Pandas and NumPy libraries.
2. Created and loaded the employee dataset.
3. Displayed the first five rows using `df.head()`.
4. Inspected dataset information using `df.info()`.
5. Checked original data types using `df.dtypes`.
6. Checked missing values using `df.isnull().sum()`.
7. Converted Age from object to integer using `astype(int)`.
8. Converted Salary into numeric using `pd.to_numeric()`.
9. Converted Joining_Date into datetime using `pd.to_datetime()`.
10. Converted Department into category using `astype('category')`.
11. Compared original and corrected data types.
12. Saved the cleaned dataset as a CSV file.

### Data Type Conversion Summary

| Column | Original Type | Corrected Type |
|---|---|---|
| Employee_ID | object | object |
| Name | object | object |
| Age | object | int64 |
| Salary | object | int64 |
| Joining_Date | object | datetime64[ns] |
| Department | object | category |

### Important Pandas Functions

- `df.dtypes` – Checks column data types.
- `df.info()` – Displays dataset information.
- `astype()` – Converts data types.
- `pd.to_numeric()` – Converts values into numeric format.
- `pd.to_datetime()` – Converts values into date format.
- `df.isnull().sum()` – Checks missing values.
- `df.to_csv()` – Saves the cleaned dataset.

### Output Files

- `Data_Type_Cleaning.ipynb`
- `cleaned_employee_dataset.csv`

### How to Run the Project

1. Open Google Colab.
2. Create a new notebook.
3. Import the required libraries.
4. Execute the code cells one by one.
5. Check original and corrected data types.
6. Save and download the cleaned dataset.

### Conclusion

Successfully completed Data Type Cleaning using Python and Pandas. Identified incorrect data types, converted columns into appropriate formats, and verified the cleaned dataset.

### Internship Details

- **Organization:** VEDA TECHNOLOGY
- **Track:** AI & ML
- **Task:** Data Type Cleaning

---
**Thank You!**
