# Marven Toys Sales Performance Report



## Table of content



- [Project Overview](project-overview)
- [Data Source](data-source)
- [Tools](tools)
- [Data Import](data-import)
- [Data Cleaning](data-cleaning)
- [Exploratory Data Analysis](eloratory-data-analysis)
- [Data Analysis](data-analysis)
- [Result / Findings](result-/-findings)
- [Recommendations](recommendations)



### Project Overview



This Sales Analysis Project aims to provide insights into the sales performance of Marven Toys for a two year period (2017-2018). I will be analysing trends, patterns that will help me make data driven recomendations that will guide Marven Toys in their expansion project.  


![Projectuse](https://github.com/lumanex/Marven-Toys/assets/112433135/6f464236-6d64-4236-b057-ace971df2fa4)



![Projectuse2](https://github.com/lumanex/Marven-Toys/assets/112433135/e4c8ff82-5ec3-4b00-a18b-a5eaa5d5fb6c)



### Data Source 



Sales Data: The primary dataset for this analysis is a set of CSV files namely "INVENTORY","PRODUCTS","SALES","STORE" and "DATETABLE" They contain detailed information on the sales made by Marven Toys in 2017-2018.



### Tools



- PostgreSQL - Data Import
- Power BI - Data Cleaning, Creating Measures, New Columns and Final Report



### Data Import



In the intial preparation stage, i imported the data from PostgreSQL to Power BI




### Data Cleaning




1. Replaced numeric missing values with the MEDIAN of values in the column that contains the missing values.
2. Ensured the values are in the right Format
3. Removed outliers
4. Merged Columns
   
   

### Exploratory Data Analysis



EDA involved exploring the Data sets to answer key questions as :



- which product category drives the biggest profit?
- Is it the same across the across store locations ?
- Find the seasonal trend or pattern in the sales data.



### Data Analysis



This include Code/Features i worked with

```Power BI 

YTD Revenue = TOTALYTD([Total Revenue],DATESYTD(DateTable[Date]))

YTD Profit = TOTALYTD([Total Profit],DATESYTD(DateTable[Date]))

```


### Result / Findings



The analysis result is summarized as follows:



1. There is a increase in Both revenue and profit from the company sales
2. Arts and craft Category made the highest profit of $480,000 and its the best performing categories.
3. Downtown made the Highest profit 0f $1031,000 and tops other Sales locations
4. Ciudad Mexico 2 emerged as the best store by puling a profit of $72,000.
5. From the trend the 2018 Revenue surpasses that of 2017 and is moving towards the set TARGET of the company


### Recommendations


1. invest in product that falls withing the Art and Craft Category.
2. Expansion projects should be sited within the Top 5 Locations.
3. There should be an increase in the production of the Top 5 product that will yeild more Revenue and profit.
4. Double the sales from the Month of August till December.












