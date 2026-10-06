# Assignment-2--Data-Cleaning-and-Transformation
Data cleaning and transformation using Power Query and Excel, including missing value handling, category correction, column merging, data formatting, and conditional formatting
 Handled missing Price values by filling them with the median value using Power Query.
 Replaced missing Category values with “Unknown” using Power Query. 
 Cleaned the Product Name column by trimming extra spaces and standardizing capitalization using Power Query.
 Fixed typos in the Category column using Replace Values in Power Query.
 Removed duplicate rows using Power Query.
 Split the Product ID column into Manufacturing Date and Country Code using Power Query.
 Merged Brand Name and Product Name into a new Product Brand column using  Excel formula =[@[Product Name]]&"-"&[@[Brand Name]]
 Used the text format to convert the dates into the DD-MM-YYYY format =TEXT([@[DD-MM-YYYY2]],"DD-MM-YYYY")
 Formatted the Price column as currency using the Dollar ($) format in Excel.
 Applied a Data Bar to the Price column using Conditional Formatting in Excel.
 Created a custom Conditional Formatting rule to highlight “Electronics” in the Category column.
