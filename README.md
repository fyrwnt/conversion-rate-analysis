## **This is a Project Based Intership supported by Rakamin Academy**

# Overview
This project is used to analyze conversion rate from marketing campaign and increase performance so that customer would interact more on the company platform. For the code itself, it's in Indonesian for project purpose

# What is being done
### Task 1
- Perform feature engineering: conversion rate
- Calculate and group ‘age’ into several groups
- Create a plot that shows the relationship between conversion rate and the type of user who is more likely to respond to the campaign
- Interpret the plot and note whether there is a significant relationship between customer age and conversion rate

#### Extra
- Engineered new feature

|Feature names|Description|
|-------------|-----------|
|Total Interaction      |Combination of shopping and visit activities.|
|Conversion Rate        |Percentage of successful campaigns.|
|Customer Value Index   |Measures the value of customer purchases.|
|Family Size            |Determines whether a campaign is suitable for large or small households.|
|Recency Segment        |How long since the last purchase.|
|Income per Capita      |Can influence how responsive they are to discount/premium campaigns.|
|Channel Preference     |Dominant shopping channel: Web / Store / Catalog.|
|Loyalty Indicator      |Number of previous campaign participations.|
|Tenure                 |How long the customer has had an account.|

### Task 2
- Handle null and duplicate value
- Drop unnecessary data
- Feature encoding
- Standarization

### Task 3
- Determine the appropriate number of clusters using the elbow method
- Implement clustering using k-means clustering
- Calculate the silhouette score to see how the model performs

### Task 4
- Interpreting the existing cluster results from each feature used
- Selecting clusters for marketing retargeting
- Calculating the potential impact of marketing retargeting results from existing clusters

# Final Result
Cluster 4 should be considered for retargetting, **WHY?**
- Lots of customer, and it's not niche (402 customer with 1.04 spend rate; cluster 0 and 2 have high spend rate but small customer)
- Based on previous interpretation, this group haven't been shopping lately so it's recommended to reactivate them by doing campaign