# ✅ Day 4 – Pandas: Series, DataFrames, Filtering

---

## 🟢 Beginner Level
(Series and basic DataFrame creation)

1. Create a Pandas **Series** from a Python list `[10, 20, 30, 40, 50]`.  
2. Create a **Series** with custom index labels `['a','b','c','d','e']`.  
3. Convert a dictionary `{'name': ['Alice','Bob'], 'age': [25,30]}` into a DataFrame.  
4. Read a CSV file into a DataFrame (use any small dataset like `sample.csv`).  
5. Display the **first 5 rows** and **last 3 rows** of a DataFrame.  
6. Get the **column names** and **shape** of the DataFrame.  
7. Select a single column (Series) from the DataFrame.  

---

## 🟡 Mid Level
(Filtering, indexing, basic operations)

1. Create a DataFrame with columns: `Name, Age, Salary` for 5 employees.  
   - Display only the `Name` and `Salary` columns.  
2. Filter rows where `Age > 30`.  
3. Add a new column `Department` to the DataFrame.  
4. Change all salaries by adding a 10% increment.  
5. Sort the DataFrame by `Salary` in descending order.  
6. Find the **mean age** and **max salary** from the DataFrame.  
7. Select rows using `.iloc[]` (by position) and `.loc[]` (by label).  

---

## 🔴 Advanced Level
(Complex filtering, groupby, multi-index)

1. Create a DataFrame with students’ details: `Name, Subject, Marks`.  
   - Filter students who scored more than 80 in Math.  
2. Group the DataFrame by `Department` and calculate average salary for each department.  
3. Create a DataFrame with a **multi-index** (e.g., Employee → Year → Salary). Retrieve salaries of one employee across years.  
4. Replace missing values (`NaN`) in a DataFrame with column mean.  
5. Drop duplicate rows from a DataFrame.  
6. Merge two DataFrames:  
   - `df1 = { 'ID': [1,2,3], 'Name': ['A','B','C'] }`  
   - `df2 = { 'ID': [1,2,3], 'Salary': [5000,6000,7000] }`  
7. Create a pivot table from a DataFrame of sales data: `Region, Product, Sales`. Show total sales per region.  
