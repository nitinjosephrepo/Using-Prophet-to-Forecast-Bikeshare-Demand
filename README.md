# Forecast Bikeshare Annual Demand Using Facebook Prophet
## Prophet
Prophet was developed internally at Facebook to meet the demand for high level forecasting and still provide flexibility. 
Out of the box Prophet typically produces high level forecast which is great but it's the insights into the data while doing that which are gold. 
For instance 

+ User specified seasonaility curves such as hourly, quarterly, weekly, monthly or annually.
+ Better understand effect of holidays on demand. Qunatified in percentage change.
+ Positive or negative trend once seasonality is removed from data

## Our Data for Forecast

We will be using data from Bike Share Program in Chicago, Illinois. The data contains the number of bicycle
Rides taken each our from the beginning of 2014 through the end of 2017. 

_Our objective is to forecast for 2018, and while we are at It we are going to analyze our data for demand trends during weekly, monthly and holidays._ 


## Forecast & Analysis

 **Forecast for 2018**
<img width="1067" alt="Screenshot 2023-01-14 at 1 26 04 PM" src="https://user-images.githubusercontent.com/80999165/212490174-4e866ba1-9b94-4ae7-8c3c-c317d832d7b4.png">


**Overall Trend is Positive. We see a steady increase in rideshare since 2014**


<img width="959" alt="Screenshot 2023-01-14 at 1 41 16 PM" src="https://user-images.githubusercontent.com/80999165/212490744-e5b8c833-956b-4498-8e87-26836dc1d77e.png">

**Annual Seasonality**

<img width="947" alt="Screenshot 2023-01-14 at 1 45 52 PM" src="https://user-images.githubusercontent.com/80999165/212491083-008d09f6-67e1-4061-a353-0f700b61676b.png">

- We see demand for bikes begins to increase in May (Spring) and starts to decline in November. Demand conincides with Summer and declines in Winter. 

**Weekly Seasonality**

<img width="983" alt="Screenshot 2023-01-14 at 1 56 45 PM" src="https://user-images.githubusercontent.com/80999165/212491648-ad614814-21e6-47bd-aeaa-99e9632cc4e5.png">

- Ridership peaks on Tuesday with 20% increase and then gradually declines over the week and disappears on weekends. It shows that there is different 
seasonlity for week and weekends

**Demand during holidays**

<img width="954" alt="Screenshot 2023-01-14 at 2 10 26 PM" src="https://user-images.githubusercontent.com/80999165/212492159-6e3637ab-0242-4aa8-ba31-7deb1e361529.png">

Lets convert the above output into numbers which help us see how ridership demand looks like in each of the holiday. 



<img width="432" alt="Screenshot 2023-01-14 at 2 19 02 PM" src="https://user-images.githubusercontent.com/80999165/212492417-e9d15b92-ef3c-438b-bc87-51c4ec4dc9f4.png">

We see that demand is negative on all holidays except three 

- Casmir Pulaski Day 
- Columbus day 
- Election Day 
