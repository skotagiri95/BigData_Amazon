# BigData_Amazon

# Amazon_Reviews_ETL
Using PySpark to ETL tsv files from an AWS database and analyze it in PostgreSQL.

## Project Overview
PySpark was used to extract, transform, and load the two Amazon Reviews Datasources to be analyzed on PostgreSQL

1. Imported PySpark on to my Google Colab work environment.
2. Extracted the different tsv files onto the work environment.
3. Set the different StructField for each column, changing it to either StringType, IntegerType, or DateType.
4. Separated the columns and created four different DataFrames.
5. Created separate DataFrames from the vine_table.
6. Analyzed the vine_table DataFrames in PySpark.
7. Loaded the four DataFrames onto PostgreSQL.

## Analysis
For the PC Reviews there are 36,230 Vine reviews while for the Mobile Electronics Reviews there are 18 Vine Reviews.
