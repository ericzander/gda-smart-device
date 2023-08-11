# Data Cleaning

## Daily

* Started with merged daily activity
  * No missing/duplicate data
* Create a feature indicating if the device was worn that day
* Merge sleeping data
  * Verify and dropped duplicates
  * Left merged

## Hourly

* Load calories, activity, and steps
* No duplicates
* Outer merged
* Convert datetime format

## Minutes

* Load calories, intensities, METs, sleep, steps
* Clean sleep table
  * Rename features to match and for clarity
  * Drop log Id
* No duplicates
* Convert datetime format
* Round to nearest minute
* Outer merge

## Weight

* Copy weight logs to clean data
  
## Users

* Start with minute data (no missing values)
* Compute the number of minutes users wore device
* Calculate averages of measures by user
* Cluster
  * KMeans and the elbow method
  * DBSCAN with epsilon tested
