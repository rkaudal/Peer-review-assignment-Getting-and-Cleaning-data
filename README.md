# Peer-review-assignment-Getting-and-Cleaning-data
In this work the tidy data is created for later analysis. 
# Where the data is taken from?
As instucted in the Coursera assignment instruction page: Data are taken using the accelerometers from the Samsung Galaxy S smartphone. The following URL is the link from 
[http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones] where the data is obtained.The data can be extracted from this link:[https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip]
# How to run analysis on the data?
The run_analysis.R is run by setting your working directory to the UCI HAR Dataset folder. This script is run by employing Dplyr package. The test data is read through analysis and train data merge them into one set. The variables are named with the features listed in the features.txt file. Via the combined data set, independent tidy data set that represents the average of individual variable for each activity and each subject is created and written into tidydataset.txt file.
