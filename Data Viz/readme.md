# US Filghts Data Exploration 2008 
### Cancellation Flights Reasons

## by Lama AlOud


## Dataset

> The dataset include flights info of the United States, about carriers, arrival, departure delays and cancelled trips, and reasons for delays or cancellations, for 2008.


## Summary of Findings

> By selecting the cancellation flights/trips -of 2008 year- we find:

>     - The top Months have flight cancelation are 2(FEBRUARY) and 12(DECEMBER), and the cancelled reason is weather, carrier then NAS (National Airspace System)
      - for each day (in moth or in week) we observe:
          - In Day of Month, almost all Days have the same probability to have flight cancellation 
          - In Day of Week, Day #6 #7 which is "Saturday and Sunday" have the least cancellation of flight in 2008, other days have the same probability of cancellation except day #5 (Friday) have the most cancellation filghts 
      - Form Month and DayOfWeek features, the months 2(February), 6(June), 7(July), and 12(December) of day 5 for February & December, and day 7 for June & July have peak values, so we conclude the most cnacellation happen in friday and sunday of February, June, July, and December, but the most cancellation month is February.
      

>     - The reason of flights cancellation in the dataset are 'carrier', 'weather', 'NAS' and 'security' sequentially, where carrier have 54904 then weather have 54330, NAS (National Airspace System) have 28188 and security 12 flights cancellations.
      - Form UniqueCarrier with CancellationCode features:
            - carrier is the most effect cause of cnancellation in "AA"
            - weather is the most effect cause of cnancellation in "MQ"
      - Form Mean of Distance and CancellationCode features:
          - mean of distance for carrier is 634.40, weather is 584.56, NAS is 471.27 and security(highest mean distance) is 719.58.

>      - "MQ" and "AA" Unique Carrier code have the most cancellation flights, and the least are "HA", "F9" and "AQ"! 
       - The most 2 mean of Distance of CancellationCode for each UniqueCarrier:
           - "AA" UniqueCarrier have the highest mean of ditance with security CancellationCode or cancellation reason.
           - "HA" UniqueCarrier have the highest mean of ditance with weather CancellationCode or cancellation reason.

>      - In general the most common origin and destination airport of cancellation flights are "LAS", "LAX", "OAK", "ONT", "PHX", "SAN", "SFO" and "SJC".

>      - The 5 most flight numbers are cancelled in the data set are "5961", "64", "321", "5886" and "151". 

>      - In scheduled arrival time:
          Hours between 15:00 to 20:00 have the most cancellation flights in general for both:
            - CRSDepTime - scheduled departure time (local, hhmm)
            - CRSArrTime - scheduled arrival time (local, hhmm) 




## Key Insights for Presentation

>     - The top Months have flight cancelation are 2(FEBRUARY) and 12(DECEMBER), and the cancelled reason is weather, carrier then NAS (National Airspace System)
      - Form Month and DayOfWeek features, the months 2(February), 6(June), 7(July), and 12(December) of day 5 for February & December, and day 7 for June & July have peak values, so we conclude the most cnacellation happen in friday and sunday of February, June, July, and December, but the most cancellation month is February.

>     - The reason of flights cancellation in the dataset are 'carrier', 'weather', 'NAS' and 'security' sequentially, where carrier have 54904 then weather have 54330, NAS (National Airspace System) have 28188 and security 12 flights cancellations.
      - Form Mean of Distance and CancellationCode features:
          - mean of distance for carrier is 634.40, weather is 584.56, NAS is 471.27 and security(highest mean distance) is 719.58.
          
>      - "MQ" and "AA" Unique Carrier code have the most cancellation flights, and the least are "HA", "F9" and "AQ"! 
       - The most 2 mean of Distance of CancellationCode for each UniqueCarrier:
           - "AA" UniqueCarrier have the highest mean of ditance with security CancellationCode or cancellation reason.
           - "HA" UniqueCarrier have the highest mean of ditance with weather CancellationCode or cancellation reason.
           
>      - In general the most common origin and destination airport of cancellation flights are "LAS", "LAX", "OAK", "ONT", "PHX", "SAN", "SFO" and "SJC".








