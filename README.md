# NYC Taxi trip duration estimator

![New York taxi](https://newyorkmonamour.fr/wp-content/uploads/2016/10/taxi-jaune-a-new-york.jpg "NYC taxi estimator")

* [Original competition link](https://www.kaggle.com/c/nyc-taxi-trip-duration)
* [Dataset to download](https://www.kaggle.com/c/nyc-taxi-trip-duration/data)

Dataset includes:
* id - a unique identifier for each trip
* vendor_id - a code indicating the provider associated with the trip record
* pickup_datetime - date and time when the meter was engaged
* dropoff_datetime - date and time when the meter was disengaged
* passenger_count - the number of passengers in the vehicle (driver entered value)
* pickup_longitude - the longitude where the meter was engaged
* pickup_latitude - the latitude where the meter was engaged
* dropoff_longitude - the longitude where the meter was disengaged
* dropoff_latitude - the latitude where the meter was disengaged
* store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server - Y=store and forward; N=not a store and forward trip
* trip_duration - duration of the trip in seconds
