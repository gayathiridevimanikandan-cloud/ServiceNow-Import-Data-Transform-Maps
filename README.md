# ServiceNow-Import-Data-Transform-Maps
## Description
Import employee data from an Excel spreadsheet into ServiceNow using Import Sets and Transform Maps.

## Steps
1. Created custom table Employee Test (u_employee_test)
2. Loaded Excel data into Import Set table Employee Import (u_employee_import)
3. Created Transform Map: Sample Spreadsheet Import
4. Enabled Coalesce on Employee ID to avoid duplicates
5. Re-imported data to verify Inserts, Updates and Ignored records
6. Created 3 reports: Employees by Department (Pie), Employees by Location (Bar), Employee List Report (List)
7. Created Employee Analytics Dashboard and added all 3 reports

