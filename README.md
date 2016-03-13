# peer_evaluation_week_4

-------------------------------------------------
-------------------------------------------------

Getting and Cleaning Data Assignment 4

-------------------------------------------------
-------------------------------------------------

1. Step 1:Download and unzip data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip.

2. Ensure this zipped file and run_analysis.R script are living in the same working directory and run run_analysis.R. 

4. Third, you will find two output files are generated in the current working directory: merged_data.txt. It contains a data frame called cleanedData with 10299*68 dimension.
The second file is data_with_means.txt:it contains a data frame called result with 180*68 dimension.

5. Finally, use data <- read.table("data_with_means.txt") command in RStudio to read the file. Since we are required to get the average of each variable for each activity and each subject, and there are 6 activities in total and 30 subjects in total, we have 180 rows with all combinations for each of the 66 features. 
