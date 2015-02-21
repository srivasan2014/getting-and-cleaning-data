# Getting-and-Cleaning-data-Assignment
This file
Codebook

The Codebook contains:

    A description of each of the variables, including units
    Information about the summary choices
    Information about the experimental study design

run_analysis.R

This script assumes that the raw data from the Human Activity Recognition Using Smartphones is downloaded and unzipped in the working directory along with run_analysis.R.

The HAR project data is described at: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The raw data to download and unzip is at: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
Steps to use run_analysis.R

    Download the HAR dataset
    Unzip the dataset
    Ensure that the unzipped directory 'UCI HAR Dataset' is in your working directory, along with run_analysis.R
    Execute run_analysis.R. It is known to work with R version 3.1.0 (2014-04-10), Spring Dance

Assignment criteria

To meet the assignment critera, run_analysis.R does the following (quoting from the assignment):

        Merges the training and the test sets to create one data set.
        Extracts only the measurements on the mean and standard deviation for each measurement.
        Uses descriptive activity names to name the activities in the data set
        Appropriately labels the data set with descriptive variable names.
        Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

These steps are also noted in the comments in the script.
