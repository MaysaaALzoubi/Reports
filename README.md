Sales Report
This report helps the company to understand the sales better. It helps the company which category, sales method or region has the high and low total sales. It also lets them know total quantity, number of order and YoY% values.

Steps followed
Step 1 : Load data into Power BI Desktop, dataset is a csv file.

Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.

Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".

Step 4 : It was observed that in none of the columns errors & empty values were present, so apply and load data.

Step 5 : Create empty table to store all mwasures these calculated by DAX formula.

Step 6 : In order to represent Data and measures, a new visual was added using the three ellipses in the visualizations pane in report view.

Step 7 : Add dynamic title change when use year slicer.

Step 8 : Add two cards one representing total sales and total sales LY & other representing YoY% and total quantity.

Step 9 : Add two slicers one to filter data by year and other to filter data by month.

Step 10 : Use visual level filter from the filters pane, advance filtering was used and blank values are ignored.

Step 11 : Use clustered bar chart to know different between total sales YTD and total sales YTD_LY values.

Step 12 : Use line and clustered column chart to analysis total sales and number of order by category and there was observed an inverse proportion between total sales and the number of orders.

Step 13 : Use pie chart to analysis total sales by method sales where the high sales by retail method and the low sales by door to door method.

Step 14 : Use gauge chart to analysis total sales LM and total sales MTD

Step 15 : Create KPIs to track total sales and total sales LY by year.

Step 16 : Create KPIs to track total sales and total sales MTD by month name.

Step 17 : Create map to know the high and low total sales and total quantity by region, find the high total quantity and high total sales in San Francisco & low total quantity and low total sales in Seattle.

Step 18 : Analysis the values ( total sales, total quantity and average price by category and product ) with using matrix chart, find high total sales and high average price for the Bikes category & high total quantity it has been sold components category where low total sales for the clothing category, low average price for the components category & low total quantity it has been sold Bikes category.

Step 19 : Use line chart to analysis total sales by year and quarter, apply predictive analysis (forecast) for two years in the future.

Step 20 : Use scatter chart to analysis total sales and number of order by region, apply predictive analysis (clustered) for two clusters.

Step 21 : Make report responsive with mobile screen.
