# Maven Toy Store Business Analysis

## Project Overview
This analysis evaluates sales and inventory data from Maven Toy Store, a toy retail chain in Mexico.
Using Microsoft Power BI, key insights were derived on product profitability, store performance,
seasonal trends, and inventory management. Findings revealed that Toys and Electronics drive the
highest profits, with Downtown stores performing best. Sales peak between March and July, while
October sees the lowest revenue. Inventory analysis indicates stock will last 15-17 days.
Recommendations include optimizing inventory, investing in high-performing locations, and
addressing seasonal sales fluctuations to enhance profitability and business growth.

![image alt](https://github.com/zulaiiiiikha/Power-Bi-Project/blob/b28b1de0036cb2701ced570c45bb2ba01af9b298/Screenshot%202025-07-27%20132649.png)

## Table of Content
- [Project Overview](#project-overview).
- [Objective](#objectives)
- [Key Business Questions](#key-business-questions).
- [Tools and Methodologies](#tools-and-methodologies)
- [Data Processing_](#data-processing).
- [Data Modeling](#data-modeling)
- [Key_ Insights](#key-insights)
- [Summary & Recommendations](#summary-&-recommendations).
- [References ](#references).

## Objectives of the Analysis
The primary goal of this analysis is to generate actionable insights into Maven Toy Store's overall sales
performance and profitability by evaluating:
1. Store location performance
2. Seasonal sales trends
3. Product profitability and sales effectiveness
Based on these findings, recommendations will be provided to optimize business strategies.

## Key Business Questions
1. Which product categories yield the highest profits, and how do these trends vary across
different store locations?
2. Are there identifiable seasonal sales patterns?
3. What is the company's current market reach in terms of store distribution and geographic
presence?
4. What is the total inventory value, and how long can it sustain current sales levels?
5. Which stores perform best and worst in terms of revenue and profitability?

## Tools and Methodologies
**Tool Used:** **Microsoft Power BI** [website](https://www.google.com/search?q=power+bi&rlz=1C1ONGR_enNG1157NG1157&oq=pow&gs_lcrp=EgZjaHJvbWUqCggBEAAYsQMYgAQyBggAEEUYOTIKCAEQABixAxiABDIKCAIQABixAxiABDINCAMQLhjUAhixAxiABDIQCAQQLhiDARjUAhixAxiABDIGCAUQRRg8MgYIBhBFGDwyBggHEEUYPNIBCDMyMzhqMGo3qAIAsAIA&sourceid=chrome&ie=UTF-8)

## Techniques
1. Data Cleaning & Transformation using Power Query
2. Data Modeling to establish structured relationships between tables
3. DAX Implementation for advanced calculations and metrics
4. Data Visualization for interactive and insightful dashboards
5. Comprehensive Project Documentation for clear reporting of insights

 ## Data Processing
 
### Data Importation and Cleaning
Importation Process: Data was ingested using Power BI’s Excel connector.

### Cleaning Steps:
- Promoted headers for consistent column naming.
- Converted ID columns from whole numbers to text (as they serve as unique identifiers ratherthan numerical values).
- Added calculated fields for total product cost, total product price, and profit in the salesdataset.
- Corrected data types to ensure consistency.
- Trimmed redundant store names in the Stores Table for clarity.
- Created a Dates Table using CALENDARAUTO() to facilitate temporal analysis, extractingyear, quarter, month, and day attributes.

## Data Modeling
Effective data modeling structures raw data into an analytical framework, allowing seamless relationship-building between tables. In this project, Power BI automatically identified table relationships, forming a **star schema model**

![image alt](https://github.com/zulaiiiiikha/Power-Bi-Project/blob/5fb18be9924c691d2238f6f1e7d41c78c5be6925/Screenshot%202025-07-27%20132533.png)


1. Fact Table: Sales Table, Inventory
2. Dimension Tables: Products, Stores, and Dates

## Key Insights and Recommendations

### Product Analysis
1. **Which product categories generate the highest profits?**
- Toys are the most profitable, contributing $1.08M (26.89%) of total profits.
- Electronics follow closely with $1M (25%).
- Sports & Outdoor products generate the lowest profit at $500K.
  
2. **Are these profit trends location-dependent?**
- Electronics dominate in Airport and Commercial locations.
- Toys perform best in Downtown and Residential areas.
  
3. **Top Performing Products**
Highest Profit-Generating Products:
- Colorbuds - $835K
- Action Figure - $348K
- Lego Bricks - $298K
- Deck of Cards - $252K
- Glass Marbles - $190K

4. **Most Sold Products**
- Colorbuds - 104K units (23.5%)
- Playdoh Can - 103K units (23.2%)
- Barrel O’Slime - 91K units
- Deck of Cards - 84K units
- Magic Sand - 61K units

![image alt](https://github.com/zulaiiiiikha/Power-Bi-Project/blob/65b794243d3d989a07d75eab1c91883553555410/Screenshot%202025-07-27%20132817.png)

**Notably, Playdoh Can ranks high in sales volume but not in profitability.**

### Store & Location Analysis
1. Which locations generate the highest profits?
- Downtown stores lead with over $2M in profits.
- Airport stores yield the lowest profit at $378K.
### Most Profitable Stores:
- Maven Toys Ciudad de Mexico 2 - $170K
- Maven Toys Guadalajara 3 - $121K
- Maven Toys Ciudad de Mexico 1 - $111K
- Maven Toys Monterrey 2 - $107K
- Maven Toys Toluca - $105K
### Least Profitable Stores:
- Maven Toys Cuernavaca 1 - $57K
- Maven Toys La Paz 1 - $57K

## Seasonal Trends & Patterns
1. **Peak Sales & Profits:** March–July
- Highest Sales: April (112K units)
- Highest Profit: March ($406K)
2. **Lowest Sales & Profits:** October
- Sales: 48K units
- Profit: $179K
3. **Quarterly Trends:**
- Q2 (April–June): Highest sales
- Q4 (October–December): Lowest sales
3. **Yearly Trends:**
- 2017: Sales peaked towards year-end.
- 2018: Stronger sales from February–July, with March leading

### Inventory Analysis
**Current Inventory Value & Turnover:**
- Total Inventory Value: $300K
- Total Stock: 29,742 units
- Average Daily Sales: 1,709 units
- Estimated Inventory Duration: 15-17 days before restocking is required.

## Summary & Recommendations
**Summary of Key Findings:**
1. Downtown stores are the most profitable.
2. Toys lead in profitability, followed by Electronics.
3. Sales dip in January, February, and October.
4. Electronics excel in Airport and Commercial locations, while Toys dominate Downtown and Residential areas.

## Strategic Recommendations:
1. Expand investment in Downtown stores to capitalize on high profitability.
2. Investigate low sales in January and February to identify and mitigate potential market challenges.
3. Enhance inventory management to avoid stock shortages or excesses, ensuring optimal stock levels.

## References
[Maven Toys Store Dataset](https://docs.google.com/spreadsheets/d/1GHRe0HFl8ZY0bghU87J6UYAFAQn_LLob/edit?usp=drive_web&ouid=116393543067864627875&rtpof=true)
