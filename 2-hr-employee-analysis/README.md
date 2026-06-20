# HR Employee Analysis (Excel) 

## Project Overview 
Cleaned and analysed a messy HR employee dataset using Microsoft Excel Power Query and formulas

## Data Cleaning Steps 
- Removed invalid Phone column (all negative values)
- Split Department_Region into two separate columns
- Replaced N/A salary values with column average (£85,155)
- Filled missing Age values with average age (32)
- Verified Employee_ID uniqueness (no duplicates found)
- Email field identified as unreliable for deduplication

## New Skills Used 
- IF/Nested IF formulas to create Age Group and Salary Band
- Conditional Formatting to highlight Peformance Scores
- Power Query column splitting by delimiter

## Key Insights 
- DevOps is the largest department (189 employees, 19%)
- Sales has the highest average salary (£86,867)
- Finance has the lowest average salary (£82,274)
- Only 34% of employees are Active, 66% are Pending or Inactive, which is a significant business concern
- Salary distribution is relatively flat across departments (~£4,500 range)

## Data Limitations 
- Age and Salary missing values filled with averages
