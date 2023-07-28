# Project1_Group1_HousingMarket: 
    Alex 
    Ajani
    Navreet
    Maria

### Main objective of the project:
    The primary objective of this project is to furnish a profound and all-encompassing data analysis, accompanied by profound insights, to aid an           investment realtor in pinpointing the optimal city among Montreal, Toronto, and Vancouver for constructing new residential properties. 

    The analysis will be centered around examination of historical housing market trends. A group of 4 data analysts will harness pertinent datasets and     use  statistical techniques to deliver actionable recommendations that empower the investment realtor in making well-informed decisions.

### How to naviguate this repository: 
    The main code as per a Jupyther Notebook file is named: group1_housing_solution.ipynb 
    The ressources folder will contain the csv collected for our data collection. 
    The output folder as inside the validation of our dataframe created. 
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
    With the data loaded into our analytical environment, we moved on to the critical phase of data cleaning. By selecting relevant columns, we focused our      efforts on the key variables crucial to understanding the housing market dynamics in these cities. This step not only streamlined the analysis but also enhanced the clarity of our insights. We also performed some renaming of field to make sure the filed name where relevant and under stable for everyone in the team. Then, we removed specific rows based on the "STATUS" values. This rigorous process allowed us to exclude any questionable or invalid data, or irrelevant one from our analysis. Additionally, to provide a comprehensive picture of the housing market, we took great care to remove rows with empty or "House only" "NewHousePrice_Index_Type". With a refined and polished dataset, we embarked on a city-specific analysis to uncover unique trends and patterns in Toronto, Vancouver, and Montréal. These cities serve as economic powerhouses and hold immense influence over the national real estate market. We finally made sure to export the dataset to serves as a valuable resource as a cross reference and overall validation

 ### Questions our project is trying to answer:  
    Question #1:  What is the price growth over time by city according to the price index of Statistics Canada? 
    
    Question #2: What is the price growth over time by city according to the average house prices from CREA? 
    
    Question #3: What effect Covid-19 had on the avg price of house in each city (pre covid vs post - covid)? 
        
### Vizualization and findings 
    Question #1: What is the price growth over time by city according to the price index of Statistics Canada? 
    Chart #1 - 

    Chart #2 -  

    Question #2: What is the price growth over time by city according to the average house prices from CREA? 
    Chart #3 - 

    Chart #4 -  


    Question #3: What effect Covid-19 had on the avg price of house in each city (pre covid vs post - covid)? 
    Interpretation
    Chart #5 - Housing market pre-covid
    


    Chart #6 - 
    
#### Pitch presentation
    Please see in the main repisotory our slides. You can also access it by using this link --> https://docs.google.com/presentation/d/1CJ3dPrM7Mc9OgJDJxfTJvhJdyCN2KMLb/edit?usp=sharing&ouid=104607105844137137793&rtpof=true&sd=true 

## Limitations 
    First, working in housing data can be very challenging from a statistics perspective and our team’s experience found this to be the case due to differing perspectives on insights, and limitations within the data found.
    
    From a granularity perspective, we initially targeted average price comparisons to median incomes but quickly discovered that while widely available, housing and income data is often proprietary with housing typically reported based on monthly averages. Further to this, given the nature of the real estate business, the data sets monthly averages are not consistently calculated using the exact same houses of the prior month. We parsed through StatsCan data that was rated as excellent but ran into challenges when looking to join that data to other sources. Due to the proprietary issues, our data is exclusively focused on sales prices limiting our ability to analyze the market from a Sq.Ft, Dwelling Type, Number of Bedrooms, Lot Sizes, etc. perspective. The team opted for a solution to leverage CREA average housing price data found online to develop our own dataset that compiled average housing sales prices to analyse which dataset appeared to be more reliable to answer our inquiries.
    
    Additionally, due to the dynamic nature of the housing market, data for certain periods may not be as readily accessible, leading to potential gaps in our insights. Despite these limitations, we have strived to present the most comprehensive and informative analysis possible, leveraging the data at our disposal to draw meaningful conclusions. However, the availability of data may be limited in certain regions or timeframes, which could impact the granularity and completeness of our analysis. 

 ### Going further (what would have improve our project? 


 
    
### References: 
### Statistic Canada
    ##### 


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
