
The data:
======================================

The data used in this analysis represent data collected from the accelerometers from the Samsung Galaxy S smartphone

The dataset is pulled from the following files in the UCI HAR Dataset:
=========================================

- 'features.txt': List of all features.

- 'activity_labels.txt': Links the class labels with their activity name (eg 1 represents 'Walking').

- 'train/X_train.txt': Training data set.

- 'train/y_train.txt': Training labels.

- 'test/X_test.txt': Test data set.

- 'test/y_test.txt': Test labels.

The following files are available for the train and test data. Their descriptions are equivalent. 

- 'train/subject_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30. 

- 'train/Inertial Signals/total_acc_x_train.txt': The acceleration signal from the smartphone accelerometer X axis in standard gravity units 'g'. Every row shows a 128 element vector. The same description applies for the 'total_acc_x_train.txt' and 'total_acc_z_train.txt' files for the Y and Z axis. 

- 'train/Inertial Signals/body_acc_x_train.txt': The body acceleration signal obtained by subtracting the gravity from the total acceleration. 

- 'train/Inertial Signals/body_gyro_x_train.txt': The angular velocity vector measured by the gyroscope for each window sample. The units are radians/second. 

The analysis creates the following data: 
======

- 'data': a dataframe including both train and test data labeled by subject and by activity

- 'data.mean.std': a subset of 'data' including only observations of the mean and standard deviation for each measurement

- 'aggregate.means': a dataframe containing the mean of the data for each combination of subject and activity

- 'tidy.txt': a text file containg the data in the 'aggregate.means' dataframe

