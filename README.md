**TechnoEdge HR Analytics Dashboard — Power BI Project**

Built a comprehensive HR analytics dashboard for TechnoEdge using Power BI, visualizing and analyzing workforce data from 2020-2022. The project includes employee details, departmental insights, attendance, experience, age groups, salary trends, and workforce diversity. Integrated advanced data cleaning steps and business intelligence techniques to support HR decision-making.

**Key Features & Steps**

•	Data Cleaning in Power Query

•	Appended yearly sales tables (2020-2022) into one unified table using "Append Queries".

•	Changed column data types with "Transform Data" for consistency (e.g., salary to number, date to Date/Time).

•	Capitalized names by recreating the Employee Name column using "Replace Values" and text transformations.

•	Identified and removed duplicate rows with "Remove Duplicates," documenting the count for dataset quality.

•	Created a conditional column to classify experience levels: Fresher, Junior, Senior, based on salary bands.

•	Merged Employee Attendance into Employee Details on Employee ID using "Merge Queries" for consolidated analysis.

•	Calculated age using Power Query functions: subtracting Birthdate from today's date, converting duration to years.

•	Extracted years from date columns using "Date.Year" transformation for time-based analysis.

•	Geographical Data Model

•	Categorized location fields (city, country, state, region) for dynamic map visuals and easy filtering.

**Dashboard Visuals**

•	KPI Cards displaying: Total employees, average salary, and department count.

•	Pie and Donut Charts: Show salary distribution by experience level and age group.

•	Line and Bar Charts: Track yearly salary trends and employee count.

•	Slicers/Filters: Enable interactive data exploration by country, gender, department.

•	Tables: Present detailed salary and department breakdowns per employee.

•	Stacked and Clustered Charts: Illustrate departmental headcount and yearly gender-wise attendance.

