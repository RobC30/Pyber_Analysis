# Pyber Analysis

# Overview of Project
The project's aim is to provide insight on PyBer's ride & city datas. We will create a DataFrame with each city type's total fares and compare it to its total rides & total drivers. We will then breakdown our ride dataset into weekly intervals to determine trends on PyBer's 2019 operations (January to April) in different city types.

# Results
### Pyber Data Summary based on City Types (January 2019 to April 2019)

<br>

![image](https://raw.githubusercontent.com/RobC30/School_District_Analysis/main/Resources/dist_sum_old.PNG)


<br>

We categorized our dataset into 3 different city types - __Rural, Suburban & Urban__. In the provided table, we can determine that more condensed city types tend to have a larger number of rides & drivers. __Rural__ only has a total of __125 rides__ vs. __Urban's__ total of __1,625__ rides, we saw an increase of _1,300%_ between these two.

Based on the analysis, we can conclude that a city type's total number of rides & drivers is directly proportional to a city type's revenue. __Urban__ had a revenue of __$39,854.38__, __Suburban__ at __$19,356.33__ and __Rural__ at __$4,327.93__. 

 The __Ave. Fare/Ride__ is highest on __Rural__ city types at __34.62__ followed by __Suburban__ at __$30.97__ and __Urban__ at __$24.53__. we can see a downward trend on both results as the city type goes larger. The __Ave. Fare/Driver__ is highest at __Rural__ at __$55.49__ and lowest at __Urban__ at __$16.57__.

<br>

### Weekly Total Fares (January 2019 to April 2019)

<br>

![image](https://raw.githubusercontent.com/RobC30/School_District_Analysis/main/Resources/dist_sum_old.PNG)


With the given line chart, we can better visualise how different city types performed in a span of __5 months__. This further supports our results of how __Urban__ outperforms the other two categories in terms of __Total Fares__. Given that population differs on each city type, only __Urban & Suburban__ saw an upward trend in 5 month's of operation. __Urban__ started at __$1,600__ and ended at __$2,300__ while __Suburban__ started at __$700__ ending at __$1400__.

Here can see upward ticks at the three city types on the latter half of February, which might be because of riders using PyBer before/after Valentine's Day plans. 


# Summary
There is  a disparity between _Ave. Fare/Ride & Ave. Fare/Driver_ that tends to get smaller on larger city types. Here, we want a healthy relationship between the two averages like how the Suburban category's results are.

Even though the Urban category gave the largest return, we might be able to improve it by looking at our Suburban data. It has a smaller Total Rides to Total Drivers ratio compared to the Urban category. In PyBer's 5-month opretaion, we saw bigger increase (from start to end) in the Suburban category almost doubling its Total Fares from $700 to $1,400.

Based on our __Ave. Fares__ analysis, there is a larger average return on the __Suburbancategory vs. Urban__. If we are to reduce our drivers in our Urban operations reducing the gap between Rides & Drivers, we might see a better Urban category performance.