# IPL Data Analysis Project

## 📌 Project Overview
This project analyzes cricket data using **SQL and Python** to extract insights into player performances. The dataset is sourced from **Kaggle**, cleaned using **Jupyter Notebook**, and queried using **SQL**. The results are visualized with **Matplotlib and Seaborn**.

---

## 📂 Project Structure
```
📁 Cricket Data Analysis
├── cricket_data_2025.csv        # Raw dataset (Original Kaggle data)
├── cleaned_cricket_data.csv     # Processed dataset after cleaning
├── IPL Stats.ipynb              # Jupyter Notebook for data analysis
├── SQL Querries.txt             # SQL queries used for analysis
├── SQL_Output.xlsx              # Output of SQL queries (sorted by year)
├── README.md                    # Project documentation (this file)
```

---

## 🔹 Steps Followed in This Project

### 1️⃣ **Data Cleaning in Jupyter Notebook**
- **Loaded dataset (cricket_data_2025.csv) using Pandas.**
- Checked for **missing values and duplicates**.
- Converted data types for **correct numerical and date formatting**.
- Filtered out irrelevant or inconsistent data.
- Saved the cleaned dataset as **cleaned_cricket_data.csv**.

### 2️⃣ **SQL Query Execution**
- Wrote SQL queries to extract key insights such as:
  - Top batsmen based on **batting average, strike rate, and runs**.
  - Top bowlers based on **wickets, economy rate, and bowling average**.
  - Players with the **best balance of batting & bowling stats**.
- Executed the queries and saved the output as **SQL_Output.xlsx**.
- Sorted the first table by **year** in Excel.

### 3️⃣ **Data Visualization Using Python**
- Imported **Matplotlib & Seaborn** for plotting.
- Created bar charts for:
  - Top 10 batsmen by **batting average, strike rate, and runs**.
  - Top 10 bowlers by **wickets, economy, bowling average, and balls bowled**.
- Fixed Seaborn **FutureWarning** for proper hue assignment.

### 4️⃣ **Final Review & Output**
- Ensured **SQL queries return accurate results**.
- Verified **data sorting by year** in Excel.
- Reviewed **data visualizations for clarity**.

---

## 🚀 How to Run This Project
### **Requirements**
- **Python** (Pandas, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **SQL Database (MySQL/PostgreSQL/SQLite)**
- **Excel (for viewing output)**

### **Execution Steps**
1. **Run the Jupyter Notebook** (`IPL Stats.ipynb`) to clean data.
2. **Execute SQL queries** in a database environment.
3. **Sort data in Excel** (if needed).
4. **Run Python visualization scripts** to generate insights.

---

## 📊 Key Insights from the Analysis
- 🏏 **Top batsmen** based on runs scored and strike rate.
- 🎯 **Best bowlers** based on wickets, economy, and bowling average.
- 🔥 **Balanced players** excelling in both batting & bowling.

---

## ✨ Future Improvements
- Add **interactive dashboards** using **Plotly/Tableau**.
- Expand **SQL queries** to analyze team-based performance.
- Automate **Excel sorting** with Python.

---

## 📩 Contact
For queries, feel free to reach out!

📧 **Email:** sohamsheemar@gmail.com

---
