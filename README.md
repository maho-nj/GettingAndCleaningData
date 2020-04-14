# Getting and Cleaning Data Course Project

This project serves to demonstrate the ability to collect, work with, and clean and data set.

### Raw data collection

 The raw data set was collected in a zip file from this link: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
 
### Data Processing
 
Thereafter, the data was processed as described inn the R Script file ``` run_analysis.R``` and the Code book entitled ``` CodeBook.md ```. 
The processing of the data entailed the following steps:

* The merger of the training and the test sets to create a single data set; 
* The extraction of the measurements on the mean and standard deviation for each measurement; 
* The recourse to descriptive activity names to name the activities in the data set; 
* The labeling of the data set with descriptive variable names; and 
* The creation of a second data set from the one created from the previous step with the average of each activity and each subject.

### Processed data storage 

The outcome of this data processing was saved in the document ``` CleanData.txt ```