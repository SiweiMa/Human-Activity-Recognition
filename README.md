# Human Activity Recognition by Spark
*The repository is a project in course MSDS 694.* 

#### by [Siwei Ma](https://www.linkedin.com/in/siwei-ma-28345856/)

# Data
The data of this project came from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/WISDM+Smartphone+and+Smartwatch+Activity+and+Biometrics+Dataset+). "The raw accelerometer and gyroscope sensor data is collected from the smartphone and smartwatch at a rate of 20Hz. It is collected from 51 test subjects as they perform 18 activities for 3 minutes apiece."

# Summary
Given a large amount of data (15630426 records) stored in AWS S3, the whole computing, from exploratory data analysis (EDA) to modeling, was conducted based on distributed setting using PySpark. The data was first read and processed in the format of resilient distributed dataset (RDD) and then transfered to DataFrame. Summary statistics was calculated to gain an overview of the sensor data. After feature engineering, the human activity (eating or not) was classified by random forest and GBT classifier. The performance of algorithms was measured by ROC.




