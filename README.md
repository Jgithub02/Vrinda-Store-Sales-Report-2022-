# Problem Statement/Objective:
Vrinda store wants to create an annual sales report for the year 2022. So that, they can understand their customers and grow more sales in the upcoming years. 
# Steps Followed: 
# 1. Data Loading into Excel:
Load data into Excel of Vrinda Store for the year 2022.
# 2. Data Cleaning: 
Using Excel to clean the data 
<br>
We have 'Men' and 'M' in our data for the Men, So using 'Replace' fixed it. And the same for 'Women' and 'W'.
<br>
To clean the 'Qty' column use 'Replace'


![M to men ](https://github.com/Jgithub02/Vrinda-Store-Sales-Report-2022-/assets/164842901/a47286b0-04c7-4aa7-bb73-f3f3fabf83e4)
![one to 1](https://github.com/Jgithub02/Vrinda-Store-Sales-Report-2022-/assets/164842901/51b14668-9f42-4773-ba4d-85eaf88c04c5)

Added some  new columns using the following formulas, So we can analyze the data easily.
<br>1. "Age Group" <br>
=IF(E2>=50, "Senior", IF(E2>=30, "Adult", "Teenager"))
<br>2. "Month"
<br>
=TEXT(G4,"mmm")

# 3. Data Analysis:
For data analysis, we have some sample questions 
<br> 
1. Compare the Sales and Orders using a single chart.
 <br>
For this insert a Pivot Table and a Pivot Chart.
<br>
![sales Vs orders ](https://github.com/Jgithub02/Vrinda-Store-Sales-Report-2022-/assets/164842901/26e9c54d-681f-4d5c-b063-43954a170618)

 





