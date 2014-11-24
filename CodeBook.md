##Code Book
    
Site where the data was obtained:  
  http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Data for the project:
  https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

Create one R script called run_analysis.R that does the following:
 1. Merges the training and the test sets to create one data set.
 2. Extracts only the measurements on the mean and standard deviation for each measurement. 
 3. Uses descriptive activity names to name the activities in the data set.
 4. Appropriately label the data set with descriptive variable names. 
 5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each         activity and each subject.

Load activity labels
Load data column names
Extract the mean and standard deviation for each measurement.
Load and process X_test & y_test data.
Extract the mean and standard deviation for each measurement.
Load activity labels
Bind test data
Load and process X_train & y_train data.
Extract the mean and standard deviation for each measurement.
Load activity data
Bind train data
Merge test and train data
Apply mean to dataset using dcast function
Write table to text file saved in working directory 
