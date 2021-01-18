# Movies-ETL
Extract, Transform &amp; Load

Using ETL to clean data files, parse the data that we extracted to make it look how we want. Merge parsed data sets and load the merged sets into pgadmin for further use.

## Step 1:

-- Using the ETL_function_test file by step:

1. Created a function to read in three seperate files
2. Read in the Kaggle metadata and MovieLens ratings CSV files as Pandas DataFrames.
3. Opened the Wikipedia JSON file and use the json.load() function to convert the JSON data to raw data.
4. read in the raw Wikipedia movie data as a Pandas DataFrame.
5. use the code provided to return the three DataFrames.
6. use the variables provided to create a path to the Wikipedia data, the Kaggle metadata, and the MovieLens rating data files.
7. set the three variables in Step 6 equal to the function created in Step 1.
8. set the DataFrames from the return statement equal to the file names in Step 6. In this step, you are reassigning the variables created in Step 6 to the variables in the return statement.

Now to view that all our dataframes are correct:
