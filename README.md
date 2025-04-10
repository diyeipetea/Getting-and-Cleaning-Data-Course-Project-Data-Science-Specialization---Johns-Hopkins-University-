---
title: "Getting and Cleaning Data Course Project: Readme"
author: "José Tapiz Arrondo AKA José Francisco Tapiz Arrondo AKA Pachi Tapiz Arrondo AKA PTA AKA Diyeipetea"
date: "2025-03-28"
---


# Human Activity Recognition Using Smartphones

## Project Overview
This project demonstrates the ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis.
The data used in this project is collected from the accelerometers of the Samsung Galaxy S smartphone.

## Data Source
The data for this project was obtained from the UCI Machine Learning Repository:
Human Activity Recognition Using Smartphones Data Set

## Files in the Repository
- `run_analysis.R`: The R script that performs the data cleaning and transformation.
- `CodeBook.md`: A code book that describes the variables, the data, and any transformations performed.
- `README.md`:  Explains the project and how to use the scripts.
- `FinalData.txt`: The final tidy data set.

## Steps to Run the Analysis
1. **Download and unzip the dataset**:
   - The dataset is downloaded and unzipped in the working directory in a temporal file .
   - The dataset was downloaded from here: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

2. **Run the `run_analysis.R` script**:
   - Open RStudio.
   - Set the working directory to the location where you saved the script and the unzipped dataset.
   - Source the `run_analysis.R` script to perform the analysis and generate the `FinalData.txt` file.

## Script Explanation
The `run_analysis.R` script performs the following steps:
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set.
4. Appropriately labels the data set with descriptive variable names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Dependencies
The script requires the `dplyr` package. You can install it using:

install.packages("dplyr")

## Acknowledgments
- The data used in this project was provided by the UCI Machine Learning Repository.
- Special thanks to the course instructors and peers for their guidance and support and patience.

