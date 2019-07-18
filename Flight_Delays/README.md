## Flight Delays and Cancellations

### About
In this project on Flight Delays and Cancellations in US, I have created visualizations to reveal insights from a flight dataset. These insights help us to understand more about the delay and the reasons for the delay in each state and with respect to each airline. Finally, we can find out which airline will arrive/depart on-time to avoid delays and cancellations.

### Dataset
I have used flights.csv file in creating data visualizations.
This data comes from a Kaggle dataset, it tracks the on-time performance of US domestic flights operated by large air carriers in 2015. The other two files may be used in conjunction with the flights.csv, but should not be used alone.

### Summary
The first and most important step in building data dashboards, is to understand what data we are going to analyze. I am sharing few of the insights about flight delays ,cancellations, airports and airlines using the US flight-delay dataset.
#### Insight 1
How many Us flights are cancelled in each state? What are the reasons for the  
cancellation? Which state has the most number of cancellations?
Flights get cancelled due to reasons like delay caused by Airline/Carrier , National Air System or Weather and it varies in each State accordingly. From the map ‘Cancellation Reason and count by state’, we can easily identify how many flights are cancelled in each state and the reason for the same using the cancellation reason category filter. Texas has the top cancellation count of 668, Illinois has a count of 563 and California has a count of 408. We can further drill down and get the count details from ‘Cancellation Reason Category’ horizontal bars. Texas has 202 flights cancelled due to delay caused by Airline/Carrier, 44 flights due to delay caused by National Air System and  422 flights due to delay caused by Weather.

#### Story Link:
https://public.tableau.com/profile/ramya.ponnuvel.rajathy#!/vizhome/USFlightCancellations/Story1

#### Design   : 
Used ‘Cancellation Reason category’ Filter, Color in Marks to highlight various cancellation reasons and ‘cancellation reason category’ calculated field to describe different cancellation reasons. Adding state field in detail attribute in Marks and highlighting the cancellation count with colors makes it easy to identify the states with most number of cancellations. The US Flight cancellations story gives us an insight about the cancellation count with respect to each Airport and State. ‘Chicago O’Hare International Airport’ in Illinois has a count of 454.

#### Insight 2
What is the Average Delay by airlines ? What is the count of arrival and departure delay of airlines and other delays.
The Average delay by Airlines are caused due to factors like Average air system delay, Average arrival delay, Average departure delay, Average Late aircraft delay, Average security delay and Average weather delay. ‘Southwest Airlines’ has an arrival and departure delay count. ‘Virgin America’ has the least arrival and departure delay count. ‘Alaska Airlines’ among the other average delays, has the max average for Late aircraft delay.

#### Dashboard link:
https://public.tableau.com/profile/ramya.ponnuvel.rajathy#!/vizhome/AverageDelaysandOnTimePerformanceOfUSFlights/Dashboard1

#### Design : 
Used ‘Airline’ filter to get delay details specific to airline. Highlight the different airlines and the average measures using color attribute in Marks. ‘Measure Names’ filter helps to filter data based on the required average delay field.

#### Insight 3
What is the On-Time Arrival and Departure Performance of Airlines in each State ?
The count of flights arriving and departing on-time with respect to each Airline and State will help us to understand how many flights perform better. ‘Southwest Airlines’ has the max count of on-time arrival and departure.

#### Dashboard link:
https://public.tableau.com/profile/ramya.ponnuvel.rajathy#!/vizhome/AverageDelaysandOnTimePerformanceOfUSFlights/Dashboard2

#### Design: 
Used ‘State’ filter to filter airline data based on state and find out which airlines is arrives/departs on-time in each state without much delay.

### References
https://www.kaggle.com/usdot/flight-delays
