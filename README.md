Getting And Cleaning Data Peer Reviewed Project
===============================================

This repo includes an implementation of the final project in the course "Getting and cleaning data", by Coursera.

The file run_analysis.R performs the following user defined methods:

* readFromFiles:  reads the data from the Samsung files.
* describeActivities:  describes the activities in the test and learn datasets according to the documentation, giving it more readable names rather than an enum.
* createDataSet:  merges all the data obtained from seperated files into a single data set.
* addDimensionsToDuplicatedColumns:  adding X,Y,Z to the names of columns which are duplicated.
* getSummaryStatistics:  calculates the average data
* export:  exporting the results to a text file
