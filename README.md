# Sales-Visualization-Automation-using-Power-Query-in-Excel
Project demonstrating sales data automation and visualization in Excel using Power Query.
Below are the steps that i done for this project -

****Step 1**: Data Loading**
Open Excel and go to the Data tab.

Choose Get Data > From File > From CSV and select your file (car-sales-extended-missing-data.csv).

This will open the file in Power Query Editor.

**Step 2: Data Cleaning in Power Query**
In Power Query, apply these cleaning steps to prepare the data:
Remove Empty Rows and Columns:

Delete any rows or columns with mostly empty values or those irrelevant to your analysis.
Handle Missing Data:

For columns with numerical data, you can replace missing values with the median or average of that column. Go to Transform > Replace Values > Replace Errors.
For categorical data, consider filling missing values with placeholders like "Unknown" or "Not Specified."
Change Data Types:

Ensure columns have the correct data types. For instance, sales values should be in numeric format, and dates should be in date format. Use the Data Type dropdown in Power Query for each column.
Remove Duplicates:

Go to Home > Remove Rows > Remove Duplicates to eliminate duplicate rows that might skew analysis.
Add New Columns (Optional):

You might want to create additional columns. For example:
Extract the month and year from any date columns to analyze seasonal trends.
Calculate metrics like total revenue or average sale price if not already present.
Filter Irrelevant Data:
Exclude any data points that are outliers or irrelevant to your analysis. Use Filter options to remove values outside a specific range.


**Step 3: Data Transformation**
Now, you can further transform the data to facilitate meaningful analysis:

Group By:
Use Group By to summarize data, e.g., calculate total sales by each car model or by month.
Pivot/Unpivot Columns:

If you need to reorganize the data, use Pivot Columns or Unpivot Columns to reshape it for specific visualizations or further calculations.
Calculate Sales Metrics:
Add calculated columns, like calculating the difference in sales month-over-month or year-over-year.


**Step 4: Load Data to Excel**
When you’re ready, click Close & Load to import the cleaned data back into Excel.


**Step 5: Data Visualization in Excel**
Use Pivot Tables and Pivot Charts to create interactive dashboards.
Add slicers for easy filtering by categories like car model, sales region, or sales representative.
Create visualizations, such as:
Line charts for sales trends over time.
Bar charts for total sales by model or region.
Pie charts for market share by category.
 
