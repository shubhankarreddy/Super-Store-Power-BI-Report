# Super-Store-Power-BI-Report

**Interact with the dashboard:** [View Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYTg5YjY2ODAtOThjYS00NzE3LWJjNzQtNjIxYjkzNDY0ZTcxIiwidCI6IjA1YTVjMTBmLTFiNGYtNDlkOS1hNjRhLTY1NjIwZjM0ZmUxMyJ9)

An interactive Power BI dashboard providing insights into sales, profit, and shipping performance. This project showcases data-driven decision-making through visualizations and actionable insights.

---

## Objective
The goal of this analysis is to:
- Identify key trends and patterns in sales and profits.
- Understand regional and product performance.
- Provide insights to improve customer satisfaction and business efficiency.

---

## Tools Used
- **Power BI**: For data visualization and dashboard creation.
- **Power Query**: For data cleaning and transformation.
- **DAX (Data Analysis Expressions)**: For advanced calculations and measures.

---

## Data Preparation
The following steps were performed to prepare and transform the Superstore dataset:
1. Connected Power BI to the dataset.
2. Cleaned and transformed data using **Power Query**:
   - Removed duplicates and renamed columns for clarity.
   - Changed data types where necessary.
   - Created parameters to enable filtering and dynamic analysis.
   - Encapsulated data cleaning steps into reusable functions for future datasets.

---

## Dashboard Features

### 1. **Sales Analysis**
- **Top 5 Revenue-Generating Cities**: New York, Los Angeles, Seattle, Philadelphia, and San Francisco.
- **Bottom 5 Revenue-Generating Cities**: San Luis Obispo, Pensacola, Abilene, Jupiter, and Elyria.
- **Top 5 Revenue-Generating States**: California, New York, Texas, Washington, and Pennsylvania.
- **Bottom 5 Revenue-Generating States**: Maine, Wyoming, West Virginia, South Dakota, and North Dakota.

### 2. **Product Analysis**
- **Category Performance**:
  - **Top Category**: Technology.
  - **Lowest Category**: Office Supplies.
- **Segment Insights**:
  - Consumer segment contributes the highest sales.
  - Corporate and Home Office follow.
- **Top Products**: Chairs and Tables dominate the Corporate segment. Binders and Storage lead in the Home Office category.

### 3. **Shipping Analysis**
- **Revenue by Ship Mode**:
  - Standard Class generates the highest revenue, followed by First Class and Second Class.
  - Same Day delivery accounts for the least revenue.
- **Profit by Ship Mode**:
  - Standard Class contributes the most profit, while Same Day delivery has the lowest.
- **Key Observation**: Quantity and revenue are directly proportional to profit.

---

## Key Insights

### **Regional Insights**
- California generates the highest revenue, while North Dakota is at the bottom.
- New York City leads in profit, with Philadelphia performing poorly.

### **Profitability Insights**
- Delivering fewer quantities sometimes results in higher profits.
- Shipping modes significantly impact profit margins.

### **Category Insights**
- Technology products are the best-performing category.
- The Consumer segment drives the majority of sales.

### **Shipping Preferences**
- Most customers choose Standard Class shipping, followed by First Class.

---

## Conclusion
The Superstore Dashboard provides actionable insights to:
- Focus on underperforming regions like North Dakota and cities with minimal revenue.
- Optimize shipping strategies to improve profitability.
- Leverage high-performing categories like Technology to boost overall sales.
- Target specific customer segments for enhanced customer satisfaction.

---

## Visual Preview
The dashboard includes:
- **KPI cards** for quick metrics.
- **Bar charts** and **column charts** for city, state, and shipping mode analysis.
- **Pie and donut charts** for product categories and segment insights.
- **Matrix visuals** for detailed breakdowns.

---
