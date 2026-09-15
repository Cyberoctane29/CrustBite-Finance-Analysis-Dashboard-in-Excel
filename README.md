# CrustBite Finance Analysis Dashboard in Excel - An Interactive Analysis of Sales Performance, Revenue Trends & Regional Insights

## **Introduction**

This project is an interactive Excel dashboard built to analyze CrustBite’s sales performance across daily sales trends, sales amount buckets, products, and regions. By combining overall sales and average sales analysis, transaction-value distribution, sales volume across price buckets, and product-level performance comparisons, the dashboard provides a comprehensive view of sales activity and revenue patterns. Interactive **Slicers**, **PivotTables**, and **PivotCharts** enable dynamic filtering and exploration of regional sales performance, while multiple visualizations highlight sales distribution, transaction volume, product performance, and time-based trends. Designed with a clean and structured layout, the dashboard transforms sales data into clear, interactive, and accessible insights for understanding sales patterns and supporting data-driven business decisions.

![CrustBite Finance Analysis Dashboard](Image%20-%20CrustBite%20Finance%20Analysis%20Dashboard%20in%20Excel/CrustBite%20Finance%20Analysis%20Dashboard%20-%20Slicer%20State%201.png)

### Access the Dashboards

If you’d like to directly explore the interactive dashboards and project files, you can access them here:

[Google Drive link](https://drive.google.com/drive/u/0/folders/15DBYSbktY4SfuLYSRQe6cPKpx6ibE60s) : https://drive.google.com/drive/u/0/folders/15DBYSbktY4SfuLYSRQe6cPKpx6ibE60s

[Interactive dashboard video walkthrough](https://drive.google.com/file/d/1-wgQnhj7SXR0ey4XIESRP88Yr3u9OSfh/view): https://drive.google.com/file/d/1-wgQnhj7SXR0ey4XIESRP88Yr3u9OSfh/view

For the complete project details, including dataset context, analysis workflow, and documented insights, continue with this repository.

## **Project Overview**

The **CrustBite Finance Analysis Dashboard** project aims to:

* **Monitor Sales Performance**: Track overall sales values and average sales amounts over time to provide a comprehensive view of sales performance and identify changes in revenue patterns  
* **Analyze Product Performance**: Compare products based on their total sales values and average sales amounts to identify stronger and weaker-performing products  
* **Understand Sales Amount Patterns**: Examine the distribution of sales across different **₹200 transaction-value buckets** and compare both total sales value and number of sales within each bucket  
* **Explore Time-Based Sales Trends**: Analyze daily overall sales and average sales values to identify fluctuations, trends, and changes in sales performance over the analysis period  
* **Examine Regional Performance**: Compare sales performance across **East, North, South, and West** regions to identify regional variations and support more targeted analysis  
* **Enable Interactive Analysis & Decision-Making**: Use **Slicers**, **PivotTables**, and **PivotCharts** to dynamically explore sales patterns by region and transaction-value buckets, helping stakeholders identify trends, product performance differences, and areas requiring attention

## **Dataset Structure**

The project is built on a **Finance Dataset** containing individual sales transactions along with product, sales amount, date, and regional information. The dataset provides the foundation for analyzing sales performance, transaction-value patterns, product-level performance, and regional sales activity within the Excel dashboard.

**Finance Dataset:**  
Captures individual sales transactions and their associated sales and geographical details. Key features include:

* `S.No`: Serial number representing the record sequence
* `Product`: Product associated with the sales transaction
* `Amount in Sales`: Sales amount associated with the transaction
* `Date`: Date on which the sales transaction occurred
* `Region`: Geographical region associated with the transaction, including **East, North, South, and West**

The dataset combines transaction, product, date, sales-value, and regional information at the individual sales level. The `Date` field supports daily sales trend analysis, while `Product`, `Amount in Sales`, and `Region` enable product-level, transaction-value, and regional performance analysis within the Excel dashboard. The `Amount in Sales` field is also grouped into **₹200 sales amount buckets** to support analysis of total sales value and the number of sales across different transaction-value ranges.

## **Dashboard Development & Analytical Workflow**

- **Defined Analytical Objectives**  
  Established the key analytical dimensions for evaluating CrustBite sales performance, focusing on daily sales trends, average sales values, transaction-value distributions, product performance, and regional sales activity.

- **Data Preparation & Feature Engineering**  
  - Structured the underlying finance and sales data into an Excel table to support analysis and interactive reporting.
  - Organized transaction records across fields including product, sales amount, date, and region.
  - Grouped the `Amount in Sales` field into **₹200 sales amount buckets** to support transaction-value distribution and sales-volume analysis.
  - Prepared the dataset for dynamic aggregation and filtering through Excel's table and PivotTable functionality.

- **Pivot-Based Analytical Modeling**  
  - Developed PivotTables to calculate overall sales values and average sales values across individual dates.
  - Created sales amount bucket analysis to compare total sales value and the number of sales across different transaction-value ranges.
  - Developed product-level analysis comparing total sales values and average sales values across products.
  - Incorporated regional filtering to enable exploration of sales performance across **East, North, South, and West** regions.
  - Structured supporting PivotTables to provide the analytical sources for the dashboard's charts and visualizations.

- **Interactive Dashboard Construction**  
  - Designed a single-page **CrustBite Finance Dashboard** combining daily sales trends, average sales trends, transaction-value distribution, sales volume, and product-level performance analysis.
  - Created multiple PivotCharts, including doughnut charts, combo charts, and line charts, to present different aspects of sales performance.
  - Added an interactive **Region** slicer, enabling users to dynamically filter the dashboard by geographical region.
  - Applied a clean and structured layout with clearly separated visualization panels, KPI-style summary elements, consistent chart formatting, whitespace, and a cohesive blue-gray visual theme.

- **Interactive Filtering & Dynamic Reporting**  
  - Connected the Region slicer to relevant PivotTables and PivotCharts to ensure that dashboard visualizations respond dynamically to regional selections.
  - Enabled users to explore changes in daily sales trends, average sales, transaction-value distributions, sales volume, and product performance for selected regions.
  - Designed the dashboard to support both an overall view of sales performance and focused analysis of individual regional segments.

- **Dashboard Validation & Presentation**  
  - Tested the dashboard across different regional slicer selections to ensure that charts and analytical summaries updated consistently.
  - Validated sales totals, average sales values, transaction counts, product-level metrics, and regional filtering against the underlying PivotTables.
  - Organized the workbook into four functional worksheets: **Finance Data**, **Dashboard Business Questions**, **Finance Pivot Sheet**, and **Finance Dashboard**, separating the raw data, analytical questions, supporting PivotTable analysis, and final dashboard presentation.
 
## **Dashboard Previews**  

### CrustBite Finance Dashboard - Slicer State 1

![CrustBite Finance Dashboard - Slicer State 1](Image%20-%20CrustBite%20Finance%20Analysis%20Dashboard%20in%20Excel/CrustBite%20Finance%20Analysis%20Dashboard%20-%20Slicer%20State%201.png)

### CrustBite Finance Dashboard - Slicer State 2

![CrustBite Finance Dashboard - Slicer State 2](Image%20-%20CrustBite%20Finance%20Analysis%20Dashboard%20in%20Excel/CrustBite%20Finance%20Analysis%20Dashboard%20-%20Slicer%20State%202.png)

### CrustBite Finance Dashboard - Slicer State 3

![CrustBite Finance Dashboard - Slicer State 3](Image%20-%20CrustBite%20Finance%20Analysis%20Dashboard%20in%20Excel/CrustBite%20Finance%20Analysis%20Dashboard%20-%20Slicer%20State%203.png)

## **Key Insights**

### **Overall Sales Performance**
- **Consistent Daily Sales Activity**: Daily overall sales values fluctuated throughout the June–September analysis period, generally remaining within a range of approximately **₹300–₹800**, with several noticeable peaks and declines across the period.
- **Variation in Average Sales**: Average sales values showed substantially greater volatility during June and July, followed by a noticeable decline and stabilization at lower levels from late July onward.
- **Declining Average Sales Trend**: The dashboard highlights that average sales began declining toward approximately **₹5,000 by late July**, indicating a reduction in average transaction values over the analysis period.
- **Sales Performance Over Time**: The combination of overall sales and average sales trends provides a time-based view of both sales activity and changes in transaction-value behavior.

### **Sales Amount Distribution**
- **Higher-Value Sales Contribution**: Sales transactions in the **₹500–₹699** and **₹700–₹900** buckets together accounted for approximately **72%–73% of total sales value** across the dashboard views.
- **₹700–₹900 Bucket Leads Sales Value**: The **₹700–₹900** transaction-value bucket contributed the largest share of total sales value, accounting for approximately **40%–43%** across the different regional filter states.
- **₹500–₹699 Bucket as the Second-Largest Contributor**: The **₹500–₹699** bucket consistently contributed approximately **30%** of total sales value.
- **Transaction Volume Concentration**: The number-of-sales analysis shows that the **₹300–₹499** bucket accounted for the largest share of transactions at approximately **29%–31%**, followed closely by the **₹500–₹699** and **₹700–₹900** buckets.
- **Value vs. Volume Difference**: Higher-value buckets contribute a larger proportion of total sales value than their corresponding share of transaction volume, highlighting the importance of higher-value transactions to overall sales.

### **Product Performance**
- **Strong Performance Across Four Products**: **PIZB0001, PIZB0002, PIZB0003, and PIZB0004** generated relatively similar total sales values, ranging from approximately **₹93,673 to ₹96,446**.
- **Top Product by Total Sales**: **PIZB0002** recorded the highest total sales value at approximately **₹96,446**, followed by **PIZB0003 (₹95,936)** and **PIZB0001 (₹95,451)**.
- **Underperforming Products**: **PIZB0005 (₹40,327)** and **PIZB0006 (₹17,135)** generated substantially lower total sales values than the other four products.
- **Average Sales Variation by Product**: Average sales values ranged from approximately **₹504 to ₹584**, with **PIZB0005** recording the highest average sales value despite its lower overall sales contribution.
- **Product-Level Performance Gap**: The difference between total sales and average sales across products indicates that product performance is influenced by both transaction value and sales volume.

### **Regional & Interactive Analysis**
- **Regional Sales Exploration**: The dashboard provides interactive analysis across **East, North, South, and West** regions through the Region slicer.
- **Filter-Dependent Sales Patterns**: Sales amount distributions, transaction volumes, product performance, and sales trends change across different regional filter selections, highlighting variations in sales behavior between regions.
- **Interactive Performance Analysis**: The Region slicer allows users to move from an overall view of CrustBite's sales performance to a more focused analysis of individual regional segments.
- **Business Decision Support**: Combining daily trends, transaction-value distributions, product comparisons, and regional filtering provides insights into sales patterns, product performance differences, and areas that may require further investigation.

## **Project Highlights**

* Developed a **fully interactive Excel finance dashboard** to provide a consolidated view of sales performance, transaction-value distribution, product performance, and daily sales trends.
* Adopted a **question-driven analytical approach**, using **PivotTables, PivotCharts, Slicers, and supporting calculations** to transform raw sales data into an interactive reporting solution.
* Analyzed **daily sales performance** through overall sales and average sales trends to identify fluctuations and changes in sales activity over the June–September analysis period.
* Conducted **sales amount bucket analysis** using **₹200 transaction-value ranges** to examine the distribution of total sales value and the number of sales across different transaction-value segments.
* Built **product-level sales analysis** to compare products based on total sales value and average sales value, highlighting differences in product performance.
* Implemented **interactive regional filtering through a Region Slicer**, allowing users to dynamically explore sales patterns across **East, North, South, and West** regions.
* Developed **comparative sales visualizations** combining overall sales and average sales across products to provide a broader perspective on product-level performance.
* Created **daily sales trend analysis** to examine fluctuations in overall sales and average sales throughout the analysis period.
* Designed a **single-page interactive dashboard** combining sales distributions, transaction-volume analysis, product comparisons, regional filtering, and time-based sales trends within a structured reporting layout.
* Applied a **clean and consistent visual design** with structured visualization panels, a cohesive blue-gray theme, interactive filter controls, annotations, and clearly organized analytical sections for intuitive exploration.
* Delivered a **scalable Excel-based analytical solution** that connects structured data preparation, PivotTable-based analysis, interactive filtering, visualization, and reporting within a single workbook.

This project demonstrates how **Microsoft Excel can be used to build an interactive finance and sales analysis dashboard**, combining PivotTables, PivotCharts, Slicers, and structured analytical workflows to transform transactional sales data into an accessible and decision-oriented reporting solution.
