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
For data analysis, we have some sample questions.
<br>
1. Compare the sales and orders using a single chart.
2. Which month got the highest sales and orders?
<br>
For this insert a Pivot Table and a Pivot Chart.

![pivot sales vs order ](https://github.com/Jgithub02/Vrinda-Store-Sales-Report-2022-/assets/164842901/b6f6cfcc-65fd-47b4-ac47-e3331bff4c82)

3. Who purchased more (Men or Women) in 2022?
![men vs women ](https://github.com/Jgithub02/Vrinda-Store-Sales-Report-2022-/assets/164842901/ebd70eff-f7cd-40a6-b654-9910bf2405e6)

4. What are the different order statuses in 2022?

![order status ](https://github.com/Jgithub02/Vrinda-Store-Sales-Report-2022-/assets/164842901/500c639f-e5a7-4f1d-b5ef-a4b26a659ea8)

5. List of top 5 states contributing to sales.
![top 5 state ](https://github.com/Jgithub02/Vrinda-Store-Sales-Report-2022-/assets/164842901/c10e8b78-c4fb-46e0-8cda-2ce657247ac4)

6. Which channel is contributing to maximum sales?
![channels ](https://github.com/Jgithub02/Vrinda-Store-Sales-Report-2022-/assets/164842901/ee3e25d3-74bf-4856-b04f-4bfd5daa9d23)

By using various Pivot Tables and Pivot Charts find out the answers to the above questions 

   
# 4. Vrinda Store Report 2022: 
  # Dashboard:

Using MS Excel, I created an amazing dashboard to easily analyze the insights of sales of the Vrinda store. 
 





