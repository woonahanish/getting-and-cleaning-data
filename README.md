# getting-and-cleaning-data

datasciencecoursera
My_Coursera Repo The R script called run_analysis.R can do the following:

It calls the R Markdown file, run_analysis.Rmd, which contains the bulk of the code and produces the below output files:

Tidy dataset file DatasetHumanActivityRecognitionUsingSmartphones.txt (tab-delimited text) Codebook file codebook.md (Markdown) The detailed steps to create the above output files are given in run_analysis.Rmd.

Merges the training and the test sets to create one data set. After the data is downloaded from the given link, the zip is extracted and needed files are read into variables. Then using rbind and cbind the training and test sets are merged as a single data set.

Extracts only the measurements on the mean and standard deviation for each measurement. features.txt tells which variables in dataset are measurements for the mean and standard deviation.

Uses descriptive activity names to name the activities in the data set. activity_labels.txt file is used to add descriptive names to the activities.

Appropriately labels the data set with descriptive activity names. The helper function grepthis is used to seperate features from featureName. Creates a second, independent tidy data set with the average of each variable for each activity and each subject. Using makeCodebook.Rmd, codebook.md and codebook.html are created. The tidy data set also created by following the instructions in makeCodebook.Rmd
