# Superstore Sales Case Study

## 📊 Project Overview
This project analyzes the **Superstore dataset** to uncover insights into sales trends, product performance, customer behavior, and profit distribution.  
The analysis was structured into two parts: **Exploratory Data Analysis (EDA)** and **Visualization**.

---

## 🧾 A. Analysis

1. **EDA Tasks**
   - Displayed dataset summary and shape.
   - Generated statistical summary of all columns.
   - Detected and dropped missing values.
   - Checked and removed duplicates.
   - Dropped `RowId` column.
   - Converted date columns into datetime format.
   - Calculated correlation between numeric columns.

2. **Customer Analysis**
   - Found total unique customers.
   - Identified customer with the maximum orders.

3. **Order Quantity**
   - Compared average order quantity across categories.

4. **Sales Seasonality**
   - Determined peak and low sales months for each year.

---

## 📊 B. Visualization

5. **Top 5 Most Frequently Ordered Products** – bar chart.  
6. **Profit by Sub-category** – profit distribution across different sub-categories.  
7. **Sales Distribution by State** – geographic distribution of sales.  
8. **Customer Segmentation** – consumer, corporate, home-office segments.  
9. **Top Categories & Sub-categories** – sales performance by product categories.  
10. **Monthly & Yearly Sales Trends** – analyzed sales growth and seasonality using `df.resample()`.

---

## 🛠 Tools & Libraries
- **Python**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  
- **Notebook Environment**: Jupyter Notebook  

