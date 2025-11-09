# Chicago Public Schools Data Analysis with SQL and Python

This project analyzes the **2011–2012 Chicago Public Schools (CPS) Progress Report Cards dataset** using **SQLite** and **Python**, entirely within a Jupyter Notebook environment powered by the `%sql` magic command.

The analysis demonstrates how real-world data can be queried, transformed, and visualized using SQL and Python together.  
It reproduces the type of exploratory tasks and business questions typically covered in professional data science workflows.

---

## 🧩 Project Overview

The dataset contains school-level performance indicators for Chicago Public Schools, including:
- Safety Scores  
- Student Attendance  
- College Enrollment  
- School Type (Elementary, Middle, High School)  
- Community Area information  

Using SQLite and IPython-SQL, we:
1. Load and store the dataset in a relational database (`.db`)
2. Explore table structure and metadata  
3. Write SQL queries to answer analytical questions  
4. Visualize trends with Python and matplotlib  

---

## 🎯 Objectives

After completing this notebook, you will be able to:

- Understand the dataset and its schema  
- Query the database using SQL commands inside Jupyter  
- Retrieve metadata about tables and columns  
- Use built-in SQL functions for filtering, grouping, and aggregation  
- Integrate SQL with Python-based visualizations  

---

## 📘 Notebook Contents

| Section | Description |
|----------|--------------|
| **0. Setup and Connection** | Load the `ipython-sql` extension and connect to SQLite |
| **1. Load CSV into Database** | Load the Chicago Public Schools dataset (via public URL) into SQLite |
| **2. Metadata Exploration** | Retrieve table and column metadata |
| **3. Core SQL Analysis** | Answer key analytical questions using SQL queries |
| **4. Visualizations** | Build charts to visualize attendance and enrollment metrics |
| **5. Close** | End the session and summarize findings |

---

## ❓ Key Questions Answered

1. How many **Elementary Schools** are there in the dataset?  
2. What is the **highest Safety Score**, and which schools achieved it?  
3. What are the **top 10 schools by Average Student Attendance**?  
4. Which schools have **attendance below 70%**?  
5. Which **Community Areas** have the **lowest total college enrollment**?  
6. Which are the **five least safe schools** based on Safety Score?  

Each query cell in the notebook clearly states which question it answers for maximum readability and reproducibility.

---

## 📊 Visualizations Included

1. **Distribution of Average Student Attendance** — histogram  
2. **Top 10 Schools by Attendance** — horizontal bar chart  
3. **Top 10 Community Areas by College Enrollment** — horizontal bar chart  

All visualizations are rendered automatically upon cell execution.

---

## ⚙️ How to Run the Notebook

1. Install dependencies:
   ```bash
   pip install ipython-sql pandas matplotlib sqlalchemy
