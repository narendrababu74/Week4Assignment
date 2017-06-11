Week-4-Assignment 

This repo was created to finish the assignment for week 4 of Getting and Cleaning Data Coursera course.

    Step 1) Download the R source code into your R working directory.
    Step 2) Execute R source code to generate newTidySet data file.

Data description

The variables in the data X are sensor signals measured with waist-mounted smartphone from 30 subjects. The variable in the data Y indicates activity type the subjects performed during recording.
Code explaination

The code combined training dataset and test dataset, and extracted partial variables to create new dataset with the averages of each variable for each activity.
New dataset

The new generated dataset contained variables calculated based on the mean and standard deviation. Each row of the dataset is an average of each activity type for all subjects.

The code was written based on the instruction of this assignment

Read training and test dataset into R environment. Read variable names into R envrionment. Read subject index into R environment.

    Merges the training and the test sets to create one data set.
    Extracts only the measurements on the mean and standard deviation for each measurement.
    Uses descriptive activity names to name the activities in the data set
    Appropriately labels the data set with descriptive variable names.
    From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject. 
