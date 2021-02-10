# Getting-and-Cleaning-Data-week-4
Peer-graded Assignment: Getting and Cleaning Data Course Project

Human Activity Recognition Using Smartphones Dataset

Proper data cleaning can make or break your project , usually you need to spend a very large portion of their time on this step. If you have a properly cleaned dataset, even simple algorithms can learn impressive insights from the data. Different types of data will require different types of cleaning.

Getting and Cleaning Data Project Requirements:
1. Create a README that explains the analysis files is clear and understandable
2. Create a CodeBook 
3. Create one R script called run_analysis.R that does the following. 
    1. Merges the training and the test sets to create one data set.
    2. Extracts only the measurements on the mean and standard deviation for each         measurement. 
    3. Uses descriptive activity names to name the activities in the data set
    4. Appropriately labels the data set with descriptive variable names. 
    5. From the data set in step 4, creates a second, independent tidy data set          with the average of each variable for each activity and each subject.
4. Create tidydata.txt

Step by Step Guide
1. First, download and unzip the data file into your R working directory.
2. Create a new project repository in GitHub with the Project Name and files such as :
    1. README.md
    2. CodeBook.md
    3. run_analysis.R
    4. tidydata.txt
3. We first load the libraries we need in order to perform operations on the        dataset. 
4. Training data and testing data for both signals(x) and activities(y), along      with the subject labels were merged.
5. features.txt was parsed to get the variable names of mean and std.
6. mean and std variables extracted from the data set.
7. Signal variables were renamed and improved based on features.txt
8. Renaming the descriptive activity names (6 levels of activities)
9. Summarizing dataset with the average of each variable for each activity and      each subject
10. Create final data 