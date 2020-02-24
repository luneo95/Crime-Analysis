# Crime-Analysis
In this project, I performed online analytical processing (OLAP), time series anlysis and spatial analysis on a million-scale dataset of 15-year-span San Francisco crime incidents. A similar crime analysis project is done another dataset of LA crime incidents.
The dataset in this project could be found in https://data.sfgov.org/Public-Safety/sf-data/skgt-fej3/data.
In the first part, I performed OLAPs by analyzing data patterns with respect to time, location, category and date using Spark SQL,  Spark Dataframe and Python.
Following the OLAPs, I constructed a spark pipeline to apply K-means clustering algorithm to generate spatial distributions of crimes in these 2 cities and identified the districts with high crime frequency but low resolution rate.
Based on the results, I was able to develope qualitative trends and suggestions for local police department as well as tourists and also visualized quantitative results using Matplotlib and Seaborn packages.

Note: In case .dbc file could not be previewed in github, below is a link to my published databricks notebook
https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/8510077708972645/2621864784506136/2091930064523923/latest.html
