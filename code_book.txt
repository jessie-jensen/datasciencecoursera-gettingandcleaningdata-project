#Tidy Data Set Code Book
The "Subject" dimension variable corresponds to the subject ID, ranging from 1-30.

The "Activity" dimension variable corresponds to the activity the subject was performing. The set of possible values are {WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING}.

Each of the other 66 fact variables are the calculated mean for the stated varible for the given "Subject" and "Activity". 

__________

These signals were used to estimate variables of the feature vector for each pattern:  
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.

tBodyAcc-XYZ
tGravityAcc-XYZ
tBodyAccJerk-XYZ
tBodyGyro-XYZ
tBodyGyroJerk-XYZ
tBodyAccMag
tGravityAccMag
tBodyAccJerkMag
tBodyGyroMag
tBodyGyroJerkMag
fBodyAcc-XYZ
fBodyAccJerk-XYZ
fBodyGyro-XYZ
fBodyAccMag
fBodyAccJerkMag
fBodyGyroMag
fBodyGyroJerkMag

The set of variables that were estimated from these signals are: 

mean(): Mean value
std(): Standard deviation

__________
See the included "features_info.txt" for more information on each of the un transformed individual variables. See "samsung_data_readme.txt" for more information on the original data set.

