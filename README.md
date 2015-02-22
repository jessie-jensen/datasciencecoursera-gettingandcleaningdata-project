# README
## Coursera - Data Science Certificate - Getting and Cleaning Data - Course Project

###Objectives of script, per the instructions:
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each ACTIVITY and each SUBJECT.

Comments within the R script build off of these instructions.

###Requirements to run R script
1. "UCI HAR Dataset" data repo be located in the current working directory, unaltered in its original form.
2. The 'reshape2' R package be installed and loaded. The library call is included within the script.

###Tidy Data Set
The final "tidy_data.txt" data set contains the average of the 66 mean and std variables found within the original feature set, for the combined test and train data sets.
