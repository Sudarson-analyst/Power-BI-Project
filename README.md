# RETAIL ANALYSIS DASHBOARD
## Project Overview
This Project is based on the Retail Industry by collecting the sample yearly sales data of a random company which contains various products and sales in various territories.
For more details you can download the retail analysis dashboard and interact with it.

## Problem Statement
Considering a scenario that a leading retail company is seeking to enhance its decision-making process and optimize its operations through data-driven insights. To achieve this goal, they aim to develop a comprehensive retail analysis dashboard that provides real-time and historical data visualization and analytics. The dashboard will serve as a central platform for monitoring key performance indicators (KPIs), understanding customer behavior, analyzing sales trends, and optimizing inventory management.
## Steps followed
### Data Collection and Preparation:

Identified all relevant data sources such as sales data, product data along with their category and subcategory , customer data and Marketing Territories data.
Extracted data from these sources in different formats such csv , from sql database and folders.
Transformed the data especially the currency in the form of US dollar , also checked the data and clean the data to ensure consistency, accuracy, and compatibility with Power BI. This may involve tasks like data type conversion, handling missing values, and merging queries of the tables.
### Modeling the Data:

Designed a data model that reflects the relationships between different entities in the dataset (e.g., sales, products, customers, calender etc ).
Create calculated columns and measures to derive new insights and metrics from the raw data.
Some of the calculated columns and measures are:

- First extracting the year,month,start of year,month name and start of week from the calendar dates
- Added columns in the customer table such as Customer Priority, Income level and their full name.
  
  ![Screenshot 2024-02-08 135200](https://github.com/Sudarson-analyst/Power-BI-Project/assets/159156381/20133995-0c83-4f4e-a75f-42adcf202356)


- Created new measures for data analysis and visualization like no of sales quantity,unique customers,Rolling profit by week, overall profit , total revenue and so on where you can check the pbix file I have attached.

  ![Screenshot 2024-02-08 132016](https://github.com/Sudarson-analyst/Power-BI-Project/assets/159156381/a1388c47-0022-4a3d-8bc1-f59d29d7332c)

- Data Modeling was done to create relationship between different tables with one to many cardinality which will usefull for specified outcome , for data model kindly check the pbix file.



### Designing the Dashboard:

Designed a dashboard containing of 6 pages in the Report View with specific name which consists of Retail Analysis Dashboard page,Customers Details page,Territories page,Product Details page ,Progit page for drill through and a tooltip for detailed visualization.

- These pages include the KPI displaying the Revenue,Orders,Profit,target,monthly revenue and monthly orders .The Line chart displays the weekly revenue ,Horizondal bar chart displays the no of sales of each category,also displays top 10 products and top ordered category.
- In the Customer Details page it displays the unique customers, average revenue per customer.The donut charts displays based on the occupation and income level of the customers.The line chart displays the weekly customers based on the calendar dates.The table displays the top 100 customers along with the specific details.
- In the Territories page, displays the map view where the sales is done along with the customised tooltip which I have made that gives the complete details of the sales.
- In the Product Details page, comprises of table displaying the top 1000 products filtered by the revenue,donut chart gives no of sales based on the product category,funnel chart gives the sales in value and percentage based on different colour of the products,the tree chart gives no of sales based on the product size.
- The drill through which profit page that well focused data on profit based of the product name and the last one the tooltip which is the customised one.


### Enhancing Interactivity:

For Interaction with different users I have managed the role by creating a view for bikes sales manager and Cloth sales manager.
Implemented interactive features like tooltips, cross-filtering to enhance the user experience and facilitate data exploration.
Configure dynamic filtering and sorting options to enable users to customize their views and focus on specific subsets of data.
Incorporate interactive elements such as buttons, bookmarks, and drill-through pages to navigate between different sections of the dashboard seamlessly.
