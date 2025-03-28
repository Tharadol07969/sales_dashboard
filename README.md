# Threads-Ltd---Sales-Report

<h3 align="left">This report is about Threads Ltd(alias). The company operates across the island through a network of retailers and chain stores.</h3>
<h3 align="left">I downloaded this dataset from DataCamp and this is a data description:</h3>

- Orders Table → Stores sales data such as sales, cost of goods sold (COGS)
- Returns Table → List of products that have been returned
- Products Table → Details of each product type
- Retailers Table → Details of the retailer that ordered the product

<h3 align="left">1. I open Power BI Desktop and load the dataset to inspect and clean the data for making the report.</h3>
<img width="100%" height="auto" src="./1.jpg" />
<h5 align="left">I cleaned each table, so there are no duplicates in the primary key column and don't have errors and outliers for each table. And I found the order table is a fact table and has a foreign key to connect another dimension table. So I rename the table to FactOrders, DimProducts, DimRetailers, and DimReturns.</h5>
<h5 align="left">Now the data set is clean and ready for analysis and visualization. I closed the power query to go to the next step.</h5>

<h5 align="left">In to next step, I created a dimension date table to use the time intelligence function in DAX, display data continuously even if the fact table does not contain data for every day, and easier to set the format of day, month, quarter, year</h5>
<img width="25%" height="auto" src="./2.jpg" />
<h5 align="left">And created the relationship between the table and the data model.</h5>
<img width="75%" height="auto" src="./3.jpg" />

<h3 align="left">2. Time to create the report and visualization.</h3>
<h3 align="left">Here this is my result</h3>
<h3 align="left">This is the first page "Overview"</h3>
<img width="100%" height="auto" src="./4.jpg" />
<h5 align="left">You can see total revenue, total units sold, total profit,  profit margin by year, and YoY% Change on the top.</h5> 
<h5 align="left">On the left middle chart, you will see total revenue by monthly, and On the left bottom donut chart, you will see total revenue by country and channel.</h5>
<h5 align="left">And the bottom right chart you will see total revenue and total profit by category.</h5>
<h5 align="left">This page reports on annual sales. You can filter by year in the top right corner as shown in the image.</h5>
<img width="20%" height="auto" src="./5.jpg" />


<h3 align="left">Next is the second page "Product"</h3>
<img width="100%" height="auto" src="./6.jpg" />
<h5 align="left">This page has details about the products that Threads Ltd. company sells.</h5>
<h5 align="left">You can see total sales, units sold, cost, profit, profit margin, and YoY% Change.</h5>
<h5 align="left">You can filter by category of interest by clicking on the category and color on the left side of this page or clicking on the visual on this page.</h5>


<h3 align="left">And this is the final page "Channel"</h3>
<img width="100%" height="auto" src="./7.jpg" />
<h5 align="left">On this page, you will see the details about sales by country and channel.</h5>
<h5 align="left">And on the right table, you can see the total sales all about country, region, city. How are sales increasing or decreasing in each city?</h5>
<h5 align="left">You also can filter by country, channel, and category by clicking on the left side of this page to filter more insight data.</h5>

<h3 align="left">Finally, you can download my pbix file to see more details. Thank you for watching.</h3>
