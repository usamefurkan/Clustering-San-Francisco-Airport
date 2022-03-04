# Clustering on the San Francisco Airport Dataset
![San_Francisco_International_Airport_at_night](https://user-images.githubusercontent.com/87232397/156773464-3b826a02-f699-4dbf-9642-5490fed5729f.jpeg)

## Overview
The project aims to cluster the airline companies in San Francisco Airport dataset according to number of flights and total number of passengers.

- Business Understanding
- Data Understanding
- Data Preparation
- Modeling
- Evaluation
- Deployment

## Data Understanding
The columns were examined. What information does the dataset contain about air traffic at San Fracisco Airport?

## Data Preparation
- Total number of passengers carried and total number of flights held for each airline were found.
- Outliers were removed for more accurate cluster analysis.
- Separate dataframes was created for model fitting


## Modeling
- Cluster analysis was done in 3 ways:
  - Clustering airline companies by number of flights held
  - Clustering airline companies by total number of passengers 
  - Clustering airline companies by total number of passengers and number of flights held
- Number of clusters where silhouette score remains constant number of airline companies segments should be selected

