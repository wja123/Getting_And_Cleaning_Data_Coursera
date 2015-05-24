Getting and Cleaning Data Project - README File
---------------------------------------------------------------------------------------------------------------------------

###Created using RStudio on a LINUX (Ubuntu) system

###The following sequence of steps outlines how I went about getting and cleaning my data

#### Open the necessary libraries
```
library("plyr")
library("dplyr")
library("httr")
library("RCurl")
library("reshape2")
```

###Getting the data

####Save the URL of the datafiles
```
url<-"https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip"
```

####Download the file using the URL
```
fzip<-download.file(url,destfile="./UCI HAR Dataset.zip",method="curl")
```

####Unzip the file into the current working directory
```
unzip("./UCI HAR Dataset.zip", list = FALSE, overwrite = TRUE,
      junkpaths = FALSE, exdir = ".", unzip = "internal",
      setTimes = FALSE)
```

####Set the working directory as the extracted data folder
```
setwd("./UCI HAR Dataset")
```

###Merging and cleaning the data

####Merge Test Data - merging the subject id, the activity id and the measurements
```
testmer<-cbind(read.table("./test/subject_test.txt",header=FALSE,sep=""),read.table("./test/y_test.txt",header=FALSE,sep=""),read.table("./test/X_test.txt",header=FALSE,sep=""))
```

####Merge Train Data - merging the subject id, the activity id and the measurements
```
trainmer<-cbind(read.table("./train/subject_train.txt",header=FALSE,sep=""),read.table("./train/y_train.txt",header=FALSE,sep=""),read.table("./train/X_train.txt",header=FALSE,sep=""))
```

####Merge both the test table and the train table to form one table
```
rawdata<-rbind(testmer,trainmer)
```

####getting the activity labels
```
activity_labels<-read.table("./activity_labels.txt",header=FALSE,sep="")
```

####naming the columns of the activity labels table
```
colnames(activity_labels)<-c("Activity_Num","Activity")
```

####getting the features to name the rawdata table
```
features<-read.table("./features.txt",header=FALSE,sep="")
```

####renaming the columns of the dataset
```
colnames(rawdata)<-c("Subject","Activity_Num",t(features[2]))
```

#### relabeling activity group
```
cdata<-merge(x = activity_labels, y = rawdata, by = "Activity_Num", all.y=TRUE)
```

####setting the activity to be a factor
```
cdata$Activity<-factor(cdata$Activity)
```

####Setting the Subject to be a factor
```
cdata$Subject<-factor(cdata$Subject)
```

####Save the the column names
```
cnames<-colnames(cdata)
```

####To drop the columns that did not contain Means or Standard deviations, I created a vector of the sum of vectors that was true if the column name contained Activity, Subject, mean() or std() to be used in the next step to drop those columns
```
drop_measure_columns<-t(as.logical(grepl("Activity",cnames,fixed=T)+grepl("Subject",cnames,fixed=T)+grepl("mean()",cnames,fixed=T)+grepl("std()",cnames,fixed=T)))
```

####Using the drop_activity_columns vector to drop the columns that do not have our dimensions or desired measures
```
cdata2<-cdata[,drop_measure_columns]
```

####dropping the activity_number column so that we have only activity factors to keep things neat
```
cdata2<-cdata2[,2:ncol(cdata2)]
```

###Outputting the data


####move working directory up to the main directory
```
setwd("..")
```

####save the tidy_data_set in that directory, I used a space as a separator since none was specified in the assignment
```
write.table(cdata2,file="tidy_data_set.txt",row.name=FALSE,sep=",")
```

####create columns to group the summary data byh
```
group_columns<-c("Activity","Subject")
```

####save the summary data to a variable tdset2 by first grouping by the desired columns and then getting the means of the other columns
```
tdset2<-cdata2 %>% group_by_(.dots = group_columns) %>%  summarise_each(funs(mean))
```

####save the tidy_data_set in that directory, I used a space as a separator since none was specified in the assignment
```
write.table(tdset2,file="summary_data_set.txt",row.name=FALSE,sep=",")
```
