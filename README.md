# ☕📊 Coffee Shop Sales Analysis (Excel Dashboard)
Which drinks sell the most? When are peak sales hours?  
This Excel project dives into coffee shop transaction data to explore sales trends and optimize business decisions.

---

## 🙏 Acknowledgment

This project was inspired by [WsCube Tech’s YouTube tutorial](https://www.youtube.com/watch?v=Rthh_bK5xUs), which introduced valuable techniques for building Excel dashboards using coffee shop sales data.

While I took my own approach and made custom adjustments, the video helped spark ideas for layout, interactivity, and business-focused insights.

Big thanks as well to [Maven Analytics](https://www.mavenanalytics.io/) for sharing the dataset and supporting learners like me 🌱

---

## 📌 Project Objectives

This project aims to explore and analyze transactional data from a fictional coffee shop business to uncover patterns in sales performance, customer preferences, and operational efficiency. Specifically, it focuses on answering the following key business questions:

- ☕️ Which day of the week generates the highest total revenue?
→ Identifying peak business days helps optimize staffing, promotions, and inventory planning.

- 🛍️ What are the top five best-selling products based on quantity sold?
→ Understanding customer favorites supports strategic decisions on menu offerings and stock management.

- 🧾 Which store location performs best in terms of total revenue, and what product categories dominate each location?
→ Comparing store performance and local customer preferences can guide region-specific strategies.

- ⏰ What are the busiest hours of the day across all store locations?
→ Pinpointing peak sales hours enables better workforce scheduling and targeted marketing.

- 💸 What is the average customer bill across different product categories?
→ Revealing customers' spending behavior and potential opportunities to increase order value.

- 🤑 Which product generates the highest revenue per transaction on average?
→ This tells you which products are the most profitable per sale — not just by volume, but by customer spend per purchase.
---

## 📁 Dataset

- **Source**: [Coffee Shop Sales dataset](https://mavenanalytics.io/data-playground?page=7&pageSize=5)
- **Rows**: ~149,116 customer records
- **Features**:  
  - Transaction details (transaction date, time, quatity, etc.)
  - Store information (store id, store location)
  - Product details (product id, unit price, product category, etc.)

---

## 🛠️ Tools & Libraries

![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-3E8EDE?style=for-the-badge&logo=microsoft&logoColor=white)  
![PivotTables](https://img.shields.io/badge/Pivot%20Tables-F89B29?style=for-the-badge&logo=microsoft-excel&logoColor=white)  

---

## 📈 Workflow Summary

### 1️⃣ Data Import & Inspection
- Loaded raw transactional data into Excel using Power Query
- Conducted initial review to understand field types, missing values, and inconsistencies

### 2️⃣ Data Cleaning & Transformation
- Cleaned and standardized data using Power Query (e.g., removed null rows, changed data types, renamed columns)
- Extracted additional time-based features including Day of Week, Month, and Hour from transaction timestamps
- Calculated new columns such as `total_bill` (`unit_price` × `transaction_qty`) for deeper revenue analysis

### 3️⃣ Data Aggregation & Exploration
- Built dynamic PivotTables to analyze sales performance across key dimensions:
    - Day of the week
    - Product category and product type
    - Store location
    - Hour of transaction
- Applied calculated fields and filters to uncover trends and outliers

### 4️⃣ Data Visualization & Dashboarding
- Created interactive charts (bar, column, stacked, line) to visualize sales patterns
- Used slicers and conditional formatting to build a clean, interactive dashboard
- Visualized KPIs such as top products, busiest hours, and revenue by store location

---

## 🧠 Results


...

---

## 💼 Business Impact and Suggestions

...

---

## ✨ Key Learnings

- How to turn messy raw data into something **visual** and **meaningful**
- **Dashboard** structuring and visual storytelling in **Excel**
- Ways to simplify analysis for **non-technical** users

---

## 🌱 About Me

I'm a self-taught data enthusiast and economics student passionate about using data to solve real-world problems.  
This project was part of my learning journey in Data Analytics, and you can find more of my work [here](https://github.com/uyenp30/Data-Projects) 💻🌻

---

*Thank you for reading!* ✨  
*If you found this useful or have feedback, feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/uyen-pham-sua/).*  
