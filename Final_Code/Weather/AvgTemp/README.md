 
Question 1:
Does temperature affect prices?
 
Average Monthly Weather ACCUWEATHER:
I) Raw Data
Weather data obtained from closed source and paid subscription

II) Data Cleansing
Limitations: 
Paid sources available only. Also, Accuweather only provides tables with temperature data, no csv or API queries available to abstract data. 
Missing months in our Airbnb data
Manually extracted temperature data tables and imported them in excel, transposed them in column under each month and used Vlookup to separate High and Low daily temp per month.

III) Data Manipulation
Using file names “file_high” and “file_low”:
Obtained the average temperature per month from 2015-2018, counting 40 months in total
Created a DataFrame variable to save results


IV) Result
Using Matplotlib library to generate a graph which displayed average weather trend:
Years are separated by black vertical line and numbers are outlined from 1-40, representing Sept-Dec 2015, Jan-Dec 2016 (Missing March), Jan-Dec 2017, and Jan-Dec 2018. 
Blue line representing “High” temperature and yellow “Low” temperature in farenheights.


