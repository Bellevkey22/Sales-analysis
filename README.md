# Analyzing Liquor Sales in Iowa: A Retail Supply Chain Project
![](https://github.com/Bellevkey22/Sales-analysis/blob/main/liquor%20sales%20image.jpeg)

# INTRODUCTION
ABC Liquors is a retail chain with stores across Iowa. They are looking to improve their sales and optimize their inventory management to reduce stockouts and improve profitability. To achieve this goal, they have hired a data analyst to analyze their sales data and provide insights.

# PROBLEM STATEMENT
* Analyze ABC Liquors' sales data to identify their top-selling products and brands, and the top-selling products and brands by store location.

* Identify any seasonal trends or patterns in sales, and suggest strategies to optimize inventory levels to reduce stockouts and improve profitability.

* Use the sales data to identify any gaps in ABC Liquors' product offerings and suggest new products or brands to add to their inventory.

* Create a dashboard to visualize the sales data and provide ABC Liquors' management with an at-a-glance view of their sales performance and inventory levels.


# SKILL DEMONSTRATED
* Data quality assurance
* Basic querying
* Filtering data
* Sorting data
* Aggregating data



# DATA SOURCE
we will be using a large and clean public dataset of retail sales data provided by the State of Iowa's Alcoholic Beverages Division within the Iowa Department of Commerce. This dataset contains every wholesale purchase of liquor in the State of Iowa by retailers for sale to individuals since January 1, 2012. Furthermore, this public dataset is hosted in Google BigQuery 
# DATA QUALITY TEST
1. Completeness Check : This means checking if all required data fields are filled in and if there are no missing values.


Query                       | Result
:-------------------------: | :----------------:
![](completeness_query.png) | ![](completeness_result.png)

<p> The number of missing values for price is negligible and can be worked with <p/>

2. Uniqueness Check : This means checking if there are any duplicate records or data points.


Query                       | Check                     | Result
:-------------------------: | :-----------------------: | :------------------------:
![](uniqueness_query.png)   | ![](uniqueness_check.png) | ![](uniqueness_result.png)
<p> There are no dulicate records<p/>

3. Validity Check : This means checking if the data values are in the correct format and type.


 
Result |
:----------------:|
![](validity_result.png)|
<p> They are in the correct format<p/>


4. Timeliness Check : This means checking if the data is up-to-date and relevant to the time period being analyzed


Query                       | Result
:-------------------------: | :----------------:
![](timeliness_query.png) | ![](timeliness_result.png)

<p> The dataset is up to date<p/>



# ANALYSIS & VISUALIZATION
1. Identifying top selling products and brands

# CONCLUSION & RECOMMENDATION
