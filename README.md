# Module-22-Big-Data

First I created a Spark dataframe from the provided S3 dataset and then made a temporary view of the table. Then to test the dataframe, I ran the provided four sql queries. For the fourth query, I determined the run time, for future reference and comparison.

I cached and verified the temporary table, and using this cached data, ran the fourth query again to compare against the uncached runtime. Then using parquet and partitioning on the "date_built" column, I created another temporary table and ran the fourth query again to compare against the uncached runtime.

To conclude, I uncached and verified the temporary table.