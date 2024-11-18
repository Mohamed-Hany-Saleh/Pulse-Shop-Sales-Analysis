# Pulse Shop Sales Analysis  

## Project Overview  
The **Pulse Shop Sales Analysis** project aims to analyze sales data to identify trends, evaluate performance, and provide actionable insights. This project focuses on extracting, processing, and visualizing sales-related data to support data-driven decision-making. The analysis includes identifying key performance indicators (KPIs), sales growth trends, and top-performing products, regions, and customers.  

This project is a critical step towards leveraging data to optimize sales strategies and improve overall business performance.  

---

## Project Objectives  
- **Data Preparation**: Clean, format, and organize sales data for analysis.  
- **Time-Based Analysis**: Categorize sales by time of day, day of the week, and monthly/yearly trends.  
- **Performance Evaluation**: Calculate KPIs such as total sales, profit, average order size, and growth rates.  
- **Insight Extraction**: Identify top-performing products, regions, and customers to guide strategic decisions.  
- **Visualization**: Create interactive dashboards to visualize sales performance and trends.  

---

## Key Features  
1. **Data Preparation**  
   - Import and process data from multiple Excel sheets: Orders, Products, Sales Representatives, Regions, and Customers.  
   - Categorize sales data by the time of day and aggregate monthly and yearly growth rates.  
   - Fill missing values and ensure data consistency.  

2. **Analytics**  
   - Calculate key performance indicators (KPIs):  
     - Total Sales  
     - Total Quantity Sold  
     - Total Profit  
     - Average Order Size  
     - Sales Growth (MoM & YoY)  
   - Identify top-performing products, regions, and customers based on sales data.  

3. **Data Export**  
   - Save the processed data to a new Excel file, maintaining original formatting and adding new insights.  

4. **Visualization**  
   - Create dashboards to visualize sales trends, regional performance, customer insights, and time-based sales distribution.  

---

## Technologies Used  
- **Python** for data analysis and processing.  
  - Libraries: `pandas`, `numpy`  
- **Tableau** for data visualization and dashboard creation.  
- **Google Colab** for collaborative coding and notebook execution.  

---

## Data Preparation Workflow  
1. **Data Import**  
   - Load Excel sheets into Pandas DataFrames for processing.  

2. **Time Categorization**  
   - Define sales by **Morning**, **Afternoon**, **Evening**, and **Night** based on order timestamps.  

3. **Aggregation**  
   - Aggregate monthly and yearly sales data.  
   - Compute Month-over-Month (MoM) and Year-over-Year (YoY) growth rates.  

4. **KPI Calculation**  
   - Extract critical metrics to evaluate sales performance.  

5. **Top Performers Identification**  
   - Determine top products, regions, and customers by sales.  

6. **Data Export**  
   - Save processed data into a structured Excel file for further use.  

---

## Visual Insights  
Two primary dashboards were created:  

### **Dashboard 1: Sales Performance Analysis**  
![image](https://github.com/user-attachments/assets/e7192888-1af7-4999-91f1-646b006a0747)

- Highlights:  
  - Top-performing products, regions, and customers.  
  - Sales representative performance.  
  - Revenue and growth comparison over years.  

### **Dashboard 2: Time-Based Sales Insights**  
![image](https://github.com/user-attachments/assets/ac9cd3a0-986a-41d7-80e8-e0094e84035d)


- Highlights:  
  - Sales distribution by time of day and day of the week.  
  - Sales trends over months and years.  
  - Overall KPIs such as total sales and growth rates.  

---

## Problem Statement  
The project addresses several business challenges:  
- Lack of visibility into **top-performing products** and **sales regions**.  
- Difficulty tracking **sales growth** and identifying trends over time.  
- Limited insight into how **time-based factors** (e.g., time of day, day of the week) influence sales.  
- The need for structured data export for decision-making.  

---

## Goals and Outcomes  
- **Improved Decision-Making**: Provide clear and actionable insights.  
- **Optimized Sales Strategies**: Focus on high-performing products and regions.  
- **Enhanced Reporting**: Use dashboards for real-time visualization and presentation.  
- **Data-Driven Growth**: Identify patterns to boost sales and maximize revenue.  

---

## How to Use  
1. Clone the repository.  
2. Upload the required Excel file containing the sales data.  
3. Run the provided Python script to process the data.  
4. Use the output file for creating Tableau dashboards or further analysis.  

---

## Output and Deliverables  
- **Processed Data File**: `Processed_Sales_Data.xlsx`  
- **Interactive Dashboards**:  
  - Sales Performance Analysis  
  - Time-Based Sales Insights  

---

## Future Enhancements  
- Incorporating more advanced analytics like predictive modeling for sales forecasting.  
- Automating the dashboard updates using live data connections.  
- Expanding the analysis to include cost optimization and profitability metrics.  

