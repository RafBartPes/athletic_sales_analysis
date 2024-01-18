# athletic_sales_analysis

## Module_5
import pandas as pd

## Combine and Clean the Data
   
Read the CSV files into DataFrames.
Display the 2020 sales DataFrame
Display the 2021 sales DataFrame
Check the 2020 sales data types.
Check the 2021 sales data types.
Combine the 2020 and 2021 sales DataFrames on the rows and reset the index.
Check if any values are null.
Check the data type of each column
Convert the "invoice_date" to a datetime datatype

2. Determine which Region Sold the Most Products - using group by and pivot table
   
# Show the number products sold for region, state, and city.
# Rename the sum to "Total_Products_Sold"
# Show the top 5 results.
# Show the number products sold for region, state, and city.
# Rename the "units_sold" column to "Total_Products_Sold"
# Show the top 5 results.

3. Determine which Region had the Most Sales - using pivot table and groupby

Show the total sales for the products sold for each region, state, and city.
# Rename the "total_sales" column to "Total Sales"
# Show the top 5 results. using pivot table and groupby

4. Determine which Retailer had the Most Sales - using pivot table and groupby
   
Show the total sales for the products sold for each retailer, region, state, and city.
# Rename the "total_sales" column to "Total Sales"
# Optional: Rename the "total_sales" column to "Total Sales"
data_2020_2021_r_total.head()

5. Determine which Retailer Sold the Most Women's Athletic Footwear  - using pivot table and groupby
   
# Filter the sales data to get the women's athletic footwear sales data.
# Show the total number of women's athletic footwear sold for each retailer, region, state, and city.
# Rename the "units_sold" column to "Womens_Footwear_Units_Sold"
# Show the top 5 results.

6. Determine the Week with the Most Women's Athletic Footwear Sales - using pivot table and groupby
   
# Resample the pivot table into weekly bins, and get the total sales for each week.
# Sort the resampled pivot table in ascending order on "Total Sales".
