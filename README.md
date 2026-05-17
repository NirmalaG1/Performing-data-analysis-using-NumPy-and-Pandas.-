# Performing-data-analysis-using-NumPy-and-Pandas.-
● Work with NumPy arrays for numerical computations  ● Use Pandas Series and DataFrame for data manipulation and analysis  ● Apply indexing, slicing, filtering, and aggregation techniques  ● Understand real-world data handling through temperature and transaction datasets



Numpy Array Operations:  

created 1D and 2D arrays 
 Inspected the shape, data type, and the number of elements in the array
 Found the maximum, minimum, and mean of the arrays 
 performed slicing and indexing based on instructions.

 Pandas Series:  
 Created a Pandas Series named marks with the following data:  
➢ Marks: 95, 92, 89, 85, 80  
➢ Custom Indices: 'Rank1', 'Rank2', 'Rank3', 'Rank4', 'Rank5'  
 performed indexing and slicing using loc and iloc accessor and manipulated series as per instructions.

 Pandas DataFrame: 
 Created a Pandas DataFrame named transactions with the following data: ➢ 
TransactionID: 101, 102, 103, 104, 105, 106, 107, 108, 109, 110  
➢ ProductCategory: 'Electronics', 'Clothing', 'Electronics', 'Furniture', 'Clothing', 
'Electronics', 'Furniture', 'Clothing', 'Furniture', 'Electronics'  
➢ Region: 'North', 'South', 'North', 'East', 'West', 'North', 'East', 'West', 'South', 
'North'  
➢ Amount: 200, 150, 300, 450, 200, 250, 300, 180, 350, 400  


● Displayed the transactions DataFrame and its basic information, including head, tail, 
shape, column names, and data types.  
● Displayed only the 'ProductCategory' and 'Amount' columns.  
● Retrieved the last 3 columns of the DataFrame using iloc or loc.  
● Filtered  rows where the 'Region' is 'North' and 'Amount' is greater than 200.  
● Found the value counts for the 'ProductCategory' column.-used value_counts()  
● Found the unique values in the 'Region' column.  -used unique()
● Grouped by 'Region' and found the mean amount for each region. -groupby and mean()

Manipulating the DataFrame:  
●  Modified the 'Amount' for the transaction with TransactionID 102 to 165.  -used loc and replaced
● Added a new column 'Discount' by calculating 10% of the 'Amount'. 
●  Removed the row with TransactionID 109.  -identified index using loc and removed by drop()
●  Deleted the 'Discount' column from the DataFrame. -using drop()
