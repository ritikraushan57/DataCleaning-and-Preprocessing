🧹 Sales Data Cleaning and Preparation Project

   This project demonstrates how to clean and prepare a raw sales dataset containing:

   - Missing values (nulls)

   - Duplicate rows

   - Inconsistent date formats

   - Text inconsistencies (case mismatches, extra spaces)

The goal is to transform messy data into a clean, analysis-ready dataset using Excel.

🗃️ Dataset Description

   - Column Name
     
   - Sale_ID	: Unique identifier for each sale
     
   - Customer_Name	: Name of the customer (contains nulls & extra spaces)
     
   - Product :	Product sold
     
   - Quantity	: Number of items sold (some nulls)
     
   - Price	: Price per unit
     
   - Date :	Sale date (inconsistent formats)
     
   - Payment_Method :	Payment mode used
     
   - Status	: Sale status (case inconsistencies)

🔧 Steps for Data Cleaning

   - Remove Duplicates → Data > Remove Duplicates.

   - Handle Nulls:

   - Fill blank Quantities with default value '1'.

   - Delete rows with missing Customer Names.

   - Standardize Date Format → Data > Text to Columns > Convert to DD/MM/YYYY.

   - Normalize Text Case:

   - Use =PROPER(), =UPPER() functions.

   - Trim Extra Spaces → =TRIM(A2).

   - Delete Empty Rows → Filter Blanks → Delete.

📝 Cleaning Summary
   - Removed 22 duplicate rows.
     
   - Filled 145 blank Quantity cells with default value '1'.
     
   - Deleted 49 rows with missing Customer Names.
     
   - Standardized all Date formats to DD/MM/YYYY.
     
   - Normalized text casing in Status and Payment Method columns.

🛠️ Tools Used
Microsoft Excel

