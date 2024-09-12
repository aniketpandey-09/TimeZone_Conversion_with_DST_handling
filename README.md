# TimeZone_Conversion_with_DST_handling
This PySpark script processes sales order data, converts timestamps into multiple European time zones, and partitions the data by year and month. The data is then saved into separate Delta tables based on the year and month.

## Prerequisites
Apache Spark with PySpark installed.
Sales order data stored in a CSV file with columns such as SalesOrderID, OrderQty, ProductID, and ModifiedDate.

## How To Use The Code 
- Upload the File into the DBFS
- Import the functions required for the timezone conversions
- Convert the timezone to UTC by adding a column 
- Convert the UTC column into another columns for European timezones
- Divide the table into different tables by year and month and store them as delta table. 
