# Nashville-Housing
Data Cleaning with MySQL on Nashville Housing Data

- I populated the property address and then broke out the address into individual columns (Address, City, State) to make it more readable, using the SUBSTRING and LOCATE statements.

- I continued to change Y's and N's to "Yes" and "No" using CASE statements.

- I removed duplicates using Row Number CTE. Moreover, I deleted some useless columns that offered nothing.


Notes:
I've also included the original file for that project.
Because I couldn't import .xlsx files to MySQL, I converted it to .csv file and then used the import wizard to make it happen.
