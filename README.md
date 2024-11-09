# Superstore Dataset

[Project Overview](#project-overview)

[Data Source](#data-source)

[Metrics of Focus](#metrics-of-focus)

[Tool Used](#tool-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Summary](#data-summary)

[Visual Insight](#visual-insight)

[Findings](#findings)

[Recommendation](#recommendation)


### Project Overview
----------------------------------------------------------------------------------------
The aim of this project is to analyze the  sales performance of a superstore giant over the past years. By analysising various aspect of the data, I seek to identify the products, regions, categories and customer segments they should target or avoid, make data driven reccommendation and gain deeper understanding of the store performance


### Data Source
-------------------------------------------------------------------------------------
The primary dataset used for this analysis is the "superstore dataset.csv" file and this is an open source daata that can be freely downloaded from Kaggle

This dataset include the following column:

Row ID - Unique ID for each row

Order ID - Unique Order ID for each customer

Order Date - Order date of the product

Ship Mode - Shipping mode specified by the customer

Customer ID - Unique ID to identify each customer

Customer Name - Name of the customer

Segment - The segment where the customer belongs

Country - Country of residence of the customer

City - City of residence of the customer

State - State of residence of the customer

Region - Region where the customer belong

Product ID - Unique ID of the product

Category - Category of the product ordered

Sub-Category - Sub-Category of the product ordered

Product Name - Name of the product

Sales - Sales of the product

Quantity - Quantity of the product

Discount - Discount of the product

Profit - Profit/Loss incurred


### Metrics of Focus
------------------------------------------------------------------------------------

1. Revenue Growth Rate
2. Profit Margin
3. Average Order Value
4. Customer Segment


### Tool Used
----------------------------------------------------------------------------

- Excel: 
  - Data Cleaning and Preparation
  - Data Analysis
  - Data Visualization
  - Creating Report


### Data Cleaning and Preparation
----------------------------------------------------------------------------

In the initial stage, I performed the following task:
1. Data Loading and Inspection
2. Data Cleaning and Formating


### Exploratory Data Analysis
--------------------------------------------------------------------------

EDA involves exploring the sales data to answer key questions, such as;
  1. What is the overall sales trends?
  2. Which products are top sellers?
  3. What is the regional performance?
  4. Which product has the lowest profit

### Data Summary
------------------------------------------------------------------------

Data Summary using pivot table

*CATEGORY PERFORMANCE*

![Superstore](https://github.com/user-attachments/assets/1263b5b9-58a7-471a-aa0d-0115f4617104)

*SUB-CATEGORY*

![superstore 1](https://github.com/user-attachments/assets/28f46bb3-26cf-454d-9930-022a889e77c9)

![superstore 5](https://github.com/user-attachments/assets/7a519b27-a1e9-4514-937a-200165850014)

*CUSTOMER SEGMENT*

![superstore 2](https://github.com/user-attachments/assets/8d0f98de-ceaf-40c4-807d-0d4dfc362ebd)

*REGION*

![superstore 3](https://github.com/user-attachments/assets/540dfcfa-9fdb-4e21-ae41-7e14b4b16e16)

![superstore 4](https://github.com/user-attachments/assets/60b20b87-feed-4b21-a7f2-330d23ed8b23)

### Visual Insight
------------------------------------------------------------------------

**CATEGORY PERFORMANCE**

![superstore visual](https://github.com/user-attachments/assets/fc62d873-0b39-4b5b-b7da-2e5d86a8a598)

**SUB-CATEGORY PERFORMANCE**

![superstore v1](https://github.com/user-attachments/assets/60bd25e8-b4f3-4873-b31f-5903352cbdb1)

![superstore v4](https://github.com/user-attachments/assets/9fdb4717-d256-4955-a20c-92d77c447c49)

**CUSTOMER SEGMENT PERFORMANCE**

![superstore v2](https://github.com/user-attachments/assets/3d3c9239-259b-4f46-9e71-e37d09de7cb6)

**REGIONAL PERFORMANCE**

![superstore v3](https://github.com/user-attachments/assets/7ac691e0-7707-4aff-a479-f5492b909f0b)




### Findings
---------------------------------------------------------------------------------

Category Analysis

*Top Performing Category by Revenue*

  1. Furniture: 742,000

  2. Office Supplies: 719,047

  3. Technology: 836,154  (Least Performing Category by Sales)

*Top Performing Category by Profit*

  1. Technology: 145,455

  2. Office Supplies: 122,491

3. Furniture: 18,451  (Least Performing Category by Profit)



Product Analysis

*Top Performing Product by Sales*

  1. Chairs: 328,449  (Category-Furniture)

  2. Phones: 330,007  (Category-Technology)

  3. Tables: -206,966 (Least Performing Product by Sales) (Category-Furniture)

*Top Performing Product by Profit*

  1. Copiers: 55,618 (Category-Technology)

  2. Phone: 44,516   (Category-Technology)

  3. Fasteners: 950 (Category-Office Supplies) (Least performing product by profit)



Customer Segment Analysis

  1. Consumer: 1,161,401 ...... 134,119

  2. Corporate: 706,146 ....... 91,979

  3. Home Office: 429,653 ...... 60,299 ( Least performing customer segment by sales and Profit)



Regional Analysis

  1. West: sales = 725,458, Profit = 108,418

  2. East: sales = 678,781, profit = 91,523

  3. South: sales = 391,722, profit = 46,749

  4. Central: sales = 501,240, profit = 39,706 (Top perfroming region by sales ans the least performing region by profit)



### Recommendation
-----------------------------------------------------------------------

TARGET
- For Product: Copiers, Phones, Accessories, Binders and Paper
- For Category: Technology and Office Supplies
- For Customer Segment: Customer and Corporate
- For Region: West and East


AVOID
- For Product: Tables, Bookcases, Supplies, Fasteners, Machines
- For Category: Furniture
- For Customer Segment: Home Office
- For Region: Central



