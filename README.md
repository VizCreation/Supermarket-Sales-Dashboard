# Supermarket-Sales-Dashboard
This is a self-initiated project that showcases a Supermarket Sales and Profit Dashboard in Year 2021 and 2022.

## Problem Statement
1. What is the Total Sales and Profit by Year and Month?
2. Is the Total Sales increasing or decreasing compared Year-on-Year? 
3. What are the propertions of sales for the various Sales Channel?
4. Are most of the products bought in-store via Cash payment or online payment?
5. What is the top selling and bottom selling product? And how much sales do they bring in?
6. What is the Ranking of Products based on Sales
7. What is the most popular Product Category?

## Data Sourcing
The data set is retrieved from Youtube with the Channel called 'Lean Excel Solutions'. This channel aims to share knowledge that will help individuals improve their productivity & skills when using office application.
Youtube link: https://www.youtube.com/watch?v=CGgXHsD19Ek
Data Link: https://leanexcelsolutions.com/sales-dashboard-in-excel-power-bi/

## Data Transformation/Cleaning
Data was cleaned and transformed with the Power Query Editor in Power BI and by creating new measures using DAX and the 'Quick Measure' function. Some of the applied steps include:
* Merging the Main Data set with the Product Details table by linking the "Product ID"
* Creating new measures that calculates YoY% profit and YTD profit
* Creating new columns that calculates the "Total Selling Value" and "Total Buying Value"

## Data Visualisation

The first Dashboard is a practise Dashboard created by following the Youtube Instructor. Whereas the second Dashboard is a newly created Dashboard.

![Dashboard (practise)](https://github.com/VizCreation/Supermarket-Sales-Dashboard/assets/157504708/0b9c1bee-4101-4dc6-9b97-21fa5b56f582)


![Main Dashboard](https://github.com/VizCreation/Supermarket-Sales-Dashboard/assets/157504708/7a744104-939f-45ae-987b-e59be3dfd21e)


## Findings/Conclusion
1. The Total Sales and Profit in both years are $410k and $69k
2. The YoY profit is 127%, meaning that the Sales performance is better in 2022 compared to 2021.
3. The first Donut Chart shows that the highest Sales comes in the order of Direct Sales, Online and Wholesaler.
4. The second Donut Chart shows that Sales come almost equally from in-store purchase and online purchase.
5. Based on accumulated Sales in both years, the Top Selling Product is 'Product 41' and the Bottom Selling Product is 'Product 09'.
6. The Horizontal Clustested Bar Chart shows the ranking of Products by Sales (The top products are Product 41, 31, 42...)
7. The Pie Chart shows that the most popular product category is 'Category 04'.
