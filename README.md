#  GettingAndCleaningData - Final Programming Assignment

This repository represents final programming assignment connected to getting and cleaning data. It contains folllowing files:

script run_analysis.R - downloads data and creates tidy data set
averaged_data.txt - tidy data set created as a result of run_analysis.R script
code_book.md - summarizes all data processing and analysis that lead to creating tidy dataset
Script run_analysis.R performs operations in the following manner:

Downloads data if not present in the working directory
Loads datasets and merging training and tests sets to create one dataset
Subsets given dataset - extracts only the measurements on the mean and standard deviation
Renames activity names to descriptive names using activity_labels.txt
Tidying dataset + calculating averages of each variable for each activity and subject
Writes final dataset into a txt file: averaged_data.txt
