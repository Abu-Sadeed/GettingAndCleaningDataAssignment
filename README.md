## Getting and Cleaning Data Assignment WEEK 04

### Description
A peer graded assignment for week 4 of the course. The assignment requires us to tidy up a data set.
A full description of the data can be found [here](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones).
The data for the assignment are these [DATA](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip).

### Work Procedure
All data were at first read. Then first the "features" and "activity_labels" variables were fixed. According to step 2 the mean and sd were used only. then the variables were combined using "cbind()" for both "test" and "train" data. now that we had fixed our variable issues "rbind()" command merged the two datasets.
The "acvity_labels" variable is categorized and renamed using original "activity_labels" table.
"reshape2" package was used to perform 5th step. 


### Result
The tidy_data.txt file refers to data after 4th step.
The final result is independent_tidy_data.txt.
For CodeBook Click [HERE]()


