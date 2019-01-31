Average Price per Month for “Top 30 Zipcodes:
Raw data used to leverage
Contains all data for all zip codes per year. (From main folder “PyBnB_project1”)
2015: “./Master Data 2015.csv”
2016: “./Listings_2016/2016_Listings.csv”
2017: ”./Listings_2017/Merged_2017.csv”
2018: “./2018_Listings.csv”

Data Cleansing
Steps:
Created a vlookup reference table using the top 30 zip codes for years 2015-2018 from file “consolidated30zips.csv.”
Cleansed each file per year and kept only data matching top 30 zip codes from each month.
Saved in new file below:
2015: file_input_15 = './topzips_raw_2015.csv'
From May-Dec, missing July data from Airb&b source.
2016: file_input_16 = './topzips_raw_2016.csv'
From Jan - Dec, missing March from Airb&b source.
2017: file_input_17 = './topzips_raw_2017.csv'
From Jan - Dec
2018: file_input_18 = './topzips_raw_2018.csv'
From Jan - Dec

Data Manipulation using Jupyter Notebook:

 “./Listings_2016/Project_part_Weather/MJ/Avg Price.ipynb”
Steps:
Grouped each csv file by “year_month” and calculated mean per montH
Used to plot y-axis 
Counted all listings per month for each year 
Used to display size of circle in graph (S)
 Merged all data in a series format for plotting




 
 Final Output: 
Steps:
Plotted the Average Price / Night over the 40 Months (2015-2018)
X-axis : Months
Y-axis: Average Price 
S-size: Number of Listings


FINDINGS:
Average price is positively correlated with major changes in weather
At point 20 (February, 2017) avg price dropped significantly, at which weather in New York City was highly affected by the blizzard Nor’Easter.


