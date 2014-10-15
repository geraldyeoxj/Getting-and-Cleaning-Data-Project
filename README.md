## Getting and Cleaning Data - Course Project
The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. 

[The source data for this project can be found here.](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)

### Project Overview
You should create one R script called run_analysis.R that does the following. 
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names. 
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

### Steps to reproduce output
1. Unzip source file into working directory. 
2. Open R script 'run_analysis.R' using a text editor.
3. Set path of working directory by changing parameter of 'setwd' function to reflect the location of the source files.
4. Run R script 'run_analysis.R'. 

### Codebook
Additional information about the variables, data and transformations are found in the 'CodeBook.md' file.