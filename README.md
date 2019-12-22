#Getting and Cleaning Data Course Project 

This repository is created to demonstrated how to run analysis on Human Activity recognition dataset to get tidy data.
This repository contains the following files:
README.md
CodeBook.md
run_analysis.R - Consolidates data and performs transformations on the data.

Files CodeBook.md describes the variables, the data, and any transformations or work that I performed to clean up the data.

run_analysis.R can be run as long as the Samsung data is in your working directory. The output should be the tidy data set. It performs transformation on the data by 5 steps according to the course project's requirement:
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject
