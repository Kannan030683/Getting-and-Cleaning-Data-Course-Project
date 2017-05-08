
Key Steps:

1. You have to download sourse data from link below and unzip it to working directory of R Studio.
2. You have to perform R script.

Info on Source Data:
The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone.
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Downloadable data Link:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

About R script

File with R code "run_analysis.R" perform 5 following steps (in accordance assigned task of course work):

Merging the training and the test sets to create one data set.
#Step 1  -  #Reading Files
#Step 1.1 - # Downloading and unzipping dataset
#Step 1.2 - # Unzip dataSet to /data directory
#Step 2 -   # Merge the training and test sets to create one data set
#step 2.1 - # Reading trainings tables:
#step 2.2 - # Assigning column names
#step 2.3 - # Merging all data in one set

Extracting only the measurements on the mean and standard deviation for each measurement

#step 3.1 - #Reading column names
#step 3.2 - #Create vector for defining ID, mean and standard deviation
#step 3.3 - #Making nessesary subset from setAllInOne 

Using descriptive activity names to name the activities in the data set

Appropriately labeling the data set with descriptive variable names

Creating a second, independent tidy data set with the average of each variable for each activity and each subject
#Step 5.1 - #Making second tidy data set
#Step 5.2 - #Writing second tidy data set in txt file

Note: The code assumes that all the data is present in the same folder, un-compressed and without any names modification.

About variables:

x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.
x_data, y_data and subject_data merge the previous datasets to further analysis.
features contains the correct names for the x_data dataset, which are applied to the column names stored in