## EV-Battery-Sales-Analysis Project: Problem Statement

This project focuses on a comprehensive analysis of an EV battery sales dataset from the year 2024. The primary goal is to provide a detailed, insightful overview of business performance to support data-driven decision-making. Using SQL for data management and Power BI for visualization, it provides a detailed overview of business performance. 

---



### **Overview**
This project is a comprehensive data analysis of an **EV battery sales dataset** for the year 2024. The goal is to transform raw sales data into actionable business intelligence to support data-driven decision-making. The project utilizes **SQL Server Express** for robust data management and **Power BI** for creating an interactive, insightful dashboard. This end-to-end process provides a clear view of business performance, sales trends, and key product metrics.

### **Key Features**
* **Data Cleaning and Preparation:** Transforming the raw data into a clean, structured dataset ready for analysis.
* **SQL Database Integration:** Importing the processed data into a SQL Server database for efficient querying.
* **Interactive Power BI Dashboard:** Creating a dynamic and user-friendly dashboard to visualize key insights.
* **Key Performance Indicator (KPI) Calculation:** Deriving essential metrics like Total Revenue, Average Order Value, and Top/Bottom-performing products.
### **KPI's and Charts Requirements**

#### **Key Performance Indicators (KPIs)**
To gain insights into the business's performance, the following metrics will be calculated:
1.  **Total Revenue:** The total value of all EV battery orders.
2.  **Average Order Value:** The average amount spent per order.
3.  **Total Batteries Sold:** The total quantity of all EV battery units sold.
4.  **Total Orders:** The total number of unique orders placed.
5.  **Average Batteries Per Order:** The average number of batteries sold per order.

#### **Charts Requirements**
To effectively visualize sales data and understand key trends, the following charts will be created:
1.  **Daily Trend for Total Orders:** A bar chart to display the daily trend of total orders, helping to identify daily patterns or fluctuations.
2.  **Monthly Trend for Total Orders:** A line chart to illustrate the monthly trend of total orders over the year, allowing for the identification of seasonal trends.
3.  **Percentage of Sales by Battery Category:** A pie chart showing the distribution of sales across different battery categories, providing insight into the popularity and contribution of each category to overall revenue.
4.  **Percentage of Sales by Battery Size:** A pie chart representing the percentage of sales attributed to different battery sizes, helping to understand customer preferences.
5.  **Total Batteries Sold by Battery Category:** A bar chart presenting the total number of batteries sold for each category, enabling a comparison of sales performance.
6.  **Top 3 Best Sellers:** A bar chart highlighting the top 3 best-selling batteries based on revenue, total quantity, and total orders.
7.  **Bottom 3 Best Sellers:** A bar chart showcasing the bottom 3 worst-selling batteries based on revenue, total quantity, and total orders, to identify underperforming products.

---
## **Dataset used**
- <a href="https://github.com/himanshi8700003783/EV-Battery-Sales-Analysis/blob/main/ev_batteries_1000_records.csv">EV-BATTERY-DATASET</a>

### **Technologies Used**
* **SQL Server Express:** For hosting the project database.
* **SSMS (SQL Server Management Studio):** For managing the database and executing SQL queries.
* **Microsoft Power BI:** For data visualization and dashboard creation.
* **Microsoft Excel:** For initial data cleaning and manipulation.

### **Project Structure**
* `ev_batteries_1000_records.csv`: The cleaned and prepared dataset containing 1000 records of EV battery sales from 2024.
* `ev_battery_sales_dashboard.pbix`: The Power BI project file containing the data model and all dashboard visualizations.
* `BATTERY SALES SQL QUERIES.docx`: A file containing all the SQL scripts used for table creation and data analysis.

## **DASH BOARD**
- <a href="https://github.com/himanshi8700003783/EV-Battery-Sales-Analysis/blob/main/BatterySales_page-0001.jpg">EV-BATTERY-MAIN-DASHBOARD</a>

### **How to Use**
1.  **Clone this repository** to your local machine.
2.  **Import the `ev_batteries_1000_records.csv`** file into a new table in your SQL Server database using SSMS.
3.  **Open the `ev_battery_sales_dashboard.pbix`** file in Microsoft Power BI Desktop.
4.  **Refresh the data source** in Power BI to connect to your local SQL database and view the dashboard with your data.

### **Conclusion**
This project provides a robust framework for analyzing EV battery sales data, offering critical insights that can be used to optimize business strategies and drive growth in the electric mobility market. The combination of SQL for data management and Power BI for visualization offers a powerful solution for monitoring business performance.
