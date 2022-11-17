# Sales-Forecasting-using-Linear-Regression-
Predection of next 12 week sales data with a RMSLE Score of 0.38
Problem Statement : 

One of the largest retail chains in the world wants to use their vast data source to build an efficient forecasting model to predict the sales for each SKU in its portfolio at its 76 different stores using historical sales data for the past 3 years on a week-on-week basis. Sales and promotional information is also available for each week - product and store wise. 

However, no other information regarding stores and products are available. So we need to forecast accurately the sales values for every such product/SKU-store combination for the next 12 weeks accurately.

Data Description

Variable | Definition

record_ID           | Unique ID for each week store sku combination
week                  | Starting Date of the week
store_id              | Unique ID for each store (no numerical order to be assumed)
sku_id                | Unique ID for each product (no numerical order to be assumed)
total_price        | Sales Price of the product
base_price       | Base price of the product
is_featured_sku | Was part of the featured item of the week
is_display_sku   | Product was on display at a prominent place at the store
units_sold          | (Target) Total Units sold for that week-store-sku combination


Evaluation Metric
The evaluation metric is 100*RMSLE (Root Mean Squared Log Error).
The basic objective is to implement the project with linear regression and comes up with as much accuracy we can . 
