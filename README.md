# Project1_Group1_HousingMarket: 
    Alex 
    Ajani
    Navreet
    Maria

### Main objective of the project:
    The primary objective of this project is to furnish a profound and all-encompassing data analysis, accompanied by profound insights, to aid an           investment realtor in pinpointing the optimal city among Montreal, Toronto, and Vancouver for constructing new residential properties. 

    The analysis will be centered around examination of historical housing market trends. A group of 4 data analysts will harness pertinent datasets and     use  statistical techniques to deliver actionable recommendations that empower the investment realtor in making well-informed decisions.

### How to navigate this repository: 
    The main code as per a Jupyther Notebook file is named: group1_housing_solution.ipynb 
    The ressources folder will contain the csv collected for our data collection. 
    The output folder as inside the validation of our dataframe created and the plots we made. 
    FYI + Synthax_LessonsLearned folder contains history of discussion and key learning we got from this project. 

### Methodology/steps:
    Data Collection : 
    Our journey commenced with the acquisition of the raw data from trusted sources being Statistics Canada and the Canadian Real Estate Association (CREA). These sources can be found under the references tab. We could retreivered from these website the date, the location in the country (province and city), and the status. 
    
    Data Analysis : 
    For the data cleaning, in other words getting our hands on the data, we first we imported our csv files and the library inside of pythons. Example of libraries are:
        1. from pathlib import Path
        2. from matplotlib import pyplot as plt
        3. from scipy import stats
        4. import numpy as np
        5. import pandas as pd
    
    With the data loaded into our analytical environment, we moved on to the critical phase of data cleaning. By selecting relevant columns, we focused our      efforts on the key variables crucial to understanding the housing market dynamics in these cities. This step not only streamlined the analysis but also enhanced the clarity of our insights. 
    
    We also performed some renaming of field to make sure the filed name where relevant and under stable for everyone in the team. Then, we removed specific rows based on the "STATUS" values. This rigorous process allowed us to exclude any questionable or invalid data, or irrelevant one from our analysis. 
    
    Additionally, to provide a comprehensive picture of the housing market, we took great care to remove rows with empty or "House only" "NewHousePrice_Index_Type". With a refined and polished dataset, we embarked on a city-specific analysis to uncover unique trends and patterns in Toronto, Vancouver, and Montréal. These cities serve as economic powerhouses and hold immense influence over the national real estate market. We finally made sure to export the dataset to serves as a valuable resource as a cross reference and overall validation

 ### Questions our project is trying to answer:  
    Question #1:  What is the price growth over time by city according to the price index of Statistics Canada? 
    
    Question #2: What is the price growth over time by city according to the average house prices from CREA? 
    
    Question #3: What effect Covid-19 had on the avg price of house in each city (pre covid vs post - covid)? 
        
### Vizualization and findings 
    **Question #1: What is the price growth over time by city according to the price index of Statistics Canada?**
    Chart #1 - Line plot 
    ![Average Sales Price Distribution Over the Last 10 Years.png](Project1_Group1_HousingMarket/Output/Plots/Average Sales Price Distribution Over the Last 10 Years.png)
    Findings: We noticed that price growth across the 10 years range of time, continued to increase for the market being analyzed (Toronto, Vancouver and Montreal). 
    ------------------------------------------------
    Chart #2 -  Box and Whisker plot 
    !
    Findings: This vizualization of the Box and Whisker plot's median values were floating relatively close to the 100 basis point that StatsCan used to scale the Canadian dollar for all the years to be equivalent to 2016. Montreal had many outliers on the plot, suggesting that the market does have more activity higher end away from the average sales for a given year than in Toronto and Vancouver.
    
    **Question #2: What is the price growth over time by city according to the average house prices from CREA? **
    Chart #3 - 
    !
    Findings: 
    Chart #4 -  
    !
    Findings: 
    ------------------------------------------------
    **Question #3: What effect Covid-19 had on the avg price of house in each city (pre covid vs post - covid)? **
    Chart #5 - Housing market during covid
    !
    Findings: 
    
    Chart #6 - 
    !
    Findings: 
    
#### Pitch presentation
    Please see in the main repisotory our slides. 

## Limitations 
    First, working in housing data can be very challenging from a statistics perspective and our team’s experience found this to be the case due to differing perspectives on insights, and limitations within the data found.
    
    From a granularity perspective, we initially targeted average price comparisons to median incomes but quickly discovered that while widely available, housing and income data is often proprietary with housing typically reported based on monthly averages. 
    
    Further to this, given the nature of the real estate business, the data sets monthly averages are not consistently calculated using the exact same houses of the prior month. We parsed through StatsCan data that was rated as excellent but ran into challenges when looking to join that data to other sources. 
    
    Due to the proprietary issues, our data is exclusively focused on sales prices limiting our ability to analyze the market from a Sq.Ft, Dwelling Type, Number of Bedrooms, Lot Sizes, etc. perspective. The team opted for a solution to leverage CREA average housing price data found online to develop our own dataset that compiled average housing sales prices to analyse which dataset appeared to be more reliable to answer our inquiries.
    
    Additionally, due to the dynamic nature of the housing market, data for certain periods may not be as readily accessible, leading to potential gaps in our insights. 
    
    Despite these limitations, we have strived to present the most comprehensive and informative analysis possible, leveraging the data at our disposal to draw meaningful conclusions. However, the availability of data may be limited in certain regions or timeframes, which could impact the granularity and completeness of our analysis. 

 ### Going further (what would have improve our project? 
    The available data is solely focused on sales prices, which restricts our ability to conduct a comprehensive analysis of the market from various perspectives such as Square Footage, Dwelling Type, Number of Bedrooms, Lot Sizes, and others. 
    
    Additionally, crucial data points, such as information related to income, location of the sales, the number of sales each month, and the total number of listings available during the sales period, were not included in the dataset.

    Despite these limitations, we proceeded to work with the available data and attempted to draw conclusions related to the market. 
    
    However, the inadequacy of the data led us to inconclusive findings concerning the stories we intended to communicate about the market. Nonetheless, during our analysis, we did come across intriguing observations worth considering, particularly in light of the impact of Covid-19 on the real estate market.
    
### References: 
### Statistic Canada
    Statistics Canada. (n.d.). Table 18-10-0205-01 Gross domestic product (GDP) at basic prices, by industry, monthly (dollars). Retrieved from https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1810020501


### Housing market per year trend
    WowA. (2023, July 15). Montreal Housing Market: Trends and Analysis. WowA Canada. Retrieved from https://wowa.ca/montreal-housing-market
    
    WowA. (2023, July 23). Vancouver Housing Market: Trends and Analysis. WowA Canada. Retrieved from https://wowa.ca/vancouver-housing-market
    
    WowA. (2023, July 23). Toronto Housing Market: Trends and Analysis. WowA Canada. Retrieved from https://wowa.ca/toronto-housing-market
    
    Canada Immigrants. (n.d.). Average House Price in Montreal. Retrieved from https://canadaimmigrants.com/average-house-price-in-montreal/
    
    Listing.ca. (n.d.). Toronto Real Estate Price History. Retrieved from https://toronto.listing.ca/real-estate-price-history.htm
    
    Real Estate Board of Greater Vancouver (REBGV). (2018, December). December 2018 Monthly Market Report. Retrieved from https://www.rebgv.org/market-      watch/monthly-market-report/december-2018.html
    

### Coding help website used 

    Title: Python - Creating dictionary from Excel data
    Website: Stack Overflow
    URL: https://stackoverflow.com/questions/14196013/python-creating-dictionary-from-excel-data


    Title: Convert a Pandas DataFrame to a dictionary
    Website: Stack Overflow
    URL: https://stackoverflow.com/questions/26716616/convert-a-pandas-dataframe-to-a-dictionary 


    Title: What is the difference between UTF-8 and ISO-8859-1?
    Website: Stack Overflow
    URL: https://stackoverflow.com/questions/7048745/what-is-the-difference-between-utf-8-and-iso-8859-1
