
The data:
======================================

The data used in this analysis represent data collected from the accelerometers from the Samsung Galaxy S smartphone

The dataset is pulled from the following files in the UCI HAR Dataset:
=========================================

- 'features.txt': List of all features.

- 'activity_labels.txt': Links the class labels with their activity name (e.g. 1 represents 'Walking').

- 'train/X_train.txt': Training data set.

- 'train/y_train.txt': Training activity labels.

- 'test/X_test.txt': Test data set.

- 'test/y_test.txt': Test activity labels.

The analysis creates the following data: 
=========================================

- 'data': a dataframe including both train and test data labeled by subject and by activity

- 'data.mean.std': a subset of 'data' including only observations of the mean and standard deviation for each measurement

- 'aggregate.means': a dataframe containing the mean of the data for each combination of subject and activity

- 'tidy.txt': a text file containg the data in the 'aggregate.means' dataframe

