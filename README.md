## Home Sales Project

**Objective Assessment:**
The project successfully followed the outlined instructions to analyze home sales data using PySpark and SparkSQL. Key tasks included data loading, query execution, caching, and performance comparison, demonstrating proficiency in working with large datasets in a distributed computing environment.

**Data Preparation and Processing:**

The dataset was imported from the provided AWS S3 bucket and read into a PySpark DataFrame.

A temporary table "home_sales" was created to facilitate SQL-based queries.

Data was partitioned by "date_built" and stored in a Parquet format for optimized querying.

**Key Analytical Insights:**

Average Price of Four-Bedroom Houses Sold per Year:

Successfully calculated and rounded to two decimal places.

Results provided insights into pricing trends across different years.

Average Price of Homes with Three Bedrooms and Three Bathrooms per Year Built:

Data extracted and analyzed to determine price fluctuations over time.

Average Price of Homes with Specific Criteria (3 Beds, 3 Baths, 2 Floors, ≥2000 sq ft):

Filtered dataset to meet specific housing criteria.

Results highlighted how structural attributes impact pricing trends.

Average Price per "View" Rating (Homes ≥ $350,000):

Computed and runtime recorded.

Identified view ratings correlated with higher home prices.

**Performance Optimization and Caching:**

The "home_sales" temporary table was cached, and query performance was evaluated.

Runtime for querying cached data was compared to uncached data, showcasing caching benefits.

The dataset was partitioned by "date_built," and queries were executed on the Parquet-formatted data.

Results were compared to previous executions, highlighting improvements in query efficiency.

**Final Validation Steps:**

The "home_sales" table was successfully uncached and verified.

The final Jupyter Notebook was uploaded to the GitHub repository, ensuring project reproducibility and accessibility.

Evaluation Against Key Criteria:

Spark DataFrame Creation ✅

Temporary Table Creation ✅

Correct Queries and Computations ✅

Performance Analysis and Caching ✅

Partitioning and Query Execution on Parquet Data ✅

Final Validation and GitHub Submission ✅

**Conclusion:**

This project effectively demonstrated the ability to:

Handle and process large datasets using PySpark.

Perform advanced SQL queries to derive meaningful insights.

Optimize performance through caching and partitioning.

Document and validate all analytical steps, ensuring reproducibility.

Overall, the project met all requirements, showcasing strong data analysis and performance optimization capabilities.
