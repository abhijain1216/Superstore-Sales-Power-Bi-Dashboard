# Superstore-Sales-Power-Bi-Dashboard

### *Problem Statement*
Build a Superstore Sales Dashboard that aims to provide data-driven insights regarding sales and profit among various states and regions in the United States. The superstore seeks to achieve sustainable revenue growth and profitability through the effective use of the dashboard's insights.


### *Business Objective*
The business objective of the superstore sales dashboard is to increase sales and profitability by leveraging data-driven insights. Obtained insights will be helpful in making business decisions and planning market and advertisement strategies regarding future sales. This information will also be useful in identifying opportunities for growth and improvement, such as cross-selling, upselling, and product diversification. By utilizing the insights provided by the dashboard, the superstore aims to achieve sustainable growth and profitability.

### *Project Summary*
The Superstore sales dashboard utilized a Kaggle dataset to find business insights about sales and profit. The Sample Superstore Sales dataset provides sales data for the United States, including information on products, orders, and customers. The data was initially in denormalized form, underwent normalization, and was transformed into four tables: dimCustomer, dimProducts, dimShip, and factSales. Data preprocessing was done to ensure that the data was free from errors and ready for analysis. Irrelevant columns were removed, and the error in the date format was also handled effectively. A new dimDate table was created that contained all dates, and then additional date-related columns were generated. A measures table was also created to consolidate all measures. Data modeling was done to establish one-to-many relationships between the factSales table and the dimension tables, resulting in a star schema. Time intelligence functions were also utilized in our analysis that enable us to manipulate data using time periods, including days, months, quarters, and years, and compare calculations over those periods. The resulting dashboard featured various visualizations including bar charts, pie chart, cards, tables, area chart tool tip, slicers and filters. The superstore sales analysis project aimed to provide insights about sales and profit over years across product categories, segments, and regions. The insights that have been found from the dashboard will be helpful in making business and strategic decisions.



### *Dataset Information*
#### *Variable Description*

* **Row ID** - Unique ID for each row
* **Order ID** - Unique Order ID for each Customer
* **Order Date** - Order Date of the product
* **Ship Mode** - Shipping Mode specified by the Customer
* **Customer ID** - Unique ID to identify each Customer
* **Customer Name** - Name of the Customer
* **Segment** - The segment where the Customer belongs 
* **Country** - Country of residence of the Customer
* **City** - City of residence of of the Customer
* **State** - State of residence of the Customer
* **Postal Code** - Postal Code of every Customer 
* **Region** - Region where the Customer belong
* **Product ID** - Unique ID of the Product
* **Category** - Category of the product ordered
* **Sub-Category** - Sub-Category of the product ordered
* **Product Name** - Name of the Product
* **Sales** - Sales of the Product
* **Quantity** - Quantity of the Product
* **Profit** - Profit/Loss incurred

### *Dashboard*
<img width="525" alt="Superstore Sales Dashboard" src="https://github.com/user-attachments/assets/53a49eac-0135-4def-a422-46e5a61ecc17">

### *Data Model*
<img width="602" alt="Data Model" src="https://github.com/user-attachments/assets/248e2569-a7be-4eaa-bfd3-7aeeaffae1d6">



