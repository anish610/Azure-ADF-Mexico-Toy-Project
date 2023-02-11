# Azure-ADF-Mexico-Toy-Project

I worked on a ADF project using Mexico Toy Dataset.

Steps - 

1- Configured Azure Blob storage,  ADLS Gen2, ADF instance, Azure SQL instance in Azure.

2- Loaded Mexico Toy Dataset Raw files in Azure Blob storage

3- Used CopyData Activity to move data to ADLS Gen2 folder

4- Used Dataflow to for Data Cleaning and adding conditional column Columns.
	
	4.1- Data Cleansing - 
		a. Null value check
		b. Date format check
		c. Data Types
	4.2- Data Transformation
		a. Join Operation
		b. New columns based on condition

5- Loaded Processed Data in ADLSGen2 Folder using Copy data Activity

6- Used Create scripts to create tables in Azure SQL Database

7- Used copy data activity to load data from ADLSGen2 folder to Azure SQL

![alt text](https://github.com/anish610/Azure-ADF-Mexico-Toy-Project/blob/main/Project%20Flow.png)

![alt text](https://github.com/anish610/Azure-ADF-Mexico-Toy-Project/blob/main/Dataflow1.png)










