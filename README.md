# Car Sales Dashboard – Power BI Project

## Overview

This project is an interactive **Car Sales Dashboard** developed using **Power BI** to analyze and visualize car sales performance. The dashboard provides valuable business insights such as total sales, average price, cars sold, regional performance, sales trends, and company-wise analysis using advanced Power BI features and DAX calculations.

The project demonstrates an end-to-end Power BI workflow including:

* Data Cleaning & Transformation
* Data Modeling
* Advanced DAX Measures
* Interactive Dashboard Design
* Business Insights Visualization

---

## Dashboard Preview

The dashboard includes:

* YTD Total Sales
* YTD Average Price
* YTD Cars Sold
* Weekly Sales Trend
* Sales by Body Style
* Sales by Color
* Dealer Region Sales Map
* Company-wise Sales Analysis
* Interactive Filters & Slicers

---

## Features

* Interactive and dynamic dashboard
* Advanced DAX calculations
* KPI Cards for quick business insights
* Drill-down and filtering options
* Modern dark-themed UI design
* Regional sales visualization using maps
* Trend analysis using line charts and donut charts

---

## Tools & Technologies Used

* Microsoft Power BI
* Power Query Editor
* DAX (Data Analysis Expressions)
* Data Modeling
* Excel/CSV Dataset

---

## Key DAX Measures Used

Some important DAX measures implemented in this project:

```DAX
YTD Total Sales = TOTALYTD(SUM(Sales[Sales Amount]), DateTable[Date])

YTD Cars Sold = TOTALYTD(SUM(Sales[Cars Sold]), DateTable[Date])

YTD Avg Price = DIVIDE([YTD Total Sales], [YTD Cars Sold])

MTD Total Sales = TOTALMTD(SUM(Sales[Sales Amount]), DateTable[Date])
```

---

## Dashboard Insights

* SUV body style generated the highest sales.
* Pale White cars had the maximum contribution in total sales.
* Chevrolet and Dodge showed strong sales performance.
* Weekly sales trend analysis helps identify peak sales periods.
* Regional map visualization highlights high-performing dealer locations.

---

## Learning Outcomes

Through this project, I learned:

* Creating professional Power BI dashboards
* Writing advanced DAX formulas
* Building interactive visualizations
* Data transformation using Power Query
* Business intelligence and data storytelling

---

## Project Structure

```bash
Car-Sales-Dashboard/
│── Dataset/
│── Dashboard.pbix
│── Images/
│── README.md
```

---

## Future Improvements

* Add forecasting and predictive analytics
* Integrate real-time sales data
* Add customer segmentation analysis
* Improve mobile dashboard responsiveness

---

## Author

**Saumya Mishra**
MCA Student | Aspiring Data Analyst & Developer

---

## Connect With Me

* GitHub: your-github-link
* LinkedIn: your-linkedin-profile

---

## License

This project is created for learning and portfolio purposes.
