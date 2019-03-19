
# Ford Go Bike Video Visualization for a day
## Description
The goal of this project is to create a visualization that would show the journey of ford go bikes (based on bike_id) for a full day.
This will eventually be a webapp. 

## Details 
If we create a visualization map for each minute and determine the location of the bike for each minute and the stitch all of these, we will have a moving video. 
This will have to be looped for each minute of the day.
New things will have to be calculated as in: 
1. Last location of the bike, next location of the bike, time elapsed since last location, time to next location 
2. 

## Code used 
```
jupyter notebook
```

## Change Log 
* 2019-03-18 22:25:37, Downloaded the data from: https://s3.amazonaws.com/fordgobike-data/index.html
* 2019-03-18 22:28:16, Import data in Jupyter notebook for some summary analysis 
* 2019-03-18 22:45:03, Imported data in notebook
* 2019-03-18 22:45:14, Got a quick data count of trips per day
* 2019-03-18 23:18:43, Filter on a day
* 2019-03-18 23:19:09, Counts per bike id for a day
* 2019-03-18 23:22:34, Draw each bike on a map based on starting location 
