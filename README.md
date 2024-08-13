## BIKE DEMAND DATASET

### OVERVIEW

The dataset that it was been used for this project is a dataset from a station and asked me to make a machine learning model to predict the demand at the station ( negative number means that at some time we had a lot of bikes taken than returned ) and a positive number means that we had more bikes returned than taken

this dataset is for the month **February 2023**

The dataset contained 8636 instances and 5 features

1. **TripId**: a unique id for all the customers that had taken a bike

2. **StartTime**: when did they took the bike (time and date )

3. **EndTime**: when did the returned the bike (time and date)

4. **StartStationId**: unique id of the start station id

5. **EndStationId**: unique id of the end station id 


We care for the value 1 in the columns (StartStationId and EndStationId) and we don't take in consideration the values that are != 1
