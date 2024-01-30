# Data-Cleanup-SQL

## Overview
This project focuses on cleaning up a dataset containing housing information in Nashville. The cleaning process involves multiple SQL queries to address specific data format issues and improve the overall structure of the dataset.

## Key Steps
--Adjusting Data Types: The saleDate column's data type is changed from datetime to date for consistency.
--Populating Missing Property Addresses: Addresses with null values are populated by matching equivalent ParcelID values.
--Separating Property Addresses: The PropertyAddress column is split into separate columns using a comma as the delimiter.
--Separating Owner Addresses: Similar to property addresses, the OwnerAddress column is split into separate columns for better structure.
--Standardizing the SoldAsVacant Values: 'Y' and 'N' values in the SoldAsVacant column are replaced with 'Yes' and 'No'.
--Removing Duplicate Rows: Duplicate rows in the dataset are removed.
--Deleting Unused Columns: Several unwanted columns such as OwnerAddress, TaxDistrict, and PropertyAddress are removed.

##Run
1. Ensure you have access to the SQL Server database containing the Nashville housing dataset.
2. Execute the provided SQL queries in the specified order to clean and enhance the dataset.
