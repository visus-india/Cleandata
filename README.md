1. Unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder on your local drive, C:\coursera\data1\data\UCI HAR Dataset

2. Put run_analysis.R into C:\coursera\data1\data\UCI HAR Dataset

3. In RStudio: setwd("C:\coursera\data1\data\UCI HAR Dataset"), followed by: source("run_analysis.R")
    3a. You will need foreign packages to be installed if you get error when using read.table

4. Use data <- read.table("data_set_with_the_averages.txt") to read the data. It is 180x68 because there are 30 subjects and 6 activities, thus "for each activity and each subject" means 30 * 6 = 180 rows.

5. Try to open the .txt file in the excel rather than notepad so that you can see a tidy output
