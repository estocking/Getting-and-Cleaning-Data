# Getting and Cleaning Data
Programming Assignment for Getting and Cleaning Data course

## Course Project

The ```run_analysis.R``` script does the following:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Data

The UCI Har Dataset used in this analysis can be downloaded at: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

## Steps

To successfully run this code, these are the required steps:

1. Download the data source and save it in a folder titled ```UCI HAR Dataset```.
2. Put ```run_analysis.R``` in the parent folder of ```UCI HAR Dataset```, then set the parent folder as your working directory using the ```setwd()``` function in RStudio.
3. Run ```source("run_analysis.R")``` to generate a new file ```tiny_data.txt``` in your working directory.

## Dependencies

There are no dependencies for this analysis.
