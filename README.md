# Intrenship_Task
Practical perform on various real-world dataset and perform internship tasks efficiently.

## 📂 File Descriptions

### 1. raw_employee_data.csv

Description:  
Raw dataset containing employee information including Name, Age, Gender, Email, Join Date, Salary, and Department.

Issues:  
- Missing values in Age, Salary, and Department  
- Inconsistent formatting for Gender and Join Date  
- Duplicate records  
- Invalid entries like "unknown" in Age  

---

### 2. raw_customer_data.csv

Description:  
Raw dataset of customer purchases with fields like Customer ID, Product, Price, Quantity, City, and Purchase Date.

Issues:  
- Missing values in Price, Quantity, and Product  
- Text instead of numbers in Price (e.g., "forty-five thousand")  
- Inconsistent or invalid data entries  

---

### 3. data_cleaning_employee_data.ipynb

Description:  
Jupyter Notebook for cleaning and preprocessing the employee dataset.

Key Steps:  
- Data exploration  
- Handling missing values  
- Standardizing Gender values  
- Removing duplicates  
- Fixing Join Date formatting  
- Previewing final cleaned dataset  

---

### 4. data_cleaning_customer_data.ipynb

Description:  
Notebook for cleaning customer transaction data.

Key Steps:  
- Data exploration and type inspection  
- Fixing non-numeric Price values  
- Handling missing Quantity and Product entries  
- Final output preview of cleaned data  

---

### 5. cleaned_employee_data.csv

Description:  
Cleaned version of the employee dataset — all missing values addressed, formatting corrected, and ready for analysis.

---

### 6. cleaned_customer_data.csv

Description:  
Final cleaned customer transaction dataset — ready for analysis and machine learning applications.

---

### 7. eda_employee_dataset.csv (NEW)

Description:  
This dataset is designed for Exploratory Data Analysis (EDA) and contains rich employee-level information suitable for workforce analytics.

Columns:  
- Employee ID: Unique identifier for each employee  
- Age: Age in years  
- Gender: Male/Female  
- Department: Department name (e.g., HR, Sales)  
- Location: City where the employee works  
- Experience: Total years of experience  
- Salary: Annual salary in USD  
- Score: Performance or evaluation score  

Purpose:  
- Analyze demographics (age, gender, department distribution)  
- Compare salary across departments, cities, and experience levels  
- Explore relationships between performance scores, salary, and experience  
- Investigate potential gender or location-based disparities
