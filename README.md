# Comparing-Baltimore-SanMateo-Incarceration-Rates 
Dataset Description: The Opportunity Atlas data set I used provided the incarceration rates for each census tract nationally. I chose this data set because I was interested in comparing the incarceration rates between the very different cities of San Mateo and Baltimore. Socioeconomic structure (including racial distribution and police relations) contributes significantly to incarceration rates. I hypothesized that the relatively white and high-income city of San Mateo would have lower incarceration rates than the largely black and lower income city of Baltimore.

Findings: I performed an analysis of the data that compared the incarceration rates on the level of census tract within the cities of Baltimore and San Mateo. I found there were disparities between the census tracts both within and between the two  cities. While all of the incarceration rates for San Mateo census tracts were fairly low, Baltimore showed more variance, with the highest incarceration rate being over 10 times the highest San Mateo incarceration rate. While it is difficult to extrapolate meaning from this limited window, the analysis shows a clear disparity between incarceration rates in areas with different characteristics. This shows that a policy targeting change in one neighborhood would most likely not be effective for all areas in Baltimore. Coming from a community which does not face high incarceration rates, it is important for me to consider the underlying social, political, and economic workings that contribute to high incarceration rates in select neighborhoods in Baltimore. A better understanding of the problems that Baltimore citizens face will help me make more impactful and effective decisions regarding the city and its residents.  

Data Vizualizations:
![](Screen%20Shot%202020-02-14%20at%201.06.38%20AM.png)
![](Screen%20Shot%202020-02-14%20at%2012.24.27%20AM.png)

Step by Step:
1. Download excel file from Opportunity Atlas
2. Create Pivot table with "Name" in the rows field and "Sum of Incarceration_Rate_rP_gP_pall" in the values field
3. Use the filter for the Names to select only Baltimore census tracts
4. Calculate the min and max to determine the boundaries of bins
5. Create bins and use =FREQUENCY function to determine the distribution of data into bins
6. Select the column with the bin distribution data and create a column chart
7. Set the gap width of the column chart to 0 
8. Select the column with bins as the input for the x-axis values
9. Repeat steps 2-8 for San Mateo census tracts 

Opportunity Atlas Excel Data: https://github.com/Miya-herman/Comparing-Baltimore-SanMateo-Incarceration-Rates-/blob/master/Opportunity%20Atlas%20Original%20Data.xlsx

Excel Analysis:https://github.com/Miya-herman/Comparing-Baltimore-SanMateo-Incarceration-Rates-/blob/master/Comparing-Baltimore-SanMateo-Incarceration-Rates%20.xlsx
