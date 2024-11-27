java c
Department of Accounting and Business Analytics
BTM 211
Management Information Systems
BA Assignment – Fall 2024
Case Study: Joshua Tree Instruments
Background
Joshua Tree Instruments (JTI) has been the top choice for musical instruments rentals in Alberta since 1987. What started as a hobby for Brian Edge, an avid guitar collector and rock enthusiast, slowly turned into a business. Now, Brian has expanded and carries the top brands in musical instruments.
After opening his first retail location in south Edmonton, Brain opened six more stores, another in northern Edmonton, two in Calgary, one in Grande Prairie, one in Red Deer, and his most recent expansion, a store in Lethbridge. With 90 employees spread out across his locations, JTI has been able to serve the Albertan community with pride and hopes to one day expand into other provinces on the Western coast while maintaining their reputation of carrying the biggest brands in instruments and the highest quality of rentals.
Problem
Brian Edge has expressed interest in using business analytic software to visualize his data. He needs four (4) visuals to express his repairs, revenue, customer, and employee data. He also wants you to include another visual of your choice that will provide JTI with additional insights into their business operations..
Requirements
Working individually, use Tableau to build a data analytics report using a variety of visualizations to answer the questions Brian Edge wants answered.
1. Create and Name Submission Folder (2 marks)
Create a file folder on your computer to store the files. Name this folder using the format below:
LabSection_LastNameFirstName_StudentID
You will compress (zip) this folder with all files created during this assignment as your submission.
2. Download and Extract Data ZIP File (3 marks)
Extract the data ZIP file and put all nine (9) CSV files into the folder you created above.
Data ZIP File: JoshuaTreeInstrument.zip
3. Importing Data into Tableau (4 marks)
Using Tableau, connect to the CSV files by uploading them as text files (1).
Once you have connected the nine tables, make sure all relationships have been created according to the BA_Assignment_JTI_Tableau_Relationships PowerPoint slide deck. (Published in eClass).(1)
Note: Ensure your relationships match those in the slides. Tableau is case-sensitive. If you have trouble connecting tables, ensure that the data in the field that is connecting the tables is in the same case.
Save your Tableau workbook in the folder you created at the beginning as a Packaged Workbook (.twbx)   .(1)
Arrange the Canvas view of the tables and relationships in Tableau so that all tables and relationships are viewable on the screen and take a screenshot. You may need to zoom out to capture everything.
Paste your screenshot below (1).
4. Repairs Visualization (12 marks)
Repairs Viz (5 marks)
Rename sheet 1 to “Repairs”
Use the data tables InstrumentType and Repairs to create a pie chart visualization.
Dashboard (7 marks)
Create a new dashboard and rename it to “Repairs Chart”
Add the sheet Repairs   to the dashboard. Use the visualization to answer the following questions:
1.   What instrument type is repaired the most? (2)
(use InstrumentTypeDesc and Count of Repairs in your visualization and filter out null values)
[replace this text with your answer]
2.   How can JTI use this information? (5)
[replace this text with your answer]
5. Revenue Visualization (24 marks)
Table Viz (5 marks)
Create a new sheet and rename it to “Revenue: Table”
Use the Store, and RentedItems tables to create a table. This visualization should include:
●   Store ID
●   A new calculated field named Store Location that uses a formula to include address1, address2, municipality, provincestate (separate fields with commas).
●   A new calculated field named Sum of Rental Revenue that uses a formula to add the rental price and added warranty together.
Bar chart Viz (5 marks)   
Create a new sheet and rename it to “Revenue: Bar Chart”
Use the InstrumentType table to create a bar chart. This visualization should include:
●   Instrument Description
●   Sum of Rental Revenue (which you created above)
The values (numbers) should be on the y-axis.
Dashboard (代 写BTM 211 Management Information Systems Fall 2024SPSS
代做程序编程语言14 marks)
Create a new dashboard and rename it to “Revenue”
Add the sheets Revenue: Table and Revenue: Bar chart to the dashboard. Use this dashboard to answer the following questions:
1.   What store brings in the most and least revenue? (2)
[replace this text with your answer]
2.   How can JTI use this information? (5)
[replace this text with your answer]
Turn the table into a filter and answer the following questions:
3.   How does the highest earning store make their revenue? (2)
[replace this text with your answer]
4.   How can JTI use this information? (5)
[replace this text with your answer]
6. Customer Location Visualization (20 marks)
Map Viz (5 marks)
Create a new sheet and rename it to “Customer Location: Map”.
Using the Customer table, create a new calculated field named “Full Name” which will include GivenNames and LastName. It should be in the following format: Lady Gaga
Use Longitude (generated) in the columns and Latitude (generated) in the rows. 
Use Full Name, ProvinceState, and Country in marks.
Table Viz (5 marks)
Create a new sheet and rename it to “Customer Location: Table”
Using Country and Count of Customers, create a table.
Dashboard (10 marks)
Create a new dashboard and rename it to “Customer Location”
Add the sheets Customer Location: Map and Customer Location: Table to the dashboard. Use this dashboard to answer the following questions:
1.   What conclusions can JTI draw from this visualization? (5)
[replace this text with your answer]
2.   How does the table visualization enhance what JTI has learned from the map visualization?   (5)
[replace this text with your answer]
7. Employee Visualization (15 marks)
Employee Viz (5 marks)
Create a new sheet and rename it to “Employee”
Use the Employee data table to create a horizontal bar chart that will answer the questions.
Your visualization should include the following:
●   EmployeeName as the rows
●   A new calculated field called Annual Salary that includes Commission and Salary * 12
●   A new calculated field called Years Employed as the Tooltips in marks using the expression below: DATEDIFF(‘year’,[HireDate],TODAY())
Dashboard (10 marks)
Create a new dashboard and rename it to “Employee Chart”
Add the sheet Employee to the dashboard. Use this dashboard to answer the following questions:
1.   Is there a correlation between the number of years an employee has worked for JTI and their annual salary? (5)
[replace this text with your answer]
2.   What conclusion can JTI draw from this visualization? (5)
[replace this text with your answer]
8. Bells and Whistles (10 marks)
Create a new sheet and rename it to “Bells and Whistles”
You decide to proactively answer a question with a visualization for JTI that Brian has not asked. This will help you illustrate the “bells and whistles” of Tableau and explain how Tableau can be used to answer other questions using information hidden in the data.
Choose one or more of the nine (9) tables that are in the model and create a visualization and a dashboard.
1.   Identify the table(s) you selected: (1)
[replace this text with your answer]
2.   Write a question that can be answered by your visualization: (2)
[replace this text with your answer]
3.   Describe how JTI can use this information: (7)
[replace this text with your answer]
OPTIONAL: Provide an explanation on the bells and whistles you researched and used. This can help with the assessment of this requirement.
[replace this text with your answer]
9. Professional Layout, Spelling, and Grammar (10 marks)
You have creative freedom to create additional content for your report as required
In the professional business world, the look and appearance of what you publish is very important. The aesthetic design of the pages in your final report will be considered as part of the assessment of your work. You are encouraged to design the pages in your report with professional and appealing layouts.
All visualizations should have a business professional title
Make sure that every visualization has an accompanying text box stating the question it intends to answer
All pages of your report should have no spelling or grammatical errors.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
