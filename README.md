# Home_Sales

### Overview
This repo contains an analysis of home sales data located in 'Home_Sales.ipynb'. The data was read into python and aggregated using PySpark.

### PySpark/Java Compatibility Error
There appears to be a compatibility error when trying to work with parquet files in PySpark. I took multiple steps to try to resolve this and had no success. Solutions I tried included:
- Using Java versions 8, 17, 21, and 22
- Downloading Spark version 3.5.1 and 3.4.3
- Downloading PySpark 3.5.1 and 3.4.1
- Trying all of these in different combinations
- Editing and ensuring correct environmental variable paths

None of these resolved my error on my Windows 10 pc. I plan to continue troubleshooting this, however the code provided in Home_Sales.ipynb should be correct and run without error on a machine without these compatibility issues.

### References
The data and starter code was provided by edX Boot Camps LLC.
