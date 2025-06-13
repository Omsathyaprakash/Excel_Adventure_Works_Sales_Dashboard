# Excel_Adventure_Works_Sales_Dashboard

This project features a dynamic and interactive **Excel dashboard** developed to analyze sales data from the popular **Adventure Works dataset**. Designed for business users and analysts alike, it demonstrates how Excel can be leveraged as a robust tool for business intelligence—transforming raw data into actionable insights through smart modeling and visualization.

---

## 📊 Dashboards Overview
### 🕒 Time Analysis Dashboard:
![time series dashboard](https://github.com/user-attachments/assets/2b573f0c-367d-497c-827c-9ef48bebe70f)

- **Key Metrics**: Total Quantity, Revenue, Cost, Transactions, and Profit
- **YOY Growth %** and **Monthly Profit Trends**
- **Year-wise Comparison**: Revenue, Profit, Transactions
- **Weekday vs. Weekend Profit Contribution**
- **Quarterly & Weekday Profit Distribution**
- **Interactive Filters**: Year, Month, Country

### 🔍 Detail Analysis Dashboard:
![detail dashboard](https://github.com/user-attachments/assets/9c5c49c7-699e-4e83-8012-15e47bb93e5e)

- **Top 5 Profitable Products & Customers**
- **Profit Analysis**: Product Colors, Expensive vs. Less Expensive Categories
- **Customer Demographics**:Average Age,Gender-based Profit Distribution,Age Group Contribution
- **Sales Geography**: Profit by Country (Map Visual)
- **Product Insights**: Total Products, Sold vs. Unsold
- **Dynamic Filters**: Year, Region

---

## 🛠️ Key Excel Techniques Used

### 1. Power Query for Data Cleaning
- Removed duplicates
- Deleted unnecessary columns
- Merged and transformed columns
- Added custom and conditional columns
- Ensured proper data types

### 2. Calculated Formulas
- Used advanced Excel functions: `VLOOKUP`, `IFS`, `INDEX-MATCH`, `SWITCH`
- Created dynamic and calculated fields for metrics

### 3. Power Pivot Measures (DAX)
- Custom DAX measures to calculate:
  - Total Transactions
  - Sold vs. Unsold Products
  - Total Customers
  - Profit Margin %

### 4. Data Model Design
- Built a **star schema** in Power Pivot:
  - Central FactInternetSales table
  - Linked to dimension tables: Date, Product, Customer, Geography, Sales Territory

### 5. Pivot Tables for Visuals
- Used Pivot Tables to build interactive, dynamic visualizations across dashboards

### 6. Slicers for Interactivity
- Enabled intuitive filtering by Year, Product, Country, and Region

### 7. Page Navigation & Macros
- Added page navigation buttons for seamless switching between dashboards
- Used Macros to implement a **Clear Filter** button for user-friendly experience

---

## 📁 Files Included
- `AdventureWorks_ExcelDashboard.xlsx` – Complete dashboard file
- `project.csv` – Cleaned dataset
- `README.md` – This documentation
- `Akhil_SQL_Income.pdf` – Project write-up (if relevant)

---

## 📌 Learnings & Takeaways
This project strengthened my expertise in:
- Excel as a BI tool
- Data modeling using Power Pivot
- Using DAX for business metrics
- Storytelling with data using visuals and interactivity

---

## 🔗 Connect with Me

If you're passionate about data analytics, Excel BI, or business intelligence, feel free to connect!

📧 [Email](mailto:your.email@example.com)  
💼 [LinkedIn](https://www.linkedin.com/in/your-profile/)  
📂 [Portfolio](https://your-portfolio-link.com)

---

## 🏷️ Tags

`#ExcelDashboard` `#DataAnalytics` `#PowerPivot` `#PowerQuery` `#BusinessIntelligence` `#DataVisualization` `#AdventureWorks` `#DashboardDesign` `#ExcelTips`
