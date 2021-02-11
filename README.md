# Comparing High School Graduation Rates of Baltimore, MD and New York, NY with Opportunity Atlas Data
## Background

For this assignment, we were asked to use Microsoft Excel to conduct data analysis about a social metric in Baltimore, Maryland and our hometown (or an interesting US city). As I am an international student, I have chosen to conduct the analysis on New York, New York as this is the US city I am most familiar with.

The social metric I have chosen is high school graduation rates as education has always been an important factor in my life and I am interested to learn about how the rates differ across US cities. I also think that the city of New York will be an interesting comparison to Baltimore as the socioeconomic landscapes of the cities are quite different.

I will be using open data collected by the Opportunity Atlas to analyze the high school graduation rates of the counties of Baltimore, MD and New York, NY and the average graduation rate in each city compared with the national average. 

## Business Question
How do the high school graduation rates of Baltimore, Maryland and New York, New York compare to the national average? 

## Data Sources – Open Data

1.	[Opportunity Atlas](https://www.opportunityatlas.org/)
They collect data from US cities on a variety of metrics including household income, incarceration rates, teenage birth rates, high school graduation rates, adn more.
- High School Graduation Rates in Baltimore, MD
- High School Graduation Rates in New York, NY
2.	US News
The [US News article](https://www.usnews.com/education/best-high-schools/articles/see-high-school-graduation-rates-by-state) was used to obtain information regarding the national average for high school graduation rate. The reported national graduation rate is approximately 88% as of April 22, 2020. 
    The National Center for Education Statistics reports on [public high school graduation rates](https://nces.ed.gov/programs/coe/indicator_coi.asp#:~:text=The%20U.S.%20average%20ACGR%20for,85%20percent%20in%202017%E2%80%9318) and listed it as 85% in 2017-18, however, as the data excludes private high schools, I decided to use the statistic from the US News article.

## Data Analysis
I will use Microsoft Excel to:
- Compare the graduation rates of different counties in Baltimore, Maryland and New York, New York
- Compare the graduation rates of different counties to the city average
- Compare the both the county and city graduation rates to the national graduation average

### Step-by-step descriptions
1.	I imported the data from Opportunity Insights into Excel
2.	As the data recorded the graduation rates of each city by county, I calculated the average graduation rate for each city using the average function (=average(:))
3.	I then included the national graduation rate provided by US News in the data (88%)
4.	For each set of data, I created a pivot table 
- The county names were used as the axis
- The county rate, city rate, and national rate of graduation were included as values 
- All rates were converted to percentages
5.	I inserted a column pivot chart and moved the city rate and national rate to secondary axes
- I reformatted the axes so that all of them had the same bounds
- I changed the chart type of the city and national rates to line charts so that they could be easily compared against the county rates and each other
6.	I added labels and titles to the chart and included a data call out for the city and national rates for clarity

### Data Answer
Looking at the charts below, we find that rate of high school graduation in both Baltimore and New York are higher than the national average of 88% with the city rates at 89.32% and 89.67% respectively. 

When comparing each city county to the city average and national average, there is greater variation with some counties falling more than 5% below the city rates. However, when comparing the city rates overall, both Baltimore and New York maintain high school graduation rates at least 1% above the national average. 
