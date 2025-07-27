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

![image alt](

