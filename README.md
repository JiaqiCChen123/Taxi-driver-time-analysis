# Taxi-driver-time-analysis

## Description
Given Chicago taxi drives' trip data, we are interested in predicting drive time as well as drive fares for single trip given other information (pick/drop location, time, whether, driver's information, etc.)

The data source are from [Kaggle](https://www.kaggle.com/chicago/chicago-taxi-rides-2016). 

# Tools
Because the data size is 2GB, we used __distributed computing__ for data processing and data analysis. 

* In the data storing part, we use AWS S3. 

* In the data acquisition part, we used Spark-SQL. 

* In the data processing and feture engineering part, we use Pyspark and relevent Map-Reduce functions. 

* In the modeling part, we used Pyspark.ML techniques and Spark H2O pipeline. 

All codes are run in AWS EMR.

The processing details are shown in notebooks.
