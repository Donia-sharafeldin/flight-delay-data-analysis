# (flight delays in us 2008)
## by Donia Sharafeldin


## Dataset
https://www.kaggle.com/vikalpdongre/us-flights-data-2008

> flight data tracks the on-time performance of domestic flights operated by large air carriers. Summary information on the number of on-time, delayed, canceled and diverted flights appears in this data.

> dropped cols that is not of my interest
> filtered data according to delayed rows only in Delayed flights df


## Summary of Findings


>In Univariate exploration:
1 - 76% of flights arrived on time, 15.2% arrived with delay of more than 15 min, 6.6% arrived with delay more than one hour, 0.2% was diverted and 2% was cancelled
2 - most of cancellation was due to weather conditions and no security cancellations
3 - found small corrolation between taxi out and departure delay
4 - Mesa Airline and Hawaiian Airlines are having the biggest portion of delays
5 - arrival delays increases by time , may be due to accumulation od delays in flights
6 - All delays variables show correlation with Arrdelay which make sense
DepDelay and ArrDelay shows correlation wit CarrierDelay
