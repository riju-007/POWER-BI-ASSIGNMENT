Modelling in Power BI
About Assignment 

You have been hired as a Power BI Developer for X Company. Your manager is struggling to get the data in the right format. The manager is asking to look into the data: 

The manager is finding various issues as follows:

1.	Data Understanding Issue: Your manager is finding it difficult to understand the empty and null percentages in the dataset.  He is also worried about the descriptive statistics (distribution) for all the top 1000 rows. You have been asked to show it in the power query. 
2.	Imputation of missing values: The data architect just informed your manager about a possible missing value with the column Region in the excel provided. He insisted on replacing all the missing values in Region with West. Now you are being asked to perform the data imputation. 
3.	Date Format issue: The data has been fetched from the European region’s server due to which the data format is of European standards dd/mm/yyyy. As the data is generated and relevant for the US time zone. Your manager is asking you to convert the date to US/Canadian format i.e mm/dd/yyyy. 
4.	Tax Slab Calculation: All the products sold(profit column) from the store are taxed with a standard tax slab of 2%. Your manager wants you to create a tax slab column so that it can be used for visualization. 
5.	Performance of Query: The manager also wants to have a check on the performance of the power query. So he is asking to generate the metric table as well. 

After completing your task. You have been requested to submit your .pbix file. 




Cardinality and Desktop Visualization

In continuation with the previous assessment, your manager requests you to add a couple of different tables to the existing dashboard. The manager is asking to look into the following requirements:

1.	Relationship between tables: The Manager asks you to add people and order tables into the dashboard. Make sure the order and sales tables need to have a cross filter between the tables. 

2.	Handling many to many relationships: The manager is finding difficulty with tables having many-to-many relationships. He is asking to create an intermediate table(also known as a bridge table) to handle the many to many relationship issues. 

3.	Create a Table visual on the report page: Your manager asks you to create a table using order quantity from the order table and sales from the sales tables. You have also been asked to check on the following conditions:
●	Whether the issue of many-to-many relationships arises with the created table? 
●	Apply the color gradient to values in the tables to identify the highest sales and lowest sales. Kindly use red color for minimum sales and green color for maximum sales.

4.	Create a Scatter Chart on the report page: You have been asked by the manager to create a scatter plot using sales and quantity information and represent it, which helps identify the highest and lowest sales using color.

5.	Play axis on the report page: Your manager wants you to apply the play axis on a date and see how the scatter plot changes from time to time. You also need to ensure that the play axis does not apply to the table you created. 

      After completing your task, you have been requested to submit your .pbix file.



Desktop Visualization


You are been hired as a Power BI Developer for X Company. Your manager is struggling to view the data according to his requirements. 

The manager is finding various issues as follows:

1.	Bar Chart Issue on page-1:Your manager is asking to create a drilldown on category and subcategory using a bar graph 
2.	Line Chart Issue on page 2: He also request you to create a line chart using sales, quantity and order date. Make sure the quantity is in secondary value. Kindly have a check that there need to be drilldown feature on the visual as well. 
3.	Gauge Chart with target issue on page 3: Your manager wants you to create a Sales gauge’s chart with 500000 as the sales target. 
4.	No Page navigator: Your manager needs you to create a page navigator to navigate one page to another. Feel free to use right arrow, left arrow and home button.  
5.	No Landing Page: You have been asked by your manager to create a landing page with page 1 to 3 (naming them as Bar Chart, Line Chart and Gaurge chart) buttons for navigation. After clicking which, it need to navigate us to other page. PFB the sample screenshot 
Submit the pbix file


DAX Expressions Part1


Your manager is struggling to get further insights which requires some Measures and Calculated Columns. Requirements are divided into Part1 and Part2. In continuation with the previous assessment, following are the new requirements of Part1 given by manager:

1.	GST Column: A calculated column called GST with an 18% tax slab on sales amount needs to be created on sales amount.
2.	Date difference column: A date difference column needs to be present that shows the delay between the order date and the ship date.
3.	Sales Buckets: You need to create sales buckets with the condition as follows:
a.	Sales lesser than 1000
b.	Sales between 1000 to 5000
c.	Sales between 5000 to 10000
d.	Sales between 10000-15000
e.	Sales between 15000 to 20000
f.	Sales above 20000
4.	Total Sales: A total sales measure with a filter segment = corporate is needed.
5.	multi-row card: You need to create a multi-row card with min sales, max sales, average sales, and mode.

After completing your task. You have been requested to submit your .pbix file.


DAX Expressions Part2


In continuation with the previous assessment, following are the new requirements (Part2) given by manager:

1.	Gross profit margin: You have to create a Gross profit margin measure using the formula (gross profit/net sales). Manager needs to see a matrix with the gross profit margin ratio for all the products and the matrix needs to be sorted from highest to lowest. 
2.	Segment-wise average sales: Manager wants to see segment-wise average sales. You have to create a table using group by function to identify the segment-wise average sales.
3.	Quick Measure: Manager needs a y-o-y % sales change, so he asked you to create accordingly. You have to create a quick measure.
4.	Cumulative Sales Measure: Manager needs to see cumulative sales, so you have to create it and plot it on the visualization. 
5.	3 days moving average or rolling mean: Manager asked you to create a table visual on the report page with the date, sales, and 3 days moving average or rolling mean. 
