This project involved cleaning orders dataset.


### Files:
- 'orders_dataset.xlsx' : Raw dataset
- 'cleaned_dataset.xlsx' : Cleaned dataset


### Cleaning Steps:
I cleaned this dataset in **Power Query**:


1. Loaded the source data into Power Query.
2. Merged the Order ID and Order Date columns.
3. Transposed rows and columns to correct the layout.
4. Promoted the first row to headers.
5. Filled down missing values in repeating fields.
6. Unpivoted other columns to get a tidy/long format.
7. Split a combined field (the Order ID and Order Date) into separate columns by delimiter.
8. Renamed new columns.
9. Re-applied correct data types to new column.
10. Removed unnecessary columns before final load. 
