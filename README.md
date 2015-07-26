# Getting-Cleaning-Data

This is the course project for the Getting and Cleaning Data course. The R script (run_analysis.R) run as below:

1. Download the dataset from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
2. Load the activity and feature info from the dataset zipfile
3. Loads the train and test datasets, keeping only those columns which reflect a mean or standard deviation
4. Loads the activity and subject data for each dataset. Next merge those columns with the dataset
5. Merges the two datasets
6. Converts the activity and subject columns into factors
7. Create a tidy dataset that consists of the average (mean) value of each variable for each activity and each subject.

The final result is shown in the txt file (tidy.txt).
