# GCD_CourseProject
Files submited for the Getting and Cleaning Data Course Project
=========================

This is a repository for any and all code written for the Getting and Cleaning Data Coursera Course Final Project through Johns Hopkins University.

## Course Project

* Unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder on your local drive;

* Put run_analysis.R into the same folder

* In RStudio: setwd("your folder"), followed by: source("run_analysis.R")

* Use data <- read.table("tidy_data_averages.txt") to read the data. It is 180x68 because there are 30 subjects and 6 activities, thus "for each activity and each subject" means 30 * 6 = 180 rows. Note that the provided R script has no assumptions on numbers of records, only on locations of files.
