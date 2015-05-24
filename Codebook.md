Getting and Cleaning Data Project - **CODEBOOK** File
---------------------------------------------------------------------------------------------------------------------------

The data set consisted of the mean (columns with mean() in the name) and standard deviation (mean (columns with std() in the name)) of time data (columns starting with t) and frequency data (columns starting in f) of 30 users of Samsung Galaxy SII smartphones conducting 6 different activities.


The following are the variables in the tidy data set:

####Activity                   
  Data Type: Factor
  
  Description: The activities the user was performing at the time of measurement
  
  Levels = WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING

####Subject                    
  Data Type: Factor
  
  Description: The ID number of the smartphone user, there are 30 users being measured in this data set
  
  Levels = 1,2,3,..,30

####tBodyAcc-mean()-X          
  Data Type: Numeric  
  
  Description: Mean time of Body Acceleration on the X axis measured in seconds

####tBodyAcc-mean()-Y          
  Data Type: Numeric  
  
  Description: Mean time of Body Acceleration on the Y axis measured in seconds
  
####tBodyAcc-mean()-Z          
  Data Type: Numeric  
  
  Description: Mean time of Body Acceleration on the Z axis measured in seconds

####tBodyAcc-std()-X           
  Data Type: Numeric  
  
  Description: Standard deviation of time of Body Acceleration on the X axis measured in seconds

####tBodyAcc-std()-Y
  Data Type: Numeric  
  
  Description: Standard deviation of time of Body Acceleration on the Y axis measured in seconds

####tBodyAcc-std()-Z           
  Data Type: Numeric  
  
  Description: Standard deviation of time of Body Acceleration on the Z axis measured in seconds

####tGravityAcc-mean()-X       
  Data Type: Numeric  
  
  Description: Mean time of Gravity Acceleration on the X axis measured in seconds

####tGravityAcc-mean()-Y       
  Data Type: Numeric  
  
  Description: Mean time of Gravity Acceleration on the Y axis measured in seconds

####tGravityAcc-mean()-Z       
  Data Type: Numeric  
  
  Description: Mean time of Gravity Acceleration on the Z axis measured in seconds

####tGravityAcc-std()-X        
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the X axis measured in seconds

####tGravityAcc-std()-Y        
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Y axis measured in seconds

####tGravityAcc-std()-Z
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds
  
####tBodyAccJerk-mean()-X
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the X axis measured in seconds

####tBodyAccJerk-mean()-Y      : Numeric  0.1408 -0.4805 -0.0903 0.3786 0.2861 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Y axis measured in seconds

####tBodyAccJerk-mean()-Z      : Numeric  -0.07855 -0.39695 -0.12248 -0.00329 0.08219 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####tBodyAccJerk-std()-X       : Numeric  -0.366 -0.245 -0.161 -0.173 -0.25 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the X axis measured in seconds

####tBodyAccJerk-std()-Y       : Numeric  -0.2991 -0.072 0.1138 -0.0594 -0.1168 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Y axis measured in seconds

####tBodyAccJerk-std()-Z       : Numeric  -0.444 -0.446 -0.425 -0.545 -0.38 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####tBodyGyro-mean()-X         : Numeric  -0.01634 0.3863 0.14997 0.04616 0.00533 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the X axis measured in seconds

####tBodyGyro-mean()-Y         : Numeric  -0.0877 -0.3113 -0.1156 -0.1686 -0.1671 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Y axis measured in seconds

####tBodyGyro-mean()-Z         : Numeric  0.0696 -0.0494 0.109 0.1143 0.088 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####tBodyGyro-std()-X          : Numeric  -0.434 -0.482 -0.505 -0.578 -0.57 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the X axis measured in seconds

####tBodyGyro-std()-Y          : Numeric  -0.615 -0.201 -0.129 -0.117 -0.158 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Y axis measured in seconds

####tBodyGyro-std()-Z          : Numeric  -0.378 -0.486 -0.415 -0.481 -0.5 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####tBodyGyroJerk-mean()-X     : Numeric  -0.0311 -0.2558 -0.1685 0.0347 -0.1382 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the X axis measured in seconds

####tBodyGyroJerk-mean()-Y     : Numeric  -0.0929 0.2189 -0.2103 -0.3449 0.2167 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Y axis measured in seconds

####tBodyGyroJerk-mean()-Z     : Numeric  0.1915 0.1463 0.0524 -0.3041 0.0664 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####tBodyGyroJerk-std()-X      : Numeric  -0.416 -0.354 -0.292 -0.339 -0.363 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the X axis measured in seconds

####tBodyGyroJerk-std()-Y      : Numeric  -0.61 -0.624 -0.539 -0.547 -0.601 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Y axis measured in seconds

####tBodyGyroJerk-std()-Z      : Numeric  -0.523 -0.547 -0.457 -0.518 -0.514 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####tBodyAccMag-mean()         : Numeric  -0.2881 -0.0307 -0.0144 -0.0958 -0.1301 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####tBodyAccMag-std()          : Numeric  -0.471 -0.207 -0.156 -0.234 -0.235 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####tGravityAccMag-mean()      : Numeric  -0.2881 -0.0307 -0.0144 -0.0958 -0.1301 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####tGravityAccMag-std()       : Numeric  -0.471 -0.207 -0.156 -0.234 -0.235 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####tBodyAccJerkMag-mean()     : Numeric  -0.352 -0.243 -0.15 -0.231 -0.254 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####tBodyAccJerkMag-std()      : Numeric  -0.2851 -0.1386 -0.0239 -0.1252 -0.1001 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####tBodyGyroMag-mean()        : Numeric  -0.385 -0.119 -0.19 -0.236 -0.27 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####tBodyGyroMag-std()         : Numeric  -0.527 -0.393 -0.337 -0.374 -0.369 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####tBodyGyroJerkMag-mean()    : Numeric  -0.531 -0.525 -0.444 -0.479 -0.511 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####tBodyGyroJerkMag-std()     : Numeric  -0.626 -0.617 -0.554 -0.555 -0.605 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyAcc-mean()-X          : Numeric  -0.4329 -0.0664 -0.049 -0.0588 -0.1886 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyAcc-mean()-Y          : Numeric  -0.1631 -0.0809 0.1273 0.0331 -0.0201 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyAcc-mean()-Z          : Numeric  -0.41 -0.12 -0.225 -0.357 -0.244 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyAcc-std()-X           : Numeric  -0.414 -0.178 -0.13 -0.225 -0.218 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyAcc-std()-Y           : Numeric  -0.1808 -0.1647 -0.0362 -0.0752 -0.1645 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyAcc-std()-Z           : Numeric  -0.422 -0.048 -0.246 -0.346 -0.31 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyAccJerk-mean()-X      : Numeric  -0.449 -0.232 -0.132 -0.127 -0.231 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyAccJerk-mean()-Y      : Numeric  -0.33194 -0.00336 0.05972 -0.02074 -0.10515 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyAccJerk-mean()-Z      : Numeric  -0.5 -0.363 -0.359 -0.474 -0.294 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyAccJerk-std()-X       : Numeric  -0.339 -0.329 -0.275 -0.308 -0.343 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyAccJerk-std()-Y       : Numeric  -0.3098 -0.2372 0.0988 -0.1804 -0.1966 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyAccJerk-std()-Z       : Numeric  -0.397 -0.531 -0.49 -0.62 -0.466 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyGyro-mean()-X         : Numeric  -0.336 -0.292 -0.342 -0.416 -0.42 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyGyro-mean()-Y         : Numeric  -0.598 -0.375 -0.306 -0.239 -0.341 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyGyro-mean()-Z         : Numeric  -0.294 -0.434 -0.357 -0.4 -0.434 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyGyro-std()-X          : Numeric  -0.466 -0.543 -0.557 -0.63 -0.619 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyGyro-std()-Y          : Numeric  -0.6292 -0.1158 -0.042 -0.0561 -0.0687 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyGyro-std()-Z          : Numeric  -0.465 -0.551 -0.489 -0.558 -0.569 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyAccMag-mean()         : Numeric  -0.439 -0.196 -0.133 -0.213 -0.24 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyAccMag-std()          : Numeric  -0.572 -0.337 -0.301 -0.365 -0.351 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyBodyAccJerkMag-mean() : Numeric  -0.3528 -0.0788 -0.0322 -0.1166 -0.0572 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyBodyAccJerkMag-std()  : Numeric  -0.2091 -0.2221 -0.0186 -0.1418 -0.1578 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyBodyGyroMag-mean()    : Numeric  -0.553 -0.427 -0.359 -0.413 -0.416 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyBodyGyroMag-std()     : Numeric  -0.59 -0.473 -0.436 -0.454 -0.445 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyBodyGyroJerkMag-mean(): Numeric  -0.651 -0.622 -0.586 -0.57 -0.655 ...
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds

####fBodyBodyGyroJerkMag-std() : Numeric  -0.619 -0.638 -0.543 -0.565 -0.57
  Data Type: Numeric  
  
  Description: Standard Deviation of time of Gravity Acceleration on the Z axis measured in seconds


