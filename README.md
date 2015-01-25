# Getting and Cleaning Data - Course Project

Welcome! This is the repo for submission of the Getting and Cleaning Data Course Project (Johns Hopkins).

## Project Overview

In this project, we are going to demonstrate the collection and cleaning of a tidy data set, which can then can be used for any subsequent analysis. 

The full description of the data used in this project can be found at [The UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones) website.

Furthermore, the source data for this project can be found [here.](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)

## Script Modifications

After obtaining and unzipping the source files, there is one more modification to the R file that is necessary before the data can be processed.

In run_analysis.R, you will need to reset the path of the working directory (line 18 of run_analysis.R) to reflect the location of the source files in your own personal directory.

Otherwise, the script will not run properly.

Please make the necessary modifications before grading this assignment.

## Summary of the Project

The R script called run_analysis.R does the following:

1. Merges the training and the test sets, creating one data set.

2. Extracts only the mean and standard deviation measurements for each measurement.

3. Uses descriptive activity names for the activities in the data set.

4. Labels the data set with descriptive activity names.

5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## References

Additional information about the variables, data, and transformations is located in the CodeBook.md file.