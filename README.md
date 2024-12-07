# HR-Data-Analysis-Project
 
# Project Overview
I designed a Power BI dashboard with actionable insights to support the Atliq HR team in enhancing decision-making. The dashboard tracks key HR metrics, including employee data, attendance, sick leave, and work-from-home trends, thereby automating data analysis and saving time.

# Steps followed
Load Data:
* Import your attendance dataset from a CSV file into Power BI Desktop.

Transform Data:
* Clean and organize the data using Power Query Editor.
Duplicate the query and name it "template."
Select a specific sheet (e.g., Apr 2022) in the template.
Use the first row as the header and adjust column names.

Unpivot Dates:
* Consolidate dates into a single column, excluding "Employee ID" and "Name," using the unpivot option.

Format Date Column:
* Rename the consolidated column as "Date" and convert it to a date format, eliminating text values.

Append query :
* Append all sheet in One sheet and named it "Final" 
Load "Final" sheet into Power bi.
