# (Dataset Exploration Title)
## by (your name here)


## Dataset

> I downloaded 3 years of Air traffic data that contains scheduled and actual departure and arrival times reported by certified U.S. air carriers that account for at least one percent of domestic scheduled passenger revenues. The data is collected by the Office of Airline Information, Bureau of Transportation Statistics (BTS). Since the current year only contains data through June, I've only included  Jan-June for 2018, 2019, 2020.   I used ALteryx to combine the 3 files into one large file.


## Summary of Findings

>- THere was a pattern with flight Delays with an increase in Feb, then March drops, then there's a gradual increase each month of April, May and June. With Covid however, this pattern changed completely in 2020. In 2020 there were almost no delays, only cancellations for March, April and part of May.  The cancellations were almost entirely SECURITY delays.

>- I found that there is an unexpected connection between distance flown and carrier delays. The short leg airlines have some of the higher carrier delays. 

>- The 4 largest airlines have the highest overall total delays and cancellations, but when you take the mean of the delays, they are towards the bottom of the list.

## Key Insights for Presentation

>- Houston, LA, DC and Phoenix seem to be the worst cities for weather delays.
>- Skywest, ExpressJet, Mesa, Allegiant and Hawaain air have the highest Carrier Delays.
>- In looking at city, carrier and NAS delays, it appears that Spirit and United airlines have a lot of delays, as seen in the heatmap.
>- The short hop airlines also have a lot more late aircraft delays.
>- One other interesting note, Hawaiian airlines has one of the highest Carrier delays, and if you look at all of the heatmaps, it appears to be purely the carrier. They have some high delays going into New York and Phoenix. The NAS, Security and Weather delays are almost non existant. Only carrier delays and Late aircraft delays show up. Since they are mostly long haul flights they probably turn the same aircraft around, causing a cascading effect on the later flights
>- The longest security waits are at Los Angeles.
>- The longest NAS delays are at Washington DC.

>-  The 4 airlines with the highest carrier delays, also fly some of the shortest distances.  This actually makes sense since there are more touchdowns and landings to worry about.
>- I also found it interesting that there was a seasonal pattern to the overall delays by month.  
>- Weather delays occur most frequently in the afternoon, carrier delays occur more in the morning.
>- Carrier cancellation occur more in the morning, whereas weather and NAS cancellations occur in the late afternoon
>- In looking at the large category grid plot, the most weather related cancellations happen in January and Chicago.
>-  Last but not least, I found it interesting that when you look at the means of the delays, the smaller airlines have the longest delays.  However, if you look purely at total delayed flights, and total flight delays (sum of all of those delays) in minutes, then you're looking at the big 4:  American Airlines, Southwest Airlines, Delta Air Lines, United Air Lines.

##  Resources
towardsdatascience.com
medium.com
stackoverflow
seaborn, pandas, matplotlib docs
templates, class notes and examples
