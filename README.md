# Retail-Sales-Analysis
End-to-end retail sales analysis using Python, MySQL, Excel, and Power BI

## 📌 Problem Statement  
The goal of this project was to analyze retail sales data to uncover trends across years, product categories, and gender, and to present actionable insights through visualizations and dashboards.  

---

## 🛠 Tools Used  
- **Python (Jupyter Notebook)** → Data cleaning and preprocessing.  
- **MySQL** → Querying, CTEs, and window functions for analysis.  
- **Excel** → Pivot tables and charts with insights.  
- **Power BI** → Interactive dashboard with KPIs, slicers, and filters.  

---

## 🔄 Steps Taken  
1. **Data Cleaning in Python**  
   - Loaded raw dataset into Jupyter Notebook.  
   - Cleaned and transformed columns (dates, totals, categories).  
   - Saved cleaned dataset into CSV for further analysis.  

2. **SQL Analysis in MySQL**  
   - Connected MySQL database to Python using `sqlalchemy` + `mysql-connector`.  
   - Ran queries with **CTEs** and **window functions** to analyze sales by category, gender, and year.  

3. **Excel Pivot Analysis**  
   - Created pivot tables:  
     - Sales by Year  
     - Sales by Product Category  
     - Sales by Gender  
   - Added charts (bar, line, pie) and insights for each visualization.  

4. **Power BI Dashboard**  
   - Imported cleaned dataset into Power BI.  
   - Created KPIs:  
     - Sum of total amount  
     - Count of Customer ID  
     - Customer Lifetime Value 
   - Added **slicers** (e.g., Gender) to make dashboard interactive.  
   - Exported dashboard screenshots for documentation.  

---

## 📊 Key Insights  
- Sales across product categories showed a decline in 2024 compared to 2023.  
- Female customers led in total sales in 2023, but sales dropped for both genders in 2024.  
- Overall sales trends suggest seasonality and possible external factors affecting demand.  

---

## 📸 Screenshots  

### Power BI Dashboard  
![Dashboard](PowerBI%20Retails20Sales%20Dashboard.png)  

### Pivot Table 1
![PivotTable1](Pivot%20Table%201.png)  

### Pivot Table 2
![PivotTable2](Pivot%20Table%202.png) 

### Pivot Table 3
![PivotTable3](Pivot%20Table%203.png) 


