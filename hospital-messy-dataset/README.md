## Excel Dataset Cleaning - Quantity Column

This project shows how I cleaned a messy column in Excel that contained both numeric quantities and units (e.g. '1.2Pcs', '2Tube','100Bottle'). I used **Power Query** and Excel formula to split them into two separate columns: one for numeric values (with 2decimal places) and one for units.

## Cleaning Steps Covered:
- Separated quantity values from units using Power Query's 'Text.Select()' function
- Formatted numeric values to always show two decimal places
- Converted text values to numbers for proper alignment
- General Excel formatting and data validation

## Tools Used:
- Microsoft Excel
- Power Query (M Language)
- Excel Formulas: 'TEXT()'

## Files Included:
- 'dataset_raw.xsls'_ the original messy dataset
- 'dataset_cleaned.xslx'-fully cleaned version

---
This is part of my data cleaning series using Power Query and Excel. More coming soon!
