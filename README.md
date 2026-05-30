# Sales-Report-Analysis-Assignment-2

# Description
Performing basic data exploration in Excel transforms a raw product dataset into actionable insights.
In this assignment, Excel’s data cleaning techniques, formatting tools, and transformation operations are used to prepare the dataset for analysis.
The focus of this assignment is on handling missing values, correcting inconsistencies, removing duplicate records, restructuring columns, and applying formatting rules to improve the usability and readability of the dataset. 

# What was performed in this assignment?
Used  basic Data cleaning and Preparation techniques in Product I'd, Product Name, Brand Name, and Category.
* Did average function for missing values in the price column.
      Formula --> price blank =IF(ISBLANK([@[Price ($)]]),AVERAGE([Price ($)]),[@[Price ($)]])
* Found the blanks and replaced them with the existing category, which has the same product name in the Category field using the filter arrow.
* Removed the space between some Product names by find and replace. And capitalized the First letter only.
* Found the same category with a different spelling and replaced it with one proper name [Electroni to Electronics].
* 3 duplicate product id's were removed (21-AUG-CA, 16-APR-ES, 17-JUN-IN) using Remove Duplicates option in Data Tab.
* * Product I'd column was split into two columns.							
        Using the Left function, the Manufacturing date column is created.							
        Using the right function, the country code column is created.							
* Merged the Brand Name and Product Name Columns into one column and named it Product Brand							
                    Formula -->  [@[Product Name]]&" "&[@[Brand Name]]							
* The data type of the "Price" column was converted to a currency format.  							
* Assumed that the Manufacturing year is 2026 and the manufacturing date format is converted to DD-MM-YYYY format.							
* Data bar conditional formatting is applied in the "Price" column.     							
* Using conditional formatting --> highlight cells rule is used in the "Category" column, a category named "Electronics" is highlighted.
