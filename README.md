### Getting-and-Cleaning-data

### INtroduction

The run_analysis.R script uses data from the Human Activity Recognition Using Smartphones Data Set . A full description of the data used in this project can be found at The UCI Machine Learning Repository

The dataset contains experiment findings. The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

The R scipt - Run_analysis.R  does the following.

1)Retrieves the data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
2)Merges the training and the test sets to create one data set.
3)Extracts only the measurements on the mean and standard deviation for each measurement.
4)Uses descriptive activity names to name the activities in the data set
5)labels the data set with descriptive activity names.
6) Creates a second, independent tidy data set with the average of each variable for each activity and each subject.
Motivation

How to create the tidy data set

1)Clone this repository
2)open a R console and set the working directory to the repository root (use setwd())
3)source run_analisys.R script (it requires the plyr package): source('run_analysis.R')
4)After completion, you will find the file tidydata.txt in the repository root directory
