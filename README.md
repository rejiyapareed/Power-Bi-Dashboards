
# Project Title

Data Professional Survey Breakdown

#Problem statement

The Data Professional Survey Breakdown is a Power BI dashboard that analyzes the results of an online survey of data professionals. The dashboard includes visualizations that show information such as:
Average age of survey takers
Count of survey takers
Average salary by job title
Average salary by gender
Favorite programming language by job title
Count of survey takers in different countries
Happiness with work/life balance 
Happiness with salary
The dashboard is designed to help people understand the trends, preferences, and challenges that data professionals face. It has a user-friendly interface with interactive visualizations to help with data exploration and decision-making.


#steps followed

1. Load data ito power Bi desktop, data is an excel file.
2. Open power query editor and remove empty columns.
3. Split column "Which title best suits your current role" by left most delimiter (.
4. Split column " Favorite programming language" by delimiter :.
5. Split column "Current yearly salary" from digit to non digit.
6. Replaced "k" and "-" in the split column.
7. Created a custom column for average salary.
8. Split column "Which country do you live in" with delimiter (.
9. In the report tab, created a text card and added unique id and selected count distinct and renamed it as "count of survey takers".
10. Added another text cars, added age and madeit average and renamed it as "average age of survey takers".
11. Created a stacked bar chart with job titles(y axis) and average salary(x axis), added job titles to legends.
12. Created a stacked column chart with favorite programming language (x axis) and countof unique id (y axis) and added job title to legends.
13. Created a tree map and added which country do you live in.
14. Created a guage chart and added "How happy are you in your current role with work life balance" and added average to value and min and max to minimium and maximum values.
15. Created another gauge chart and added happiness with salary.
16. Created a donut chart and added male/female in legend and average salary in value.




