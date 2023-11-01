# Home_Sales

#### Used PySpark and PySQL to determine key metrics about home sales data through completing the following steps:

- Read the home_sales_revised.csv data thats in a AWS S3 bucket into a Spark DataFrame.
- Create a temporary table called home_sales.
- Find the average price for a four-bedroom house sold for each year. 

<p align="center">
  <img src="images/4b.png" alt="images" width="600"/>
</p>

- Find the average price of a home for each year it was built that has three bedrooms and three bathrooms.

<p align="center">
  <img src="images/3b3b.png" alt="images" width="600"/>
</p>

- Find the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet.

<p align="center">
  <img src="images/3b3b2f.png" alt="images" width="600"/>
</p>

- Find the "view" rating for homes costing more than or equal to $350,000, and determine the run time for this query.

<p align="center">
  <img src="images/runtime1.png" alt="images" width="600"/>
</p>

- Cache my temporary table home_sales.
- Check if my temporary table is cached.
- Use the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000 and determine the runtime and compare it to uncached runtime.

<p align="center">
  <img src="images/runtime2.png" alt="images" width="600"/>
</p>

- Partition by the "date_built" field on the formatted parquet home sales data.
- Create a temporary table for the parquet data.
- Run the query that filters out the view ratings with an average price of greater than or equal to $350,000 and determine the runtime and compare it to uncached runtime.
- Uncache the home_sales temporary table.
- Verify that the home_sales temporary table is uncached using PySpark.

