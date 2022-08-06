# **Bikesharing**

## Overview:

The purpose of this project is to gather Citibike sharing data for the month of August and analyze the results to determine if we could create a similar bike sharing business in Des Moines, LA. 

## Results:

### Tools:

- Python Pandas
- Tableau

### Executoin: 

1. After creating the DataFrame, we were able to change the format, using the following code:

```
bike_trip_df["tripduration"] = pd.to_datetime(bike_trip_df["tripduration"], unit = 's')
bike_trip_df.head()

```

2. With the use of the tripduration we were able to crete different visualizations

## Summary:

The NYC Citibike analysis present a feasible business opportunity for Des Moines. Bike sharing services are in high demand in summer. It is affordable, eco-friendly and healthy mode of transportation to travel. 
