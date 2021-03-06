# Getting-CleaningData-Project
* First of all download project files and unzipped. Then set the directory using setwd() to unzipped files.
* Project files are downloaded from this link:
* https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
* Then all given 5 tasks performed one by one in sequence. Code file Run_Analysis.R was uploaded to this repo. CoodBook.md is created for understanding data and variables.
* All comments are given in Run_Analysis.R for each particular code command.
* Final Tidy dataset text file uploaded with name 'tidyTextFile.txt'
* Code project data also uploaded in folder name UCI_HAR_Dataset, you need to download data for reading data from folder.  As Run_Analysis script at first setting working directory to project folder and then reading files from that folder.
* Then script loading train data 3 files, X-train, Y-Train and Subject-train and assigning column names to each train variables.
* Test data 3 files loaded and column names  assigned to them.
* Train and Test data set was merged as having same columns so merged accordingly.
* Then task 2 was done by extraction of mean and standard deviation for each measurement.
* Task 3 done by giving descriptive activity names to 1st column 'Activity_Label' as this column having values 1-6 then descriptive names e.g walking, sitting, laying was assigned according to relevant number.
* Task 4 was done by giving appropriate descriptive names to data set variables e.g. std to StdDev, 't' to time or 'f' to freq.
* Task 5 was done by creating final tidy data set by average of each activity and each subject.

