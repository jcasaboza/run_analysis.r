# run_analysis.r
COding for Run_analysis project @ coursera
#
# Data for the project:
# https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
#
# Working Assumptions:
# 1) The number of variables of interest is 33 
#    The mean and standard deviation of the 33 variables will need to be summarized in a .txt file which is going to be in this repo
#      
# 2) Before merging the test and training data sets, the activity and the subject has to be added to the data sets.
#        As there is no matching involved, rbind will be used to merges these datasets 
#
# 3) The Cleanup for the variable names are going to be in the features.txt file attached
#
# 4) Give names that are going to descrube each activity 
#
# 5) Give names to describe each variable
#
