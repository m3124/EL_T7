# EL_T7
# 📊 Task 7 – Basic Sales Summary using SQLite & Python

## 🔎 Project Overview
This project is part of my **Data Analyst Internship – Task 7**, where I used **SQLite + Python** to generate a **basic sales summary**.  

The main goals were:
- Connect Python with an SQLite database  
- Run SQL queries for summarizing sales data  
- Print results in Python using Pandas  
- Create a visualization with Matplotlib  
- Document everything clearly and push to GitHub  

---

## 🛠 Tools & Libraries
- **Python** (core language)  
- **SQLite3** (database)  
- **Pandas** (data handling)  
- **Matplotlib** (visualization)  
- **Google Colab** (development environment)  
- **GitHub** (submission platform)  

---

## 📂 Dataset
A small SQLite database (`sales_data.db`) was created with one table: **`sales`**  

**Schema:**
| Column   | Type    | Description |
|----------|---------|-------------|
| id       | INTEGER | Primary Key (Auto Increment) |
| product  | TEXT    | Product Name |
| quantity | INTEGER | Number of units sold |
| price    | REAL    | Price per unit |

**Sample Data:**
| product | quantity | price |
|---------|----------|-------|
| Laptop  | 2        | 50000 |
| Laptop  | 1        | 50000 |
| Phone   | 3        | 15000 |
| Phone   | 2        | 15000 |
| Tablet  | 4        | 20000 |


