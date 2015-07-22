Getting and Cleaning Data - Course Project

Source of the original data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Original description: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Files

CodeBook.md describes the variables 
run_analysis.R contains all the code to perform the analyses described in the 5 steps. 
output of the 5th step is tidy.txt
 
The R script  run_analysis.R  does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3.  Uses descriptive activity names to name the activities in the data set
4.  Appropriately labels the data set with descriptive activity names.
5.  Creates a second, independent tidy data set with the average of each variable for each activity and each subject.
