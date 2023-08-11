# Case Study: Bellabeat Smart Devices

Data analysis case study concerning health-related smart devices. Implemented for the Google Data Analytics certificate.

## ***Ask***: Objectives

* Observe trends in smart device usage
* Determine applicability to Bellabeat products
* Suggest takeaways for marketing strategy

## ***Prepare***: Data Description

This project uses crowd-sourced FitBit Fitness Tracker data collected via Amazon Mechanical Turk between 3/12/2016 and 5/12/2016. Includes info concerning activity, calories burnt, sleep, steps, and logged weight for 30 participants.

Unzip *data/Fitabase Data 4.12.16-5.12.16.zip* for the raw data and to replicate cleaning. Unzip *data/cleaned/* to analyze and visualize.

* Acknowledgment
  * Source: [Furberg, Robert; Brinton, Julia; Keating, Michael; Ortiz, Alexa @ Zenodo](<https://zenodo.org/record/53894#.YMoUpnVKiP9>)
  * Accessed: [Möbius @ Kaggle](<https://www.kaggle.com/datasets/arashnic/fitbit>)
* Other references
  * FitBit sleep stages: <https://blog.fitbit.com/sleep-stages-explained/>

## ***Process***: Cleaning Data

Data manipulation steps included:

* Dropping missing data
* Identifying and dropping duplicated data
* Column renaming
* Date/time conversions
* Rounding to nearest minutes
* Merging tables into following groups
  * Daily
  * Hourly
  * Minute
  * Weight logging
  * User measures
* Feature creation
  * Whether a user wore a device on a given day
  * Compute number of minutes each user wore device
  * Clustering users with KMeans

A more detailed breakdown can be found with the cleaned data in *data/cleaned/steps.md*

## ***Analysis***: Findings

## ***Share***: Visualization

## ***Act***: Recommendations

---

## Deliverables

* Summary of business task (**Ask**)
* Description of all data sources used (**Prepare**)
* Documentation of any cleaning or manipulation of data (**Process**)
* A summary of analysis (**Analyze**)
* Supporting visualizations and key findings (**Share**)
* Top high-level content recommendations based on analysis (**Act**)
